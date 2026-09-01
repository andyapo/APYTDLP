# APYTDLP - Batch frontend for yt-dlp and FFmpeg<br>
**Download and convert videos from a single interactive CLI interface.**

[![Download](https://img.shields.io/badge/Download-Latest%20Release-brightgreen?style=for-the-badge)](https://github.com/andyapo/APYTDLP/releases/latest/download/APYTDLP.cmd)<br>

> **No installation needed** — just download and run

![Windows 10+](https://img.shields.io/badge/Windows-10%2B-blue)
![Release](https://img.shields.io/github/v/release/andyapo/APYTDLP)
![License](https://img.shields.io/github/license/andyapo/APYTDLP)
![Downloads](https://img.shields.io/github/downloads/andyapo/APYTDLP/total)
![Stars](https://img.shields.io/github/stars/andyapo/APYTDLP)


APYTDLP is a keyboard-driven Batch **media toolkit** and **frontend** for `yt-dlp` and `FFmpeg` used for:

+ **downloading** videos and audio
+ **converting** videos
+ **media toolkit** with quick lossless processing

The project is designed for power users who prefer **keyboard workflows,
fine-grained control and transparent configuration** rather than graphical frontends.

✅ The project is actively maintained.

---

## Features

### Downloading
- Video and audio downloads powered by **yt-dlp**
- Multiple simultaneous download windows
- Built-in **YouTube search**
- URL list loading, saving and management

### Converting
- Video conversion powered by **FFmpeg**
- Software and hardware encoder support
- Profile and bit depth support
- Flexible bitrate / quality configuration
- Speed change support
- Batch mode for converting all media files in entire folder structure
- Media info

### Media Toolkit
- Change container format
- Extract audio/subtitle stream to a file
- Add audio/subtitle stream with advanced options
- Add multiple audio/subtitle/thumbnail streams
- Remove streams from within container
- Edit stream metadata
- Change time offset of the streams
- Create a short media clip

### Environment management
- Automatic download and update of required tools
- Self-contained runtime environment
- Single-instance execution protection

### Customization
- yt-dlp and FFmpeg configuration via menus
- Script theming and console customization
- Persistent configuration with backup system
- Logging and history tracking
- Optional PowerShell integration

---

## Screenshots

### MAIN MENU and Configuration Screens
<p align="center">
<img src="docs/images/start_page-90.png" width="400" alt="APYTDLP Start page">
<img src="docs/images/main_menu-90.png" width="400" alt="APYTDLP Main menu">
<img src="docs/images/yt-dlp_configuration-90.png" width="400" alt="APYTDLP YT-DLP Configuration">
<img src="docs/images/script_configuration-90.png" width="400" alt="APYTDLP Script Configuration">
</p>

---

### Download and YouTube search
<p align="center">
<img src="docs/images/download_result-90.png" width="400" alt="APYTDLP Download result">
<img src="docs/images/youtube_search-90.png" width="400" alt="APYTDLP Youtube search">
</p>

---

### Video Converter | Conversion result | Media Toolkit | Media Inspector
<p align="center">
<img src="docs/images/converter_menu-90.png" width="400" alt="APYTDLP Video Converter menu">
<img src="docs/images/conversion_result-90.png" width="400" alt="APYTDLP Video Converter Conversion result">
<img src="docs/images/media_toolkit-90.png" width="400" alt="APYTDLP Video Converter Media Toolkit">
<img src="docs/images/media_inspector_details-90.png" width="400" alt="APYTDLP Video Converter Media Inspector">
</p>

---

### Video Converter Configuration Screens
<p align="center">
<img src="docs/images/converter_config1-90.png" width="400" alt="APYTDLP Video Converter Configuration 1">
<img src="docs/images/converter_config2-90.png" width="400" alt="APYTDLP Video Converter Configuration 2">
<img src="docs/images/converter_config3-90.png" width="400" alt="APYTDLP Video Converter Configuration 3">
<img src="docs/images/converter_config4-90.png" width="400" alt="APYTDLP Video Converter Configuration 4">
</p>

---

## Requirements

- Windows **10 or newer**
- Internet connection

Optional:
- PowerShell (for some advanced features)

---

## Third-party tools used by the script
- [![Static Badge](https://img.shields.io/badge/YT--DLP-blue)](https://github.com/yt-dlp/yt-dlp)<br>
- [![Static Badge](https://img.shields.io/badge/FFmpeg-blue)](https://www.ffmpeg.org)<br>
- [![Static Badge](https://img.shields.io/badge/deno-blue)](https://github.com/denoland/deno)<br>
- [![Static Badge](https://img.shields.io/badge/7ZR-blue)](https://www.7-zip.org)<br>
- [![Static Badge](https://img.shields.io/badge/Unzip-blue)](https://infozip.sourceforge.net)<br>
- [![Static Badge](https://img.shields.io/badge/ChromeCookieUnlock-blue)](https://github.com/seproDev/yt-dlp-ChromeCookieUnlock)<br>
- [![Static Badge](https://img.shields.io/badge/APSETSCR-blue)](https://github.com/andyapo/APSETSCR)<br>

All required third-party tools in the newest versions are automatically downloaded by the script.

---

## Installation

1. Download the latest release from:<br>
**https://github.com/andyapo/APYTDLP/releases/latest/download/APYTDLP.cmd**

3. Place the script into any directory
4. Double click the file **APYTDLP.cmd** or run it from Command Prompt. If Windows SmartScreen message appears, choose “More info” → “Run anyway”
5. First run may take longer due to 3rd party tool checks and downloads

---

## Notes
- This release is intended for **Windows 10 and newer**
- Configuration and user data are stored per-user in `%APPDATA%`
- What started as a small, simple script two and a half years ago gradually evolved over time.
  As more features were added, I decided to share the project in its current state.
  This is a hobby project, so it may contain bugs or lack certain features.
  Constructive feedback and suggestions for improvement are very welcome.


---

## Security Notice

APYTDLP is distributed as plain Batch source code.<br>
It's an independent project and is not affiliated with or endorsed by the yt-dlp authors.

- You are encouraged to **review the script** before running.
- Only releases from the **official repository** should be trusted.
- Modified versions are **not supported** by the author.
- The author is **not responsible** for any issues caused by unofficial versions.
- This script is unsigned; for code-signing verification see the repository instructions.

---

### Integrity Check

☝️To ensure the file has not been tampered with, verify its size and SHA-256 checksum.<br>
**Version:**<br>
9.0<br>
**Size:**<br>
1 030 133 bytes<br>
**SHA-256**:<br>
779c9654ba5f50c2dec6627d8579e53645441f61f82da57dd00a95e4f06e78b3<br>

To verify SHA-256, please run:<br>
**Command Prompt**:<br>
```bat
certutil -hashfile APYTDLP.cmd SHA256
```

**PowerShell**:<br>
```powershell
Get-FileHash .\APYTDLP.cmd -Algorithm SHA256
```

⚠️ If the checksum does not match, do not run the file and download the latest version directly from this repository.

---

## License

MIT License
© 2023–2026 andyapo
