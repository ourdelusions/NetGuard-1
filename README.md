# NetBlocker Privacy Policy

## Summary

NetBlocker does not collect, share, or sell any personal information, and it has no permission to use the internet. This policy takes effect on November 24, 2026.

NetBlocker is an Android app that blocks the apps you choose from using Wi-Fi or mobile data. Everything it does happens on your phone.

## How blocking works

NetBlocker blocks an app by sending only that app's network traffic into a local tunnel that goes nowhere. It uses Android's VPN service to do this, but it is not a real VPN: no traffic is forwarded, read, logged, or sent to any server. The chosen apps' traffic is simply dropped, and every other app connects as normal.

While blocking is on, Android shows its standard VPN notice and key icon.

## Information NetBlocker handles

NetBlocker collects no personal data: it has no accounts, analytics, advertising, or crash reporting, and no way to send anything off your device.

The app saves a few settings on your phone, in storage only NetBlocker can read:

- Which apps you chose to block on Wi-Fi, and which on mobile data
- Whether blocking is switched on
- Your color scheme and the "Hide fully blocked apps" setting

These settings never leave your device. NetBlocker also opts out of Android's automatic backups, so they are not copied to a cloud backup.

## Permissions

NetBlocker asks for the permissions below, each only for the purpose listed, and none of them gives it internet access.

| Permission | Why NetBlocker needs it |
| --- | --- |
| VPN service | Routes only the apps you chose into a local tunnel that drops their traffic. |
| See all installed apps | Shows your app list so you can pick which to block. The list is displayed on screen only and is never sent anywhere. |
| Network state | Detects whether you are on Wi-Fi or mobile data, so the matching block list applies. |
| Foreground service | Keeps blocking running reliably, with a notification that lets you stop it. |
| Notifications | Shows that blocking is active. Optional: blocking works without it. |
| Run at startup | Turns blocking back on after a restart, if it was on before. |

## Importing and exporting your block lists

Export and import work only with files you choose yourself. Export saves your two block lists, as app package names such as com.example.app, to a location you pick in Android's file picker. Import reads one file you pick and replaces your current block lists.

NetBlocker does not upload these files or read any other file. If you keep or share an exported file, you decide who can see it.

## Third parties

NetBlocker contains no third-party tracking, advertising, or analytics code, and shares nothing with anyone. It is built only on Google's standard Android libraries (AndroidX and Jetpack Compose), which run on your device.

If you download NetBlocker from Google Play or GitHub, that service handles the download under its own privacy policy. NetBlocker does not receive that information.

## Keeping and deleting your data

Uninstalling NetBlocker deletes all of its settings from your phone. You can also turn blocking off at any time from inside the app. Files you exported stay where you saved them until you delete them yourself.

NetBlocker holds no data on any server, so there is nothing for us to delete or send you on request.

## Children

NetBlocker is not directed at children under 13, and it collects no information from anyone, including children.

## Changes to this policy

If this policy changes, the new version will replace this one at the same web address, with an updated effective date at the top of the Summary.

## Contact

Send privacy questions to [add your contact email here].

Developer: Obsidian.
