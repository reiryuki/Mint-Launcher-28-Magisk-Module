# Mint Launcher Magisk Module

## DISCLAIMER
- Xiaomi apps are owned by Xiaomi™.
- The MIT license specified here is for the Magisk Module only, not for Xiaomi apps.

## Descriptions
Home launcher app by Xiaomi Inc. ported and integrated as a Magisk Module for all supported and rooted devices with Magisk

## Sources
- https://apkmirror.com com.mi.android.go.globallauncher by Xiaomi Inc.
- libmagiskpolicy.so: Magisk (stable) 30.7 (30700)

## Changelog

v0.5
- Update libmagiskpolicy.so from Magisk (stable) 30.7 (30700)
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/
- Prepare /storage/emulated/"$USR"/Android/data/com.mi.android.go.globallauncher/files

v0.4
- Fix denial if executing default.sh

v0.3
- Fix permissions
- Add Action button to clear app caches
- Fix bug in uninstall.sh

v0.2
- largeHeap="false"

v0.1
- Initial release

## Screenshots
https://t.me/ryukimodsscreenshots/2

## Requirements
- Android 5 (SDK 21) and up
- Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install this module via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (enable show system apps) and reboot afterwards
- Change your default launcher to this Mint Launcher via Settings app (or you can copy the content of default.sh and paste it to Termux/Terminal Emulator app. Type su and grant root first!)

## Optionals
- https://t.me/ryukinotes/42
- Global: https://t.me/ryukinotes/35

## Troubleshootings
- https://t.me/ryukinotes/19
- Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


