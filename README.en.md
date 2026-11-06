# Paper7 Screen Tuner 1.8.14

| [简体中文](README.zh-CN.md) | **English** |
|:---:|:---:|

Paper7 Screen Tuner is an Android display color adjustment app primarily intended for the Paper7. The app was developed entirely with AI. Related resources are available from [Keji Wanjia](https://www.kejiwanjia.net/).

## Features

- Adjust contrast, saturation, gamma, picture brightness, hue, and the red, green, and blue channels.
- Preview and tune the display in real time with a floating panel over other apps.
- Apply the recommended preset from either the main screen or the floating panel. Its saturation value uses the system-native index `4`.
- Includes an experimental HAL calibration page for trying alternate device controls. Its controls have not yet been verified to work; an accepted write does not prove that the display effect was applied.
- Keeps the displayed values synchronized between the main screen and the floating panel.

## Requirements

- Root access is required. Allow superuser access for `com.paper7.displaytuner` in your root manager.
- Allow the app to display over other apps to use the floating panel.
- Primarily intended for the Paper7. Other devices and firmware versions are untested.

## Safety Notice

This app uses root privileges to access device display controls. Root operations and display adjustments may affect device operation or image quality. Use it at your own risk. The app is provided for learning and personal use, without warranty.

## GitHub Release

- Version: `1.8.14` (version code `51`)
- APK: `Paper7-screen-tuner-1.8.14.apk`
- SHA-256: `3AD364014FF9792F4B03E5B3239178F8D29CE764E2F4BE0E67686FBF95B064BB`

## What's New

- Added recommended preset controls to the main screen and floating panel, with synchronized parameter displays.
- Set the recommended saturation value to the system-native index `4`.
- Enabled code obfuscation and shrinking for the release build.
