# Yonto Player

Yonto Player plays the videos you own, in one app on Android TV and on Android phones and tablets: your [Jellyfin](https://jellyfin.org), [Plex](https://www.plex.tv) or [Emby](https://emby.media) server, and the video files on a NAS (SMB or WebDAV), a USB drive or a folder.
Bought once, with no account, and it comes with no content: you bring your own.

This repository holds the releases and takes bug reports and feature requests.
The apps' source is not here; the plugin SDK and the CLI are, under MIT, in [yonto-app/yonto-player-plugins](https://github.com/yonto-app/yonto-player-plugins).

- **Set up from your phone.** The TV shows a QR code, and you type the server address and password on your phone instead of with the remote. What you type is encrypted on your phone, the relay only passes it on, and nothing is saved until you confirm on the TV.
- **Made for the remote.** Back returns you to the card you left, and Continue playing and your launcher's Watch Next row pick up where you stopped.
- **Plays the file as it is.** No transcoding on the server, and FFmpeg audio decoders for AC3, E-AC-3, DTS and TrueHD where the device has none.
- **No account, no ads.** The apps have no analytics, and your history and settings stay on the device.

Free with one source. Pro is one payment, no subscription, for more sources, plugins and up to five devices, TVs, phones and tablets together, and you can try it free for 7 days in the app, once per device, with no payment details: see [pricing](https://player.yonto.app/pricing/).

## Download

Each [release](https://github.com/yonto-app/yonto-player-releases/releases/latest) has two APKs:

- `Yonto-AndroidTV-vX.Y.Z.apk` for Android TV and Google TV, Android 8.0 or later.
- `Yonto-Phone-vX.Y.Z.apk` for Android phones and tablets.

On a TV, the quickest way is the Downloader app: type `player.yonto.app/tv` and it fetches the latest TV APK.
[Install on Android TV](https://player.yonto.app/docs/install-on-android-tv/) has that, sending it from your phone, and a USB drive.
Then [Getting started](https://player.yonto.app/docs/getting-started/) takes you through the demo library and your first source.

## Help

- [Docs](https://player.yonto.app/docs/) and [Troubleshooting](https://player.yonto.app/docs/troubleshooting/).
- [Report a problem or ask for a feature](https://github.com/yonto-app/yonto-player-releases/issues/new/choose).
- No GitHub account? Write to support@yonto.app ([support](https://player.yonto.app/support/)).

Jellyfin, Plex, Emby, Dolby and DTS are trademarks of their owners; Yonto Player is not affiliated with or endorsed by them.
