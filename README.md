<div align="center">

  <img src="fastlane/metadata/android/en-US/images/icon.png" alt="Transfer Logo" width="120" />

  # Transfer

  <p align="center">
    <strong>A simple local file server app for Android.</strong><br>
    Download and upload files quickly across devices over Wi-Fi — no cables, no cloud.
  </p>

  <p align="center">
    <a href="https://github.com/matan-h/Transfer/releases"><img src="https://img.shields.io/github/v/release/matan-h/Transfer?style=flat-square&color=6C63FF&label=Release" alt="Latest Release" /></a>
    <a href="https://play.google.com/store/apps/details?id=com.matanh.transfer"><img src="https://img.shields.io/badge/Google_Play-Available-34A853?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play" /></a>
    <a href="https://apt.izzysoft.de/fdroid/index/apk/com.matanh.transfer"><img src="https://img.shields.io/badge/IzzyOnDroid-F--Droid-1E88E5?style=flat-square&logo=f-droid&logoColor=white" alt="IzzyOnDroid" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" alt="License: MIT" /></a>
    <img src="https://img.shields.io/badge/Android-10%2B%20(API%2029%2B)-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android 10+" />
    <img src="https://img.shields.io/badge/Kotlin-1.8%2B-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
  </p>

  <h4>
    <a href="#-how-to-get-the-app">Download</a>
    <span> · </span>
    <a href="#-key-features">Features</a>
    <span> · </span>
    <a href="#-getting-started">Quick Start</a>
    <span> · </span>
    <a href="#-cli--curl-usage">CLI & curl</a>
    <span> · </span>
    <a href="#-faq">FAQ</a>
    <span> · </span>
    <a href="CONTRIBUTING.md">Contributing</a>
  </h4>

</div>

---

## Overview

**Transfer** turns your Android phone into an ad-hoc local HTTP file server. Think of it as a wireless USB flash drive accessible from any PC, Mac, Linux box, iPhone, or Android device on your network using just a web browser or terminal command.

No client software needed. No cloud accounts. No slow uploads to third-party servers.

Basically, a clean, modern, battery-friendly alternative to running `uploadserver` via Termux or configuring Samba/SMB.

---

## Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center" width="16%">
        <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/01.png" width="100%" alt="Main Screen" /><br>
        <sub><b>Fast Transfers</b></sub>
      </td>
      <td align="center" width="16%">
        <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/02.png" width="100%" alt="Web Interface" /><br>
        <sub><b>Any Browser</b></sub>
      </td>
      <td align="center" width="16%">
        <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/03.png" width="100%" alt="Dark Mode" /><br>
        <sub><b>Dark Mode</b></sub>
      </td>
      <td align="center" width="16%">
        <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/04.png" width="100%" alt="Permission Prompt" /><br>
        <sub><b>Device Approvals</b></sub>
      </td>
      <td align="center" width="16%">
        <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/05.png" width="100%" alt="Clipboard Paste" /><br>
        <sub><b>Clipboard Paste</b></sub>
      </td>
      <td align="center" width="16%">
        <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/06.png" width="100%" alt="Settings Screen" /><br>
        <sub><b>Settings</b></sub>
      </td>
    </tr>
  </table>
</div>

---

## Why Transfer?

| Traditional Methods | Transfer |
|---------------------|----------|
| ❌ Hunting for a USB cable or dongle | ✅ Works seamlessly over local Wi-Fi or mobile hotspot |
| ❌ Uploading gigabytes to the cloud & waiting | ✅ High-speed local LAN transfer speed |
| ❌ Setting up Samba, NFS, or complex file shares | ✅ One tap: opens standard HTTP server |
| ❌ Installing proprietary sync apps on every computer | ✅ Built-in browser web UI — zero client software |
| ❌ Unclear privacy & external telemetry | ✅ 100% open source, strictly local, zero internet required |

---

## ✨ Key Features

- 🌐 **Instant LAN & Hotspot Sharing**: Serve files directly from a designated folder on your Android storage over standard HTTP.
- 📱 **QR Code Quick Connect**: Scan a dynamic QR code on your phone screen to connect laptops, tablets, or phones in seconds.
- 🛡️ **Interactive Security Controls**:
  - **IP Permission Prompts**: Whenever a new device attempts to connect, an *Allow / Deny* prompt appears on your phone (approved sessions valid for 1 hour).
  - **Password Protection**: Option to enforce HTTP Basic Authentication with a custom password.
- 💻 **Responsive Web Interface**: Modern, lightweight web dashboard featuring drag-and-drop file upload, file downloads, and multi-file selection.
- 📋 **Single-Tap Clipboard Sharing**: Paste text from your phone's clipboard into a new `.txt` file in the shared folder instantly.
- ⚡ **curl & Terminal Friendly**: Full support for downloading and uploading using standard CLI tools (`curl`, `wget`, scripts).
- 🌙 **System Dark & Light Themes**: Beautiful Material design adhering to your device theme.
- 🔒 **Privacy by Design**: No telemetry, no ads, no trackers, no external servers.

