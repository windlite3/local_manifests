# local_manifests
Redmi Note7 (Lavender)  yaap 16 的自定义项目

```
repo init -u https://github.com/yaap/manifest.git -b sixteen --git-lfs --depth=1

git clone https://github.com/windlite3/local_manifests.git -b yaap-16 .repo/local_manifests

repo sync --force-sync -c

source build/envsetup.sh

lunch yaap_lavender-userdebug

m otapackage
```
