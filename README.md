# 🍽️ Cottage Tandoori - Kitchen Display System

> Real-time kitchen order management system with AI-powered voice integration

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue)]()

## ✨ Features

- ✅ **Real-time Order Feed** - NEW → PREPARING → READY workflow
- 🔐 **PIN-Based Access** - Secure kitchen staff authentication
- 📱 **Multi-Platform** - Standalone PWA and Desktop (Electron) app
- 🔊 **Audio Alerts** - Customizable notifications for new orders
- 🎨 **Premium Dark Theme** - Optimized for kitchen environments
- 🔄 **Live Sync** - Instant updates with POS and Online Orders
- 📊 **Order Source Tracking** - POS vs Online order identification
- 🚀 **High Performance** - Built for speed and reliability

## 📦 Installation

### Desktop App (Recommended)

Download the latest release for your platform:

| Platform | Download |
|----------|----------|
| 🪟 Windows | [Windows Installer (.exe)](../../releases/latest) |
| 🍎 macOS | [macOS DMG](../../releases/latest) |
| 🐧 Linux | [Linux AppImage](../../releases/latest) |

### Web App

Access directly at: **[KDS Web App](https://exoticcreations.databutton.app/cottage-tandoori-restaurant/kds-v2)**

## 💻 System Requirements

- **Browser:** Chrome 90+, Firefox 88+, Safari 14+, or Edge 90+
- **Screen:** 1920x1080 or higher recommended
- **Network:** Stable internet connection for real-time updates
- **Audio:** Speakers/headphones for order alerts

## 🚀 Quick Start

1. **Launch** the KDS application
2. **Set PIN** on first run (4-digit code)
3. **Enable Fullscreen** for optimal kitchen display
4. **Configure Audio** alerts (optional)
5. **Start Receiving** orders in real-time

## 🏗️ Tech Stack

- **Frontend:** React + TypeScript + Tailwind CSS
- **Backend:** Supabase (Real-time subscriptions + PostgreSQL)
- **Desktop:** Electron
- **State Management:** Zustand
- **Audio:** Web Audio API
- **Build System:** Vite

## 📚 Documentation

- [Installation Guide](docs/installation.md)
- [User Manual](docs/user-guide.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Development Setup](docs/development.md)

## 🔧 Development

```bash
# Clone repository
git clone https://github.com/Bodzaman/cottage-tandoori-kds.git
cd cottage-tandoori-kds

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Build Electron app
npm run electron:build
```

## 📝 License

MIT License - See [LICENSE](LICENSE) file for details

## 🆘 Support

For issues, questions, or feature requests:

- 🐛 [Report a Bug](../../issues/new?template=bug_report.md)
- 💡 [Request a Feature](../../issues/new?template=feature_request.md)
- 📧 Contact: [Cottage Tandoori Restaurant](https://exoticcreations.databutton.app/cottage-tandoori-restaurant)

## 🙏 Acknowledgments

Built with ❤️ for Cottage Tandoori Restaurant

---

**[Visit Cottage Tandoori](https://exoticcreations.databutton.app/cottage-tandoori-restaurant)** | **[Download Latest Release](../../releases/latest)**
