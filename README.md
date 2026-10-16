# MHARItv Music Android app

This is an Android Studio project wrapping the current MHARItv Music Distribution & Publishing HTML prototype in a native Android WebView. It is source code, not a prebuilt APK.

## Build an installable APK
1. Install Android Studio on a computer and open this `MHARItvAndroid` folder.
2. Allow Android Studio to install the Android SDK / Build Tools it requests (compile SDK 35).
3. Wait for Gradle sync to finish.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Click **locate** in the build notification. The debug APK will be at `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer that APK to your Android phone and open it to install. You may need to allow installation from that file manager. Only install APKs you trust.

## Important limitations
- The app is currently a packaged prototype. This does not provide a live global music-distribution service, actual royalty payouts, licensing contracts, or an approved YouTube Official Artist Channel merge.
- Before production release, connect and test a secure backend, authentication, upload storage, metadata validation, royalty/payment reporting, privacy policy, terms, and support process.
- Use your own signing key for release builds. Do not share passwords or signing keys.
- Store developer accounts must be owned/managed by an eligible adult or organization where required.
