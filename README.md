# Suthra Punjab Agency

Flutter project foundation for worker attendance and complaint management.

## Firebase setup
1. Install Flutter and Android Studio.
2. Install FlutterFire CLI: `dart pub global activate flutterfire_cli`
3. Run: `flutterfire configure`
4. Enable Firebase Authentication > Email/Password.
5. Create Firestore database.
6. Add a Google Maps Android API key if using maps.
7. Run `flutter pub get`.

## Build APK
`flutter clean`
`flutter pub get`
`flutter build apk --release`

APK output: `build/app/outputs/flutter-apk/app-release.apk`

## Important
`lib/firebase_options.dart` is intentionally a placeholder because Firebase credentials are project-specific. Review Firestore rules before production deployment. PDF/Excel services are scaffolded by dependencies; connect them to your production report queries before release.
