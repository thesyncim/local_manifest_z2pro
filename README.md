#### Local manifest for build Cyanogenmod for Zuk Z2 Pro ####

### How to use:
```
mkdir z2pro
cd z2pro
repo init -u git://github.com/CyanogenMod/android.git -b cm-13.0  --depth=1
git clone https://github.com/thesyncim/local_manifest_z2pro.git -b cm-13.0 .repo/local_manifests
repo sync --force-sync -c
. build/envsetup.sh
lunch cm_z2pro-userdebug
brunch z2pro
```
