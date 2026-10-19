# FinancialAdvisor downloads

Public mobile and desktop installers and desktop automatic-update metadata for FinancialAdvisor. Application source code remains in a separate private repository.

Preview downloads include [Android APK/AAB and unsigned iOS IPA v1.6.0](https://github.com/wacns/financial-advisor-releases/releases/tag/v1.6.0), plus [Windows EXE, Linux AppImage/DEB and macOS DMG/ZIP v1.6.1](https://github.com/wacns/financial-advisor-releases/releases/tag/v1.6.1). Verify desktop files with SHA256SUMS.txt and mobile files with MOBILE-SHA256SUMS.txt from the corresponding release.

The Android preview uses the Expo testing key. The iOS IPA is unsigned and must be signed before installation on a device. Publishing it here does not remove Apple signing requirements.

Windows and macOS preview installers are unsigned. macOS automatic updates require a signed application; use the newer installer manually for now. Linux automatic updates work with AppImage; DEB upgrades use the newer package. Save your work before restarting to install an update.

The `updates/` directory contains public update metadata only. No account records, credentials or application source belong in this repository.
