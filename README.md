# 🔵 Bluetooth Auto-Off Timer

<p align="center">
  <img src="app/src/main/res/drawable/ic_app_logo.png" width="120" alt="Bluetooth Timer Logo"/>
</p>

<p align="center">
  <strong>Never miss your morning alarm again!</strong><br>
  Auto-disconnect Bluetooth devices before you fall asleep
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#why-this-app">Why This App</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#contributing">Contributing</a>
</p>

---

## 🎯 The Problem

Ever fallen asleep with your Bluetooth earbuds in, only to miss your morning alarm because:

- Your earbuds fell out during sleep
- The alarm played through disconnected earbuds instead of your phone speaker
- You couldn't hear the alarm at all

**This app solves that problem!**

## 💡 Why This App

As someone who loves listening to podcasts or music before sleeping, I realized a common issue — **my Bluetooth earbuds would fall out during sleep, but my phone still thought they were connected**. This meant my morning alarm would play through the earbuds lying somewhere on my bed instead of the phone speaker.

I built this app to **automatically disconnect Bluetooth after a set time**, ensuring:

- ✅ Your alarm plays through your phone speaker
- ✅ You wake up on time
- ✅ Better battery life for both phone and earbuds

## ✨ Features

- ⏱️ **Custom Timer** - Set any duration in minutes
- 🚀 **Quick Presets** - One-tap buttons for 5, 15, 30, or 60 minutes
- 📱 **Clean UI** - Modern Material Design interface
- 🔔 **Notification** - Shows countdown while timer is running
- 🔋 **Battery Friendly** - Minimal background resource usage
- 🎯 **Simple & Focused** - Does one thing and does it well

## 📱 Screenshots

|     Home Screen      |         Timer Running         |
| :------------------: | :---------------------------: |
| Set your sleep timer | See countdown in notification |

## 📥 Installation

### From APK

1. Download the latest APK from [Releases](../../releases)
2. Enable "Install from unknown sources" if prompted
3. Install and enjoy!

### Build from Source

```bash
# Clone the repository
git clone https://github.com/BurningHat20/bluetooth-auto-off-timer.git

# Navigate to project directory
cd bluetooth-auto-off-timer

# Build debug APK
./gradlew assembleDebug

# APK will be at: app/build/outputs/apk/debug/app-debug.apk
```

## 🚀 Usage

1. **Open the app** - See your current Bluetooth status
2. **Set timer** - Enter minutes or use quick preset buttons (5/15/30/60 min)
3. **Start timer** - Tap "Start Timer" button
4. **Sleep peacefully** - Bluetooth will auto-disconnect when timer ends
5. **Wake up on time** - Your alarm will play through phone speaker!

## 📋 Requirements

- Android 12 (API 31) or higher
- Bluetooth-enabled device
- Bluetooth permission granted

## 🔐 Permissions

| Permission           | Why Needed                     |
| -------------------- | ------------------------------ |
| `BLUETOOTH_CONNECT`  | To disconnect Bluetooth        |
| `FOREGROUND_SERVICE` | To run timer in background     |
| `POST_NOTIFICATIONS` | To show countdown notification |

## 🛠️ Tech Stack

- **Language:** Java
- **Min SDK:** 31 (Android 12)
- **Target SDK:** 32
- **UI:** Material Components
- **Architecture:** Service-based background timer

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**BurningHat** - _19-year-old Software Engineer_

- GitHub: [@BurningHat20](https://github.com/BurningHat20)

---

## 🌟 Support

If this app helped you wake up on time, consider:

- ⭐ Starring this repository
- 🐛 Reporting bugs or suggesting features
- 📢 Sharing with friends who have the same problem

---

<p align="center">
  Made with ❤️ for better mornings
</p>
