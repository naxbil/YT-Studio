# ▶ YT Studio

**A desktop app to inspect YouTube channel analytics and download video, playlists, or entire channels — built with PySide6 + yt-dlp.**

[![Download](https://img.shields.io/badge/Download-Windows%20(.exe)-E8722C?style=for-the-badge)](https://github.com/naxbil/YT-Studio/releases/latest/download/YT_Studio.exe)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-1f1f1f?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.2.0-E8722C?style=for-the-badge)

> ⬇️ **[Download the latest version (Windows)](https://github.com/naxbil/YT-Studio/releases/latest/download/YT_Studio.exe)**

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
| ![Channel Inspect](docs/screenshots/channel-inspect.png) | ![Download](docs/screenshots/download.png) |

---

## Install

1. Click **[Download](https://github.com/naxbil/YT-Studio/releases/latest/download/YT_Studio.exe)**.
2. Run the `.exe`.
3. **Windows SmartScreen** may show *"Windows protected your PC"* because the app isn't code-signed. Click **More info → Run anyway**. This is expected for independent software.
4. Some antivirus tools flag PyInstaller + yt-dlp apps as false positives. The build is clean — scan report: *(add VirusTotal link here)*. If blocked, allow-list the file.

**Requirements:** Windows 10/11 (64-bit). ~300 MB. No Python install needed — everything is bundled.

---

## Notes

- First run may take a few seconds while bundled FFmpeg initializes.
- For best Channel Inspect results, close your browser so the app can read cookies (or set cookies to *None* in Settings).

---

## Disclaimer

YT Studio is a personal-use utility built on [yt-dlp](https://github.com/yt-dlp/yt-dlp). Use it only for content you own, content you have permission to download, or content permitted under YouTube's Terms of Service and your local laws. The developer is not responsible for misuse.

---

**Developer:** Devesh Shukla · [LinkedIn](https://www.linkedin.com/in/devesh-shukla-er)
