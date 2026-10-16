# Snippbot Desktop releases

Installers for **Snippbot Desktop**, the native macOS and Windows app for your own Snippbot daemon: Quick Chat on a global hotkey (⌥Space / Alt+Space) and a split-pane workspace for all your agents. This repository only hosts release files; it contains no source code.

**Download the latest:** [Releases → latest](https://github.com/saixiong/snippbot-desktop-releases/releases/latest)

- **macOS:** `Snippbot_<version>_macOS-AppleSilicon.dmg` (M1 and later) or `Snippbot_<version>_macOS-Intel.dmg`
- **Windows:** `Snippbot_<version>_Windows.exe` (installs for your account only, no admin rights needed)

More: [snippbot.com/desktop](https://snippbot.com/desktop) · [Setup guide](https://docs.snippbot.com/desktop/overview/) · [Troubleshooting](https://docs.snippbot.com/troubleshooting/desktop/)

## Requirements

- macOS 13 or later, or Windows 10 (1809+) / Windows 11
- A Snippbot daemon, version 0.11.1 or newer, on this computer, your network, or a server (`pipx install snippbot`)

## Beta builds are unsigned

- **macOS:** open the app once, then go to **System Settings → Privacy & Security** and choose **Open Anyway**. (On macOS 15 and later, right-click → Open no longer skips this.)
- **Windows:** SmartScreen shows "Windows protected your PC". Choose **More info → Run anyway**.

There's no auto-update yet: download each new version from the latest release and install it over the old one.
