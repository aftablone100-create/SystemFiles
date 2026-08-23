# System Files Launcher 📂

A lightweight, minimal Android application built to bypass third-party file managers and launch the native system document picker directly.

## 🚀 Features

* **Direct Intent Launch:** Triggers `Intent.ACTION_OPEN_DOCUMENT` immediately upon launch.
* **Lightweight & Fast:** Built without bloated dependencies or unnecessary UI components.
* **Auto-Termination:** Closes automatically in the background once a file is selected or the action is canceled.
* **Modern Target:** Fully compatible with Android 15 (API level 35).

## 🛠️ Tech Stack & Requirements

* **Language:** Kotlin
* **Min SDK:** `23` (Android 6.0 Marshmallow)
* **Target SDK:** `35` (Android 15)
* **JDK Version:** `17`
* **Build System:** Gradle 8.7 (via GitHub Actions)

## 📁 Project Structure

```text
SystemFiles/
├── .github/workflows/
│   └── build.yml               # Automated APK CI/CD pipeline
├── app/
│   ├── build.gradle.kts        # App-level build configurations
│   └── src/main/
│       ├── AndroidManifest.xml
│       ├── java/com/example/systemfiles/
│       │   └── MainActivity.kt # Core launch logic
│       └── res/                # App resources and icons
├── build.gradle.kts            # Project-level build configuration
├── gradle.properties
└── settings.gradle.kts

