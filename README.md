# LCS Ventoy BootLab

Official downloads and signed updates by LayerCraft Studio.

[Download the latest release](https://github.com/AdminBotLCS/LCS-BootLab-Releases/releases/latest)

- **Setup EXE**: installation wizard for Windows 10/11 (64 bit).
- **Portable ZIP**: extract and run `LCS-VentoyBootLab.exe`. Keep the portable `data` folder when updating manually.
- **Handbook PDF**: complete offline manual, also embedded in the app.

Starting with version 0.6.5, BootLab checks for updates at startup. Users can update or keep their current version. Versions up to 0.6.4 require one manual upgrade to enable this feature.

Updates use an RSA-SHA-256 signed `update.json` manifest and verify the size and SHA-256 of downloads before execution. The private signing key is never distributed. Windows executables are currently self-signed; Windows may display a publisher trust warning.

This repository distributes release binaries and update metadata. Application source code is maintained separately.

Independent Ventoy management tool. Not an official Ventoy product.
