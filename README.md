# mi_card_flutter

Simple Flutter "Mi Card" business-card style demo application.

**Summary**
- A minimal Flutter app that displays a personal/business card UI with image, name, role, and contact actions.

**Features**
- Clean, single-screen layout
- Uses local assets for fonts and images (see `assets/`) 
- Ready to run on Android and iOS

**Prerequisites**
- Flutter SDK (stable channel). See https://flutter.dev/docs/get-started/install
- macOS with Xcode for iOS builds (optional)

**Quick Start**
1. Clone the repo:

   git clone <repo-url>
   cd mi_card_flutter

2. Get dependencies:

   flutter pub get

3. Run on a connected device or simulator:

   flutter run

4. Build release APK:

   flutter build apk --release

5. Build iOS (macOS + Xcode required):

   flutter build ios --release

**Project Structure (high level)**
- `lib/main.dart` - app entrypoint and UI layout ([lib/main.dart](lib/main.dart))
- `assets/` - fonts, images and other static assets
- `android/`, `ios/` - platform-specific build code

**Customization**
- Change displayed name, title, contact info or image by editing `lib/main.dart`.
- Add images to `assets/images/` and fonts to `assets/fonts/`. Update `pubspec.yaml` if adding new assets.

**Testing**
- This demo doesn't include automated tests. You can run `flutter analyze` to check for static issues.

**Contributing**
- Contributions are welcome — open an issue or PR with proposed changes.

**License**
- This repository doesn't include a license file. Add a license if you plan to share it publicly.

**Contact**
- For questions, update the repo README or open an issue in the project.
  
