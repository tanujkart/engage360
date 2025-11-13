# Engage360

A mobile app built with React Native and Expo to help people get more involved in their community. It's a one-stop shop for civic information, quizzes, events, and news.

## What it does

**Home Tab** - Daily quizzes to test your civic knowledge. Answer questions and track your score.

**Events Tab** - Browse upcoming community events, see details, and RSVP. You can also share events with others.

**News Tab** - Read local and national civic news. See how many people viewed, liked, or commented on articles.

**Community Tab** - Post to the community, edit or delete your posts, and see what others are sharing.

## Getting started

### What you need

- Node.js (v18 or higher)
- npm or yarn
- Expo Go app on your phone ([iOS](https://apps.apple.com/app/expo-go/id982107779) | [Android](https://play.google.com/store/apps/details?id=host.exp.exponent))

### Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/soccertanuj/Engage360.git
   cd Engage360
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the app:
   ```bash
   npm start
   ```
   or
   ```bash
   npx expo start
   ```

### Running on your phone

1. Download Expo Go on your phone
2. Make sure your phone and computer are on the same Wi-Fi network
3. Scan the QR code that shows up in your terminal

### Running on simulator/emulator

```bash
npm run ios      # iOS Simulator (Mac only)
npm run android  # Android Emulator
npm run web      # Web browser
```

## Project structure

```
Engage360/
├── App.js              # Main entry point
├── app.json            # Expo config
├── package.json        # Dependencies
│
├── assets/             # Images and icons
├── components/         # Reusable components
│   └── Header.js
├── navigation/         # Navigation setup
│   └── TabNavigator.js
└── screens/            # Screen components
    ├── Home.js
    ├── Events.js
    ├── News.js
    └── Community.js
```

## Tech stack

- React Native & Expo
- React Navigation for tabs
- Ionicons for icons

## Contributing

Feel free to contribute! Check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

1. Fork the repo
2. Create a branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to your branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

This project is licensed under the 0BSD License - see [LICENSE](LICENSE) for details.

## Contact

Questions or suggestions? Open an issue or reach out to [@soccertanuj](https://github.com/soccertanuj).
