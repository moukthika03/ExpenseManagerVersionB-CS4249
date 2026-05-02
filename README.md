# CS4249 UI Comparative Study - Expense Manager Version B

## Hosted UI

GitHub Pages URL: [https://moukthika03.github.io/ExpenseManagerVersionB-CS4249/](https://moukthika03.github.io/ExpenseManagerVersionB-CS4249/)

## Project Overview

This repository contains Expense Manager Version B, a Flutter web application created for the CS4249 UI comparative study. The app supports an expense-entry flow, including category selection, amount entry, payment method selection, transaction details, and expense confirmation.

## Files and Folders

- `.github/workflows/` - GitHub Actions workflow used to build and deploy the Flutter web app to GitHub Pages.
- `build/` - Generated Flutter build output. This folder is produced by the build process.
- `lib/` - Main Flutter application source code.
- `lib/main.dart` - App entry point and top-level app setup.
- `lib/firebase_options.dart` - Firebase configuration generated for the app.
- `lib/models/` - Data models used by the app, including the expense model and generated serialization code.
- `lib/screens/` - UI screens for the expense manager flow, such as home, new expense, category selection, payment method, transaction details, and confirmation screens.
- `lib/services/` - App services for analytics, expense handling, flow state, and platform/device detection.
- `lib/widgets/` - Shared reusable widgets used across screens.
- `web/` - Flutter web shell files, icons, favicon, manifest, and `index.html`.
- `analysis_options.yaml` - Dart analyzer and lint configuration.
- `firebase.json` - Firebase-related project configuration.
- `pubspec.yaml` - Flutter project metadata and dependency definitions.
- `pubspec.lock` - Locked dependency versions for reproducible builds.
