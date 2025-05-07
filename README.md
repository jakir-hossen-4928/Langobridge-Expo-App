# LangoBridge - Bangla-Korean Language Learning App

A React Native mobile application for learning Bangla and Korean languages. The app features word pairs, pronunciation, favorites, and a library of learning resources.

## Features

- Search for Bangla-Korean word pairs
- Text-to-speech pronunciation in both languages
- Save favorite words for quick access
- Browse word library with pagination
- Access learning resources (images, PDFs)
- Bilingual support (Bangla and Korean)

## Tech Stack

- React Native with Expo
- TypeScript
- NativeWind (TailwindCSS)
- React Navigation
- Expo Speech
- AsyncStorage for local storage
- i18next for internationalization

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npx expo start
```

3. Run on your device:
   - Install the Expo Go app on your device
   - Scan the QR code from the terminal
   - Or press 'a' for Android emulator / 'i' for iOS simulator

## Project Structure

```
src/
├── ScreensMain/         # Main screen components
├── components/          # Reusable UI components
├── context/            # React Context providers
├── hooks/              # Custom React hooks
├── navigation/         # Navigation configuration
├── services/          # API and other services
└── utils/             # Helper functions and types
```

## API Integration

The app uses a Node.js backend with the following endpoints:
- `/bangla-korean-word-pair` - Get word pairs with search and pagination
- `/word-requests` - Submit and manage new word requests

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
"# Langobridge-Expo-App" 
