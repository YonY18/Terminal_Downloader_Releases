#🚀 Terminal Downloader – Official Releases

Welcome to the official release repository for Terminal Downloader.

This repository serves as the distribution hub for production-ready Windows builds.

Note: The source code is maintained in a private repository for development.

---

## 📦 What is Terminal Downloader?

**Terminal Downloader** is a powerful and lightweight desktop application designed for high-quality media extraction. It allows you to download both audio and video content with a single click, featuring a sleek "Dark Mode" interface and real-time technical logs.

---

## 🌐 Supported Platforms

  -  🎥 YouTube (including Shorts)

  -  🎵 YouTube Music

  -  📸 Instagram (Reels & Video)

  -  👥 Facebook

  -  ⚡ And many more via universal engine updates.

---

## ⬇️ Download
![Downloads](https://img.shields.io/github/downloads/YonY18/Terminal_Downloader_Releases/total?style=for-the-badge&color=red)

1. **Go to the latest Release:**
   👉 [Download Latest Version](https://github.com/YonY18/Terminal_Downloader_Releases/releases/latest)

2. **Download the executable:**
   Look for the `Terminal_Downloader_vX.X.X.exe` file in the **Assets** section.

3. **Run the App:**
   Double-click to start downloading.

> [!IMPORTANT]
> **Windows SmartScreen:** Because the app is not code-signed, Windows may show a warning. 
> Click **"More info"** and then **"Run anyway"**. The app is 100% safe and verified by the SHA256 hashes provided.

---
### 🐧 Linux Installation (Ubuntu/Debian)
1.  Download the `terminal-downloader_vX.X.X_amd64.deb` package.
2.  Install it using your package manager or the terminal:
    ```bash
    sudo apt install ./terminal-downloader_vX.X.X_amd64.deb
    ```
3.  **Note:** Requires `ffmpeg` (It is automatically installed as a dependency).

---

## 🔄 Automatic Updates

Terminal Downloader features a built-in update detection system:
- The app checks for the latest version on startup.
- If a new version is found, a subtle notification appears in the footer.
- You can also check manually using the **"CHECK UPDATES"** button.

---

## 🔐 Security & Integrity

Every release is published with a unique **SHA256 checksum** generado automáticamente por nuestro sistema de build de GitHub Actions para asegurar que el archivo no haya sido alterado.

**Cómo verificar:**
* **Windows (PowerShell):**
    ```powershell
    Get-FileHash .\TerminalDownloader_vX.X.X.exe -Algorithm SHA256
    ```
* **Linux (Terminal):**
    ```bash
    sha256sum terminal-downloader_vX.X.X_amd64.deb
    ```

Compare it with the hash published in the release notes.

---
## 🛠️ Tech Stack

- Language: Python 3.x

- UI: Tkinter with Custom Dark Styles

- Core: Based on the yt-dlp engine

---

## 🐞 Reporting Issues

This repository is for binary releases only.

For bug reports or feature requests, please contact the developer directly.

---

## 👨‍💻 Author

Developed by **Jonathan P**

---

## 📜 License & Usage

© 2026 Jonathan P. All rights reserved.
 - This software is distributed "as is" for educational and personal use.
 - Use responsibly and respect the terms of service of the supported platforms.
