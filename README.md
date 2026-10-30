<div align="center">

<img src="assets/icon.png" alt="SiliconRiver app icon" width="112" height="112">

# SiliconRiver for Android

**The social network for PC builders.**<br>
Show off your rig, rate other people's builds, and climb the leaderboards.

[![Latest release](https://img.shields.io/github/v/release/raigon-pawa/siliconriver-release?include_prereleases&label=latest&color=00F5FF&style=flat-square)](https://github.com/raigon-pawa/siliconriver-release/releases)
[![Downloads](https://img.shields.io/github/downloads/raigon-pawa/siliconriver-release/total?color=BF00FF&style=flat-square)](https://github.com/raigon-pawa/siliconriver-release/releases)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-FF006E?style=flat-square&logo=android&logoColor=white)
[![License: MIT](https://img.shields.io/badge/license-MIT-555?style=flat-square)](LICENSE)

### [⬇ Download the APK](https://github.com/raigon-pawa/siliconriver-release/releases/download/v1.2.0-beta.3/siliconriver-1.2.0-beta.3.apk)

<sub>1.2.0 beta 3 · [All releases](https://github.com/raigon-pawa/siliconriver-release/releases) · or use it in your browser at [myrig.app](https://myrig.app)</sub>

<br>

<img src="assets/screenshots/feed.webp" alt="Home feed with a rig post" width="200">&nbsp;
<img src="assets/screenshots/explore.webp" alt="Explore: search and trending builds" width="200">&nbsp;
<img src="assets/screenshots/hardware.webp" alt="Hardware catalog with the featured part" width="200">&nbsp;
<img src="assets/screenshots/profile.webp" alt="Profile with system specs" width="200">

</div>

## Features

- **Your rigs:** list your parts in the spec sheet (search the dropdowns or type your own) and your primary rig shows on your profile and tags your posts.
- **Feed:** Trending, Latest and Following, with photo galleries, benchmark posts, questions and Rate My Rig.
- **Reactions and comments:** five community reactions (✨ ⚡ 🔌 🔥 👑) and threaded replies.
- **Explore:** search builders, parts and posts, and see what's trending.
- **Hardware:** a catalog of popular parts, with the rigs and posts that use each one.
- **Benchmarks:** log Cinebench, 3DMark and Geekbench scores and compete on the leaderboards.
- **Notifications:** push alerts for reactions, comments, replies, follows and @mentions.
- **Saved posts, editing and pinning:** bookmark posts, fix typos, pin your best post to your profile.
- **Dark and light themes**, and sign-in with Google or email.

## Install

1. On your Android phone, tap **[Download the APK](https://github.com/raigon-pawa/siliconriver-release/releases/download/v1.2.0-beta.3/siliconriver-1.2.0-beta.3.apk)**.
2. Open the downloaded file.
3. If Android asks, allow your browser or Files app to **install unknown apps**, then tap **Install**.

**Requirements:** Android 7.0 or newer.

### Updates

- **Small fixes arrive on their own.** The app downloads them in the background and applies them the next time you open it. Settings shows the current patch, e.g. `1.2.0 (patch 4)`.
- **Bigger updates** come as a new APK here. Install it over the old one; you stay signed in.
- If an older test build won't update ("App not installed"), uninstall it first.

## Releases

Builds marked **Pre-release** are betas: newest features first, so expect the odd bug.

| Version | Date | Highlights |
|---|---|---|
| [**1.2.0 beta 3**](https://github.com/raigon-pawa/siliconriver-release/releases/tag/v1.2.0-beta.3) | Oct 2026 | Push notifications, saved posts, @mentions, edit and pin posts. Since then: follower lists, searchable part dropdowns (as updates) |
| [1.2.0 beta 2](https://github.com/raigon-pawa/siliconriver-release/releases/tag/v1.2.0-beta.2) | Oct 2026 | Automatic small updates |
| [1.2.0 beta 1](https://github.com/raigon-pawa/siliconriver-release/releases/tag/v1.2.0-beta.1) | Oct 2026 | First public beta, native Google sign-in |

## FAQ

<details>
<summary><b>Why isn't it on the Play Store?</b></summary>

It will be. Until then, betas are published here first.
</details>

<details>
<summary><b>Is it safe to install an APK?</b></summary>

Only install APKs from this page. Every release is signed with the same key, which is why new versions install over old ones, and each release lists the file's SHA-256 so you can check it (see below).
</details>

<details>
<summary><b>Is there an iPhone app?</b></summary>

Not yet. On iPhone, use [myrig.app](https://myrig.app) in Safari. It's the same account and content.
</details>

<details>
<summary><b>Is my account the same as on the website?</b></summary>

Yes. Sign in with the same Google account or email and everything is there: posts, rigs, followers and notifications.
</details>

<details>
<summary><b>Check the download (optional)</b></summary>

Compare the APK's SHA-256 with the one in the release notes:

```sh
sha256sum siliconriver-*.apk                            # Linux
shasum -a 256 siliconriver-*.apk                        # macOS
certutil -hashfile siliconriver-<version>.apk SHA256    # Windows
```
</details>

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/raigon-pawa/siliconriver-release/issues/new/choose). For bugs, include your phone model, Android version and the app version (Profile → Settings).

## License

[MIT](LICENSE)
