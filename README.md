<div align="center">

# Keypad Studio

**A modern, cross-platform configurator for "MINI KeyBoard" macro keypads.**

Remap keys, record macros, drive multiple layers, switch presets per app, and light up the
RGB — all from a clean desktop UI, on macOS, Windows, and Linux.

[![Latest release](https://img.shields.io/github/v/release/keypad-studio/keypad-studio?label=latest&sort=semver)](https://github.com/keypad-studio/keypad-studio/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/keypad-studio/keypad-studio/total?label=downloads)](https://github.com/keypad-studio/keypad-studio/releases)
[![Platforms](https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey)](#download)

</div>

---

## Download

Grab the latest installer for your platform — these links always resolve to the most recent
release:

| Platform | Download |
|---|---|
| macOS (Apple Silicon) | [KeypadStudio-macos-arm64.dmg](https://github.com/keypad-studio/keypad-studio/releases/latest/download/KeypadStudio-macos-arm64.dmg) |
| Windows (x64) | [KeypadStudio-windows-x64.exe](https://github.com/keypad-studio/keypad-studio/releases/latest/download/KeypadStudio-windows-x64.exe) |
| Debian / Ubuntu / Linux Mint (x64) | [KeypadStudio-linux-x64.deb](https://github.com/keypad-studio/keypad-studio/releases/latest/download/KeypadStudio-linux-x64.deb) |
| Debian / Ubuntu / Raspberry Pi OS 64-bit (arm64) | [KeypadStudio-linux-arm64.deb](https://github.com/keypad-studio/keypad-studio/releases/latest/download/KeypadStudio-linux-arm64.deb) |
| Linux (x64) | [KeypadStudio-linux-x64-appimage.AppImage](https://github.com/keypad-studio/keypad-studio/releases/latest/download/KeypadStudio-linux-x64-appimage.AppImage) |
| Linux / Raspberry Pi OS 64-bit (arm64) | [KeypadStudio-linux-arm64-appimage.AppImage](https://github.com/keypad-studio/keypad-studio/releases/latest/download/KeypadStudio-linux-arm64-appimage.AppImage) |

Older versions and full release notes live on the
[**Releases**](https://github.com/keypad-studio/keypad-studio/releases) page.

## Installing

- **macOS** — open the `.dmg` and drag Keypad Studio to Applications. Builds are code-signed and
  notarized when signing is configured; otherwise the first launch needs a right-click → **Open**
  to bypass Gatekeeper on the unsigned app.
- **Windows** — run the `.exe` installer. It installs per-user (no admin required).
- **Linux (Debian family / Raspberry Pi OS 64-bit)** —
  ```bash
  sudo apt install ./KeypadStudio-linux-x64.deb     # or the arm64 file on a Pi / arm64
  ```
- **Linux (AppImage, other distros)** —
  ```bash
  chmod +x KeypadStudio-linux-*-appimage.AppImage
  ./KeypadStudio-linux-*-appimage.AppImage
  ```

> On Linux the app uses raw USB HID access plus X11 desktop integration, so it needs a little
> one-time setup (a `udev` rule and an X11 session). The app's first-run checklist walks you
> through it.

## What it does

- **Remap keys & record macros** across the pad's keys and rotary knob(s).
- **Layers** — multiple key layouts you can switch between on the fly.
- **Per-app presets** — the active layout follows whichever app is in focus.
- **Reusable key library** — build a key once, drop it onto any slot.
- **Host actions** — launch an app or open a URL straight from a key.
- **RGB control** — set the backlight modes and colors the pad supports.

## Supported hardware

Keypad Studio targets the affordable USB "MINI KeyBoard" macro keypads (3×4 / 3×2 / 6×4 layouts sold
under many brand names) built on the **CH57x-family** firmware that enumerates under USB vendor ID
`0x1189`. It speaks the same HID protocol as the bundled Windows-only vendor tool, but adds a
polished native app on all three desktops plus features the original never had.

## Privacy & license

Keypad Studio has no built-in analytics or telemetry. It is currently a private/proprietary beta.

_Have an issue or a hardware variant to report? Use the contact link in the website footer._
