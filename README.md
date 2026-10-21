# MelodyRise — Android Alarm App

## Project Overview

MelodyRise is an Android alarm application designed to let users schedule alarms that play their selected songs, including full-length music tracks.

The project is an existing Android application being improved incrementally. The goal is to preserve working functionality, fix bugs, improve the user interface, and add reliable calendar-based and weekly alarms.

## Current Project Version

- Project: MelodyRise
- Source version: 2.5.1 — Calendar Weekly Compile Fix
- Platform: Android
- Build system: Gradle
- Language: Kotlin
- UI: Jetpack Compose

## Latest Updates

### 1. Calendar Alarm Improvements

Planned and ongoing calendar alarm functionality:

- Select specific dates for alarms using a calendar.
- Navigate between months and years.
- Select multiple dates, including dates across different months and years.
- Schedule an alarm for a selected date and time.
- Use the selected song for the scheduled dates.
- Disable or remove individual scheduled dates.
- Display markers for dates with scheduled alarms.
- Prevent scheduling alarms for dates in the past.

### 2. Weekly Alarm Improvements

Weekly alarm functionality:

- Select individual weekdays.
- Repeat alarms on selected weekdays.
- Choose the alarm time and song.
- Edit or disable weekly alarms.

### 3. Existing Alarm Functionality to Preserve

The following existing features must continue working during updates:

- Multiple alarms.
- Full-song playback.
- Song selection from phone storage.
- Background music playback.
- Alarm operation when the app is closed or the screen is locked.
- Restore scheduled alarms after device reboot.
- Alarm notification and stop controls.
- Permission handling for notifications and exact alarms.
- Existing themes and wallpaper customization.

### 4. User Interface Improvements

- Improve the alarm creation and management screens.
- Make calendar and weekly alarm selection easy to understand.
- Keep the interface modern, clean, and responsive.
- Support 12-hour time format with AM/PM as the default.
- Retain an option for 24-hour time format.

## Build Status

The Gradle debug build completed successfully on the development computer using:

    .\gradlew.bat assembleDebug

The generated debug APK is expected at:

    app/build/outputs/apk/debug/app-debug.apk

Build success confirms that the project compiled. It does not confirm that all alarm features have been tested on a physical Android device.

## Testing Checklist

The following tests still need to be completed or verified:

- [ ] Install the generated APK.
- [ ] Create and schedule multiple alarms.
- [ ] Select multiple calendar dates.
- [ ] Navigate between months and years.
- [ ] Verify alarms ring only on selected dates.
- [ ] Verify past dates cannot be selected.
- [ ] Edit and remove individual calendar dates.
- [ ] Configure weekly alarms for selected weekdays.
- [ ] Verify full-length songs play without being cut off.
- [ ] Verify alarms work when the app is closed.
- [ ] Verify alarms work when the screen is locked.
- [ ] Verify alarm restoration after device reboot.
- [ ] Test notification and stop-alarm controls.
- [ ] Verify permissions are requested when required.
- [ ] Test the 12-hour and 24-hour time formats.
- [ ] Check for crashes, duplicate alarms, and scheduling errors.

## Development Setup

Requirements:

- Android Studio
- Android SDK
- Java Development Kit compatible with the project's Gradle configuration

### Build the project

Open PowerShell in the project directory and run:

    .\gradlew.bat assembleDebug

### Install the debug APK

Locate the generated APK at:

    app/build/outputs/apk/debug/app-debug.apk

Transfer it to an Android device and install it. Grant the required permissions and test the alarm functionality.

## Development Principles

1. Continue improving the existing MelodyRise project. Do not recreate the application from scratch.
2. Preserve existing working features when adding new functionality.
3. Remove fake data, unnecessary demo elements, and unused code.
4. Ensure buttons, controls, and alarm settings perform their intended actions.
5. Avoid claiming features are complete until they have been tested.
6. Prioritize reliability, low resource usage, and a clean user experience.

## Current Development Stage

Calendar and weekly alarm improvements are being integrated into the existing application.

The current source version has successfully completed a debug build. Device testing and verification of the updated alarm features remain the next steps.
