# Notes Android App

A modern, offline-first notes application built using Jetpack Compose, Kotlin, and modern Android development practices.

## Features

- 📝 **Create, Edit, and Delete Notes**: Easy note management with a clean, fluid user interface.
- 🎨 **Beautiful Aesthetics**: Premium HSL-curated colors, dark/light theme support, and smooth micro-animations.
- 📂 **Categorization**: Organize notes into categories/labels for better management.
- 🔍 **Real-time Search**: Quick and fuzzy searching across all notes instantly.
- 💾 **Local Persistence**: Built using modern local storage (Room database/DataStore) to keep notes fully local and secure.

## Tech Stack

- **UI Framework**: [Jetpack Compose](https://developer.android.com/compose)
- **Programming Language**: [Kotlin](https://kotlinlang.org/)
- **Navigation**: Modern Compose Navigation3
- **Dependency Injection**: Hilt / Kotlin Inject
- **Design System**: Material Design 3 (M3)
- **Local Database**: Room

## Getting Started

### Prerequisites

- Android Studio (latest stable version recommended)
- Android SDK 36 (Android 12/13/14/15/16)
- Java 17+

### Running the App

To run the application locally via terminal, make sure you have a connected device or emulator running:

```bash
# Clean and build the project
./gradlew clean build

# Run the app on the connected device
android run
```

Alternatively, open the project directory in Android Studio and click the **Run** button.
