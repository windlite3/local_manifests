# local_manifests
Redmi Note7 (Lavender)  CalyxOS android15-qpr2 的自定义项目

```
repo init -u https://github.com/CalyxOS-Lavender/platform_manifest.git -b android15-qpr2 --git-lfs --depth=1

git clone https://github.com/windlite3/local_manifests.git -b calyx-15-qpr2 .repo/local_manifests

repo sync --force-sync -c

source build/envsetup.sh

breakfast lavender userdebug

m otapackage
```

