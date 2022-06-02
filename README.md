This is a device tree for Lenovo A850+ (MT6592) which is based on MT6592 SoC. Based on Stock Kitkat kernel (3.4.67)


# Specifications:-
   * CPU	1.4GHz Octa-Core MT6592
   * Memory 1GB RAM
   * Android Version 4.4.2 & 5.1.1
   * Storage	2GB
   * Battery	2500 mAh
   * Display	5.0" 720 x 1280 DPI 320
   * Rear Camera	8MP
   * Front Camera	3MP


# Working
  * unknown



# Build

  * repo init -u git://github.com/LineageOS/android.git -b cm-14.1
  * repo sync
  * git clone https://github.com/tt468/android_device_Lenovo_anchi.git -b cm-14.1 device/lenovo/anchi
  * git clone https://github.com/tt468/MT6592-Vendor-Blobs.git vendor/lenovo/proprietary/
  * ./unzip.sh
  * git clone https://github.com/tt468/android_vendor_Lenovo_anchi.git vendor/lenovo/
  * cd device/lenovo/anchi/patches
  * source apply.sh 
  * source build/envsetup.sh
  * brunch anchi
  * Done :)
  
  # Credits/Thanks to:-
  * Fire855 
  * Axet
  * chrmhoffmann
  * DerTeufel1980
  * Al3XKOoL
  * xen0n
  * kashifmin
  * Santhosh M
  * ariafan
  * hyperion70
  * tribetmen
  * CyanogenMod Team
  * Tirth Patel
  * Kishan Patel
  * Yazad Madan 
  * tt468
  * SamarV-121
