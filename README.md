# 0KCK

![Banner](https://i.postimg.cc/MTb8QxJB/image-2026-03-10-010117357.png)

0KCK is an external cheat client for FPS games like Rainbow Six Siege and COD. It combines anti-recoil, 
weapon presets, and advanced macros in one tool, allowing hotkey preset switching and features like 
rapid fire, burst fire, quick scope, dropshot, lean macros, auto crouch, and jump fire.

---

## Features

- Recoil control sliders (pull down / left / right)
- Adaptive recoil + dynamic spread behavior
- Preset system (create, edit, delete, import, export)
- Active preset + global hotkey slots for fast preset swaps
- Macro modules:
  - Rapid Fire
  - Burst Fire
  - Dropshot
  - Quickscope
  - Lean macros
  - Auto Crouch
  - Jump Fire
- Overlay-aware behavior (macro control tied to menu visibility)
- Built-in AutoHotkey bootstrap support

---

## Setup

### 1) Download
Download the latest installer from this repository’s release/build output.

### 2) Install
Run `0KCK-Setup.exe` as Administrator and complete setup.

### 3) First Launch
- Open app
- Assign keys in the UI (`SELECT` buttons)
- Configure sliders/toggles
- Press `INS` to toggle menu visibility while using it

---

## Usage Notes

- Macros rely on valid key assignments.  
- Some modules are disabled while the overlay is visible by design.  
- Presets and hotkeys are saved locally per user.  
- If using bundled AHK runtime, no manual AHK install is required.

---

## Troubleshooting

If automation does not trigger:

1. Confirm module toggle is enabled  
2. Confirm keybinds are assigned (not `SELECT`)  
3. Hide overlay (`INS`) and test again  
4. Reopen app after changing key assignments  
5. Reinstall using latest setup build

---

## License

This project is distributed under a **Personal Use License**.  
See [`LICENSE.md`](./LICENSE.md) for full terms.

---

## Contact

For support, permissions, or questions:

- Email: `Sysk3y@proton.me`
- Discord: `0x.rian`
