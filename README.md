# Vidyut Suraksha — Android MVP

A small native Android learning app for electrical safety awareness.

## Included
- Home dashboard with learning progress and best quiz score
- Five short learning modules
- Mark lesson complete; progress persists locally on the device
- Six-question multiple-choice quiz with immediate feedback and explanations
- Quiz best score saved locally
- No login, analytics, network permissions, or backend required

## Build with Android Studio
1. Install Android Studio (current stable release) and its Android SDK.
2. Unzip this project folder.
3. In Android Studio, choose **Open** and select the `VidyutSurakshaMVP` folder (the one containing `settings.gradle`).
4. Allow Gradle sync. If prompted, install Android SDK Platform 35 and a compatible Android Gradle Plugin/JDK.
5. Connect an Android phone with USB debugging enabled, or create an emulator.
6. Press **Run**. App label: **Vidyut Suraksha**.

## Build an APK
In Android Studio: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
The debug APK is usually created at:
`app/build/outputs/apk/debug/app-debug.apk`

To install on a phone, transfer that APK to the device and allow installation from that source if Android asks. For distribution to others, create a signed release build.

## Build from command line
If Gradle is installed and Android SDK configured:
```bash
gradle assembleDebug
```
Run from the project root. The Android Gradle Plugin will require a compatible JDK and SDK.

## Important content note
This MVP is a learning aid and not an official CEA publication or compliance tool. Verify regulatory content against the latest applicable CEA regulations, Indian standards, utility procedures, and competent professional advice before using it for training or operational decisions. It does not authorise electrical work.
