# Skool Class Downloader v1.1.0

## What's New in v1.1.0

### Video Playback Improvements 🎬
- **Enhanced Codec Support**: Videos now prefer H.264 format for maximum compatibility
- **Hardware Acceleration**: Enabled for smoother video playback
- **Better Error Handling**: Clear error messages when videos fail to play
- **Loom Video Support**: Improved compatibility with Loom video downloads
- **Codec Detection**: Automatic detection of supported video codecs

### Bug Fixes
- Fixed video playback issues for users experiencing codec compatibility problems
- Improved video download format selection for better playback reliability
- Enhanced error messages to help users understand video issues

## Previous Features (v1.0.0)

### Freemium Model
- **Free Tier**: Download 1 course for free
- **Premium**: Unlimited course downloads with a valid license key

### Core Features
- Download courses from Skool.com communities you're a member of
- Supports video downloads (Mux, Vimeo, Loom, YouTube)
- Downloads images and attachments
- Pause/Resume/Cancel downloads
- Re-download courses to update content
- Organized storage by Community/Course structure
- Cross-platform support (macOS, Windows, Linux)

## Download

Choose the right version for your operating system:

### macOS
- **Apple Silicon (M1/M2/M3)**: `Skool Class Downloader-1.1.0-arm64.dmg`
- **Intel Mac**: `Skool Class Downloader-1.1.0-x64.dmg`

### Windows
- **Installer**: `Skool Class Downloader-1.1.0-x64.exe`

### Linux
- **AppImage**: `Skool Class Downloader-1.1.0-x86_64.AppImage`
- **Debian/Ubuntu**: `Skool Class Downloader-1.1.0-amd64.deb`

## Installation

### macOS
1. Download the DMG file for your Mac type
2. Open the DMG file
3. Drag "Skool Class Downloader" to Applications
4. On first launch, right-click and select "Open" to bypass Gatekeeper

### Windows
1. Download the EXE installer
2. Run the installer
3. Follow the installation wizard

### Linux
**AppImage:**
1. Download the AppImage file
2. Make it executable: `chmod +x Skool*.AppImage`
3. Run it: `./Skool*.AppImage`

**Debian/Ubuntu:**
```bash
sudo dpkg -i Skool*.deb
```

## Requirements

- **yt-dlp**: Required for video downloads
- **ffmpeg**: Required for video processing

The app will guide you through installing these dependencies on first launch.

## License Activation

To unlock unlimited downloads:
1. Go to Settings tab
2. Enter your license key (format: XXXX-XXXX-XXXX-XXXX)
3. Click "Activate"

## Support

For issues and feature requests, please use the [GitHub Issues](https://github.com/toolmaster-tech/skool-class-downloader/issues) page.
