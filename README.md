<div align="center">

<img src="https://i.imgur.com/cZJZNQd.png" width="120" />

# Elite Level Account Manager
### by Elite Level Software

**Launch and manage multiple Roblox accounts simultaneously — now with a fully reimagined glass UI.**

![Version](https://img.shields.io/badge/version-2.0.0-red?style=flat-square&color=701F27)
[![Electron](https://img.shields.io/badge/Built%20With-Electron-47848F?style=flat-square&logo=electron)](https://www.electronjs.org/)
![Platform](https://img.shields.io/badge/platform-Windows-blue?style=flat-square)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](https://github.com/EliteLevelSoftware/Elite-Level-Account-Manager)
![Downloads](https://img.shields.io/github/downloads/EliteLevelSoftware/Elite-Level-Account-Manager/total?style=flat-square&color=701F27&label=downloads)

</div>

---

## What's New in 2.0.0

- **Complete visual overhaul** — real Windows Acrylic blur-behind, tinted glass panels, gold-accented toggles and scrollbars, themed dropdowns
- **Anti-AFK** — briefly focuses the window and sends a real keypress to prevent idle-kick, then restores your previous window. Configurable action, interval, and per-account toggle, with built-in statistics
- **Auto-Relaunch** — automatically relaunches an account if it closes unexpectedly (crash, kick, disconnect), with a safety cap
- **Performance / Graphics Limiting** — FPS cap and graphics quality override across all launched clients, for smoother multi-boxing
- **Update Checker** — checks for new releases on launch, Discord-style, with a Settings toggle to disable
- **Faster, more reliable mutex handling** — Fix Now now verifies Roblox has fully closed before reholding, instead of guessing

See the full [Changelog](CHANGELOG.md) for details.

---

## Features

- **Multi-Account Management** — Add accounts via browser login or cookie import. Supports groups and aliases.
- **Per-Account Game Selection** — Each account remembers its own game dropdown independently.
- **Anti-AFK** — Keeps accounts active in-game with a configurable action and interval, per-account.
- **Auto-Relaunch** — Automatically brings a client back up if it closes unexpectedly.
- **Performance Limiting** — Cap FPS and reduce graphics load across all clients.
- **Launch Presets** — Save and reuse multi-client launch configurations instantly.
- **Saved Games Library** — Bookmark your favorite games for quick access.
- **Roblox Charts Dashboard** — Browse top trending games directly inside the app.
- **Window Layout Editor** — Arrange Roblox windows across monitors with drag-and-drop cells and merging.
- **Active Clients Monitor** — Live view of running instances with per-client close controls.
- **Multi-Instance** — Multiple clients run without conflict.
- **Focus Toggle Hotkey** — Bindable hotkey that expands any focused Roblox window to fill its monitor, then restores it to its original position on second press.
- **Update Checker** — Automatically checks for new releases so you're never behind.

---

## Requirements

- Windows 10 / 11 (x64)
- .NET Framework 4.x *(pre-installed on most Windows machines)*

---

## Installation

1. Download `Elite Level Account Manager 2.0.0.exe` from the [Releases](../../releases) page
2. Run the installer
3. Launch **Elite Level Account Manager** from your desktop or Start Menu

---

## Getting Started

### Adding Accounts
1. Go to the **Accounts** page
2. Click **Add Account** and log in via the browser login flow
3. Your cookie is imported automatically once you're signed in

### Launching Multiple Clients
1. Go to the **Launcher** page
2. Select accounts and assign a game to each via the dropdown
3. Toggle 🔁 Auto-Relaunch or 💤 Anti-AFK per account as needed
4. Click **Launch Selected**

### Anti-AFK
1. Enable the 💤 toggle for any account on the **Launcher** page
2. Configure the action and interval in **Settings** → *Anti-AFK*
3. Use **Test Action** to confirm it's working, and check the built-in statistics for actions performed

### Performance Limiting
1. Go to **Settings** → *Performance / Graphics Limiting*
2. Enable and configure FPS cap / graphics quality — applies to every launched client

### Fix Now (Mutex)
If Roblox is already running when you open the app, a warning banner will appear. Click **Fix Now** — this closes all running Roblox instances, verifies they're fully closed, and reholds the multi-instance mutex so new clients launch correctly.

### Focus Toggle Hotkey
1. Go to **Settings** → *Focus Toggle Hotkey*
2. Click the input and press your desired key combo (e.g. `Alt+F`)
3. Click **Set**
4. While a Roblox window is focused, press the hotkey to expand it fullscreen — press again to restore

### Updates
The app checks for new releases automatically on launch and shows a banner if one's available. Disable this in **Settings** → *Updates*, or check manually anytime with **Check Now**.

---

## Data & Privacy

All account data is stored locally on your machine at: %APPDATA%\Elite-Level-Account-Manager\Elite-Level-Account-Manager\
Nothing is transmitted externally. No account info is bundled into the installer.

---

## License

© 2026 Elite Level Software. All rights reserved.
This software is proprietary. Redistribution or modification without written permission from Elite Level Software is prohibited.

---

<div align="center">
  Made with ❤️ by <strong>Elite Level Software</strong>
</div>
