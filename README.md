# Auto Read Scroll Android

Auto Read Scroll is a small native Android app that helps with hands-free reading. It uses an Accessibility Service to scroll the currently open app or web page at a steady speed, and it can show a floating Start/Pause control over other apps.

## Build

Open this folder in Android Studio:

```text
D:\New folder\AutoReadScroll
```

Then let Android Studio sync Gradle and run the `app` configuration on a phone or emulator.

## Use

1. Open the app.
2. Tap **Open Accessibility Settings** and enable **Auto Read Scroll Service**.
3. Tap **Allow Floating Controls** if you want the small control panel over other apps.
4. Open a web page, PDF, or app you want to read.
5. Press **Start Auto Scroll** in the app or **Start** on the floating control.

## Notes

Android requires the accessibility permission because normal apps are not allowed to control other apps. Some apps may block scroll actions; when that happens, Auto Read Scroll falls back to a gentle swipe gesture.

## PC Version

The PC version is in:

```text
D:\New folder\AutoReadScrollPC
```

It includes a Chrome/Edge extension for web pages and a Windows helper script for other desktop apps.
