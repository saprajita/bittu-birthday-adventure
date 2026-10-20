# 24 Hours to Find Vinnie — Android project

This Android Studio project wraps the included offline HTML game in a native Android WebView. The game assets are bundled locally; no website is required to play. Browser local storage is enabled for save progress.

## Build an APK locally
1. Install Android Studio (including Android SDK Platform 35) and JDK 17.
2. Open this folder as a project.
3. Let Gradle sync, then choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. The debug APK is generated at `app/build/outputs/apk/debug/app-debug.apk`.

## Build using GitHub Actions
1. Create a GitHub repository and upload all files in this folder.
2. Open **Actions** and select **Build Android APK**; run the workflow.
3. Download the `Bittu-Birthday-Adventure-APK` artifact from the completed workflow run. Extract it to get `app-debug.apk`.

The generated debug APK is installable on Android, but it is not Play Store-signed. iPhones cannot install APKs; for iPhone use the browser/PWA version.
