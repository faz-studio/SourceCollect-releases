# SourceCollect downloads

This repository holds public SourceCollect installer assets and signed automatic-update manifests. Application source is maintained separately.

Store editions:

- [Microsoft Store](https://apps.microsoft.com/detail/9N0XT13Q4FM5)
- [Mac App Store](https://apps.apple.com/app/id6815009285)

The [SourceCollect download page](https://sourcecollect.fazstudio.net/) shows available Store and direct installer options. Direct downloads become available when a qualified release is published.

Direct MSI and DMG editions are designed for seven days of full functionality, followed by inspection and complete collection without reduction through the context menu or Dashboard file drop. The Library continues showing projects and thumbnails; restricted actions require purchase of the Store edition.

Windows direct installers have no production Authenticode signature. Automatic-update payloads require a separate cryptographic updater signature. Mac direct releases require Developer ID signing and notarization. Store editions receive updates through their respective Stores.

Release tags `msi-<version>` and `dmg-<version>` hold immutable payloads. The `direct-msi` and `direct-dmg` channel tags hold the current `latest.json` updater manifests. No direct release is available until its installer, signature and supported native configuration have passed qualification.
