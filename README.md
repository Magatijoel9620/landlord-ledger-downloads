# Landlord Ledger Android Downloads
flutter pub get
flutter analyze
flutter test
flutter build apk --release

cp build/app/outputs/flutter-apk/app-release.apk landlord-ledger.apk

gh release create vX.Y.Z landlord-ledger.apk \
  --repo Magatijoel9620/landlord-ledger-downloads \
  --title "Landlord Ledger vX.Y.Z" \
  --notes "Describe changes and fixes."
