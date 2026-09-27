# SWG Datapad

A crafting planner for SWG Legends. Pick an item to see every component, sub-component and resource it takes, which resource slots need high quality and which can take junk, and whether your resources (or the spawns up now) cap each experiment line. Custom builds set up a whole item the way you want it, such as a bomb droid with 180 Detonation Power, and tell you what's missing.

## Download

Get the latest desktop build from [Releases](https://github.com/SmeagolDanger/SWG-Datapad-releases/releases/latest):

- **Windows x64:** download the `-x64-setup.exe` installer. It adds Start-menu and desktop shortcuts. Later updates download inside the app; choose **Restart and install** when you're ready.
- **macOS Apple Silicon:** download the `-arm64.dmg`, open it, and drag SWG Datapad into Applications. macOS updates are manual: the app tells you when a new version is out and opens this page. (The `-arm64.zip` is the same app.)

Builds are unsigned. Windows may show a SmartScreen prompt on first launch: click **More info → Run anyway**. macOS blocks the first launch: open **System Settings → Privacy & Security** and click **Open Anyway**, or run `xattr -dr com.apple.quarantine "/Applications/SWG Datapad.app"` once.

## Your data

Projects, resources, custom builds, guards and settings stay on your computer, in the app's profile folder (`%APPDATA%\SWG Datapad` on Windows, `~/Library/Application Support/SWG Datapad` on macOS), and are kept through updates. **My resources** exports and imports SWGAide-style CSV files to move your inventory between computers.

The app downloads Legends schematic and current-resource data from [SWGAide](https://swgaide.com)'s public exports and checks this repository for updates. No account is needed, and nothing about you or your resources is sent anywhere.

This repository holds downloads and release notes. Source development happens in a separate private repository; the automatic Source code archives here contain only this repository's documentation.

## Feedback

Please [open an issue](https://github.com/SmeagolDanger/SWG-Datapad-releases/issues) with the app version (Settings → Updates) and the steps to reproduce a problem.

Unofficial SWG Legends fan tool, not affiliated with SWG Legends or SWGAide.
