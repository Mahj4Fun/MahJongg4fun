# Mah Jongg App

![Banner](https://github.com/Mahj4Fun/MahJongg4fun/blob/main/banner.jpg) <!-- Replace with project banner -->

A cross-platform desktop application supporting Windows, macOS, and Linux.

## 📥 Download

Visit the [Releases page](https://github.com/Mahj4Fun/MahJongg4fun/releases) to download the latest version:

| Platform   | Architecture Support | File Format   |
|------------|----------------------|---------------|
| Windows    | x64                  | `.exe`        |
| macOS      | Intel, Apple Silicon | `.dmg`        |
| Linux      | x64, arm64           | `.AppImage` `.deb` `.rpm` |           

> - Play Web Game [Web](https://www.mahjongg4fun.com)
> - iOS App [AppStore](https://apps.apple.com/app/id6746219026)

## ⚙️ System Requirements

- ​**Windows**: 10/11 (64-bit)
- ​**macOS**: 10.15+
- ​**Linux**: GLIBC 2.28+   libfuse2

## 🚀 Quick Start

1. ​**Download the installer**: Choose your platform from Releases.
2. ​**Run**:
   - ​**Windows/macOS**: Double-click the installer.
   - ​**Linux**:
     - **AppImage** 
        - method 1. “Right-click the .AppImage file → Properties → Check ‘Allow executing file as program’”
        - method 2. install system libfuse2 and Grant execute permission then run:
        ```bash
        sudo apt install libfuse2
     
        sudo chmod a+x Mah\ Jongg.AppImage

        Double-click the AppImage to Run
        ```
     - **deb**
        - method 1. Double-click the deb package to install if you don't installed
        - method 2. sudo dpkg -i Mah.Jongg-Linux-arm64.deb
     - **rpm**
        - method1. Double-click the rpm package to install if you don't installed
        - method2. sudo rpm -i Mah.Jongg-Linux-x64.rpm

     - **How to uninstall**
       - **deb** sudo dpkg -r mahjongg4fun
       - **rpm** sudo rpm -e mahjongg4fun
       
## 🚀 macOS Security Alert Solution

When running the app for the first time, you may see a security warning. This occurs because project without an Apple Developer certificate. You can:

1. ​**Recommended Method**: Right-click the app → Select "Open"
2. ​**OR**​ Run this terminal command:
   ```bash
   sudo xattr -rd com.apple.quarantine /Applications/Mah\ Jongg.app
   
## 📖 Features

- Feature 1: Multi-platform support.
- Feature 2: Auto-update functionality.
- Feature 3: High-performance local storage.


## ↘️ Official Account

> - [Facebook](https://www.facebook.com/MahJongg4Fun)
> - [Instagram](https://www.instagram.com/mahj4fun/)
> - [YouTube](https://www.youtube.com/@MahJongg4Fun)
> - [Twitter](https://twitter.com/FunMah97331)
