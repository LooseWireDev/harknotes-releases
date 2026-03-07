# Harknotes Releases

Download the latest version of [Harknotes](https://harknotes.app) — privacy-first meeting transcription that runs locally on your machine.

## Downloads

Head to the [latest release](https://github.com/LooseWireDev/harknotes-releases/releases/latest) and grab the right package for your platform:

| Platform | Format | Notes |
|----------|--------|-------|
| macOS | `.dmg` | macOS 13+ (Apple Silicon & Intel) |
| Linux | `.AppImage` | Universal — runs on any distro |
| Linux | `.deb` | Debian, Ubuntu, Mint, Pop!_OS |
| Linux | `.rpm` | Fedora, RHEL, openSUSE |

## macOS: "Open Anyway"

Harknotes is not yet notarized with Apple. After installing, macOS will block the app on first launch.

1. Open the DMG and drag Harknotes to Applications
2. Try to open Harknotes (it will be blocked)
3. Go to **System Settings → Privacy & Security**
4. Scroll down and click **"Open Anyway"** next to Harknotes

You only need to do this once.

## Linux

**AppImage:**
```bash
chmod +x Harknotes-*.AppImage
./Harknotes-*.AppImage
```

**DEB:**
```bash
sudo dpkg -i harknotes_*.deb
```

**RPM:**
```bash
sudo rpm -i harknotes-*.rpm
```

## About

Harknotes captures and transcribes meetings using whisper.cpp — entirely on your device. No bot joins your calls, no audio leaves your machine.

- Website: [harknotes.app](https://harknotes.app)
- Privacy: [harknotes.app/harknotes/privacy](https://harknotes.app/harknotes/privacy)
