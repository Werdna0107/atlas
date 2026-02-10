# atlas
Insta360 Controller for photo
# Atlas — Insta360 Controller

Android application for controlling Insta360 camera. Designed for systematic 360° photo documentation with automatic project/date organization.

## Features

- 📷 **360° Photo Capture** — Remote shutter control via WiFi
- 📍 **GPS Tagging** — Automatic coordinates in EXIF metadata
- 📁 **Smart Organization** — Photos sorted by Project → Date → Point
- 🔄 **Panorama Viewer** — Built-in 360° photo preview
- 📱 **Works with Mobile Data** — WiFi binding allows camera connection even with cellular enabled
- 🔢 **Point Numbering** — Sequential naming for hotspot identification

## Folder Structure

```
Download/Atlas/
├── ProjectName/
│   ├── 20260204/
│   │   ├── ProjectName_20260204_1842_1.jpg
│   │   ├── ProjectName_20260204_1845_2.jpg
│   │   └── ProjectName_20260204_1850_3.jpg
│   └── 20260205/
│       └── ProjectName_20260205_0930_1.jpg
└── AnotherProject/
    └── 20260204/
        └── ...
```

## Installation

1. Download `atlas-v2.0.0.apk` from [Releases](../../releases)
2. Enable "Install from unknown sources" on your Android device
3. Install the APK
4. Grant permissions (Location, Storage)

## Usage

### First Launch
1. Choose **NEW** to create a new project or **OPEN** to continue existing one
2. Enter project name (latin letters, no spaces)

### Taking Photos
1. Connect your phone to Insta360 X4 WiFi network
2. Tap camera icon to connect
3. Tap GPS icon to enable location tagging
4. Press shutter button to capture
5. Enter point number and save

### Photo List
- Swipe up on the `^` icon to see session photos
- Tap photo to preview in 360° viewer
- Tap trash icon to delete

## Use Case

Designed for construction site documentation:
- Walk through key positions on the site
- Capture 360° photos at each marked point
- Photos automatically organized by project and date
- Ready for upload to virtual tour platforms

## Requirements

- Android 7.0+
- Insta360 camera
- WiFi connection to camera

## Author

- YouTube: [@a2-lab](https://youtube.com/@a2-lab)
- Telegram: [@a2blog](https://t.me/a2blog)

## License

MIT License — feel free to use and modify.
