# Flightscry

A simple Android flight information app built with Kotlin and Backpack UI components.

## Features

- Flight information display with flight number
- Departure card showing airport code (LHR) and departure time
- Arrival card showing airport code (JFK) and arrival time
- Flight duration information

## Tech Stack

- **Language:** Kotlin
- **Min SDK:** API 33 (Android Tiramisu)
- **Target SDK:** API 34
- **UI Library:** Backpack Android (v43.0.0)
- **Build System:** Gradle with Kotlin DSL

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/flightscry/
│   │   │   └── MainActivity.kt
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   │   └── activity_main.xml
│   │   │   ├── values/
│   │   │   │   ├── colors.xml
│   │   │   │   ├── strings.xml
│   │   │   │   └── themes.xml
│   │   │   └── ...
│   │   └── AndroidManifest.xml
│   └── ...
├── build.gradle.kts
└── ...
```

## Getting Started

1. Clone this repository
2. Open the project in Android Studio
3. Sync Gradle files
4. Run the app on an emulator or physical device

## Dependencies

- AndroidX Core KTX
- AndroidX AppCompat
- Material Components
- ConstraintLayout
- Backpack Android UI Library

## Screenshots

The app displays flight information in a clean, card-based UI using Skyscanner's Backpack design system.

## License

This project was created as part of a learning exercise.
