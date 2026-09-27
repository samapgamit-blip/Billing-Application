Building Rent Manager Android project

This is an Android Studio project wrapper for the included rent management app.
The web app is bundled locally in app/src/main/assets/index.html and uses local browser storage (WebView DOM storage).

Build:
1. Install Android Studio on a computer.
2. Open this extracted folder as an existing Android Studio project.
3. Let Gradle sync and install any requested Android SDK platform (API 35) and build tools.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Debug APK output is typically app/build/outputs/apk/debug/app-debug.apk.
6. For personal installation, copy the APK to your Android phone and allow installation from that source when prompted.

Notes:
- This source project has not been compiled or tested here; no Android SDK/Gradle build tool was available in the creation environment.
- For distribution to other people, create a signed release APK from Android Studio.
- App data is stored locally on the phone. Use the app's Backup function regularly.