---

## 📥 How to Get the App

### Recommended Sources

<a href="https://play.google.com/store/apps/details?id=com.matanh.transfer">
  <img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="54">
</a>
<a href="https://apt.izzysoft.de/fdroid/index/apk/com.matanh.transfer">
  <img alt="Get it on IzzyOnDroid" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroidButtonGreyBorder_nofont.png" height="54">
</a>

- **[Google Play Store](https://play.google.com/store/apps/details?id=com.matanh.transfer)**
- **[IzzyOnDroid Repository](https://apt.izzysoft.de/fdroid/index/apk/com.matanh.transfer)** (use Neo Store, Droid-ify, or F-Droid client)

### Other Options
- **[GitHub Releases](https://github.com/matan-h/Transfer/releases)**: Download signed APKs directly (compatible with [Obtainium](https://github.com/ImranR98/Obtainium) for auto-updates).

---

## 🚀 Getting Started

1. **Install & Open**: Launch **Transfer** on your Android device.
2. **Select Folder**: Pick or create a folder for shared files (e.g. `Storage` in your device's internal memory).
3. **Start Server**: Tap **Start Server**. The app will display your local IP and port (e.g., `http://192.168.1.42:8000`).
4. **Connect**: Open that address in a browser on any device connected to the same Wi-Fi or Hotspot, or tap the QR icon to scan.
5. **Approve & Transfer**: If IP permissions are enabled, tap **Allow** on your phone prompt to grant access.

---

## 💻 CLI & curl Usage

Transfer is built to be terminal-friendly. You can automate uploads and downloads without opening a browser:

### Upload a file
```bash
curl -T document.pdf http://<phone-ip>:8000/
```

### Download a file
```bash
curl -O http://<phone-ip>:8000/document.pdf
```

### Upload with password protection
```bash
curl -u :your_password -T backup.tar.gz http://<phone-ip>:8000/
```

### Stream / pipe remote file
```bash
curl -s http://<phone-ip>:8000/script.sh | bash
```

---

## 🛠️ Built With

- **[Kotlin](https://kotlinlang.org/)** — 100% modern Kotlin codebase
- **[Ktor (CIO Engine)](https://ktor.io/)** — High-performance asynchronous HTTP engine
- **[Android Jetpack](https://developer.android.com/jetpack)** — ViewModel, Coroutines, Flow, Lifecycle
- **[DocumentFile & Scoped Storage](https://developer.android.com/training/data-storage)** — Strict privacy compliance
- **[ZXing](https://github.com/zxing/zxing)** — On-device QR code rendering
- **[Material Design 3](https://m3.material.io/)** — Native Android UI components

---

## ❓ FAQ

<details>
<summary><b>Why does my browser show an SSL/HTTPS error?</b></summary>
<br>
If your browser displays errors such as <code>ERR_SSL_PROTOCOL_ERROR</code>, <code>ERR_CONNECTION_CLOSED</code>, or <code>SSL_ERROR_RX_RECORD_TOO_LONG</code>, it is because you are attempting to connect via <b>HTTPS</b> instead of <b>HTTP</b>.
Make sure your URL explicitly starts with <code>http://</code> (e.g., <code>http://192.168.1.50:8000</code>).
</details>

<details>
<summary><b>Can I use Transfer without an active internet connection?</b></summary>
<br>
Yes! Transfer only requires a local network. You can connect devices to the same local Wi-Fi router (even without WAN/Internet) or simply turn on your Android device's <b>Wi-Fi Hotspot</b> and connect your laptop directly to it.
</details>

<details>
<summary><b>Can I set a fixed or static IP address?</b></summary>
<br>
Yes, you can configure a static IP in your Android device's Wi-Fi network settings or assign a DHCP reservation in your home router.
</details>

<details>
<summary><b>Where are uploaded files stored?</b></summary>
<br>
All uploaded and shared files are placed directly in the folder you selected during setup (configurable in Settings).
</details>

<details>
<summary><b>What happens if you tap "T0" on the About screen?</b></summary>
<br>
It increments to <code>T1</code> :)
</details>

---

## 🗺️ Planned Changes

- [ ] add an option to change the port in the settings
- [x] fallback to hotspot IP in the display.
- [x] automatically update the IP when Wifi changes

---

## 🤝 Contributing

Contributions, bug reports, and suggestions are warmly welcomed!
- Please read the [Contributing Guidelines](CONTRIBUTING.md) before submitting a PR.
- Found a bug? Feel free to [open an issue](https://github.com/matan-h/Transfer/issues).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
