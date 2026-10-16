# focusly 🍅

A simple **Pomodoro focus timer** app built with Flutter for my Mobile Application Development course.

**Live demo:** https://minahilfatima18.github.io/Focusly/

## Screens

1. **Splash** – app logo shown for 2 seconds
2. **Onboarding (3 pages)** – swipeable intro with Skip, dots and Next / Get started
3. **Timer – Idle** – ready to start (25:00)
4. **Timer – Short break** – teal timer with a "session saved" snackbar
5. **Timer – Long break** – shown after 4 focus sessions
6. **Session complete** – dialog with Skip break / Start break
7. **Bottom navigation** – Timer, Stats, Settings

## Features

- Focus (25 min), Short break (5 min) and Long break (15 min) modes
- Circular progress ring that counts down
- Play / pause, reset and skip buttons
- Session counter (Session 1 of 4) with progress dots
- "Working on" card in focus mode, "Break tip" card in break mode
- Material 3 design with a tomato red and teal color theme

## Built with

- Flutter (Dart)
- No extra packages, only Flutter's own widgets

## How to run

```bash
git clone https://github.com/MinahilFatima18/Focusly.git
cd Focusly
flutter pub get
flutter run
```

To run in the browser: `flutter run -d chrome`

## Project structure

```
lib/
  main.dart     # all screens and logic in one file
web/            # web support files
docs/           # built web app (GitHub Pages)
```

## Author

Minahil Fatima
