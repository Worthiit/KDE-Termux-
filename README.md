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
- Run kde in your terminal and switch to the X11 app.

# Quick Install
Run this command to install the base packages and the launcher:
```
curl -fsSL https://raw.githubusercontent.com/Worthiit/KDE-Termux-/main/setup-kde | bash

```

# How to use /commands

- `kde`: Cleans up old sessions and starts the Plasma desktop in Termux:X11 app.
- `setup-kde`: Re-installs dependencies and refreshes the launcher.


# Known Bugs

 * Icons: Sometimes icons don't show up immediately; clicking them usually triggers a refresh.
 * Borders: You might see thick black borders on some windows; this is an X11 rendering quirk in Termux.
I’ve kept the instructions short and direct—real humans don't like reading essays just to start a GUI. Should I add an alias to your main .zshrc that automatically launches KDE whenever you type desktop? maybe yes , I'll do it later
