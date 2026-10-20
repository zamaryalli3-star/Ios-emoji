8# KernelSU iOS Emoji Module
Systemlessly replaces the Android emoji font with an updated iOS-style emoji set.

## Changelog
v2.051
- Updated `NotoColorEmoji.ttf` to newer build (`Version 2.051`, `noto-emoji:20250818`).
- Reworked installer/runtime scripts for dual compatibility with **Magisk** and **KernelSU**.
- Added service-based app font replacement and font-cache cleanup for better cross-app coverage.

## Troubleshooting 
If it doesn't work delete all files under /data/font/files/(Random folder name)

## Tested on
Realme x7 Max 5g(A14)

## Installation
1. Download the latest release from the [Releases page](https://github.com/n4bi10p/Ios-emoji/releases/latest).
2. Open **KernelSU** or **Magisk** app.
3. Go to **Modules** → **Install from storage** and select the downloaded ZIP file.
4. Reboot your device.
5. Enjoy iOS emojis system-wide!

## Screenshot
<img src="https://github.com/n4bi10p/Ios-emoji/blob/main/emojiss.jpg" alt="iOS Emojis on Android" width="400" />  
Example of iOS emojis displayed on an Android device.
