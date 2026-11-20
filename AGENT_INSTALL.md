# Install saTV with an AI agent

Give this file and the [saTV install guide](https://github.com/kcmaker10/satv/blob/main/INSTALL.md) to your agent. Use the instructions below to install the signed APK and help the person turn on the features they want.

## Identify the TV and the APK

1. Ask which TV to use and whether it is free for setup. It should run Android TV or Google TV on Android 9 or newer.
2. Use Google's [Platform-Tools](https://developer.android.com/tools/releases/platform-tools). Have the person enable debugging and approve the connection on the TV. List the devices with `adb devices -l` and confirm the intended target with the person. Use `adb -s TV_SERIAL` for every device command, replacing `TV_SERIAL` with the confirmed device.
3. Download the signed APK for the requested version from [saTV Releases](https://github.com/kcmaker10/satv/releases). Verify its checksum if one is posted and compare its signing certificate with any installed saTV copy before updating. If the release has no APK, tell the person the download is pending.

## Install and try the launcher

Ask for approval to install on the confirmed TV. Use `adb -s TV_SERIAL install -r path-to-satv.apk`. Wait for `Success`, then have the person open saTV from the TV's Apps list. If Android reports a signing mismatch, keep the existing version and help the person back up their setup before considering a replacement.

Let the person try Home, All Apps, and Ambient with the remote. For the remote Home shortcut, guide them to **saTV Settings → General → Home button helper** and have them review the TV's Accessibility prompt. Notification access for Now Playing and local watch history, and Microphone permission for Aura, are optional. The install guide shows how to find these settings.

Keep the TV's system apps, existing launcher, and security protections in place. Avoid modifying TV-wide defaults during a basic install. Ask separately before changing the screensaver, default Home app, or DNS settings, and record the prior setting locally if the person wants one changed. Keep credentials on the person's TV and use saTV's own settings for optional integrations.

## Verify or undo

Have the person launch an app and press **Home** to check the shortcut if they enabled it. When they're done, they can turn off debugging from Developer options.

To return to their original Home, switch off **saTV home button** in the TV's Accessibility settings. Restore any system defaults they chose to change. If they want to remove saTV and its local settings, have them use **TV Settings → Apps → saTV → Uninstall**.
