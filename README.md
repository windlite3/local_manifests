# local_manifests
Redmi Note7 (Lavender)  Project-Flare 15 的自定义项目

```
repo init -u https://github.com/Project-Flare/manifest.git -b 15 --git-lfs --depth=1
git clone https://github.com/windlite3/local_manifests.git -b flare-15 .repo/local_manifests
repo sync --force-sync -c
source build/envsetup.sh
lunch flare_lavender-userdebug
m otapackage
```
