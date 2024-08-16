**Flashing Instructions for Marble**

**Before start flashing.....**

- Always have backup of your internal storage
- Use TWRP recovery meant for Android 14. Check link in my channel [**#twrp_a14**](https://t.me/kenway_playground/68)
- To retain TWRP recovery after rom flash, don't forget to tick the option "Automatically Reflash TWRP after flashing a rom" in recovery. Else TWRP will be replaced by recovery from rom
- For Kernel SU check note in my channel [**#ksu_a14**](https://t.me/kenway_playground/69)
- For vanilla variant, if u need gapps, [**Nikgapps is Recommended**](https://sourceforge.net/projects/nikgapps/files/Releases/Android-14/)

----

## If on miui based rom and flashing HyperOS based custom rom first time (Clean flash is must) 

## Gapps variant
- Download the ROM
- Flash Recommended TWRP
   ```fastboot flash recovery_ab RECOVERY_NAME.img```
- Boot into recovery
   ```fastboot reboot recovery```
- Wipe Dalvik/Art Cache, cache and data , (do not wipe internal storage)
- (MUST) Flash your region's latest HyperOS firmware from [**#here**](https://xiaomifirmwareupdater.com/firmware/marble/) 
- Flash rom
- Tap on format data, type yes and reboot to system

# Vanilla Variant
- Download the ROM and Gapps package from nikgapps
- Flash Recommended TWRP
   ```fastboot flash recovery_ab RECOVERY_NAME.img```
- Boot into recovery
   ```fastboot reboot recovery```
- Wipe Dalvik/Art Cache, cache and data , (do not wipe internal storage)
- Flash your region's latest HyperOS firmware from [**#here**](https://xiaomifirmwareupdater.com/firmware/marble/)
- Flash the ROM and reboot to recovery
- Flash the Nikgapps
- Tap on format data, type yes and reboot to system

----

## If already on HyperOS based custom rom

## Gapps variant

**Clean flash:**
- Download the ROM
- Boot into recovery
- Wipe Dalvik/Art Cache, cache and data
- Flash the ROM
- Tap on format data, type yes and reboot to system

**Dirty flash:**
- Download the ROM
- Boot into recovery
- Wipe Dalvik/ArtCache and Cache
- Flash the ROM
- Reboot To System

----

## Vanilla variant

**Clean flash:**
- Download the ROM and Gapps package from nikgapps
- Boot into recovery
- Wipe Dalvik/Art Cache, cache and data
- Flash the ROM and reboot to recovery
- Flash the Nikgapps
- Tap on format data, type yes and reboot to system

**Dirty flash:**
- Download the ROM
- Boot into recovery
- Wipe Dalvik/ArtCache and Cache
- Flash the ROM and reboot to recovery
- Flash the Nikgapps
- Reboot To System

----


**Happy Flashing.......Enjoy the Rom**
