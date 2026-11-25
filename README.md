# Ichigo Bankai / Shikai Widget — upgraded edition

A dark Bleach-inspired Android home-screen widget using original generated Ichigo-themed artwork.

## Features
- **Ichigo artwork panel** bundled offline (no network needed).
- Clock + weekday/date display.
- Battery level shown as a **Reiatsu meter**; charging state changes the label.
- Tap the **Bankai/Shikai control** in the widget to switch mode, theme accent and quote.
- Tap the artwork or info area to open the companion screen.
- Companion screen with artwork and mode toggle.
- Widget supports resizing; designed for a wide home-screen placement.
- Refreshes on minute-boundary alarms where Android permits, plus time/date and power events. Android may defer refreshes in battery-saving modes.

## Build APK (Windows / Android Studio)
1. Install Android Studio (current stable) and Android SDK Platform 35.
2. Extract the ZIP; open the **`ichigo_widget`** folder (the one containing `settings.gradle`).
3. Let Android Studio sync/download dependencies. If asked, select a compatible Gradle 8.x version for Android Gradle Plugin 8.7.3 (Gradle 8.9 recommended).
4. Connect your Android phone with USB debugging enabled, or use an emulator.
5. Run the `app` configuration to install the app. Then long-press the phone home screen → **Widgets** → **Ichigo Bankai Widget** and place it.
6. To make an APK: **Build → Build Bundle(s) / APK(s) → Build APK(s)**. Debug APK output: `app/build/outputs/apk/debug/app-debug.apk`.

## Widget controls
- Tap artwork or the text/info panel: opens the companion app.
- Tap the bottom release/seal button: switches between Bankai and Shikai states.
- Long-press the widget on your launcher to resize it.

## Notes
- Widget update cadence is ultimately controlled by Android and the launcher; alarms can be deferred by Doze/battery restrictions.
- This source project has not been compiled in this workspace because Android SDK/Gradle build tools are not installed here. Build in Android Studio to produce the APK.
- No analytics, ads, internet permission, or external services are included.
