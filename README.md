# local_manifests
Redmi Note7 (Lavender)  Arrow 12.1 的自定义项目

```
repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-12.1 --git-lfs --depth=1

git clone https://github.com/windlite3/local_manifests.git -b arrow-12.1 .repo/local_manifests

repo sync --force-sync -c

source build/envsetup.sh

lunch arrow_lavender-userdebug

m otapackage
```
