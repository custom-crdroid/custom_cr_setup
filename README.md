# To seup Custom Cr build env 

### Clone the official source go to dir where you cloned official source then follow below steps 


```bash
wget https://raw.githubusercontent.com/custom-crdroid/custom_cr_setup/refs/heads/15.0/vendorsetup.sh
```

```bash
bash vendorsetup.sh
```
# now sit back and let it do it work 
_________________________________________________________________________________________________________________________________________________________________________________

### Now let's add some flag in your tree 

#### To build Gapps use flag:
```bash
WITH_GMS := true
```

#### To add maintainers string:
```bash
PRODUCT_SYSTEM_PROPERTIES += \
     ro.crdroid.maintainer=Maintainers_name
```

## To add ota support (its already included in rom) you just need to open pull request on https://github.com/custom-crdroid/vendor_crDroidOTA with you device file and details (check other json there for reference) 

## With this, I bid a heartfelt farewell to this side project of mine. It has been an incredible journey, filled with moments of creativity and growth. I’ve truly enjoyed building and nurturing it, but the time has come to move on. This will be the final update as I now shift my focus to Project Matrixx, where I aim to pour my energy into reviving and redefining its vision. Thank you all for being a part of this journey—it’s been an absolute pleasure. Here’s to new beginnings! 🌟



