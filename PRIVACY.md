# Privacy Policy

Effective date: October 22, 2026

This policy describes the current Frames-sample app configuration (`Frames`, application ID `dev.jahir.frames.app`). A customized build may use a different wallpaper catalogue, publisher, or integrations; its publisher should update this policy before distribution if its data practices differ.

## Information and app data

The app does not require an account or ask for a name, email address, or profile. It stores app settings and feature data on the device, which can include the selected language and theme, download and display preferences, favorite-wallpaper references, cached catalogue data, thumbnails, and wallpaper images. The app does not send this locally stored preference or favorites data to the app publisher.

When you choose to download a wallpaper, the image is saved to the configured download location (by default, the device's Pictures/Frames folder). When you apply a wallpaper, Android's wallpaper service handles setting it on the screen you selected. The app can also receive an image you select through Android's system picker; access is limited to the selected item and the system-granted access.

## Network requests and third parties

The app needs internet access to retrieve wallpaper catalogue data, wallpaper thumbnails and images, and remote creator or asset images shown in the About screen. The current catalogue is [hosted on GitHub](https://raw.githubusercontent.com/user774820/wallrepos/refs/heads/main/wavywalls.json). That catalogue can link to wallpaper files hosted by other services. The app also opens external websites when you choose a link in the app.

The GitHub and other content hosts receive ordinary connection data needed to serve requests, such as your IP address, requested URL, request time, and standard network or device connection metadata. Those providers handle their server logs under their own privacy policies. The app does not control their collection, retention, or use of that information.

Release builds use Google Play licensing and installation validation. The app includes Google Play Billing support, but no purchase products are configured in this source build. If a customized or later build enables purchases, Google Play processes the information needed for licensing or transactions under Google's terms and privacy policy. The app publisher does not receive payment-card details through the app.

The app does not configure an app-publisher account service, advertising service, or app-owned analytics or crash-reporting service. This does not cover diagnostics or data processing performed independently by Android, Google Play, or the content hosts you contact.

## Permissions and system integrations

The app's merged Android manifest includes permissions for internet and network-state access, wallpaper operations, system-setting integration, and background work needed for wallpaper downloads. It also includes legacy external-storage permissions restricted by Android version. Android controls any system prompts and file access. The app does not request notification, location, contacts, camera, microphone, SMS, or call-log permissions.

The app does not send push or promotional notifications. Android or Google Play may show system-managed notices or dialogs related to operating-system features, licensing, or a user-requested operation.

An optional Muzei provider is included. If you connect the app to Muzei, the wallpaper and related metadata requested by Muzei are shared with that app through Android's provider interface. Muzei's own privacy policy then applies to its handling of that information.

## Storage, backup, and deletion

Settings, favorites, and cached app data remain in app storage until you clear them, clear app storage, or uninstall the app. Use the app's cache-clearing setting or Android's app settings to remove app data. Wallpaper files saved to a shared Pictures folder may remain after app data is cleared or the app is uninstalled; delete those files using your device's file or gallery app.

Android cloud backup and device transfer are enabled for app data. Whether a backup is made and how long it is retained depends on your Android device and backup-account settings. The app publisher does not operate that backup service.

## Children's privacy

The app does not request age or account information and is not designed to collect personal information from children. Wallpaper and external website content may be supplied by third parties and is subject to their own practices.

## Policy changes and contact

This policy should be revised when the app's data sources, permissions, billing, or integrations change. No dedicated privacy email address is configured in this project. For privacy questions about a distributed build, contact its publisher through the app's [Google Play developer page](https://play.google.com/store/apps/dev?id=7791472155222642322) or the publisher's support channels.
