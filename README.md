# local_manifests
Redmi Note7 (Lavender)  Lineage 20.0 的自定义项目

```
repo init -u https://github.com/LineageOS/android.git -b lineage-20.0 --git-lfs --depth=1

git clone https://github.com/windlite3/local_manifests.git -b lineage-20.0 .repo/local_manifests

repo sync --force-sync -c

source build/envsetup.sh

lunch lineage_lavender-userdebug

m otapackage
```
