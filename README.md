# HisabKitab Android project

This is an Android Studio project wrapping the existing HisabKitab HTML prototype in a WebView.

## Build locally
1. Install Android Studio and Android SDK Platform 35.
2. Open this folder in Android Studio and allow Gradle sync.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Debug APK output: `app/build/outputs/apk/debug/app-debug.apk`.

## Build APK using GitHub Actions
1. Create a new GitHub repository and upload these project files.
2. Open the Actions tab and run **Build HisabKitab APK** (or push to `main`).
3. Open the completed workflow run and download the `HisabKitab-debug-apk` artifact.

This prototype stores data on the device/browser storage. It does not provide cloud sync, login, bank integration, or a production backup service. Test thoroughly before public release.
