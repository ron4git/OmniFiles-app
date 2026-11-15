# 🌐 OmniFiles

<p align="center">
  <b>Smart Downloads Radar & Zero-Friction Cross-Device Drop</b><br>
  <i>The missing bridge between your file downloads and all your devices.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20macOS%20%7C%20Windows%20%7C%20Linux-blue?style=flat-square" alt="Platforms" />
  <img src="https://img.shields.io/badge/Built%20With-Compose%20Multiplatform-orange?style=flat-square" alt="Compose Multiplatform" />
  <img src="https://img.shields.io/badge/Kotlin-2.0+-purple?style=flat-square" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Privacy-100%25%20Offline%20%26%20P2P-success?style=flat-square" alt="Privacy" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square" alt="License" />
</p>

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

### 📡 1. Wi-Fi Drop (High-Speed Cross-Platform P2P)
- **50–80+ MB/s Transfers**: Stream files over local hardware Wi-Fi without compression or size limits.
- **Dual-Engine Peer Discovery**: Combines **mDNS (DNS-SD)** with **cross-platform UDP subnet broadcast** on port `8923`. Discovers nearby phones, Macs, and PCs reliably even on routers that block multicast or isolate client ports.
- **PIN Verification & Trusted Devices**: Protects your device with one-time 6-digit verification codes. Mark machines you own as "Trusted" for instant 1-click transfers.

### ⚡ 2. Automatic Emergency Hotspot (Car, Outdoor & Travel Mode)
- **Zero-Friction Offline Sharing**: When you turn on Radar outdoors or in a car with no Wi-Fi router, OmniFiles automatically spins up an ad-hoc local Wi-Fi hotspot on Android.
- **Universal Wi-Fi QR Code**: Formats credentials into standard `WIFI:S:...;T:WPA;P:...;;`. Any iPhone, Android, or laptop camera scanning the code connects in 1 tap without typing passwords.
- **Built-in QR Scanner Chip**: Includes an in-app camera scanner powered by Google Play Services Code Scanner with **zero camera permission prompts**.

### 🌐 3. Browser Web Drop (Zero App Installation Required)
- Share files with a friend who has an iPhone or a laptop without OmniFiles installed.
- Expand **Browser Web Drop** on your screen; your friend points their phone camera at the screen and instantly opens a sleek local web interface to download your file or upload photos from their camera roll.

### 📥 4. Smart Download Radar
- **Chronological Time Buckets**: Categorizes all incoming downloads into **Just Now** (< 30 min), **Today**, **Yesterday**, **This Week**, and **Older**.
- **App Origin Badges**: Automatically detects and badges files from **Chrome**, **WhatsApp**, **Telegram**, **Slack**, and **Browsers**.
- **Smart Photo Deduplication**: Checks image EXIF metadata and SHA-256 hashes to prevent downloading identical copies.

### 📁 5. "All Folders" Explorer (List & Thumbnail Views)
- **Latest First**: Always prioritizes your most recently modified files and folders at the top.
- **Unified Timestamp**: Formats all timestamps cleanly as `<yyyy-mm-dd:hh.mm>` (e.g. `2026-10-22:10.15`).
- **List / Thumbnail View Toggle**: Switch anytime from the toolbar or context menu. Thumbnail view renders image previews with memory-safe downsampling alongside large media badges.
- **Context Actions**: Right-click or long-press any file to **Rename**, **Send via Wi-Fi Drop**, **Copy Path**, or **Delete**.

---

## 🚀 Quick Download

### Option 1: Direct High-Speed Download (Recommended for Mainland China / No VPN Needed)
- 🌐 **OmniFiles Web Showcase & Mobile QR**: [**grepcode.net/omnifiles**](https://grepcode.net/omnifiles)
- 🤖 **Android Signed APK**: [**`https://grepcode.net/download/omnifiles.apk`**](https://grepcode.net/download/omnifiles.apk)
- 💻 **Desktop Bundle (macOS, Windows, Linux)**: [**`https://grepcode.net/download/omnifiles-desktop.zip`**](https://grepcode.net/download/omnifiles-desktop.zip)

### Option 2: GitHub Distribution Mirror
Pre-built installable packages are also hosted at [**github.com/ron4git/OmniFiles-app**](https://github.com/ron4git/OmniFiles-app):

- 🤖 **Android**: [**`OmniFiles-release.apk`**](https://github.com/ron4git/OmniFiles-app/raw/main/OmniFiles-release.apk) *(Direct download & install on any Android 8.0+ device)*
- 💻 **Desktop (macOS, Windows & Linux)**: [**`OmniFiles-Desktop.zip`**](https://github.com/ron4git/OmniFiles-app/raw/main/OmniFiles-Desktop.zip) *(Single unified desktop package containing `OmniFiles.jar`, macOS `OmniFiles.app` & `OmniFiles.command`, Windows `OmniFiles.bat`, and Linux `OmniFiles.sh`)*

👉 Browse all installers, releases, and setup guides at the [**OmniFiles App Distribution Hub**](https://github.com/ron4git/OmniFiles-app).

---

## 🛠️ Building From Source

### Prerequisites
- **JDK 17 or 21**
- **Android SDK** (API 34)

### 1. Build Desktop App (macOS, Windows, Linux)
```bash
# Run desktop app directly:
./gradlew :desktopApp:run

# Package standalone universal Uber JAR:
./gradlew :desktopApp:packageUberJarForCurrentOS
```
Output: `desktopApp/build/compose/jars/OmniFiles-macos-arm64-1.0.0.jar`

### 2. Build Android App
```bash
# Build debug APK:
./gradlew :androidApp:assembleDebug

# Build release APK:
./gradlew :androidApp:assembleRelease
```
Output: `androidApp/build/outputs/apk/debug/androidApp-debug.apk`

---

## 🔒 Privacy & Security

- **100% Offline by Design**: OmniFiles never dials home, requires no accounts, and contains zero trackers or analytics.
- **Local Network Only**: All transfers travel directly between devices over your local Wi-Fi or ad-hoc hotspot connection.
- **Accidental Deletion Guard**: System files, app bundles, and root directories are protected from accidental deletion.

---

## 📄 License

OmniFiles is open-source under the [MIT License](LICENSE). Contributions, bug reports, and feature requests are welcome!
