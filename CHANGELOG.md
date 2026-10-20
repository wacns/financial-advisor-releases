# FinancialAdvisor changelog

Public release history. Application source remains private.

## 1.6.1

FinancialAdvisor preview for Android, iOS, Windows, macOS and Linux.

### What's Changed

- Document published cross-platform preview and verified release checksums by @wacns in [4ec8d16](https://github.com/wacns/Financial-Advisor/commit/4ec8d16cd3a0be0fc10601f4f5cd2019451a3a78)
- Add credential-safe update connection diagnostics by @wacns in [367381e](https://github.com/wacns/Financial-Advisor/commit/367381ef29ed5c53f6aab06107418d67b6c63fb7)
- Connect desktop updates to public installers repository by @wacns in [ef59f9b](https://github.com/wacns/Financial-Advisor/commit/ef59f9ba542b5febcfa36bbc4cdbcee3db055433)

### Release highlights

#### Added

- Public downloads for Android APK/AAB, unsigned iOS IPA, Windows EXE, macOS DMG/ZIP and Linux AppImage/DEB in one release.
- A public automatic-update feed included in Windows NSIS and Linux AppImage v1.6.1 installers.
- Separate checksum lists for desktop and mobile downloads.

#### Improved

- Consolidated mobile and desktop downloads into one release page, with each file's actual build version preserved.
- Release publishing verifies mobile files against their original checksums and rejects replacements with different contents.
- Desktop releases also attach the current existing mobile build to the same release.

#### Update instructions

- Install desktop v1.6.1 manually once when upgrading from v1.6.0 to connect to the public update feed.
- Windows NSIS and Linux AppImage check for updates and download them in the background. Save your work before choosing **Restart and install update** in Settings.
- Compatible mobile JavaScript updates use the Expo preview channel. Native changes require a new APK/IPA.

### Downloads

| Platform | File | Actual build version |
| --- | --- | --- |
| Android | APK / AAB | 1.6.0 |
| iOS / iPadOS | Unsigned IPA | 1.6.0 |
| Windows x64 | EXE | 1.6.1 |
| macOS Intel / Apple Silicon | DMG / ZIP | 1.6.1 |
| Linux x64 | AppImage / DEB | 1.6.1 |

Download files from **Assets** below. The existing mobile binaries are unchanged; their filenames and embedded versions remain v1.6.0. Verify desktop downloads with `SHA256SUMS.txt` and mobile downloads with `MOBILE-SHA256SUMS.txt`.

### Mobile installers

The Android preview uses the Expo testing key. Its AAB is for build testing and must not be submitted to Google Play with that key. The iOS IPA is unsigned and requires signing before installation on a device.

### Known limitations

- Windows and macOS preview installers are unsigned. macOS updates remain manual until signing is configured.
- DEB upgrades use the newer package; automatic Linux updates use AppImage.
- Mobile update publishing and runtime compatibility were verified; physical-device update delivery still needs testing.
- These are preview builds. Successful packaging and update downloads do not establish store approval or installation on every operating system.

**Full Changelog**: https://github.com/wacns/Financial-Advisor/compare/v1.6.0...desktop-v1.6.1

Source commit, PR and comparison links require access to the private source repository.

[Public release history](https://github.com/wacns/financial-advisor-releases/blob/main/CHANGELOG.md)

## 1.6.0

Initial cross-platform installer preview, published on 2026-10-19. These changes are included in the unified v1.6.1 downloads.

### What's Changed

#### Added

- Android APK/AAB, unsigned iOS IPA, Windows EXE, macOS DMG/ZIP and Linux AppImage/DEB packaging.
- An Electron desktop app that bundles the shared React interface and local receipt OCR assets.
- Desktop system-browser sign-in, an isolated renderer and sandboxed web content.
- Expo Updates with runtime fingerprint compatibility and preview/production publishing channels.
- Update checking and restart controls in Settings.

#### Fixed

- Android release builds now use the runner's installed SDK rather than Google's retired SDK tools package.
- App-owned Firebase notification metadata explicitly resolves the Android manifest merge conflict.
- The unsigned iOS build configures Firebase as static frameworks and disables the conflicting Firebase Swift Package Manager integration.

### Preview status

The Android preview uses a testing key, the iOS IPA is unsigned, and Windows/macOS signing is not configured. Desktop v1.6.0 had no default public update feed; install desktop v1.6.1 to enable supported automatic updates. Physical-device and OS installation checks remain separate from successful compilation.
