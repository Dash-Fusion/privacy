---
layout: default
title: List Countdown — Privacy Policy
description: Privacy policy for the List Countdown Android app by Dash Fusion.
---

# List Countdown — Privacy Policy

**Effective date:** 2026-08-28
**Last updated:** 2026-08-28

## Summary

List Countdown is an offline-first event countdown app with home-screen
widgets. We do **not** create accounts, do **not** ask for your email, do
**not** read your calendar or contacts, and do **not** ship any analytics or
tracking SDK. The events you enter — names, dates, times, notes — never leave
your device. The only data that leaves your device is what Google AdMob needs
to serve ads.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Countdown
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listcountdown`)

## Data the app stores on your device

The following data is created and kept **locally** on your device. It never
leaves the device unless you explicitly export it.

- The events you type in: name, date, an optional time, whether it repeats
  every year, an emoji and colour you pick, optional notes, and which
  milestone alerts you switched on for it
- A record of which alerts have already been shown, so the same one is never
  sent twice
- App preferences: theme, Material You on/off, the daily alert time, whether
  past events stay on the list, and the ad-free window state
- For each home-screen widget you place, which event that widget is pinned to

Everything is entered by hand. **The app does not read your calendar,** does
not request calendar permission, and has no access to any account.

You can export this data at any time via **Settings → Export a backup**,
which writes a readable JSON file wherever you choose. You can delete
individual events inside the app, or uninstall the app — Android removes the
local database with it.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so your events are not copied into Google's backup service.

We have no servers and no cloud storage. We cannot see your events and we
cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads inside the app, plus an optional rewarded ad that you can
choose to watch to remove ads for 24 hours. **Home-screen widgets never show
an ad of any kind.** Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your events, dates, notes or preferences. Google's
handling of the data above is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed.
You can change your answer at any time from **Settings → Ad privacy options**
inside the app. You can also opt out of personalised advertising via your
device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash
reporter that phones home, no Firebase, and no custom telemetry. We don't log
app usage anywhere we can read it.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can
  fetch ads. Disabling Wi-Fi/data simply means no ads load; every countdown
  feature, including the widgets, still works fully offline.
- **Notifications (Android 13+)** — only if you keep milestone alerts on.
  Alerts are generated entirely on your device: a heads-up as one of your own
  events gets closer, on the schedule you choose.
- **Run at startup (boot)** — solely to re-arm the once-a-day alert check and
  the widget's daily refresh after the phone restarts. Nothing else runs in
  the background.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

The alert check is deliberately *inexact* (battery-friendly); the app never
requests Android's exact-alarm permission. The app does **not** hold access to
your calendar, location, contacts, camera, microphone, files, SMS or any
account.

## Children

List Countdown is not directed to children under 13 and is not designed for
use under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads
- **Export your data** — Settings → Export a backup, which writes a JSON file
  you control
- **Delete your data** — delete events inside the app, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
