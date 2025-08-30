# local_manifests
Redmi Note7 (Lavender)  SuperiorOS 13 的自定义项目

```
repo init -u https://github.com/SuperiorOS/manifest.git -b thirteen --git-lfs --depth=1

git clone https://github.com/windlite3/local_manifests.git -b superior-13 .repo/local_manifests

repo sync --force-sync -c

source build/envsetup.sh

lunch superior_lavender-userdebug

m otapackage
```
