TWRP device configuration for LeEco Le Pro3 Elite
==============

kernel source used for prebuilt kernel:
https://github.com/LineageOS/android_kernel_leeco_msm8996/

To compile android-9.0 based TWRP
==============

    export ALLOW_MISSING_DEPENDENCIES=true
    . build/envsetup.sh
    lunch omni_zl1-eng && \
    mka adbd recoveryimage 2>&1 | tee make_zl1.log

tee command makes a copy of the terminal output to a file.
If you're using Windows PowerShell? Please relace tee with
Tee-Object


Device configuration for LeEco Le Pro3 Elite (x722)
=====================================

Basic                   | Spec Sheet
-----------------------:|:-------------------------
CPU                     | Dual-core 2.15GHz Kryo & dual-core 1.6GHz Kryo
CHIPSET                 | Qualcomm MSM8996 Snapdragon 820
GPU                     | 624MHz Adreno 530
Memory                  | 4 GB (LPDDR4)
Shipped Android Version | 6.0 (Marshmallow)
Storage                 | 32 GB (UFS2.0)
Battery                 | 4070 mAh (non-removable)
Dimensions              | 151.4 x 73.9 x 7.5 mm
Display                 | 1080 x 1920 pixels, 5.5" LTPS IPS LCD, 16:9 ratio (~401 PPI density)
Rear Camera             | 16.0 MP, LED flash (Sony Exmor RS IMX298 f/2.0, 1/2.8")
Front Camera            | 8.0 MP (OmniVision OV8865 f/2.2, 1/3.2")
Extra Features          | Stereo speakers
Release Month           | March 2017

![LeEco Le Pro3 Elite](https://wiki.lineageos.org/images/devices/zl1.png "LeEco Le Pro3 Elite")
