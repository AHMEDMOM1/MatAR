# Setup Guide

Android app (Kotlin) built with Gradle.

## Requirements
- Android Studio (latest stable) with JDK 17
- Android SDK matching compileSdk in app/build.gradle.kts
- A Firebase project (Authentication enabled)

## Steps
1. Clone this repository and open it in Android Studio.
2. In the Firebase console, add an Android app with package name com.achelmas.numart.
3. Download google-services.json and place it in the app/ folder (see app/google-services.json.example for the format).
4. Never commit the real google-services.json file.
5. Sync Gradle, then run the app on an emulator or a device.
