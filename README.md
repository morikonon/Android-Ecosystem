# Android Ecosystem Lab 🚀

This repository contains the optional bonus lab demonstrating integration with the **Android Ecosystem** using Jetpack Compose.

## 📱 About the Project
Instead of just building an isolated app UI, this project proves how an app communicates with the broader Android Operating System. It utilizes **Implicit Intents** to trigger the native Android Share Sheet, allowing data to be sent from this application to any other supported app on the user's device (e.g., Gmail, Telegram, Bluetooth, Notes).

## 🛠️ Technical Details
* **Framework:** Jetpack Compose
* **Language:** Kotlin
* **Core Concept Demonstrating "Ecosystem":** `Intent.ACTION_SEND` and `Intent.createChooser()`

## 📝 How it works
1. The user types a message into the Compose `TextField`.
2. Upon clicking the share button, the app constructs an intent with the `text/plain` MIME type.
3. The Android OS intercepts this intent and presents the native ecosystem share drawer.
4. The user can seamlessly pass the typed data to other applications.
