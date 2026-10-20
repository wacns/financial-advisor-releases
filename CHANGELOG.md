# FinancialAdvisor changelog

Public release history. Application source remains private.

## 1.7.0

Walletry-inspired finance tools across the shared web, mobile and desktop interface.

### What's Changed

- Document public installers and verified update downloads by @wacns in [d86b9d0](https://github.com/wacns/Financial-Advisor/commit/d86b9d006c7571ad7136cd6c4458813626551634)
- Publish mobile release installers to public downloads repository by @wacns in [2a247bd](https://github.com/wacns/Financial-Advisor/commit/2a247bda484eb8b7a19a6ed5955af9329a503a78)
- Read newly created release drafts through release listing by @wacns in [2a78c47](https://github.com/wacns/Financial-Advisor/commit/2a78c47ecaade4f33ed7a6ca029fd0b6081f78ba)
- Document public mobile downloads and verified publication by @wacns in [ab4a046](https://github.com/wacns/Financial-Advisor/commit/ab4a0466801d38a168b83e8548546245b10ec450)
- Keep mobile and desktop installers together in unified releases by @wacns in [193110f](https://github.com/wacns/Financial-Advisor/commit/193110fea727b1b31d528dd4a0a2d8cad2bf20d9)
- Document unified release and verified consolidation by @wacns in [cf0281c](https://github.com/wacns/Financial-Advisor/commit/cf0281c7fae966368a42d4e0a90f1c67d028f549)
- Publish versioned release changelogs with public history links by @wacns in [4ba9442](https://github.com/wacns/Financial-Advisor/commit/4ba94421a8be3b77e821d0b6dc8a7a95882353ba)
- Record verified public changelog publication by @wacns in [c0f163b](https://github.com/wacns/Financial-Advisor/commit/c0f163b9f84dbeb303856af37fb7aae84ad440ff)
- Generate release changelogs from verified commits and merged pull requests by @wacns in [6e3f3f4](https://github.com/wacns/Financial-Advisor/commit/6e3f3f49825f7f3408be267e13c1a4fc6c8bb787)
- Record verified commit and PR release history by @wacns in [b31785d](https://github.com/wacns/Financial-Advisor/commit/b31785dab09b62e67b2a2be9f4d99b10647f4e0e)
- Add Walletry-inspired organization, commitments and shared accounts by @wacns in [9a3c4b8](https://github.com/wacns/Financial-Advisor/commit/9a3c4b84990bc70d93a8da80a5f356971420ce35)
- Keep captured currency labels aligned with reviewed accounts by @wacns in [2f620c5](https://github.com/wacns/Financial-Advisor/commit/2f620c5b9cd8aed5c82d13a373e92fd6e4ca14b8)
- Document new finance tools and optional assistant setup by @wacns in [6bd64c2](https://github.com/wacns/Financial-Advisor/commit/6bd64c2f7ec7ff4c246b6a6c6494ca9ec5bff09f)
- Fix Xcode Shortcuts source paths and verify native build inputs by @wacns in [3be71ea](https://github.com/wacns/Financial-Advisor/commit/3be71eaa6777a179a98653cce151b72ca3e1ceed)
- Align plan category defaults with visible and imported choices by @wacns in [cb4e94e](https://github.com/wacns/Financial-Advisor/commit/cb4e94e45c451a119878012002199d0f09bf6272)

### Release highlights

- Add customizable account colors/icons, a default entry account, optional exclusion from tracked totals and reward-point tracking.
- Add payee/payer directories and colored tag management with searchable linked transactions.
- Add pinned entries, day grouping, location/receipt metadata and filters for dates, amounts, contacts, tags and multiple accounts.
- Add rolling report ranges, multiple-account charts and payee reports; show budget days remaining, daily allowance and limit warnings.
- Add dedicated subscriptions, trial/renewal tracking and billing intervals such as every three or six months.
- Add finite installment plans with exact thousandth-unit allocation, payment progress and remaining totals. Distinguish a real expense from marking an already-recorded payment paid; reversing an expense restores its balance and reopens the tracker occurrence.
- Add shared accounts with owner/editor/viewer access, expiring single-use invitations, an activity history and conflict-aware editing. Shared balances are independent of personal workspaces.
- Add a currency calculator, reviewed reference-rate refresh with saved history and an external ATM map search.
- Add local text capture, duplicate protection and editable review drafts; support device speech capture in new iOS/Android builds and compatible browsers.
- Add local money insights and an optional authenticated cloud assistant with explicit sharing consent, aggregate-only optional summaries, bounded usage and validated suggestions. The assistant cannot write financial records.
- Add iOS Shortcuts for payment text and expense drafts, plus reviewed capture URLs on both mobile platforms.
- Preserve existing personal records, balances and backups; older workspaces gain empty feature collections.

### Installers

| Platform | Format | Version |
| --- | --- | --- |
| Android | APK / AAB | 1.7.0 |
| iOS | Unsigned IPA | 1.7.0 |
| Windows | EXE | 1.7.0 |
| macOS | DMG / ZIP | 1.7.0 |
| Linux | AppImage / DEB | 1.7.0 |

### Known limitations

- Preview signing remains unchanged: Android uses the testing key unless a release keystore is configured; iOS requires signing before installation; Windows/macOS signing is not configured.
- Native speech and iOS Shortcuts require these new binaries; an OTA update cannot add native permissions or code. Physical-device microphone, Shortcuts, push and installation checks remain separate from successful compilation.
- Cloud AI stays unavailable until the server has an AI Gateway key and a supported model configured. Local capture and insights work without it. Provider calls may incur charges; no key or budget is automatically created.
- Currency quotes are reference rates, not bank settlement rates. Shared accounts track a collaborative ledger and do not connect to a bank or combine personal ledgers.
- Apple Watch/visionOS apps, iOS WidgetKit/Control Center widgets and Live Activities are not included. Android's existing quick-entry/template widgets remain available.

**Full Changelog**: https://github.com/wacns/Financial-Advisor/compare/desktop-v1.6.1...v1.7.0

Source commit, PR and comparison links require access to the private source repository.

[Public release history](https://github.com/wacns/financial-advisor-releases/blob/main/CHANGELOG.md)

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
