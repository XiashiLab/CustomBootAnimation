❄️ Aemeath Boot Animation

<p align="center">
  <img src="banner.png" alt="Aemeath Boot Animation Banner" width="100%">
</p><p align="center">
  **A Custom Android Boot Animation**Featuring Aemeath from Wuthering Waves

Created by Xiashi | XiashiLab

</p><p align="center">
  <a href="https://github.com/XiashiLab/CustomBootAnimation/releases">
    Download Latest Release
  </a>
</p>---

✦ About

Aemeath Boot Animation is a custom Android boot animation featuring Aemeath from Wuthering Waves.

This project aims to provide a smoother and more personalized Android startup experience through a custom boot animation.

The module is designed for supported root environments using SukiSU.

✦ Features

- Smooth 30 FPS animation
- 720 × 1600 animation frames
- 1080 × 2400 display canvas
- PNG animation frames
- ZIP Store compression (no compression)
- SukiSU module support
- Custom module banner
- Adjustable resolution and FPS through "desc.txt"

✦ Device Compatibility

Successfully tested on:

- Infinix Note 12 2023

The module has been installed and successfully booted on the device listed above.

Compatibility with other devices has not yet been fully tested.

Compatibility may vary depending on:

- Android version and firmware
- Root environment and module manager
- Device display resolution
- Boot animation implementation

If you successfully test this module on another device, feel free to share your results.

⚙️ Resolution & FPS Customization

Android devices come with different screen resolutions and display configurations.

The default configuration is:

1080 2400 30

You can customize the boot animation settings through the "desc.txt" file.

Configuration Format

WIDTH HEIGHT FPS

Parameter| Description
WIDTH| Boot animation canvas width
HEIGHT| Boot animation canvas height
FPS| Animation playback speed

Example

1080 2400 30

If the animation appears too fast or too slow, adjust the FPS value.

If the animation does not fit your screen properly, adjust the canvas dimensions to match your device.

Important:

Changing the canvas dimensions in "desc.txt" does not automatically resize the PNG frames.

For the best result, prepare the animation frames with dimensions and proportions appropriate for your target display.

Always keep a backup of the original "desc.txt" before making changes.

⚠️ Important: Backup Before Installation

Always back up your original stock boot animation before installing this module.

This module replaces your device's existing boot animation.

Without a backup, restoring the original animation may be difficult.

Common Stock Boot Animation Locations

The original "bootanimation.zip" location varies depending on the device and firmware.

Common locations include:

/system/media/bootanimation.zip

/system/product/media/bootanimation.zip

These are only examples. Your device may use a different location.

Backup Instructions

1. Locate your device's original "bootanimation.zip".
2. Copy the file to internal storage or external storage.
3. Keep the backup somewhere safe.
4. Verify that the backup file is accessible before installing the module.

«Do not skip this step. Keep your original boot animation backup even after successful installation.»

✦ Installation

1. Download the latest module ZIP from "GitHub Releases" (https://github.com/XiashiLab/CustomBootAnimation/releases).
2. Open SukiSU Manager.
3. Select the downloaded module ZIP.
4. Install the module.
5. Reboot your device.
6. Enjoy the Aemeath boot animation!

Note: Installation steps may differ depending on your root manager.

✦ Restore Original Boot Animation

If you want to return to your original boot animation:

1. Make sure you have a valid backup of your stock "bootanimation.zip".
2. Disable the Aemeath Boot Animation module through your module manager, if supported.
3. Restore your backup to the appropriate original location if necessary.
4. Check that the restored file has the correct name and permissions.
5. Reboot your device.

Important: The correct restoration procedure depends on how your device and root environment handle module overlays. Do not delete or modify system files blindly.

✦ Troubleshooting

Animation does not appear

- Check whether the module is enabled.
- Verify that the ZIP was installed successfully.
- Check whether your device uses a different boot animation location.
- Check your root manager's module logs.

Animation is too fast or too slow

- Open "desc.txt".
- Adjust the FPS value.
- Save your changes and reinstall or update the module as appropriate.

Animation does not fit the screen

- Check your device's display resolution.
- Adjust the canvas dimensions in "desc.txt".
- Make sure the PNG frames are also prepared for the intended dimensions.

Animation stutters or freezes

- Check the frame image dimensions.
- Avoid unnecessary image compression.
- Keep the animation frame rate and image sequence consistent.
- Check available device resources during boot.

✦ Project Information

Detail| Information
Project| XiashiLab
Module| Aemeath Boot Animation
Version| 1.0
Version Code| 1
Status| Stable
Creator| Xiashi
Tested Device| Infinix Note 12 2023

✦ Credits & Disclaimer

- Character: Aemeath
- Game: Wuthering Waves
- Original Game Developer: Kuro Games
- Module Creator: Xiashi

This is an unofficial fan-made project.

It is not affiliated with, endorsed by, or sponsored by Kuro Games.

All character names, designs, and related intellectual property belong to their respective owners.

This project is created for customization and fan appreciation purposes.

---

<p align="center">
  **Made by Xiashi | XiashiLab**A different start to your Android experience.

© 2026 Xiashi

</p>