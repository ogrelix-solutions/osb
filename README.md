# OSB – Ogrelix Secure Browser

**OSB (Ogrelix Secure Browser)** is a cross-platform, secure, distraction-free browser specifically designed for conducting online exams. It restricts user activity, enforces fullscreen mode, and blocks access to unauthorized tools during the test.

---

## 🚀 Features

- Fullscreen secure window (kiosk-style)
- Disables right-click, copy-paste, and developer tools
- Supports `ogre://` protocol to launch tests directly
- Cross-platform compatibility
- Clean, minimal UI for distraction-free testing
- Can be integrated with custom test platforms

---

## 🖥️ Compatibility

| Platform | Supported | Notes |
|----------|-----------|-------|
| **Windows 10/11** | ✅ Yes | Tested on 64-bit systems |
| **macOS (Intel & Apple Silicon)** | ✅ Yes | DMG installer available |
| **Linux (Debian-based)** | 🔶 Planned | AppImage/DEB support coming soon |

> 💡 Windows build comes with an NSIS installer. macOS uses a signed `.dmg`. Protocol handling (`ogre://`) is auto-registered during installation.

---

## 📦 Installation

### Windows

1. [Download the latest `.exe` installer from Releases](https://github.com/your-username/your-repo/releases)
2. Run the setup and follow the instructions
3. After installation, you can launch secure tests using links like:  
   `ogre://__testlink`

### macOS

1. [Download the latest `.dmg` installer from Releases](https://github.com/your-username/your-repo/releases)
2. Drag **Ogrelix Secure Browser** to Applications
3. Open using Control + Click > Open (for unsigned apps)

---

## 🔐 Protocol Integration (`ogre://`)

After installation, your system will recognize `ogre://` links and open them with Ogrelix Secure Browser.

Example:
