## The Pixel Project - OFFICIAL

**Device Changelog 10.09.2024**

- Fixed auto-brightness issue, ensuring the screen doesn't automatically brighten to max when unlocking, particularly in dark environments.
- Resolved the issue where display saturation settings (Settings > Display > Display Saturation) are not applied after a device restart.
- Switched to oneplus Dolby (Settings > Sound & Vibration > Dolby Atmos)
- Enabled and fine-tuned Always-On Display (AOD) burn-in protection.
- Added Pocket Mode
- Fixed Wi-Fi display functionality.
- Enabled support for Spatial Audio.
- Migrated to Xiaomi IR AIDL.
- Built open-source SoundTrigger HAL from source.
- Compiled libsndcardparser from source.
- Compiled libbatterylistener from source.
- Built most AGM and PAL targets from source.
- Compiled mtdservice interface library from source.
- Switched to source-built Mlipay interface.
- Built SoundDose interfaces from source.
- Renamed "Xiaomi Parts" to "Xiaomi Settings" in the Parts module.
- Updated SEPolicy to fix issues related to Xiaomi Parts.
- Removed MiSound from the Parts module.
- Improvement in doze mode
- Tuned powerhint from AOSPA
- Updated Dolby Atmos blobs from oneplus 9R
- Updated perf blobs from AOSPA
- Added Dolby volume listener and Dolby spatial audio support
- Enable vonr in unsupported contries
- fix some log spam
- rebased trees and upstream kernel
- Updated power hints for SM7450.

**Device Changelog 16.08.2024**

- Fix battery and USB OTG detection
- Drop xiaomi libsensor_cal@2.0.so
- Build xiaomi-telephony-stub
- wifi: Enable support for IEEE80211AX
- audio: Disable DRC
- audio: Fix mic issues in apps like WhatsApp
- Explicitly disable GL comp backpressure
- overlay: Enable Night Display and Extra Dim
- rootdir: Add sdcard1 and usbotg to recovery fstab
- Load adsp_loader_dlkm for battery status in recovery
- sensors: Increase _oem_msg struct size
- Kill xiaomi citsensorservice and sensor communicate
- sensors: Introduce LightNotifier and use libssccalapi@2.0
- sensors: Add aod notifier
- sensors: Convert nonui notifier into a generalized sensor based notifier
- sensors: Close touch dev fd after usage
- Use kernel provided xiaomi_touch.h
- sensors: Pass nonui value unmodified to touchscreensensors: Pass nonui value unmodified to touchscreen
- sensors: Cleanup code and drop unused dependencies
- Drop nfc services from manifest
- Migrate to QTI USB Gadget 1.2 HIDL
- Swap to QTI USB init scripts
- Assert for marble or marblein
- Introduce sensor notifier extension to report raw brightness
- Set HWC-specific properties
- Add missing kvh2xml.xml
- Add Xiaomi sensor module

**Device Changelog 08.08.2024**

- Auto brightness much more responsive
- Tuned haptics
- Fixed aod blinking
- Switched to xiaomi dolby with graphical eq
- Removed Misound enhancer

**Device Changelog 03.08.2024**

- Fixed haptics
- Fixed AOD
- Fixed dt2w and dt2s
- Fixed Auto brightness
- Fixed manual saturation slider sometimes reset
- Fixed Google recorder Speech recognition
- Fixed miui Camera OIS

**Device Changelog 28.07.2024**

- Initial Official build
- Includes oneplus dolby
- Added Qcom audio effects from oneplus 9R
- Added Mi Sound Enhancer
- Added new manual saturation display slider
