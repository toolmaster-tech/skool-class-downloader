<img src="https://drive.google.com/thumbnail?id=1IVe3KMrx5sJYvves4N-9J7rgbhlasOSR&sz=w1920" alt="Skool Class Downloader" style="max-width: 100%;" />

# Skool Class Downloader

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey.svg" alt="Platform">
  <img src="https://img.shields.io/badge/license-Proprietary-red.svg" alt="License">
</p>

A desktop application to download courses from Skool.com communities you're a member of.

## ⬇️ Download Latest Version (v1.0.0)

| Operating System | Architecture | Download |
|------------------|--------------|----------|
| 🍎 **macOS** | Apple Silicon (M1/M2/M3) | [Download DMG](https://github.com/toolmaster-tech/skool-class-downloader/releases/download/v1.0.0/Skool.Class.Downloader-1.0.0-arm64.dmg) |
| 🍎 **macOS** | Intel | [Download DMG](https://github.com/toolmaster-tech/skool-class-downloader/releases/download/v1.0.0/Skool.Class.Downloader-1.0.0-x64.dmg) |
| 🪟 **Windows** | x64 | [Download EXE](https://github.com/toolmaster-tech/skool-class-downloader/releases/download/v1.0.0/Skool.Class.Downloader-1.0.0-x64.exe) |
| 🐧 **Linux** | AppImage | [Download AppImage](https://github.com/toolmaster-tech/skool-class-downloader/releases/download/v1.0.0/Skool.Class.Downloader-1.0.0-x86_64.AppImage) |
| 🐧 **Linux** | Debian/Ubuntu | [Download DEB](https://github.com/toolmaster-tech/skool-class-downloader/releases/download/v1.0.0/Skool.Class.Downloader-1.0.0-amd64.deb) |

> 📋 See all releases: [Releases Page](https://github.com/toolmaster-tech/skool-class-downloader/releases)

## Features

- 📚 **Download Skool Courses** - Save courses from your Skool communities
- 🎬 **Video Support** - Downloads videos from Mux, Vimeo, Loom, and YouTube
- 🖼️ **Media & Attachments** - Saves images and file attachments
- ⏸️ **Pause/Resume** - Control your downloads with pause and resume
- 🔄 **Re-download** - Update previously downloaded courses
- 📁 **Organized Storage** - Courses organized by Community/Course structure
- 💻 **Cross-Platform** - Works on macOS, Windows, and Linux

## Pricing

| Plan | Price | Features |
|------|-------|----------|
| **Free** | $0 | 1 course download |
| **Premium** | License Key | Unlimited downloads |

## Installation

### 🍎 macOS

1. Download the DMG file for your Mac (Apple Silicon or Intel)
2. Open the DMG file
3. Drag "Skool Class Downloader" to Applications
4. **First launch**: Right-click the app and select "Open" (required for unsigned apps)
5. The app will automatically install required dependencies (yt-dlp, ffmpeg) via Homebrew

> **Note**: If you don't have Homebrew installed, the app will install it automatically. If auto-install fails, you can install manually:
> ```bash
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
> brew install yt-dlp ffmpeg
> ```

### 🪟 Windows

1. Download the EXE installer
2. Run the installer and follow the wizard
3. **Install dependencies manually** (the app will guide you):

   **Option A - Using winget (recommended):**
   ```powershell
   winget install yt-dlp
   winget install ffmpeg
   ```

   **Option B - Manual download:**
   - Download [yt-dlp.exe](https://github.com/yt-dlp/yt-dlp/releases/latest) and place it in a folder in your PATH
   - Download [FFmpeg](https://www.gyan.dev/ffmpeg/builds/) and add the `bin` folder to your PATH

4. Restart the app after installing dependencies

### 🐧 Linux

**AppImage:**
1. Download the AppImage file
2. Make it executable and run:
   ```bash
   chmod +x Skool*.AppImage
   ./Skool*.AppImage
   ```

**Debian/Ubuntu (.deb):**
```bash
sudo dpkg -i Skool*.deb
```

**Install dependencies:**
The app will attempt to auto-install using your package manager. If it fails:

```bash
# Ubuntu/Debian
sudo apt update
sudo apt install yt-dlp ffmpeg

# Fedora
sudo dnf install yt-dlp ffmpeg

# Arch Linux
sudo pacman -S yt-dlp ffmpeg
```

## Requirements

The app requires these tools for video downloads:

| Dependency | Purpose | Auto-Install |
|------------|---------|--------------|
| **yt-dlp** | Downloads videos from various platforms | ✅ Mac/Linux, ❌ Windows |
| **ffmpeg** | Video processing and conversion | ✅ Mac/Linux, ❌ Windows |

> On **macOS** and **Linux**, dependencies are installed automatically on first launch.
> On **Windows**, you need to install them manually (see installation instructions above).

## Getting Started

1. Download and install the app for your platform
2. Launch the app (dependencies will auto-install on Mac/Linux)
3. Upload your Skool cookies (use the EditThisCookie browser extension)
4. Select a community and course
5. Click Download!

## License Activation

Have a license key? Activate it in **Settings > License** to unlock unlimited downloads.

## Support

- 🐛 **Bug Reports**: [Open an issue](https://github.com/toolmaster-tech/skool-class-downloader/issues/new?template=bug_report.md)
- 💡 **Feature Requests**: [Open an issue](https://github.com/toolmaster-tech/skool-class-downloader/issues/new?template=feature_request.md)
- ❓ **Questions**: [Start a discussion](https://github.com/toolmaster-tech/skool-class-downloader/discussions)

## Legal

This software is proprietary. Unauthorized copying, distribution, or modification is prohibited.

**Disclaimer**: This tool is for personal use only. Please respect the terms of service of Skool.com and the content creators. Only download courses from communities you are a legitimate member of.

---

<p align="center">Made with ❤️ by <a href="https://toolmaster.tech/">Tool Master Technology</a></p>
