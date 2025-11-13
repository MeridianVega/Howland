# Howland

**AI-Powered Code Conversion Platform**

Howland transforms legacy codebases into modern, maintainable applications through advanced AI assistance and interactive code editing. Built for enterprises modernizing their software infrastructure.

[Visit howland.ai](https://howland.ai) | [Documentation](https://howland.ai/docs) | [Support](https://github.com/MeridianVega/Howland/issues)

---

## Download

[Desktop Releases](https://github.com/MeridianVega/Howland/releases?q=desktop-v) | [Mobile Releases](https://github.com/MeridianVega/Howland/releases?q=mobile-v) | [All Releases](https://github.com/MeridianVega/Howland/releases)

### Desktop Applications

**[Download Latest Desktop Version →](https://github.com/MeridianVega/Howland/releases?q=desktop-v)**

#### Windows

**Installer** (Recommended)
- Look for: `Howland-Setup-*-Windows-x64.exe` (Intel/AMD)
- Look for: `Howland-Setup-*-Windows-arm64.exe` (ARM devices)
- Standard installation with automatic updates

**Portable Edition**
- Look for: `Howland-Portable-*-Windows-x64.exe`
- No installation required, run from any location

**Microsoft Store**
- Search "Howland" in Microsoft Store
- Automatic updates, sandboxed security

**Requirements**: Windows 10 (64-bit) or later

#### macOS

**Direct Download**
- Universal (Recommended): `Howland-*-macOS-universal.dmg`
- Apple Silicon: `Howland-*-macOS-arm64.dmg`
- Intel: `Howland-*-macOS-x64.dmg`

**Mac App Store**
- Search "Howland" in Mac App Store
- Automatic updates, App Store integration

**Homebrew**
```bash
brew install howland
```

**Requirements**: macOS 10.13 (High Sierra) or later

#### Linux

**Debian/Ubuntu**
- Intel/AMD: `Howland-*-Linux-x64.deb`
- ARM: `Howland-*-Linux-arm64.deb`

**Universal Binary**
- Intel/AMD: `Howland-*-Linux-x64.AppImage`
- ARM: `Howland-*-Linux-arm64.AppImage`

**Snap Store**
```bash
snap install howland
```

**Flatpak**
```bash
flatpak install howland
```

**Requirements**: glibc 2.28 or later

### Mobile Applications

**[Download Latest Mobile Version →](https://github.com/MeridianVega/Howland/releases?q=mobile-v)**

#### iOS

**App Store**
- Search "Howland" in Apple App Store
- iPhone and iPad compatible
- Automatic updates

**Direct Download** (Advanced)
- Look for: `*.ipa` files in mobile releases
- Requires AltStore, Sideloadly, or enterprise certificate

**Requirements**: iOS 14.0 or later

#### Android

**Google Play Store**
- Search "Howland" in Google Play Store
- Automatic updates

**Direct Download** (APK)
- Look for: `app-release.apk` or `Howland-*.apk`
- Install directly on Android devices
- Enable "Install unknown apps" in device settings

**Direct Download** (AAB)
- Look for: `app-release.aab` or `Howland-*.aab`
- For manual upload to your own Google Play Console account

**Requirements**: Android 14.0 (API 34) or later

---

## Installation Instructions

### Windows

**Using the Installer (Recommended)**

1. Click "Download: Howland-Setup-Windows.exe" above
2. When the download completes, open your Downloads folder
3. Double-click the installer file
4. If Windows Defender shows a warning:
   - Click "More info"
   - Click "Run anyway"
5. Follow the installation wizard prompts
6. Howland launches automatically when installation completes

The application installs to `C:\Program Files\Howland` with Start Menu shortcuts. A tray icon appears in the taskbar notification area.

**Using the Portable Version**

1. Click "Download: Howland-Portable-Windows.exe" above
2. Move the downloaded file to your preferred location
3. Double-click the file to launch
4. No installation or administrator privileges required

Configuration is stored in the same folder as the executable.

### macOS

1. Click "Download: Howland-macOS-ARM64.dmg" above
2. Double-click the downloaded DMG file
3. Drag the Howland icon to the Applications folder
4. Eject the DMG
5. Navigate to Applications
6. Right-click Howland and select "Open"
7. In the security dialog, click "Open"

**Important**: Gatekeeper security requires right-click → Open for the first launch. Subsequent launches work normally by double-clicking.

### Linux

**Debian-based Systems (Ubuntu, Debian, Mint)**

Open terminal and execute:

```bash
cd ~/Downloads
sudo dpkg -i Howland-Linux.deb
sudo apt-get install -f
```

Launch from applications menu or run `howland` in terminal.

**All Other Distributions**

Open terminal and execute:

```bash
cd ~/Downloads
chmod +x Howland-Linux.AppImage
./Howland-Linux.AppImage
```

For permanent installation, move to `~/Applications` or `/opt`.

### Mobile Apps

**iOS (TestFlight Beta)**

1. Install TestFlight from the App Store if not already installed
2. Open the beta invitation link sent via email
3. Tap "Accept" to join the beta
4. Tap "Install" to download Howland
5. Open Howland from your home screen

**Android (Internal Testing)**

1. Accept the internal testing invitation sent via email
2. Open Google Play Store on your device
3. Search for "Howland" or tap the link in the invitation
4. Tap "Install"
5. Open Howland from your app drawer

---

## Features

### AI Code Conversion
Transform legacy applications to modern languages and frameworks with specialized AI models trained on enterprise codebases including VB6, legacy C#, and outdated JavaScript.

### Interactive Artifacts
View, edit, and validate converted code in real-time within an integrated development environment with syntax highlighting and error detection.

### Tiered AI Models
- **Electra**: Fast conversions for straightforward transformations
- **Noonan**: Balanced performance for complex codebases
- **Vega**: Premium analysis with architectural recommendations

### Cross-Platform Availability
- **Desktop**: Windows, macOS, Linux
- **Mobile**: iOS, Android (beta)
- **Web**: Access from any browser at howland.meridianvega.com

### Desktop Integration
- **Global Hotkey**: Alt+H opens an assistant window from any application
- **Persistent Sessions**: Maintains conversation context across app restarts
- **System Tray**: Always accessible without cluttering your taskbar
- **Automatic Updates**: Security patches and features install seamlessly

### Enterprise Features
- SOC 2 Type II certified infrastructure
- Role-based access control
- Comprehensive audit logging
- SSO integration available
- Dedicated support channels

---

## System Requirements

### Desktop Applications

**Minimum**
- **RAM**: 2GB
- **Storage**: 200MB available
- **Internet**: Broadband connection required
- **Processor**: 64-bit processor (Intel or ARM)

**Recommended**
- **RAM**: 4GB or more
- **Storage**: 500MB available
- **Internet**: High-speed broadband

**Operating Systems**
- **Windows**: 10 or 11 (64-bit)
- **macOS**: 10.13 (High Sierra) or later
- **Linux**: Modern distribution with glibc 2.28+

### Mobile Applications

**iOS**
- iOS 17.0 or later
- iPhone 8 or newer
- 150MB available storage
- Internet connection required

**Android**
- Android 14.0 (API 34) or later
- ARM64 or x86_64 processor
- 150MB available storage
- Internet connection required

---

## Getting Started

After installation, Howland integrates with your system for quick access.

### Desktop Quick Start

**Opening Howland**
- Press `Alt+H` (Windows/Linux) or `Cmd+H` (macOS) anywhere to open the assistant
- Click the system tray/menu bar icon
- Press `Alt+Shift+H` for the full application window

**Using the Assistant**
1. Press `Alt+H` to open the assistant popup
2. Type your code conversion request
3. Paste legacy code when prompted
4. Review the AI-generated modern code
5. Copy the result or download the file

**Using the Main Window**
1. Press `Alt+Shift+H` or select "Show Howland" from tray menu
2. Create a new conversation
3. Select source and target languages
4. Paste or upload your legacy code
5. Review conversions with interactive artifacts
6. Export results in your preferred format

### Mobile Quick Start

1. Open the Howland app
2. Sign in with your account
3. Tap the new conversation button
4. Select your conversion parameters
5. Enter or paste your code
6. Review the conversion results
7. Share or export the modernized code

---

## Automatic Updates

Desktop applications check for updates automatically.

**Update Process**
- Checks occur on app startup and daily
- Updates download in the background
- Notification appears when ready
- Install by restarting Howland

**Manual Check**
- Right-click tray icon → Settings → Check for Updates

Mobile apps update through the App Store and Google Play respectively.

---

## Privacy & Security

- End-to-end encrypted connections for all code transmission
- Conversations stored in SOC 2 Type II certified infrastructure
- No third-party analytics or tracking
- GDPR and CCPA compliant data handling
- Code is never used for model training without explicit consent

Full privacy policy: [howland.ai/privacy](https://howland.ai/privacy)

---

## Support

**Documentation**

[howland.ai/docs](https://howland.ai/docs)

**Technical Support**

[howland.ai/support](https://howland.ai/support)

**Bug Reports**

[github.com/MeridianVega/Howland/issues](https://github.com/MeridianVega/Howland/issues)

**Enterprise Sales**

enterprise@meridianvega.com

**General Inquiries**

support@meridianvega.com

---

## Release Notes

Detailed version history and changelogs available in [CHANGELOG.md](CHANGELOG.md).

---

## License

Proprietary software. See [LICENSE](LICENSE) for terms and conditions.

---

**© 2025 Meridian Vega Corporation. All rights reserved.**

Howland is a trademark of Meridian Vega Corporation.
