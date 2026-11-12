# AI Video Studio — Android starter project

This is a native Android Studio starter app written in Kotlin + Jetpack Compose.

## Included in this starter
- Pick a video from the phone using Android's system picker.
- Preview/play the selected video with AndroidX Media3 ExoPlayer.
- Type Hindi or English narration and play it using the phone's installed Android Text-to-Speech engine.
- Stop narration.
- UI sections reserved for trim/cut, subtitles, music, cartoon animation and HD export.

## Important limitations
This is a starter/MVP, not a finished professional editor. Timeline trimming, rendering/export, auto subtitles, background music mixing, and AI cartoon generation are not implemented yet. Text-to-Speech is free through the phone's installed engine; voice availability and quality depend on the device and installed language data. Cloud AI generation may require a paid provider/API and should not be advertised as universally free.

## Build
1. Install Android Studio (current stable) and Android SDK 35.
2. Open this folder in Android Studio.
3. Let Gradle sync complete (internet is needed to download dependencies).
4. Run on an Android device (Android 6.0/API 23 or newer).

Package: `com.aivideostudio.app`
