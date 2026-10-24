# 🌐 OmniFiles — App Downloads & Releases

<p align="center">
  <b>Smart Downloads Radar & Zero-Friction Cross-Device Drop</b><br>
  <i>Direct installers and pre-built packages for Android, macOS, Windows, and Linux.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20macOS%20%7C%20Windows%20%7C%20Linux-blue?style=flat-square" alt="Platforms" />
  <img src="https://img.shields.io/badge/Source%20Code-ron4git%2FOmniFiles-purple?style=flat-square" alt="Source" />
  <img src="https://img.shields.io/badge/Privacy-100%25%20Offline%20%26%20P2P-success?style=flat-square" alt="Privacy" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square" alt="License" />
</p>

> 📌 **Looking for the source code?**  
> The full source code and developer documentation are located at [**github.com/ron4git/OmniFiles**](https://github.com/ron4git/OmniFiles).

---

## 🚀 Download Installers

Download the package for your operating system directly from this repository:

| Platform | Package | Description | Quick Start |
|---|---|---|---|
| **macOS, Windows & Linux** | [**`OmniFiles-Desktop.zip`**](./OmniFiles-Desktop.zip) | Unified Desktop Bundle (`OmniFiles.jar` + `OmniFiles.app` + `OmniFiles.command` + `OmniFiles.bat` + `OmniFiles.sh`) | Unzip & run `./OmniFiles.command` (Mac), `OmniFiles.bat` (Windows), or `./OmniFiles.sh` (Linux) |
| **Android** (8.0+ Oreo to 14/15) | [**`OmniFiles-release.apk`**](./OmniFiles-release.apk) | Signed Release Android APK with Radar & Hotspot Drop | Download & tap to install |

---

## 💻 Installation & Usage Guide

### 🍏 macOS (Apple Silicon & Intel)
1. Download [**`OmniFiles-Desktop.zip`**](./OmniFiles-Desktop.zip) and extract it (keep `OmniFiles.app`, `OmniFiles.command`, and `OmniFiles.jar` in the same folder).
2. **First Launch (Bypasses macOS Gatekeeper *"Apple could not verify"* dialog)**:
   - Open Terminal in the extracted folder and run:
     ```bash
     ./OmniFiles.command
     ```
     *(Or right-click `OmniFiles.command` in Finder and click **Open**).*
   - `OmniFiles.command` automatically removes the macOS `com.apple.quarantine` flag from `OmniFiles.app` and launches `OmniFiles.jar` from the same folder. After running once, you can double-click `OmniFiles.app` anytime!
3. **Optional — Install to `/Applications`**:
   ```bash
   ./OmniFiles.command --install
   ```

### 🪟 Windows
1. Download [**`OmniFiles-Desktop.zip`**](./OmniFiles-Desktop.zip) and extract it.
2. Ensure **Java 17 or higher** is installed.
3. Double-click **`OmniFiles.bat`** (or run `java -jar OmniFiles.jar`).

### 🐧 Linux
1. Download [**`OmniFiles-Desktop.zip`**](./OmniFiles-Desktop.zip) and extract it.
2. Ensure **Java 17 or higher** is installed (`sudo apt install openjdk-21-jre`).
3. Run the launcher script from the extracted folder:
   ```bash
   ./OmniFiles.sh
   ```
   *(Optional: Run `./OmniFiles.sh --install` to add OmniFiles to your Linux Desktop Application Menu).*

### 🤖 Android
1. Download [**`OmniFiles-release.apk`**](./OmniFiles-release.apk) directly on your Android device (or transfer it from your computer).
2. Open the downloaded `.apk` file from your notification panel or Files app.
3. If prompted, toggle **"Allow from this source"** in your phone's Settings to enable sideloading.
4. Tap **Install** and launch OmniFiles.

---

## 💡 What Problem Does OmniFiles Solve?

Modern multi-device users face two frustrating daily friction points:

1. **The Fragmented Download Maze**:  
   On Android, files don't go to one place. Chrome saves to `/Downloads`, WhatsApp buries media in private sandboxes, Telegram creates its own subfolder, and Slack puts documents elsewhere. Finding a file you downloaded 5 minutes ago requires hunting through multiple app directories.
2. **The Ecosystem Walled Gardens**:  
   If you have a **Mac and an Android phone** (or a **Windows PC and an iPhone**), seamless local file sharing simply does not exist out of the box:
   - **AirDrop** locks out all non-Apple devices.
   - **Quick Share** locks out macOS and Linux.
   - Cloud storage and messaging apps (WeChat, WhatsApp, Slack) compress photos, upload sensitive files to third-party servers, and eat up mobile data.
   - Pure transfer utilities (like LocalSend) are merely pipes—they don't organize your downloads, can't work without a shared Wi-Fi router, and require every participant to install their app first.

**OmniFiles unifies a Smart Downloads Manager and a High-Speed Offline Wi-Fi Drop into a single, cohesive experience.**

---

## ⚔️ Comparison Matrix

| Feature | **OmniFiles** | **Apple AirDrop** | **Google Quick Share** | **LocalSend** | **Snapdrop / PairDrop** | **Send Anywhere** |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| **Cross-Platform Support** | **Android, macOS, Windows, Linux** | Apple Only | Android & Windows | All Platforms | Browser-based | All Platforms |
| **Integrated File Manager** | ✅ **Yes** (Timeline & Folders) | ❌ No | ❌ No | ❌ No | ❌ No | ❌ No |
| **Download Origin Tracking** | ✅ **Yes** (WhatsApp, Chrome...) | ❌ No | ❌ No | ❌ No | ❌ No | ❌ No |
| **Works Offline (No Router / Hotspot)** | ✅ **Yes** (Auto Local-Hotspot) | ✅ Yes (Apple Direct) | ⚠️ Android-to-Android only | ❌ Manual setup | ❌ No (Needs STUN/Internet) | ❌ No (Needs Cloud) |
| **No App Required on Peer (iPhone / Guests)** | ✅ **Yes** (Browser Web Drop) | ❌ No | ❌ No | ❌ No | ✅ Yes | ⚠️ Needs 6-digit key |
| **Zero Cloud / 100% Private LAN** | ✅ **Yes** | ✅ Yes | ✅ Yes | ✅ Yes | ⚠️ WebRTC Signaling | ❌ Routes via Servers |
| **Photo Deduplication (EXIF + SHA-256)** | ✅ **Yes** | ❌ No | ❌ No | ❌ No | ❌ No | ❌ No |
| **In-App Wi-Fi QR Scanner** | ✅ **Yes** (Google ML Kit) | ❌ No | ❌ No | ❌ No | ❌ No | ❌ No |
| **List & Rich Thumbnail Views** | ✅ **Yes** | ❌ N/A | ❌ N/A | ❌ N/A | ❌ N/A | ❌ N/A |
| **Ad-Free & Tracker-Free** | ✅ **Yes** | ✅ Yes | ✅ Yes | ✅ Yes | ⚠️ Ads on public servers | ❌ Heavy Ads |

---

## ✨ Key Features

- **📡 Wi-Fi Drop**: 50–80+ MB/s offline peer-to-peer sharing over Wi-Fi without compression or size limits.
- **⚡ Emergency Hotspot**: Turns on an instant ad-hoc local Wi-Fi hotspot on Android when outdoors or traveling without a Wi-Fi router.
- **📷 Standard Wi-Fi QR**: Displays universal `WIFI:S:...;T:WPA;P:...;;` code for any iPhone or Android camera to connect in one tap.
- **🔍 Built-in QR Scanner Chip**: Scans peer QR codes directly within OmniFiles without leaving the app.
- **🌐 Browser Web Drop**: Share files directly to iPhone users or guests through their web browser without installing any app.
- **📥 Smart Download Radar**: Sorts downloads into chronological buckets (*Just Now*, *Today*, *Yesterday*, *This Week*) with app origin badges (*WhatsApp*, *Chrome*, *Telegram*).
- **📁 "All Folders" Explorer**: Dual List & Thumbnail views, latest files sorted first, formatted timestamps `<yyyy-mm-dd:hh.mm>`, and context menu file renaming.

---

## 🔒 Privacy & Security

- **100% Offline by Design**: OmniFiles never dials home, requires no accounts, and contains zero trackers or analytics.
- **Local Network Only**: All transfers travel directly between devices over your local Wi-Fi or ad-hoc hotspot connection.
- **Accidental Deletion Guard**: System files, app bundles, and root directories are protected from accidental deletion.

---

## 📄 License & Source

- **Source Code Repository**: [github.com/ron4git/OmniFiles](https://github.com/ron4git/OmniFiles)
- **License**: [MIT License](https://github.com/ron4git/OmniFiles/blob/main/LICENSE)
