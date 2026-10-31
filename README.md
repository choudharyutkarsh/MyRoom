# My Room — Offline Android project

This Android Studio project wraps the supplied `index.html` + `bundle.js` inside a native Android WebView. Both files are bundled in `app/src/main/assets`, so the game launches locally and does not need a website or internet connection. The manifest intentionally declares no INTERNET permission.

## Build the APK
1. Open this folder in Android Studio (a current version with Android SDK Platform 35).
2. Allow Gradle to sync and download the Android Gradle Plugin/Kotlin plugin if prompted.
3. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
4. Android Studio creates the APK under `app/build/outputs/apk/debug/`.

The supplied game source is about 1 MB before APK packaging. APK size depends on Android/WebView packaging and does not become a 200–300 MB commercial game just by increasing its file size. No additional room models, textures, sounds, or levels were present in the uploaded ZIP.
