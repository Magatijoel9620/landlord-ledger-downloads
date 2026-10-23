# Landlord Ledger Android Downloads
flutter pub get
flutter analyze
flutter test
flutter build apk --release

cp build/app/outputs/flutter-apk/app-release.apk landlord-ledger.apk


gh release create v1.3.0 landlord-ledger.apk \
  --repo Magatijoel9620/landlord-ledger-downloads \
  --title "Landlord Ledger v1.3.0" \
  --notes "Deep link fixed."
