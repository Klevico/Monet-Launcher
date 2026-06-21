# Monet Launcher

Monet is an Android TV launcher with dynamic colors. The whole home screen is
themed from your wallpaper and recolors automatically when you change it.

This repository is only for distributing the APK. If the Play Store says your
device is "not compatible" (common on Ugoos, AOSP boxes and other non-certified
hardware), download the APK from the Releases page and install it manually.

Supported devices can install from the Play Store:
https://play.google.com/store/apps/details?id=com.klevico.monet

![Monet home screen](screenshots/dynamic-colors.png)

## Features

- Dynamic colors based on your wallpaper
- Custom wallpapers, including video and aerial wallpapers
- Home screen widgets
- Per-app artwork. Set your own image for any app tile
- Content rows: Recommendations, Continue Watching and Live TV channels
- A favorites dock for the apps you use most
- Multiple user profiles
- Optional PIN lock and autostart on boot

## Requirements

- Android TV or Google TV device
- Android 8.0 (API 26) or newer

## Installation

1. Open the [Releases](https://github.com/Klevico/Monet-Launcher/releases) page and download the latest `monet-x.x.x.apk`.
2. On your TV, allow installs from unknown sources
   (Settings → Device Preferences → Security & restrictions → Unknown sources).
3. Install the APK with a file manager (X-plore, Send Files to TV, etc.) or over adb.
4. Press the Home button and pick Monet as your default home app.

### Install over adb

    adb install monet-x.x.x.apk

If you're updating and get a signature error, remove the old build first:

    adb uninstall com.klevico.monet
    adb install monet-x.x.x.apk

## Notes

This is the official signed build. The source code is not part of this repository.
