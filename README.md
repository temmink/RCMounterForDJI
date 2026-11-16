<div align="center">

# RC Mounter for DJI

**Transfer files from a DJI RC2, DJI RC Pro or DJI RC Pro 2 controller to your Mac over USB-C.**

Flight records (flight logs), screenshots, movies and waypoint missions — one click, no drivers, no DJI software, no cloud.

[![macOS 14+](https://img.shields.io/badge/macOS-14%2B-blue?logo=apple&logoColor=white)](#requirements)
[![Latest Release](https://img.shields.io/github/v/release/temmink/RCMounterForDJI?label=download&color=brightgreen)](https://github.com/temmink/RCMounterForDJI/releases/latest)
[![License](https://img.shields.io/badge/license-proprietary-lightgrey)](#license)

<br>

<img src="https://www.snelgraveren.nl/Apps/RCMounterForDJI/screenshots/mainscreen.png" alt="RC Mounter for DJI on macOS showing a connected DJI RC2 with internal storage and SD card" width="720">

[Download Latest Release](https://github.com/temmink/RCMounterForDJI/releases/latest) &nbsp;&bull;&nbsp; [Website](https://www.snelgraveren.nl/Apps/RCMounterForDJI/) &nbsp;&bull;&nbsp; [Buy License](https://www.snelgraveren.nl/product/rc-mounter-for-dji/) &nbsp;&bull;&nbsp; [FAQ](#faq) &nbsp;&bull;&nbsp; [Support](https://github.com/temmink/RCMounterForDJI/issues)

[English](https://www.snelgraveren.nl/Apps/RCMounterForDJI/) · [Nederlands](https://www.snelgraveren.nl/Apps/RCMounterForDJI/nl/) · [Deutsch](https://www.snelgraveren.nl/Apps/RCMounterForDJI/de/) · [Français](https://www.snelgraveren.nl/Apps/RCMounterForDJI/fr/) · [Español](https://www.snelgraveren.nl/Apps/RCMounterForDJI/es/)

</div>

---

## What is RC Mounter for DJI?

RC Mounter for DJI is a native macOS app that transfers files between a Mac and DJI's Android-based screen controllers — the **DJI RC2**, **DJI RC Pro** and **DJI RC Pro 2** — over a USB-C cable. It uses MTP (Media Transfer Protocol), the protocol Android devices use for file transfer.

**Why do you need it?** macOS does not support MTP, so when you plug a DJI RC2 or RC Pro 2 into a Mac it never shows up in Finder. Windows opens these controllers natively; on a Mac you need an app that speaks MTP over USB. RC Mounter does exactly that — and it knows where DJI Fly keeps flight logs, waypoint missions and media.

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

<img src="https://www.snelgraveren.nl/Apps/RCMounterForDJI/screenshots/media_overview.png" alt="RC Mounter for DJI media browser listing movies on a DJI RC2" width="720">

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

## Supported DJI Controllers

| Controller | Used with (examples) | Status |
|---|---|---|
| **DJI RC2** | DJI Air 3, Air 3S, Mini 4 Pro | Supported |
| **DJI RC Pro** | DJI Mavic 3 series, Air 2S, Mini 3 Pro | Supported |
| **DJI RC Pro 2** | DJI Mavic 4 Pro | Supported |

Controllers without a screen (DJI RC-N1, RC-N2, RC-N3) don't store files — your phone does — so they don't need RC Mounter. Other Android-based DJI screen controllers may work but are untested; try them with the free trial.

## Requirements

| | Minimum |
|---|---|
| **macOS** | 14 Sonoma or later (Apple Silicon and Intel) |
| **Controller** | DJI RC2, DJI RC Pro, DJI RC Pro 2 |
| **Connection** | USB-C cable (direct to Mac) |
| **Disk space** | ~15 MB |

> **Note:** RC Mounter is a macOS-only app. It is not available for Windows or Linux.

## FAQ

### How do I transfer files from a DJI RC2 to a Mac?
Install **RC Mounter for DJI**, connect the DJI RC2 to your Mac with a USB-C data cable and switch the controller on. The app detects it automatically. Click **Flight Records**, **Screenshots**, **Movies** or **Waypoints** in the sidebar and choose a folder on your Mac. The same works for the DJI RC Pro and DJI RC Pro 2.

### Why doesn't my Mac show my DJI RC2 or RC Pro 2 in Finder?
DJI's screen controllers run Android and share files over **MTP (Media Transfer Protocol)**. macOS only mounts USB drives and cameras, not MTP devices, so the controller never shows up in Finder. Windows supports MTP natively; on a Mac you need an app such as RC Mounter for DJI that speaks MTP over USB.

### How do I get DJI flight logs (flight records) from the controller onto my Mac?
Click **Flight Records** in RC Mounter. It collects the flight logs from all the places DJI Fly stores them on the controller's internal storage and copies them to your Mac, keeping the folder structure. You can then upload the log files to a flight log viewer or analysis service of your choice.

### Can I back up waypoint missions (KMZ) and put them back on the controller?
Yes. **Waypoints** downloads every waypoint mission with its folder structure. To change a mission, open it in the Waypoints tab and drag a new KMZ file from Finder onto it — RC Mounter replaces the mission file on the controller. **Back Up / Restore** saves and restores all DJI data, including waypoints, for example after a factory reset.

### Which DJI controllers and drones are supported?
The **DJI RC2** (used with e.g. DJI Air 3, Air 3S and Mini 4 Pro), the **DJI RC Pro** (Mavic 3 series, Air 2S, Mini 3 Pro) and the **DJI RC Pro 2** (Mavic 4 Pro). Controllers without a screen, such as the RC-N1, RC-N2 and RC-N3, store nothing themselves, so they don't need this app.

### Do I need DJI Fly, DJI Assistant or extra drivers on my Mac?
No. RC Mounter talks to the controller directly over USB. You don't need DJI software, drivers, Android File Transfer, a DJI account or an internet connection to transfer files.

### Does RC Mounter for DJI work on Windows?
No, it is a macOS-only app (macOS 14 Sonoma or later, Apple Silicon and Intel). On Windows you don't need it: File Explorer can open MTP devices such as the DJI RC2 natively.

### How much does RC Mounter for DJI cost?
The first **10 file downloads are free**, no account required. After that a **one-time license costs €7.50** per Mac — no subscription. You receive an activation code by email and enter it in the app.

### Can I free up storage space on my DJI controller?
Yes. After a download RC Mounter offers to delete the downloaded files from the controller. **Clean Up Disk Space** clears whole categories (media, waypoints, flight records, logs, cache) with a size preview, and **Free Up Space** only empties the DJI app's caches without touching your media or flight data.

### Are my files uploaded to the cloud?
No. Files go directly from the controller to your Mac over the USB cable. RC Mounter has no cloud sync and does not collect your data. It only contacts the internet to check for app updates and to activate a license.

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

For support inquiries: sales@snelgraveren.nl

---

<div align="center">

**[Download RC Mounter for DJI](https://github.com/temmink/RCMounterForDJI/releases/latest)**

*DJI, RC2, RC Pro, and RC Pro 2 are trademarks of SZ DJI Technology Co., Ltd. This app is not affiliated with or endorsed by DJI.*

</div>
