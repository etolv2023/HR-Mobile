<h1 align="center">Fingerprint Mobile App</h1>

<p align="center">
  Secure fingerprint-based authentication app built with Flutter.
</p>

<p align="center">
  <a href="https://github.com/MNaguib2/fingerprint_v1_1/tags">
    <img alt="Download from Tags" src="https://img.shields.io/badge/Download%20APK-From%20Tags-0A66C2?style=for-the-badge&logo=github" />
  </a>
  <a href="https://github.com/MNaguib2/fingerprint_v1_1/releases/latest">
    <img alt="Latest Release" src="https://img.shields.io/github/v/release/MNaguib2/fingerprint_v1_1?style=for-the-badge" />
  </a>
</p>

---

## App Overview

Fingerprint is a Flutter mobile application focused on secure identity access and user verification workflows.

### Main Features

- Fingerprint/local authentication flow
- Secure app structure with modular routing
- Multi-platform Flutter setup (Android, iOS, Web, Desktop)
- Arabic and English translation support

---

## Download From Tags

1. Open project tags page:
   https://github.com/MNaguib2/fingerprint_v1_1/tags
2. Select the version you want (example: v1.0.0)
3. Open the release/tag assets
4. Download the APK file

Direct latest release page:
https://github.com/MNaguib2/fingerprint_v1_1/releases/latest

---

## App Design Demonstration

### Branding

<p align="left">
  <img src="assets/images/logo.png" alt="App Logo" width="120" />
</p>

### UI Preview Concept

Use this section to display your app screens on GitHub after upload.

- Add login screen screenshot
- Add fingerprint verification screen screenshot
- Add dashboard/home screen screenshot

Example template (replace paths after adding screenshots):

```md
<p align="center">
  <img src="assets/screenshots/login.png" alt="Login Screen" width="250" />
  <img src="assets/screenshots/fingerprint.png" alt="Fingerprint Screen" width="250" />
  <img src="assets/screenshots/home.png" alt="Home Screen" width="250" />
</p>
```

---

## Tech Stack

- Flutter
- Dart
- Local Auth / Biometric authentication
- Android and iOS native runners

---

## Build Release APK

```bash
flutter build apk --release --dart-define=PRODUCTION=true --obfuscate --split-debug-info=build/app/outputs/symbols
```

---

## Project Structure (Quick View)

- lib/
- assets/
- android/
- ios/
- test/

---

## Author

MNaguib2
