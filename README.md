# Full Song Alarm 2.3 — UI update (source project)

## Included in this update
- Restored an Android-style Material 3 clock time picker. It displays AM/PM in the default 12-hour format and switches to 24-hour mode when selected in the Theme menu.
- The selected time is committed only when the user taps **OK**; Cancel dismisses without changing the time.
- Kept the +1 min, +5 min, and +10 min quick-adjust controls.
- Added a **Glassy wallpaper theme** with translucent cards and a lighter overlay so the selected wallpaper remains visible.
- Added a first-launch optional name prompt, locally saved on the device, and a greeting that changes by local time (Good morning/afternoon/evening/Hello). The name can be changed from the home screen or skipped.
- Updated the full-screen alarm screen to show the saved wallpaper, a glass-style alarm card, the selected alarm time, greeting, song title, and existing Stop/Snooze actions.
- Preserved existing alarms, music selection/playback, wallpaper choices, and light/dark/system themes.

## Build
Open this `FullSongAlarm` folder in Android Studio, allow Gradle sync, and select **Build > Build APK(s)**. The debug APK is normally created at `app/build/outputs/apk/debug/app-debug.apk`.

If building from PowerShell, run `.\gradlew.bat assembleDebug` from this folder. If Android SDK location is not found, create `local.properties` in this folder with your actual SDK path, for example:

```properties
sdk.dir=C:/Users/YOUR_USERNAME/AppData/Local/Android/Sdk
```

Do not copy that example literally; replace it with the SDK location shown in Android Studio's SDK Manager.

## Important test checklist
- Test the time picker in both 12-hour and 24-hour modes; verify AM/PM and midnight/noon conversions.
- Verify the wallpaper shows through glass cards with built-in and local wallpapers.
- Verify first-run name prompt, Skip, Edit name, and persistence after restarting the app.
- Test the full-screen alarm UI with the phone locked and unlocked; confirm Stop and Snooze still work.
- Test alarms after granting Android 14 notification, exact-alarm, and full-screen intent access.
- Test short and long audio files, repeated alarms, and app relaunch.

## Limitations
This ZIP contains source code, not a prebuilt APK. It has not been compiled or device-tested in this environment because a local Android SDK/Gradle build environment was unavailable. Treat it as a development build until Android Studio compiles it and it passes the checklist above. Device reboot restoration is not implemented.
