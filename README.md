# AutoTube Studio — Releases

Download the latest version of **AutoTube Studio** for your platform.

---

## Download

| Platform | File | Notes |
|----------|------|-------|
| macOS | `AutoTube-Studio.dmg` | Apple Silicon (M1 / M2 / M3 / M4) |
| Windows | `AutoTube-Studio-Setup.exe` | Windows 10 / 11 64-bit |
| Linux | `AutoTube-Studio.AppImage` | Ubuntu, Debian, Arch |

→ **[View all releases](https://github.com/Tattva-Mind/autotube-studio-releases/releases)**

---

## Install

### macOS

1. Open the `.dmg` and drag **AutoTube Studio** to your Applications folder.
2. On first launch macOS may show a **"damaged app"** warning — this is Gatekeeper blocking unsigned apps, not an actual problem.
3. Run this once in Terminal to fix it:

   ```bash
   xattr -cr "/Applications/AutoTube Studio.app"
   ```

4. Open the app normally.

> **Alternative:** Go to **System Settings → Privacy & Security** and click **Open Anyway**.

---

### Windows

1. Run `AutoTube-Studio-Setup.exe`.
2. If Windows SmartScreen shows a warning, click **More info → Run anyway**.
3. Follow the installer steps.

---

### Linux

1. Make the file executable:

   ```bash
   chmod +x AutoTube-Studio.AppImage
   ```

2. Run it:

   ```bash
   ./AutoTube-Studio.AppImage
   ```

---

## About

AutoTube Studio is a native desktop app that runs a full AI video pipeline locally — script, visuals, voiceover, and YouTube upload — with no external AI subscriptions.  
Source code lives in the private [autotube-studio](https://github.com/Tattva-Mind/autotube-studio) repository.

Built by [Tattva Mind](https://github.com/Tattva-Mind).
