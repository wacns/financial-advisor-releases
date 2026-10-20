# FinancialAdvisor downloads

Public mobile and desktop installers and desktop automatic-update metadata for FinancialAdvisor. Application source code remains in a separate private repository.

All current downloads are in the [unified v1.6.1 release](https://github.com/wacns/financial-advisor-releases/releases/tag/v1.6.1): Android APK/AAB, unsigned iOS IPA, Windows EXE, Linux AppImage/DEB, and macOS DMG/ZIP. Desktop binaries are v1.6.1; mobile binaries retain their actual v1.6.0 filenames and versions. Verify desktop files with SHA256SUMS.txt and mobile files with MOBILE-SHA256SUMS.txt.

[Read the full changelog](CHANGELOG.md) for changes, update instructions and known limitations.

The Android preview uses the Expo testing key. The iOS IPA is unsigned and must be signed before installation on a device. Publishing it here does not remove Apple signing requirements.

Windows and macOS preview installers are unsigned. macOS automatic updates require a signed application; use the newer installer manually for now. Linux automatic updates work with AppImage; DEB upgrades use the newer package. Save your work before restarting to install an update.

The `updates/` directory contains public update metadata only. No account records, credentials or application source belong in this repository.
