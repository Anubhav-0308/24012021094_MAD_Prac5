# Android Login and Registration App

A simple Android application built with **Kotlin** and **Jetpack Compose**. The app demonstrates a login and registration interface with navigation between the two screens.

<img width="200" height="400" alt="WhatsApp Image 2026-10-14 at 16 35 37 (1)" src="https://github.com/user-attachments/assets/5b57155e-14aa-42fa-a540-92ad2cbf1d59" />
<img width="200" height="400" alt="WhatsApp Image 2026-10-14 at 16 35 37" src="https://github.com/user-attachments/assets/90e94088-c33a-4963-aa79-86ee5e0b0057" />

## Features

- Login screen
- Registration screen
- Navigation between Login and Register using Jetpack Compose Navigation
- Reusable form-field component
- Material 3 UI components
- Edge-to-edge layout support

## Tech Stack

- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Design components:** Material 3
- **Navigation:** Navigation Compose
- **Build system:** Gradle with Kotlin DSL
- **IDE:** Android Studio

## Project Structure

```text
.
├── app/
│   └── src/
│       └── main/
│           ├── java/com/example/a24012021094_anubhav_prac5/
│           │   ├── MainActivity.kt
│           │   ├── AppNavigation.kt
│           │   ├── LoginScreen.kt
│           │   ├── RegisterScreen.kt
│           │   ├── FormField.kt
│           │   └── ui/theme/
│           ├── res/
│           └── AndroidManifest.xml
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## Requirements

- Android Studio
- Android SDK 35
- JDK 11-compatible setup
- Android device or emulator running **Android 8.0 (API 26) or later**

## How to Run

1. Download or clone this repository.
2. Open the project folder in Android Studio.
3. Allow Gradle to sync and download the required dependencies.
4. Select an Android emulator or connect an Android device with USB debugging enabled.
5. Click **Run ▶** to build and launch the app.

## App Navigation

The app starts on the **Login** screen. Users can navigate to the **Register** screen using the navigation controls provided in the UI.

## Configuration

The app module is configured with:

- `minSdk`: 26
- `compileSdk`: 35
- `targetSdk`: 35
- `versionName`: `1.0`

## Notes

- This project is intended for learning and practical work with Android development, Kotlin, Jetpack Compose, and screen navigation.
- Review `LoginScreen.kt` and `RegisterScreen.kt` for the current form behavior.
- A UI login or registration form does not automatically provide secure account management. For real authentication, connect the app to a backend and store passwords securely on the server; do not store plain-text passwords in the app.


👨‍💻 Author
Name: Anubhav Kanthariya
Enrollment Number: 24012021094
Subject: Mobile Application Development
Practical Number: 8


