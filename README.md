Manifest for OneOfaKind
====================
OneOfaKind is a lightweight AOSP ROM focused on battery, performance and stability.

The philosophy of OneOfaKind is to stay relatively close to Google's stock Marshmallow with the additions of essential features that should have been included with stock Marshmallow.

    repo init -u https://github.com/ipromeh/oneofakind_manifest.git -b M
    repo sync
    source build/envsetup.sh
    lunch
    make otapackage -j8/16 (depending on your hardware)

[@ipromeh](https://twitter.com/ipromeh) on Twitter
