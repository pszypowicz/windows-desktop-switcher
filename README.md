# windows-desktop-switcher
An AutoHotKey script for Windows that lets a user change virtual desktops by pressing CapsLock + &lt;num>. It also allows for creation/deletion of desktops by hotkey (see below).

## Overview
This script creates 'better' hotkeys for switching virtual desktops in windows 10. I built this to better mirror
the mapping I use on linux (with dwm), and it's always annoyed me that Windows does not have better
hotkey support for this feature (for instance, there's no way to go directly to a desktop by number).

Note that this only overrides CapsLock for the key combinations below. Otherwise, CapsLock will function normally.

## Installation
Install AutoHotKey, then run the desktop_switcher.ahk script (open with AutoHotKey if prompted). I would recommend putting it in your startup folder and it'll be invoked on login.

## Hotkeys
        Win + <Num>      - Switches to virtual desktop "num".
        Win + =          - Create a new virtual desktop
        Win + -          - Delete the current virtual desktop
        Win + P          - Switch to virtual desktop on left
        Win + N          - Switch to virtual desktop on right
        Win + ~          - Switch between 2 last virtual desktops

To change the key mappings, modify the bottom of the script and reload. Be sure to read about the [symbols AutoHotKey uses](https://autohotkey.com/docs/Hotkeys.htm) for key mapping.

## Other
To see debug messages, download [SysInternals DebugView](https://technet.microsoft.com/en-us/sysinternals/debugview).

Disclaimer: I've only tried this on my machine, and on Windows 10. Use at your own risk.