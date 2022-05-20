# i2c-tools for aosp

Forked from repo : 

https://github.com/TedNIVAN/i2c-tools-xu3-xu4.git

## 0. Get the binaries

Clone to external directory or add it to your local manifest if you're using repo tool

## 1. Add Product packages

To device/vendor/product/device.mk

```
PRODUCT_PACKAGES += \
        i2cdump \
        i2cget \
        i2cset \
        i2cdetect
```
