# Cryptogram - Fill the blanks (Word Puzzle Game)

<div align="center">
<img width="250" height="250" alt="icon" src="https://github.com/user-attachments/assets/245823d8-1d27-4bff-97e3-9ca0e8ce7c44" />

**A challenging word puzzle game built with Jetpack Compose**

[![Get it on Google Play](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](https://play.google.com/store/apps/details?id=com.cryptogram.filltheblanks) 
[![Android](https://img.shields.io/badge/Android-API%2027+-green.svg)](https://developer.android.com/about/versions/android-14.0)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9+-blue.svg)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-1.5+-orange.svg)](https://developer.android.com/jetpack/compose)

</div>

## 📱 Introduction Video

<div align="center">

**(Coming soon...)**
https://github.com/yourusername/cryptogram-jetpack-compose/assets/youruserid/sample.mp4

*Watch the introduction video to see Cryptogram in action!*

</div>

## 🎮 About Cryptogram

Cryptogram is an engaging word puzzle game where players solve famous quotes by filling in the blanks. The game features an intelligent algorithm that automatically generates puzzles from inspirational quotes, creating a unique and challenging experience for each level.

### 🎯 How to Play

1. **Select a Blank**: Tap on any numbered blank in the quote
2. **Guess the Letter**: Use the custom keyboard to input your guess
3. **Solve the Puzzle**: Fill all blanks correctly to complete the quote
4. **Use Hints**: Get help when stuck (costs coins)
5. **Manage Lives**: You have limited attempts - use them wisely!

### 🏆 Game Features

- **2000+ Inspirational Quotes**: Famous sayings from great minds
- **Smart Puzzle Generation**: Automatic blank creation for optimal difficulty
- **Custom Keyboard**: Beautiful, responsive on-screen keyboard
- **Hint System**: Purchase hints with coins when you're stuck
- **Life Management**: Limited attempts with life regeneration
- **Coin Economy**: Earn coins through gameplay and ads
- **Dark/Light Theme**: Toggle between themes for your preference
- **Sound & Vibration**: Immersive feedback for correct/incorrect answers
- **Progress Saving**: Your progress is automatically saved
- **Lots of new Feautures**: coming in new versions.....

## 📸 Screenshots

<div align="center">

### Some Glimps of First verison!

![cryptogramSS](https://github.com/user-attachments/assets/641f894a-275b-4df1-a1e0-15b8a5bebedc)

</div>

## 🛠️ Technical Details

### Built With

- **Kotlin** - Primary programming language
- **Jetpack Compose** - Modern Android UI toolkit
- **Material Design 3** - Latest design system
- **MVVM Architecture** - Clean architecture pattern
- **DataStore** - Modern data persistence
- **Coroutines** - Asynchronous programming
- **Google Ads** - Monetization integration

### Key Components

- **GameViewModel** - Core game logic and state management
- **Custom Keyboard** - Responsive on-screen keyboard
- **Quote Display** - Dynamic quote rendering with blanks
- **Hint System** - Intelligent hint management
- **Life Manager** - Life regeneration and management
- **Theme System** - Dark/light theme switching
- **Sound Manager** - Audio feedback system

### Architecture

```
app/src/main/java/com/cryptogram/filltheblanks/
│
├── data/
│   └── repository/         // Handles data operations (e.g., QuoteRepository)
│
├── domain/
│   └── entity/             // Core data models (e.g., Quote, GameState)
│
├── ui/
│   ├── composables/        // Reusable UI components (e.g., CustomKeyboard, Dialogs)
│   ├── navigation/         // Screen definitions (e.g., HomeScreen, GameScreen)
│   ├── theme/              // App theme, colors, and typography
│   └── viewmodel/          // ViewModels for each screen (e.g., GameViewModel)
│
├── utils/
│   └── ...                 // Helper classes for ads, audio, analytics, etc.
│
└── MainActivity.kt         // Main entry point
```

### 🔒 Private Repository

> ⚠️ **Note:** The full source code for this project is in a **private repository**. This public README is made available for portfolio and reference purposes.  
>  
> If you're a potential employer or buyer and would like access to the codebase, feel free to reach out.



### Prerequisites

- Android Studio Hedgehog | 2023.1.1 or later
- Android SDK API 27+ (Android 8.1)
- Kotlin 1.9+
- JDK 11

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
<div align="center">

**Made with ❤️ using Jetpack Compose**

[Download on Google Play](https://play.google.com/store/apps/details?id=com.cryptogram.filltheblanks) | [Privacy Policy and Terms of Service](https://cryptogr.netlify.app/)

</div>
