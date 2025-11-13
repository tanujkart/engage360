<div align="center">

# 🗳️ Engage360

### **Engage, Educate, Empower**

[![React Native](https://img.shields.io/badge/React%20Native-0.79.5-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-~53.0.17-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev/)
[![License](https://img.shields.io/badge/License-0BSD-blue.svg?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-lightgrey?style=for-the-badge)](https://expo.dev/)

**A modern mobile application designed to increase civic participation through centralized information, interactive quizzes, community events, and real-time news updates.**

[Features](#-features) • [Getting Started](#-getting-started) • [Project Structure](#-project-structure) • [Contributing](#-contributing) • [License](#-license)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 About

Engage360 is a comprehensive civic engagement platform built with React Native and Expo. The app serves as a one-stop solution for citizens to stay informed, participate in community events, test their civic knowledge, and connect with their local community.

### Mission
To bridge the gap between citizens and civic participation by providing accessible, engaging, and informative tools that empower individuals to be active members of their community.

---

## ✨ Features

### 🧠 **Home Tab - Daily Quizzes**
- Interactive daily civic knowledge quizzes
- Real-time score tracking
- Immediate feedback on answers
- Progressive difficulty system

### 📆 **Events Tab - Community Events**
- Browse upcoming civic and community events
- Detailed event descriptions and information
- RSVP functionality
- Share events with friends and family
- Location-based event discovery

### 📰 **News Tab - Civic News**
- Curated local and national civic news
- Engagement metrics (views, likes, comments)
- Real-time news updates
- Categorized news feed

### 🗣️ **Community Tab - Social Engagement**
- Create and share community posts
- Edit and delete your own posts
- View and interact with community posts
- Scrollable feed of community discussions

---

## 📸 Screenshots

> _Screenshots coming soon! Add your app screenshots here to showcase the UI._

<!-- 
Add screenshots like this:
![Home Screen](assets/screenshots/home.png)
![Events Screen](assets/screenshots/events.png)
![News Screen](assets/screenshots/news.png)
![Community Screen](assets/screenshots/community.png)
-->

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18 or higher)
- **npm** or **yarn**
- **Expo CLI** (will be installed globally or via npx)
- **Expo Go app** on your mobile device ([iOS](https://apps.apple.com/app/expo-go/id982107779) | [Android](https://play.google.com/store/apps/details?id=host.exp.exponent))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/soccertanuj/Engage360.git
   cd Engage360
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

3. **Start the Expo development server**
   ```bash
   npm start
   ```
   or
   ```bash
   npx expo start
   ```

### Running the App

#### On Physical Device (Recommended)

1. **Install Expo Go**
   - [Download for iOS](https://apps.apple.com/app/expo-go/id982107779)
   - [Download for Android](https://play.google.com/store/apps/details?id=host.exp.exponent)

2. **Connect to the same network**
   - Ensure your computer and mobile device are on the same Wi-Fi network

3. **Scan the QR code**
   - Open Expo Go on your device
   - Scan the QR code displayed in your terminal or browser
   - The app will load on your device

#### On iOS Simulator (macOS only)

```bash
npm run ios
```

#### On Android Emulator

```bash
npm run android
```

#### On Web Browser

```bash
npm run web
```

---

## 📁 Project Structure

```
Engage360/
├── 📱 App.js                 # Main application entry point
├── 📄 app.json               # Expo configuration
├── 📦 package.json           # Dependencies and scripts
├── 📖 README.md              # This file
│
├── 📂 assets/                # Static assets
│   ├── 🖼️ icon.png
│   ├── 🖼️ splash-icon.png
│   ├── 🖼️ adaptive-icon.png
│   └── 🖼️ event*.png
│
├── 📂 components/            # Reusable components
│   └── Header.js            # Header component
│
├── 📂 navigation/            # Navigation configuration
│   └── TabNavigator.js      # Bottom tab navigator
│
├── 📂 screens/               # Screen components
│   ├── Home.js              # Home screen with quizzes
│   ├── Events.js            # Events listing screen
│   ├── News.js              # News feed screen
│   └── Community.js         # Community posts screen
│
└── 📂 dist/                  # Build output (gitignored)
```

---

## 🛠️ Tech Stack

### Core Technologies
- **[React Native](https://reactnative.dev/)** - Cross-platform mobile framework
- **[Expo](https://expo.dev/)** - Development platform and toolchain
- **[React](https://react.dev/)** - UI library

### Navigation
- **[React Navigation](https://reactnavigation.org/)** - Navigation library
  - `@react-navigation/native` - Core navigation
  - `@react-navigation/bottom-tabs` - Bottom tab navigator

### UI & Icons
- **[React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)** - Icon library
- **[Expo Vector Icons](https://docs.expo.dev/guides/icons/)** - Expo icon components

### Additional Libraries
- `react-native-gesture-handler` - Gesture handling
- `react-native-reanimated` - Animations
- `react-native-safe-area-context` - Safe area handling
- `react-native-screens` - Native screen components
- `expo-status-bar` - Status bar component
- `expo-updates` - Over-the-air updates

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details on:

- Code of Conduct
- How to submit pull requests
- Development guidelines
- Reporting issues

### Quick Contribution Steps

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the **0BSD License** - see the [LICENSE](LICENSE) file for details.

The 0BSD license is a permissive license that allows you to use, modify, and distribute the software without restrictions.

---

## 📞 Contact

**Project Maintainer:** [@soccertanuj](https://github.com/soccertanuj)

**Project Link:** [https://github.com/soccertanuj/Engage360](https://github.com/soccertanuj/Engage360)

---

## 🙏 Acknowledgments

- Built with ❤️ using React Native and Expo
- Icons provided by [Ionicons](https://ionic.io/ionicons)
- Community-driven development

---

<div align="center">

**⭐ Star this repo if you find it helpful!**

Made with ❤️ for civic engagement

</div>
