<div align="center">
    <h1>SpotifyNext</h1>
    <p>Unlock more possibilities for Spotify</p>

[![Github Release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/cc.meteormc.spotifynext?color=green&logo=github)](https://github.com/Xposed-Modules-Repo/cc.meteormc.spotifynext/releases)
[![Release Downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/cc.meteormc.spotifynext/total?color=orange)](https://github.com/Xposed-Modules-Repo/cc.meteormc.spotifynext/releases)
[![Telegram](https://img.shields.io/badge/Join-Telegram-blue.svg?logo=telegram)](https://t.me/+uECDhJ01E1ExZjFh)

[English](README.md) | [简体中文](README_zh.md)
</div>

---

> [!CAUTION]
> Please read the disclaimer carefully before use and make sure you understand the associated risks.

> [!NOTE]
> This module is theoretically compatible with most Android devices and Spotify client versions.  
> However, Spotify updates its client frequently, so some features may stop working or behave unexpectedly.  
> Compatibility with older client versions will not be guaranteed in future releases.  

## ✨ Features

<details>
  <summary><strong>Better Fullscreen Lyrics</strong></summary>
  <br/>
　Provides a cleaner and more beautiful fullscreen lyrics interface with support for word-by-word lyrics. All features use the player's native interfaces.
</details>

<details>
  <summary><strong>Clickable Lyrics Preview</strong></summary>
  <br/>
　Turns the lyrics preview area on the playback page into a clickable entry point for opening fullscreen lyrics.
</details>

<details>
  <summary><strong>Enable Shuffle Toggle</strong></summary>
  <br/>
　Enables the shuffle toggle so that users can freely control the shuffle state.
</details>

<details>
  <summary><strong>Force Syllable Lyrics</strong></summary>
  <br/>
　Allows syllable-synced lyrics to be shown in the playback page's lyrics preview.
</details>

<details>
  <summary><strong>Remove Ads</strong></summary>
  <br/>
　Removes advertising-related content from the client and attempts to skip advertising tracks automatically whenever possible. Since Spotify's advertising logic depends on both the client version and server-side configuration, this feature does not guarantee that every form of advertising can be blocked.
</details>

<details>
  <summary><strong>Lyrics Translation</strong></summary>
  <br/>
　Automatically translates the current lyrics into a specified language through a translation API.
</details>

<details>
  <summary><strong>More Lyric Sources</strong></summary>
  <br/>
　Adds additional lyrics sources to the client. When no lyrics are available, or the synchronization level of the original lyrics does not meet your requirements, the module matches tracks from configured sources using the song title, album, and artist.

> Custom lyrics sources must be hosted and maintained by the user or provided by a third-party platform. If an endpoint is unavailable, returns an unsupported format, matches the wrong track, or is subject to lyrics copyright restrictions, lyrics may be mismatched or poorly synchronized.
>
> This module writes data back strictly according to the client's expected format. If you use other modules or plugins that do not follow the expected format or do not obtain lyrics through the correct client interface, any resulting malfunction is unrelated to this module.
>
> The following lyrics source is currently supported:
> 1. NetEase Cloud Music
</details>

<details>
  <summary><strong>Remove Premium Button</strong></summary>
  <br/>
　Removes the Premium entry from the bottom navigation bar. This only hides the button in the client interface; it does not change your account type, subscription status, or Premium benefits.
</details>

<details>
  <summary><strong>Remove Restrictions</strong></summary>
  <br/>
　Removes certain player restrictions, such as being unable to skip to the previous track or drag the seekbar.
</details>

## 🚀 Usage

1. Download and install the latest version from [Releases](https://github.com/Xposed-Modules-Repo/cc.meteormc.spotifynext/releases).
2. Enable SpotifyNext in your Xposed framework and make sure Spotify is included in its scope.
3. Restart Spotify.
4. Open **SpotifyNext Settings** from Spotify's sidebar and enable the features you need.

> [!TIP]
> Spotify requires a restart after changing settings.

## 🎯 Disclaimer

- This project is not affiliated with Spotify or any of its related companies, and has not been authorized, endorsed, maintained, or technically supported by Spotify.
- The authors are not responsible for any risks or losses caused by using this project, including application crashes, data loss, playback failures, account restrictions, or any other direct or indirect loss.
- Some features may bypass Spotify's product design, account permissions, or service restrictions. This may violate Spotify's Terms of Service, account rules, or applicable laws and regulations. You are solely responsible for all consequences arising from your use.
- This project does not provide any Premium benefits and does not modify your Spotify account's subscription status, payment status, or server-side permissions. Changes in the client interface do not mean that your account has obtained the corresponding service eligibility.
- Lyrics sources, translation APIs, and other network services are provided by third parties. Using these features may send song titles, artists, albums, device network information, and other data to those services. Their responses may be subject to copyright, regional restrictions, or terms of service; make sure you have the right to access, use, and distribute the relevant content.
- This project has no control over the availability, accuracy, privacy policies, data processing practices, or copyright compliance of any third-party service.
- By continuing to use this project, you acknowledge that you have read, understood, and accepted the risks and allocation of responsibility described above.