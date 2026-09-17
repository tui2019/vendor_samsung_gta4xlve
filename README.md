# Samsung Galaxy Tab S6 Lite 2022 (SM-P613 / gta4xlve) Vendor Blobs

This repository contains the vendor partition blobs for the **Samsung Galaxy Tab S6 Lite 2022 (`SM-P613` / `gta4xlve`)** with Snapdragon 720G (`sm7125`).

## Included Fixes & Updates
- **One UI 8.5 Qualcomm Lights HAL**: Includes the official One UI 8.5 Qualcomm Lights HAL daemon (`vendor.samsung.hardware.light-service`) and AIDL Version 2 NDK libraries (`android.hardware.light-V2-ndk.so`, `vendor.samsung.hardware.light-V2-ndk.so`) supporting extended brightness (> 255 / sunlight overdrive mode).
- **Extra Dim / Snapdragon Tone Control (STC) Fix**: Includes official Qualcomm `libcolor-default.so` from Samsung One UI 8 Snapdragon firmware (`SM-X210R`). Restores native hardware color transforms (Polynomial Color Correction / PCC) on LCD displays where QDCM XML profiles are not present, fixing the Extra Dim feature.
