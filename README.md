# 🎵 MelodyRise
### Wake Up to Your Favourite Music

MelodyRise is an Android alarm clock application designed to make waking up more personal. Choose your favourite music, manage multiple alarms, and customize your alarm experience with a modern interface.

> 🚧 **Project Status: In Development**
>
> MelodyRise is an ongoing Android development project. Some features are still being implemented or tested. This is not yet an official Google Play release.

---

## 📥 Download the APK

Want to try MelodyRise on your Android phone?

**Latest Development Build:**

Once a release is published, replace the placeholder above with your actual GitHub Releases URL.

### Installation Instructions

1. Download the APK to your Android device.
2. Open the downloaded APK file.
3. If Android requests permission to install apps from that source, enable it only if you trust the APK.
4. Return to the installer and tap **Install**.
5. Open MelodyRise and review the requested permissions.

⚠️ **Safety notice:** Install only APKs from sources you trust. Development builds may contain bugs and should not be relied on for important wake-up times until thoroughly tested.

---

## ✨ Features

### ⏰ Alarm Management

- Create and manage multiple alarms.
- Set individual alarm times.
- Enable or disable alarms independently.
- Edit and delete alarms.
- Configure repeating alarms for selected weekdays.
- Organize alarms using individual clock-style cards.

### 🎶 Music-Based Alarms

- Select music files stored on your device.
- Choose different songs for different alarms.
- Play selected music as an alarm.
- Aim for complete-song playback rather than short alarm tones.

### 🎨 Personalization

- Modern glass-inspired user interface.
- Adjustable glass transparency.
- Customizable accent colours.
- Custom text and UI colours.
- Light and dark themes.
- Built-in wallpapers and custom wallpaper selection.
- Individual clock-card styling.

### ⚙️ Convenience and Settings

- 12-hour clock with AM/PM.
- Optional 24-hour clock format.
- Quick-alarm shortcuts.
- Alarm notifications and controls.
- Permission guidance for supported Android features.
- Settings and application information screen.

**Note:** The feature list describes the intended application capabilities. Individual features must be verified in the relevant build before being considered fully functional.

---

## 🛠️ Technology Stack

- **Programming language:** Kotlin
- **Platform:** Android
- **User interface:** Android UI components and Jetpack Compose where implemented
- **Build system:** Gradle
- **Development environment:** Android Studio

---

## 📱 Android Compatibility

MelodyRise is being developed for Android devices.

Alarm scheduling, notifications, full-screen alarm displays and background music playback can depend on:

- Android version.
- Notification and alarm permissions.
- Full-screen intent access where applicable.
- Battery optimization settings.
- Device manufacturer restrictions.

The minimum supported Android version and target SDK will be documented after they are verified in the project configuration.

---

## 🚀 Build from Source

### Prerequisites

- Android Studio.
- Android SDK compatible with the project.
- A JDK version supported by the project's Gradle configuration.

### Steps

1. Clone or download this repository.
2. Open the project root folder in Android Studio.
3. Allow Gradle to synchronize.
4. Configure the Android SDK if prompted.
5. Connect an Android device or start an emulator.
6. Build and run the application.

### Build a Debug APK on Windows

Open PowerShell in the project root and run:

```powershell
.\gradlew.bat assembleDebug
```

If the build succeeds, the APK is normally generated at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

The resulting debug APK is intended for development and testing, not as a substitute for a properly signed production release.

---

## 🔐 Permissions and Privacy

Depending on the implemented features, MelodyRise may require permissions or special access for:

- Notifications.
- Exact alarm scheduling.
- Access to user-selected music files.
- Full-screen alarm display.
- Background playback and alarm operation.

Android may require users to grant certain permissions through system settings.

MelodyRise's actual data handling must be reviewed before making privacy claims. A privacy policy and accurate Google Play Data safety declaration should be prepared before a Play Store release.

---

## 🗺️ Development Roadmap

- [ ] Verify a successful project build.
- [ ] Finalize the MelodyRise app name and launcher logo.
- [ ] Improve individual alarm clock cards.
- [ ] Verify multiple independent alarms.
- [ ] Test complete-song playback.
- [ ] Verify alarm behaviour with the app closed and screen locked.
- [ ] Test restoration after device reboot.
- [ ] Improve stop and snooze controls.
- [ ] Finalize glass-theme intensity controls.
- [ ] Add and test colour customization.
- [ ] Finalize wallpaper selection and theme persistence.
- [ ] Review permissions and error handling.
- [ ] Test on physical Android devices.
- [ ] Prepare a signed Android App Bundle for Google Play.

Roadmap items will be marked complete after implementation and testing.

---

## 🐛 Bug Reports

If you encounter an issue, please include:

- Android device model.
- Android version.
- MelodyRise version.
- Steps to reproduce the problem.
- Expected behaviour.
- Actual behaviour.
- Relevant error logs or screenshots.

Please do not include passwords, private files or other sensitive information in bug reports.

---

## 🤝 Contributions and Suggestions

Ideas, suggestions and bug reports are welcome.

Before submitting code contributions, please check the project's license and repository contribution guidelines. A license has not yet been selected.

---

## 📄 License

**No open-source license has been selected yet.**

Until a license is added, public visibility does not automatically grant permission to reuse, modify or redistribute the source code. A suitable license should be chosen before inviting public code contributions.

---

## ⚠️ Disclaimer

MelodyRise is an independent development project and is not affiliated with Google or any music-streaming service.

The application is still under development. Alarm reliability may vary depending on device settings, Android restrictions and the features available in a particular build.

Please test the application before relying on it for important alarms.

---

### 🎵 MelodyRise
**Wake Up to Your Favourite Music.**
