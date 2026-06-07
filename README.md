# ▶ YT Studio

**A desktop app to inspect YouTube channel analytics and download video, playlists, or entire channels — for Windows and macOS. Built with PySide6 + yt-dlp.**

![Windows](https://img.shields.io/badge/Windows-10%2F11-1f1f1f?style=for-the-badge&logo=windows)
![macOS](https://img.shields.io/badge/macOS-11%2B-1f1f1f?style=for-the-badge&logo=apple)
![Version](https://img.shields.io/badge/version-1.2.0-E8722C?style=for-the-badge)

### ⬇️ Download

| Platform | Download |
|---|---|
| **Windows** (10/11, 64-bit) | **[YT_Studio.exe](https://github.com/naxbil/YT-Studio/releases/latest/download/YT_Studio.exe)** (~320 MB) |
| **macOS** (11 Big Sur or newer) | **[YT_Studio.dmg](https://github.com/naxbil/YT-Studio/releases/latest/download/YT_Studio.dmg)** |

🔗 **Product page:** [naxbil.com](https://naxbil.com) · *(set exact URL, e.g. https://naxbil.com/products/yt-studio)*

---

## Features

### 🔍 Channel Inspect
Paste any channel URL and pull a full analytics snapshot — subscribers, total/median/average views, top video, upload cadence per year, and a sortable, filterable video list. Export everything to **CSV / JSON** in one click.

### ⬇️ Download
Three modes, one queue:
- **Video** — single or batch (stage multiple URLs, drag & drop links)
- **Playlist** — full playlist grab
- **Channel** — pull an entire channel

Options: MP4 (video) or MP3 (audio-only), quality selector, subtitles, embed thumbnail, embed metadata. FFmpeg bundled — no separate install needed.

---

## Screenshots

| Channel Inspect | Download |
|---|---|
| ![Channel Inspect](https://naxbil.com/assets/img/products/yt_studio/channel_inspect.png) | ![Download](https://naxbil.com/assets/img/products/yt_studio/content_download.png) |

---

## Install

### Windows
1. Download **[YT_Studio.exe](https://github.com/naxbil/YT-Studio/releases/latest/download/YT_Studio.exe)** and run it.
2. **Windows SmartScreen** may show *"Windows protected your PC"* because the app isn't code-signed. Click **More info → Run anyway**. This is expected for independent software.
3. If antivirus flags it, that's a known false positive for PyInstaller + yt-dlp apps — allow-list the file. Scan report: *(add VirusTotal link here)*.

### macOS
1. Download **[YT_Studio.dmg](https://github.com/naxbil/YT-Studio/releases/latest/download/YT_Studio.dmg)**, open it, and drag **YT Studio** into **Applications**.
2. On first launch, macOS **Gatekeeper** may say *"YT Studio cannot be opened because the developer cannot be verified."* Fix it one of two ways:
   - **Right-click** the app → **Open** → **Open** again, **or**
   - **System Settings → Privacy & Security → Open Anyway**.
3. If it still refuses, run this once in Terminal:
   ```bash
   xattr -cr /Applications/YT\ Studio.app
   ```

**Requirements:** Windows 10/11 (64-bit) or macOS 11+. No Python install needed — everything is bundled.

---

## Notes

- First run may take a few seconds while bundled FFmpeg initializes.
- For best Channel Inspect results, close your browser so the app can read cookies (or set cookies to *None* in Settings).

---

## Disclaimer

YT Studio is a personal-use utility built on [yt-dlp](https://github.com/yt-dlp/yt-dlp). Use it only for content you own, content you have permission to download, or content permitted under YouTube's Terms of Service and your local laws. The developer is not responsible for misuse.

---

**Developer:** Devesh Shukla · [naxbil.com](https://naxbil.com) · [LinkedIn](https://www.linkedin.com/in/devesh-shukla-er)
