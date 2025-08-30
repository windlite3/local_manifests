# local_manifests
Redmi Note7 (Lavender)  ProjectInfinity-X 16 的自定义项目

repo init -u https://github.com/ProjectInfinity-X/manifest.git -b 16 --git-lfs --depth=1

git clone https://github.com/windlite3/local_manifests.git -b infinity-16 .repo/local_manifests

repo sync --force-sync -c

source build/envsetup.sh

breakfast lavender

m otapackage
