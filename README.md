# Termux-Native-KDE


This project allows you to run KDE Plasma natively in Termux for maximum performance and audio support.
Prerequisites
 * Install the Termux:X11 app on your Android device.
 * In Termux:X11 settings, set Display resolution mode to "native" for the best experience.
Quick Install
Run this command to install the base packages and the launcher:
```
curl -fsSL https://raw.githubusercontent.com/YourRepo/NativeKDE/main/install_kde.sh | bash
```

How to use
Once installed, just type:
`kde`

Then switch to the Termux:X11 app to see your desktop.


# Known Bugs

 * Icons: Sometimes icons don't show up immediately; clicking them usually triggers a refresh.
 * Borders: You might see thick black borders on some windows; this is an X11 rendering quirk in Termux.
I’ve kept the instructions short and direct—real humans don't like reading essays just to start a GUI. Should I add an alias to your main .zshrc that automatically launches KDE whenever you type desktop? maybe yes , I'll do it later
