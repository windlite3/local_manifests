# local_manifests
Redmi Note7 (Lavender) VoltageOS 13 的自定义项目

```
repo init -u https://github.com/VoltageOS/manifest.git -b 13 --git-lfs --depth=1

git clone https://github.com/windlite3/local_manifests.git -b voltage-13 .repo/local_manifests

repo sync --force-sync -c

source build/envsetup.sh

lunch voltage_lavender-userdebug

m otapackage
```
