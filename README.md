# Termux-Native-KDE


This project allows you to run KDE Plasma natively in Termux for maximum performance and audio support.
Prerequisites
 * Install the Termux:X11 app on your Android device.
 * In Termux:X11 settings, set Display resolution mode to "native" for the best experience.



# Why Native?

PRoot environments like Ubuntu or Debian add a heavy translation layer between your hardware and the OS. By running KDE natively, we use Termux's own libraries for 1:1 speed and better battery life.


# Setup (Important)

- Before launching, you need the Termux:X11 app installed.
- Open Termux:X11 settings.
- Set Display resolution mode to native.
- Set Fullscreen on device display to ON.
- Run `kde` in your terminal after installation and switch to the X11 app.

# Quick Install
Run this command to install the base packages and the launcher:
```
curl -fsSL https://raw.githubusercontent.com/Worthiit/KDE-Termux-/main/setup-kde | bash

```

# How to use /commands

- `kde`: Cleans up old sessions and starts the Plasma desktop in Termux:X11 app.
- `setup-kde`: Re-installs dependencies and refreshes the launcher.


# Known Bugs

* ​Icons: If icons appear as white boxes, run kbuildsycoca5 in the desktop terminal to refresh the cache.
* ​Borders: Black borders around windows are a Termux-X11 quirk. It doesn't affect speed.
* ​Sound: Audio is bridged via PulseAudio. If it cuts out, restart the kde command. maybe yes , I'll do it later
