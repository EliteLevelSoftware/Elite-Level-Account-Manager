<div align="center">

<img src="https://imgur.com/a/s0WE2OY" width="120" />

# Elite Multi-Client
### by Elite Level Software

**Launch and manage multiple Roblox accounts simultaneously.**

![Version](https://img.shields.io/badge/version-1.0.0-red?style=flat-square&color=701F27)
![Platform](https://img.shields.io/badge/platform-Windows-blue?style=flat-square)
![License](https://img.shields.io/badge/license-UNLICENSED-gold?style=flat-square&color=D4AF37)

</div>

---

## Features

- **Multi-Account Management** — Add accounts via browser login or cookie import. Supports groups and aliases.
- **Per-Account Game Selection** — Each account remembers its own game dropdown independently.
- **Launch Presets** — Save and reuse multi-client launch configurations instantly.
- **Saved Games Library** — Bookmark your favourite games for quick access.
- **Roblox Charts Dashboard** — Browse top trending games directly inside the app.
- **Window Layout Editor** — Arrange Roblox windows across monitors with drag-and-drop cells and merging.
- **Active Clients Monitor** — Live view of running instances with per-client close controls.
- **Multi-Instance** —  Multiple clients run without conflict.
- **Focus Toggle Hotkey** — Bindable hotkey that expands any focused Roblox window to fill its monitor, then restores it to its original position on second press.

---

## Requirements

- Windows 10 / 11 (x64)
- .NET Framework 4.x *(pre-installed on most Windows machines)*

---

## Installation

1. Download `Elite Multi-Client Setup 1.0.0.exe` from the [Releases](../../releases) page
2. Run the installer
3. Launch **Elite Multi-Client** from your desktop or Start Menu

---

## Getting Started

### Adding Accounts
1. Go to the **Accounts** page
2. Click **Add Account** and log in via the browser login flow
3. Your cookie is imported automatically once you're signed in

### Launching Multiple Clients
1. Go to the **Launcher** page
2. Select accounts and assign a game to each via the dropdown
3. Click **Launch Selected**

### Fix Now (Mutex)
If Roblox is already running when you open the app, a warning banner will appear. Click **Fix Now** — this closes all running Roblox instances and reholds the multi-instance mutex so new clients launch correctly.

### Focus Toggle Hotkey
1. Go to **Settings** → *Focus Toggle Hotkey*
2. Click the input and press your desired key combo (e.g. `Alt+F`)
3. Click **Set**
4. While a Roblox window is focused, press the hotkey to expand it fullscreen — press again to restore

---

## Data & Privacy

All account data is stored locally on your machine at:
```
%APPDATA%\elite-multi-client\elite-multi-client\
```
Nothing is transmitted externally. No account info is bundled into the installer.

---

<div align="center">

Made with ❤️ by **Elite Level Software**

[Discord](https://discord.gg/elitelevelsoftware) • [GitHub](https://github.com/EliteLevelSoftware)

</div>
