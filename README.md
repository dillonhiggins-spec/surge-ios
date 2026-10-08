# Surge for iPhone

The Surge Command Center web app inside a real iOS app shell (Capacitor 8).
Built for free on GitHub Actions. Installed on one iPhone with a free Apple ID.

## Install on the iPhone (one time)

1. On the PC: install iTunes and iCloud from apple.com (not the Microsoft Store versions), then Sideloadly from https://sideloadly.io
2. On the iPhone: Settings > Privacy & Security > Developer Mode > on (it reboots).
3. Download `Surge-unsigned.ipa` from the latest run under Actions > Build iOS.
4. Plug the iPhone in. In Sideloadly: pick the .ipa, sign in with an Apple ID, Start.
5. On the iPhone: Settings > General > VPN & Device Management > trust the profile. Open Surge.
6. In Sideloadly turn on the daemon and iTunes Wi-Fi sync so it re-signs the app every week by itself.

Tailscale must be on for the app to reach the server, same as the web app today.

## Limits of the free Apple ID

- The app is signed for 7 days at a time. Sideloadly re-signs it automatically while the PC is on and on the same Wi-Fi.
- No push notifications. Alerts keep coming as texts.
- Up to 3 sideloaded apps per Apple ID.
