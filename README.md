# System Files Launcher 📂

[![Build APK](https://github.com/aftablone100-create/SystemFiles/actions/workflows/build.yml/badge.svg)](https://github.com/YOUR_USERNAME/SystemFiles/actions)
![Platform](https://img.shields.io/badge/Platform-Android-green.svg)
![Target SDK](https://img.shields.io/badge/Target%20SDK-35-blue.svg)
![License](https://img.shields.io/badge/License-MIT-orange.svg)

A lightweight, minimal Android application built to bypass third-party file managers and launch the native system document picker directly.

---

## 🚀 Features

* **Direct System Access:** Triggers `Intent.ACTION_OPEN_DOCUMENT` immediately upon launch to open the native storage provider.
* **Lightweight & Fast:** Built without bloated dependencies, unnecessary permissions, or heavy UI frameworks.
* **Auto-Termination:** Cleanly closes background tasks once a file is selected or the action is canceled.
* **Modern Target:** Compiled with Android SDK 35 (Android 15) and Kotlin JVM target 17.

---

## 📁 Project Structure

```text
SystemFiles/
├── .github/
│   └── workflows/
│       └── build.yml               # Automated APK CI/CD pipeline
├── app/
│   ├── build.gradle.kts        # App-level build configurations
│   └── src/main/
│       ├── AndroidManifest.xml
│       ├── java/com/example/systemfiles/
│       │   └── MainActivity.kt # Core launch logic
│       └── res/                # App resources and vector icons
├── build.gradle.kts            # Project-level build configuration
├── gradle.properties
└── settings.gradle.kts
```
