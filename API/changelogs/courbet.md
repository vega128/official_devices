# 12-July-2022
- Rebased on the latest xiaomi-sm6150 sources
- Switched to QTI bluetooth
- Added ANXCamera and fixed an issue where AI mode caused CPU to be stuck on maximum frequency
- Fixed PixelOS recovery not being able to flash stuff like Magisk
- Fixed a few issues with the microphone (R.I.P. Dolby)
- Labeled new wake-up nodes
- Fix-up more sepolicy
- Upstreamed kernel to 4.14.287
- Enabled Ultra Low Power State Mode on suspend
- Other misc. changes and fixes

# 26-June-2022
- Switched to user builds
- Updated courbet blobs from miui_COURBETGlobal_V13.0.8.0.SKQMIXM
- Updated common blobs from miui_SWEETEEAGlobal_V13.0.10.0.SKFEUXM
- Added thermal profiles
- Added Neural Networks and Snapdragon Computer Vision Engine stack
- Updated media configs
- Change cache partition to f2fs
- Labeled more wakeup nodes
- Switch SchedTune to UClamp
- Updated VantomKernel
- Other misc. changes and fixes

# 09-June-2022
- Updated blobs from MIUI V13.0.8.0.SKFMIXM
- Switched to EROFS (Enhanced read only file system)
- Enabled F2FS compression (Needs a clean flash to work)
- Added Moto Dolby with a tuned configuration from MIUI on the Redmi Note 10 Pro (Thanks helenius147)
- Optimize native executables for Cortex-A76 CPU
- Switch to dot product CPU variant
- Improved vibrations
- Nuked Vulkan (due to some heating/drain)
- Fixed picture adjustment in LiveDisplay (Do NOT change kernel if you want LiveDisplay to function properly)
- Fixed the remaining stuff in miuicamera like clone mode (thanks to Adarsh) P.S. slow-mo is still dead
- Updated VantomKernel and PlayGround clang
- Other misc. changes

# 15-May-2022
- Initial official and stable build based on Android 12L
