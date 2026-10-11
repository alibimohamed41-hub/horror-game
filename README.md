# Nightfall: Horror Survival (Android APK project)

A small, playable, offline 2D horror-survival game built with Android WebView. You collect 5 fuses, avoid the shadow creature, and escape through the exit. Touch controls work on phones.

## Build an APK
This project is a starter Android Studio project. The easiest beginner route is:
1. Install Android Studio on a computer.
2. Open this folder using **Open**.
3. Let Gradle sync. If Android Studio asks to install Android SDK/build tools, accept.
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. When complete, click **locate** to find `app-debug.apk`.
6. Copy the APK to your Android phone and install it. You may need to allow installation from that file manager/browser. Only install APKs you built or trust.

## Upload to MediaFire
1. Sign in to MediaFire in your phone browser or app.
2. Upload `app-debug.apk` to your account.
3. Copy the share link and send it to friends.
4. Tell friends this is an Android APK; they must download it and install it. Android may show a warning for apps installed outside Google Play.

## Notes
- The APK is not built automatically by this ZIP. Android Studio/Gradle is required to compile the source into an APK.
- Package name: `com.novagames.nightfall`
- The game works offline and does not request internet permission.

## Build using GitHub from your Android phone (no computer needed, if GitHub Actions is available)
1. Create a new GitHub repository.
2. Extract this ZIP on your phone if possible, then upload the project files/folders into the repository. Keep the `.github/workflows/build-apk.yml` file and its folder structure.
3. Open the repository's **Actions** tab. If prompted, enable Actions.
4. Choose **Build Nightfall APK** and tap **Run workflow** (or push/upload a commit to `main` to trigger a build).
5. Open the finished workflow run. Under **Artifacts**, download `Nightfall-Horror-APK`. Extract the downloaded artifact ZIP to get `app-debug.apk`.
6. Upload `app-debug.apk` to MediaFire and share its link.

GitHub's web interface on Android can be awkward for uploading many folders. If uploading folders is difficult, use GitHub's upload-files page from a browser in desktop mode or build on a computer with Android Studio.
