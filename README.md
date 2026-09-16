# DiskScape

![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black) ![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-native-black) ![v1.0.0](https://img.shields.io/badge/version-1.0.0-blue)

**[🌐 diskscape-site.vercel.app](https://diskscape-site.vercel.app)** ·
**[⬇ Download DiskScape 1.0.0](../../releases/latest/download/DiskScape-1.0.0.dmg)**

Native macOS disk space analyzer. See what's eating your disk, stage a cleanup,
never lose anything to the Trash by accident.

- **Treemap + ranked list** — two ways to see the same scan, instant switching
- **Quick wins** — node_modules, Rust targets, Xcode DerivedData, simulators, caches, logs
- **Duplicates** — byte-for-byte SHA256 matching; click any copy to choose the keeper
- **Uninstaller** — apps plus their Library leftovers, sized and staged together
- **Staged cleanup** — nothing deletes behind your back; everything goes to the Trash after review

## Install

1. Download the DMG
2. Open it and drag **DiskScape** into Applications
3. First launch: right-click → **Open** if Gatekeeper asks (the app is notarized — this is only needed on some setups)

Requires macOS 14 or later. Apple Silicon.

Signed with a Developer ID certificate and notarized by Apple.

## Notes

- This repository hosts DiskScape releases. The source code is private.
- Every release is scanned by notarization before upload.
