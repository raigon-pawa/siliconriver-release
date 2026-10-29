# SiliconRiver for Android

Android downloads for [SiliconRiver](https://myrig.app), the social network for PC builders.
Show off your rig, rate other people's builds, and climb the leaderboards.

## Download

**[Latest release →](https://github.com/raigon-pawa/siliconriver-release/releases)**

Each release has an `.apk` file under **Assets**. Builds marked **Pre-release** are betas: they have the newest features but may have bugs.

| Build | Version |
|---|---|
| Beta | [1.2.0 beta 1](https://github.com/raigon-pawa/siliconriver-release/releases/tag/v1.2.0-beta.1) |

## Install

1. Open the release on your Android phone and tap the `.apk` file to download it.
2. Open the downloaded file.
3. If Android asks, allow your browser or Files app to **install unknown apps**, then tap **Install**.

To update, install the newer `.apk` over the old one; you stay signed in.
If an older test build won't update ("App not installed"), uninstall it first.

**Requirements:** Android 7.0 or newer.

## Check the download (optional)

Each release lists the APK's SHA-256. To compare it on a computer:

```sh
sha256sum siliconriver-*.apk                       # Linux
shasum -a 256 siliconriver-*.apk                   # macOS
certutil -hashfile siliconriver-<version>.apk SHA256   # Windows
```

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/raigon-pawa/siliconriver-release/issues) with your phone model, Android version and the app version (Profile → Settings).

You can also use SiliconRiver in the browser at [myrig.app](https://myrig.app).

## License

[MIT](LICENSE)
