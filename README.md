CyanogenMod 11.0 device configuration for LG L65 D285

How to build:
-------------

Initializing a Build Environment:

    https://source.android.com/source/initializing.html

Initialize repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/L65/android_local_manifest/cm-11.0/local_manifest.xml
    repo sync
    vendor/cm/get-prebuilts

Compile:

    . build/envsetup.sh
    brunch cm_w55ds-userdebug
