# saTV

**An ad-free, privacy-focused launcher for Android TV and Google TV.**

Pick up your next episode from a cinematic **Continue Watching** row with full-screen show artwork. Keep your favourite apps in a glass dock with animated folders, and give everyone their own profile and theme. When the TV goes idle, turn it into a parallax photo gallery or put your music on the big screen with **synced lyrics and seven audio-reactive visualizers**.

**Every saTV feature is free. No paid tiers or feature unlocks.**

No analytics or saTV account. Local watch history stays on your TV.

[Screenshots](#screenshots) · [Feature guide](#feature-guide) · [Install](#install) · [Permissions and privacy](#permissions-and-privacy)

![saTV in Dracula with full-screen Andor artwork, Continue Watching, and a glass dock with Nuvio, Netflix, Prime Video, HBO Max and YouTube](screenshots/08-continue-watching.jpg)

*Captured in the Dracula theme on an Android TV demo setup.*

## Screenshots

### Continue Watching

Move across the row to change the full-screen backdrop, title logo, and episode details. **Trakt** can open an episode in Nuvio. **Watched on this TV** works with Trakt switched off and reopens the app that reported playback.

| **Trakt and title artwork** | **Local history with Trakt off** |
| --- | --- |
| ![Arcane artwork and title logo above the Trakt row](screenshots/09-watch-artwork.jpg) | ![Sample local history from Prime Video, HBO Max, and Netflix](screenshots/18-local-continue-watching.jpg) |

#### Episode details and source settings

| **Episode progress** | **Separate source switches** |
| --- | --- |
| ![Severance selected with full-screen artwork and time remaining](screenshots/10-artwork-focus.jpg) | ![Settings with Trakt off and Watched on this TV on](screenshots/19-watch-sources.jpg) |

### Home, apps, and PIN-locked profiles

Press **Down** from the glass dock to open All Apps. Pin your favourites, group apps in animated folders, and hide apps per profile.

**Give everyone their own Home on one TV.** Each profile can connect its own Trakt account, choose its own Continue Watching sources, and keep its own local watch history. Everyone can arrange their apps and folders, pick a wallpaper and theme, and protect their profile with an optional four-digit PIN.

| **All Apps** | **Animated folders** |
| --- | --- |
| ![All Apps with Nuvio in focus beside HBO Max, Netflix, Prime Video, and YouTube](screenshots/04-all-apps.png) | ![A Media folder opening from the dock with Nuvio, YouTube, and YouTube Music](screenshots/06-folders.png) |

| **PIN-locked profile** | **Enter PIN to switch** |
| --- | --- |
| ![The Dracula profile switcher with Movie Night highlighted and marked Locked](screenshots/20-profile-lock.png) | ![The four-digit PIN prompt when opening the locked Movie Night profile](screenshots/21-profile-pin.png) |

#### Profiles and appearance settings

| **Profile switcher** | **Theme, glass, and fonts** |
| --- | --- |
| ![The profile switcher showing two profiles](screenshots/07-profiles.png) | ![Appearance settings for themes, glass, and fonts](screenshots/03-appearance.png) |

### Now Playing and synced lyrics

See the current track in the **Now Playing** chip on Home. Press **OK** for album art and playback controls. In Ambient, follow timed lyrics when available.

| **Now Playing chip** | **Synced lyrics** |
| --- | --- |
| ![The Now Playing chip beside the saTV logo with track artwork and a waveform](screenshots/11-music-chip.jpg) | ![Album art and timed lyrics with the current words highlighted](screenshots/13-synced-lyrics.jpg) |

#### Expanded playback controls

![The Now Playing panel showing album art, playback progress, and play, pause, and skip controls](screenshots/12-music-controls.jpg)

### Aura music visualizer

Choose from seven audio-reactive looks: **Ribbons**, **Silk**, **Retro TV**, **Neon signal**, **Bubbles**, **Birds at dusk**, and **Waterfall**.

| **Retro TV** | **Ribbons** |
| --- | --- |
| ![Aura Retro TV with a neon sunset and grid on a curved screen](screenshots/16-aura-retro.jpg) | ![Aura Ribbons flowing behind the live track display](screenshots/14-aura-ribbons.jpg) |

#### Waterfall visualizer

![Aura Waterfall with a forest waterfall and audio-reactive lights](screenshots/17-aura-waterfall.jpg)

### Wallpapers and photo Ambient

Choose a rotating photo collection from Wikimedia Commons or NASA. Photo Ambient defaults to gentle parallax and has eight built-in photos for offline rotation.

| **Photo wallpapers** | **Photo Ambient** |
| --- | --- |
| ![saTV Home with a Mount Rainier wallpaper and a Media folder in the glass dock](screenshots/01-home.png) | ![The Nā Pali Coast photo in Ambient with the clock and photo credit](screenshots/05-ambient.png) |

### Quick settings and DNS

The gear puts Wi-Fi, Bluetooth, Ambient, and optional system-wide DNS blocking within reach. With NextDNS set up, the stats panel shows blocked queries, top trackers, and a seven-day chart.

| **Quick settings** | **NextDNS dashboard** |
| --- | --- |
| ![Quick settings with Wi-Fi, Bluetooth, ad blocking, and Ambient tiles](screenshots/02-settings.png) | ![Expanded NextDNS panel with blocked-query statistics and a weekly chart](screenshots/15-nextdns.jpg) |

#### Pause blocking for apps that need it

If DNS blocking interferes with an app, hold **OK** on its tile and choose **Pause ad blocking in this app**. With the Home button helper enabled, saTV pauses blocking while that app is on screen and resumes it when you leave.

![An app menu with Pause ad blocking in this app highlighted](screenshots/22-dns-app-exception.png)

## Feature guide

- **Make your next episode the centrepiece.** Browse full-screen backdrops, title logos, progress, and time remaining right from Home. Use Trakt, local playback history from supported apps, or both. Trakt can open an episode in Nuvio. Add your own TMDB key under **Continue watching → Artwork**.
- **Put your favourite apps one press away.** Keep them in a glass dock with app icons or wide banners. Press **Down** to open All Apps and hold **OK** to pin, reorder, group, or hide apps. Restore hidden apps from **Settings → Hidden apps**.
- **Set up a shared TV for everyone.** Select the profile circle to switch. Hold **OK** on a profile to rename it or add a PIN. Set which profile opens at startup in the same menu.
- **Make the idle screen worth looking at.** Rotate photos from Wikimedia Commons or NASA with parallax or slow zoom. Eight built-in photos keep rotating offline. When music is playing, Ambient can show synced lyrics or seven Aura visualizers. Use the Now Playing chip to control supported players from Home.
- **Tune the look and feel.** Pick from ten themes, change the font and dock size, and choose an interface sound or wake-up intro. Liquid glass adds depth on supported Android 13+ TVs. Frosted glass works on older TVs.
- **Pause DNS blocking when an app needs it.** Set an exception from the app's hold-OK menu, or pause blocking on a timer from the gear. The Home button helper makes per-app pauses automatic.
- **Save your setup.** Find manual and scheduled backups under **Settings → General** to save your profiles and launcher settings.

## Install

saTV runs on **Android TV and Google TV with Android 9 or newer**. Install the APK from an [Android phone](INSTALL.md#install-from-an-android-phone) or a [computer](INSTALL.md#1-get-the-two-downloads). The first public APK is in preparation. When it's available, you'll find it under [Releases](https://github.com/kcmaker10/satv/releases).

The [install guide](INSTALL.md) walks through both routes, the optional Home button helper, and the steps to restore your original Home.
If you want an AI agent to help, give it the [agent install guide](AGENT_INSTALL.md).

## Permissions and privacy

The launcher, dock, folders, profiles, and photo Ambient are ready to try after installing. Turn on extra access for the features you use.

| Access | What it's for |
| --- | --- |
| **Accessibility** | The optional Home button helper detects the remote's Home press and the foreground app for features like per-app DNS pausing. |
| **Notification access** | Now Playing and local watch history receive playback metadata from Android media sessions. |
| **Microphone permission** | Android requires this permission for Aura's playback-audio effects. saTV uses the TV's audio output for the visualizer. |
| **Secure settings via ADB** | Optional system-wide DNS controls and automatic Home button helper repair. |
| **Location and nearby devices** | Optional access for showing the Wi-Fi network and connected Bluetooth device names. |

saTV has no launcher ads, analytics, or saTV account. Local playback history stays on the TV and can be cleared from Continue Watching. Trakt, artwork, wallpaper, weather, lyrics, and DNS features connect to their respective services when used. DNS blocking starts off.

## Credits

saTV builds on trbrnt's Veil, licensed under the GNU GPL v3. [Veil on GitHub](https://github.com/trbrnt/Veil) · [GPL v3](https://spdx.org/licenses/GPL-3.0-only.html)

- **Watch artwork and progress.** Artwork and logos use TMDB. Watch progress can be synced from Trakt. saTV is unaffiliated with either service. [TMDB](https://www.themoviedb.org) · [Trakt](https://trakt.tv)
- **Photos, lyrics, and weather.** Wallpaper credits appear on the TV. Timed lyrics come from LRCLIB, and weather from Open-Meteo. [Wikimedia Commons](https://commons.wikimedia.org) · [NASA Image Library](https://images.nasa.gov) · [LRCLIB](https://lrclib.net) · [Open-Meteo](https://open-meteo.com)
- **Theme and type.** The Dracula gallery uses the Dracula palette. saTV uses Manrope for the interface and Monoton for the wordmark. [Dracula](https://draculatheme.com) · [Manrope](https://github.com/sharanda/manrope) · [Monoton](https://fonts.google.com/specimen/Monoton)
