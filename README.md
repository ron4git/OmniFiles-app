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
| **macOS** (Apple Silicon / Intel) | [**`OmniFiles-macOS.zip`**](./OmniFiles-macOS.zip) | Standalone portable macOS Application (`OmniFiles.app`) | Unzip & double-click `OmniFiles.app` |
| **Windows & Linux & Mac** | [**`OmniFiles-Desktop-Universal-JAR.zip`**](./OmniFiles-Desktop-Universal-JAR.zip) | Standalone executable universal Uber JAR | Unzip & run `java -jar OmniFiles...jar` |
| **Android** (8.0+ Oreo to 14/15) | [**`OmniFiles.apk`**](./OmniFiles.apk) *(Manual upload)* | Full Android APK with Radar & Hotspot Drop | Download & tap to install |

---

## 💻 Installation & Usage Guide

### 🍏 macOS
1. Download [**`OmniFiles-macOS.zip`**](./OmniFiles-macOS.zip) and extract it.
2. Drag `OmniFiles.app` to your `/Applications` folder (or run it directly from anywhere).
3. If macOS displays a Gatekeeper prompt (*"unidentified developer"* or *"app is damaged"*):
   - Right-click `OmniFiles.app` and choose **Open**, then click **Open** in the dialog.
   - Alternatively, open Terminal and run:
     ```bash
     xattr -cr /Applications/OmniFiles.app
     ```

### 🪟 Windows & 🐧 Linux
1. Download [**`OmniFiles-Desktop-Universal-JAR.zip`**](./OmniFiles-Desktop-Universal-JAR.zip) and extract it.
2. Ensure you have **Java 17 or higher** installed (`java -version`).
3. Run the application:
   ```bash
   java -jar OmniFiles-macos-arm64-1.0.0.jar
   ```
   *(Or double-click the `.jar` on Windows if Java file associations are configured).*

### 🤖 Android
1. Download [**`OmniFiles.apk`**](./OmniFiles.apk) directly on your Android device (or transfer it from your computer).
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
