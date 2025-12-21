# APYTDLP

Adrenaline Powered YT-DLP Batch Frontend for Windows
----------------------------------------------------

APYTDLP is a highly configurable, interactive Batch-based frontend for 
[yt-dlp](https://github.com/yt-dlp/yt-dlp), focused on power users who prefer
keyboard-driven workflows and full control over download behavior.

This is the first public release of APYTDLP.  
🔥The project is currently in **beta** and is actively developed.

---

## Features

- Video, audio, and batch downloads
- Simultaneous download windows management
- Youtube Search support 
- YT-DLP configuration via menus
- Script configuration and theming
- Persistent configuration and backups
- Logging and history tracking
- Optional PowerShell 5 / PowerShell 7 integration
- Zero external GUI dependencies

---

## Requirements

- ![Static Badge](https://img.shields.io/badge/Required-lightgreen?style=flat-square) Microsoft Windows 8 or newer
- ![Static Badge](https://img.shields.io/badge/Required-lightgreen?style=flat-square) Internet connection
- ![Static Badge](https://img.shields.io/badge/Optional-lightblue?style=flat-square) PowerShell (for advanced features)

---

## Third-party tools used by the script
- [![Static Badge](https://img.shields.io/badge/YT--DLP-blue)](https://github.com/yt-dlp/yt-dlp)<br>
- [![Static Badge](https://img.shields.io/badge/7ZR-blue)](https://www.7-zip.org)<br>
- [![Static Badge](https://img.shields.io/badge/FFMPEG-blue)](https://www.ffmpeg.org)<br>

All required third-party tools in the newest versions are automatically downloaded by the script.

---

## Installation

1. [![Static Badge](https://img.shields.io/badge/Download-green?style=plastic)](https://github.com/andyapo/APYTDLP/releases/download/v6.5-beta/APYTDLP.cmd) the latest release from:<br>
**https://github.com/andyapo/APYTDLP/releases/download/v6.5-beta/APYTDLP.cmd**
2. Place the script into any directory
3. Double click the file **APYTDLP.cmd** or run it from Command Prompt. If Windows SmartScreen message appears, choose “More info” → “Run anyway”
4. First run may take longer due to 3rd party tool checks and downloads

---

## Notes
- This release is intended for **Windows 8.1 and newer**
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

☝️To ensure the file has not been tampered with, verify its size and SHA-265 cheksum.<br>
**Size:**<br>
445 458 bytes<br>
**SHA-256**:<br>
C3D59BD09F8CE53033654576D6CB8C8A7A0FE5AA8B521064310FB9CBF80BA225<br>

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
© 2023–2025 andyapo
