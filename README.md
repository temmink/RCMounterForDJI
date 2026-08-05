<div align="center">

# RC Mounter for DJI

**Direct USB file access for your DJI RC2, RC Pro, and RC Pro 2 on macOS.**

Browse, download, and manage files on your DJI remote controller — no drivers, no DJI software, no cloud.

[![macOS 14+](https://img.shields.io/badge/macOS-14%2B-blue?logo=apple&logoColor=white)](#requirements)
[![Latest Release](https://img.shields.io/github/v/release/temmink/RCMounterForDJI?label=download&color=brightgreen)](https://github.com/temmink/RCMounterForDJI/releases/latest)
[![License](https://img.shields.io/badge/license-proprietary-lightgrey)](#license)

<!-- TODO: Uncomment when screenshot is available
<br>

![RC Mounter for DJI — main window](screenshots/main-window.png)
-->

[Download Latest Release](https://github.com/temmink/RCMounterForDJI/releases/latest) &nbsp;&bull;&nbsp; [Buy License](https://www.snelgraveren.nl/product/rc-mounter-for-dji/) &nbsp;&bull;&nbsp; [Support & FAQ](https://github.com/temmink/RCMounterForDJI/issues)

</div>

---

## What is RC Mounter?

RC Mounter for DJI is a native macOS app that connects to your **DJI RC2**, **DJI RC Pro**, or **DJI RC Pro 2** controller via USB-C and gives you full file access using the MTP (Media Transfer Protocol) — the same protocol Android uses for file transfers.

Plug in your controller, and within seconds you can browse its storage, download flight records, manage media, back up everything, and even swap waypoint mission files.

**Try it free** — the first 10 file downloads require no license.

## Key Features

### One-Click Media Downloads
Download flight records, screenshots, movies, and waypoint missions with a single click from the sidebar. Each category shows a live file count, and files already on your Mac are automatically skipped — no duplicates, no wasted time. After a download, optionally delete the files from the controller to free up space.

### Backup & Restore
Create a complete backup of your controller's data to your Mac — flight records, waypoints, media, and logs — with one click. Back up everything or a single storage volume, then restore it later, for example after a factory reset or when moving to a new controller.

### Free Up Space
Reclaim storage on the controller by clearing whole categories of files (media, waypoints, flight records, logs, cache) with a size preview and confirmation. A separate one-click cache cleaner safely empties the DJI app's caches without touching your media.

### Media Browser
Browse photos and videos directly on the controller. Grid or list view with thumbnails. Right-click to preview, download, or delete files on the device.

<!-- TODO: Uncomment when screenshot is available
![Media Browser](screenshots/media-browser.png)
-->

### Waypoint Mission Manager
Browse waypoint mission files stored on the controller. Drag and drop a KMZ file from Finder to replace a mission in-place — perfect for updating planned routes before a flight.

### Dual Storage Support
Switch between Internal Storage and SD Card instantly. All operations — browsing, downloading, deleting, backing up — work across both storage volumes.

### Finder Integration (Advanced)
Mount the controller's filesystem as a native Finder volume via macOS FileProvider. Browse and open files as if the controller were an external drive.

### File Explorer
Full directory browser for the controller's filesystem. Navigate any folder, view file details, and download individual files — straight to the download folder you configured per category.

### Automatic Updates
The app checks for new versions on its own and offers an assisted, signature-verified update — so you always run the latest release without hunting for downloads.

### Smart & Lightweight
- Built in pure Swift with direct IOKit USB access — no middleware, no background processes
- No DJI SDK or third-party software required
- No cloud sync, no data collection — everything stays on your Mac
- Automatic PTPCamera conflict resolution — no manual setup needed
- Configurable default download and backup folders; remembers your window position

## Getting Started

1. **Download** the latest DMG from [Releases](https://github.com/temmink/RCMounterForDJI/releases/latest)
2. **Open** the DMG and drag *RC Mounter for DJI* to your Applications folder
3. **Connect** your DJI RC2, RC Pro, or RC Pro 2 via USB-C
4. **Launch** the app — it detects your controller automatically

> The app is notarized by Apple and signed with a Developer ID certificate. If macOS shows a security prompt on first launch, right-click the app and choose "Open".

### Trial & Licensing

RC Mounter works immediately with a **free trial of 10 file downloads**. After that, a one-time license purchase unlocks unlimited use.

[Buy a License](https://www.snelgraveren.nl/product/rc-mounter-for-dji/)

Activation is instant — enter your email and activation code in the app, and you're set. No subscription, no recurring fees.

## Requirements

| | Minimum |
|---|---|
| **macOS** | 14 Sonoma or later |
| **Controller** | DJI RC2, DJI RC Pro, DJI RC Pro 2 |
| **Connection** | USB-C cable (direct to Mac) |
| **Disk space** | ~15 MB |

> **Note:** RC Mounter is a macOS-only app. It is not available for Windows or Linux.

## Troubleshooting

**Controller not detected?**
- Make sure the controller is powered on and connected via USB-C
- Enable *Advanced Options* in Settings to show the Logs tab for diagnostic output
- Try a different USB-C cable or port

**Files not showing up?**
- Switch storage volumes (Internal Storage / SD Card) using the storage picker
- Some folders are only accessible on Internal Storage (e.g., waypoint missions, flight records)

**"App is damaged" or security warning?**
- Right-click the app, choose "Open", and confirm. This is a one-time macOS Gatekeeper prompt for apps downloaded outside the App Store.

For more help, visit our [support page](https://github.com/temmink/RCMounterForDJI/issues) or email info@snelgraveren.nl.

## Feedback & Bug Reports

Found a bug or have a feature idea? File an issue right here on GitHub:

- [Report a Bug](https://github.com/temmink/RCMounterForDJI/issues/new?template=bug_report.yml&labels=bug)
- [Request a Feature](https://github.com/temmink/RCMounterForDJI/issues/new?template=feature_request.yml&labels=enhancement)

Please check [existing issues](https://github.com/temmink/RCMounterForDJI/issues) first to avoid duplicates.

## License

RC Mounter for DJI is proprietary software. The source code is not included in this repository.

- **Trial:** 10 free file downloads, no license required
- **Full license:** One-time purchase at [snelgraveren.nl](https://www.snelgraveren.nl/product/rc-mounter-for-dji/)
- **Scope:** One license per Mac (tied to hardware serial number)

## About

RC Mounter for DJI is developed and maintained by [Martin Temmink](https://github.com/temmink).

For support inquiries: info@snelgraveren.nl

---

<div align="center">

**[Download RC Mounter for DJI](https://github.com/temmink/RCMounterForDJI/releases/latest)**

*DJI, RC2, RC Pro, and RC Pro 2 are trademarks of SZ DJI Technology Co., Ltd. This app is not affiliated with or endorsed by DJI.*

</div>
