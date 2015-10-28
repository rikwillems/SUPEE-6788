# SUPEE-6788

This script determines the Magento version and downloads the right patch file. For ease of use it also disables and clears compilation. After this take the normal steps for applying Magento patches.

## Excluding cron patch in .htaccess

This branch does not contain the patch to .htaccess and .htaccess.sample. This has to be added manually.

## Usage

```
bash < <(wget -q --no-check-certificate -O - https://raw.githubusercontent.com/rikwillems/SUPEE-6788/without-cron-patch/PATCH_SUPEE-6788.sh)
```
