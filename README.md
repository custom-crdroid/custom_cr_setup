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

Additional Gapps Flags:

TARGET_INCLUDE_STOCK_ARCORE := true
TARGET_SUPPORTS_GOOGLE_RECORDER := true
TARGET_SUPPORTS_NEXT_GEN_ASSISTANT := true
```

#### To add maintainers string:
```bash
PRODUCT_SYSTEM_PROPERTIES += \
     ro.crdroid.maintainer=Maintainers_name
```


## To add ota support (its already included in rom) you just need to open pull request on https://github.com/custom-crdroid/vendor_crDroidOTA with you device file and details (check other json there for reference) 



