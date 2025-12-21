# APYTDLP

Adrenaline Powered YT-DLP Batch Frontend for Windows
----------------------------------------------------

APYTDLP is a highly configurable, interactive Batch-based frontend for
[yt-dlp](https://github.com/yt-dlp/yt-dlp), focused on power users who prefer
keyboard-driven workflows and full control over download behavior.

This is the first public release of APYTDLP.  
The project is considered **beta** and actively developed.

---

## Features

- Video, audio, and batch downloads
- Simultaneous download windows management
- YT-DLP configuration via menus
- Script configuration and theming
- Persistent configuration and backups
- Logging and history tracking
- Optional PowerShell 5 / PowerShell 7 integration
- Zero external GUI dependencies

---

## Requirements

- Microsoft Windows 8 or newer
- PowerShell (optional)
  
Third-party tools:
- `yt-dlp`
- `7zr`
- `ffmpeg`

All required third-party tools in the newest versions are automatically downloaded by the script.

---

## Installation

1. Download the latest release from:
   **https://github.com/andyapo/APYTDLP/releases/download/v6.5-beta/APYTDLP65beta.cmd**
2. Place the script into any directory
3. Run it from Command Prompt
4. First run may take longer due to initialization and tool checks

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

This script is distributed as plain Batch source code.

- You are encouraged to review it before running.
- Only releases from the official repository should be trusted.
- Modified versions are **not supported** by the author.
- This script is unsigned; for code-signing verification see the repository instructions.

---

## Integrity Check

To ensure the file has not been tampered with, verify its SHA-256 checksum:
C3D59BD09F8CE53033654576D6CB8C8A7A0FE5AA8B521064310FB9CBF80BA225

On Windows, run:
certutil -hashfile APYTDLP65beta.cmd SHA256

PowerShell alternative:
Get-FileHash .\APYTDLP65beta.cmd -Algorithm SHA256

If the checksum does not match, do not run the file and download the latest version directly from this repository.

---

## License

MIT License
© 2023–2025 andyapo
