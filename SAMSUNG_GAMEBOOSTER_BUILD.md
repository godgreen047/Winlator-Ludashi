# Samsung Game Booster test build

This branch builds a Winlator Ludashi v4.1 Vanilla test APK for Samsung Game Booster recognition.

Changes:

- Uses package id `com.winlator` for recognition testing.
- Keeps Winlator Ludashi/CMOD code namespace.
- Keeps `android:isGame="true"` and `android:appCategory="game"`.
- Adds extra Samsung/Game Booster manifest metadata.

Install note:

This APK cannot be installed alongside official Winlator because it uses `com.winlator`.
