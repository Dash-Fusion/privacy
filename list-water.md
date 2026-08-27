---
layout: default
title: List Water — Privacy Policy
description: Privacy policy for the List Water Android app by Dash Fusion.
---

# List Water — Privacy Policy

**Effective date:** 2026-08-27
**Last updated:** 2026-08-27

## Summary

List Water is an offline-first water intake log with a daily goal and
reminders. We do **not** create accounts, do **not** ask for your email, and
do **not** ship any analytics or tracking SDK. What you drink, your goal and
your reminder schedule never leave your device. The only data that leaves
your device is what Google AdMob needs to serve ads.

List Water is a hydration log, not a medical device. It gives no medical
advice and is not connected to Health Connect or any other health platform.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Water
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listwater`)

## Data the app stores on your device

The following data is created and kept **locally** on your device. It never
leaves the device unless you explicitly export it.

- Every drink you log: the amount and the time it was logged
- Your daily goal, and the history of goal changes with the day each one took
  effect (so a new target never rewrites past days or your streak)
- Your cup presets: the amounts on the one-tap buttons
- Your reminder settings: whether reminders are on, your waking window, how
  often to be nudged, and whether reminders pause once the goal is met
- App preferences: millilitres or fluid ounces, theme, Material You colours,
  and the ad-free window state

If you use the optional goal estimator, the body weight and activity level
you type are used **once**, in memory, to produce a suggested number. They
are never written to storage and never transmitted. Only the resulting goal
is saved.

You can export all of it as a JSON backup file at any time via
**Settings → Export a backup**; the file is written where you choose and is
entirely under your control. Export and import are never behind an ad.

To remove data: delete individual entries inside the app, replace everything
with **Settings → Restore a backup**, clear the app's storage from Android's
own **Settings → Apps → List Water → Storage**, or uninstall the app —
Android removes the local database with it.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so what you drink is not copied into Google's backup service.

We have no servers and no cloud storage. We cannot see what you log and we
cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads at a natural stopping point — after the day's goal is
reached, or when you close a history review — plus an optional rewarded ad
that you can choose to watch to remove ads for 24 hours. There are no banner
ads, and an ad never interrupts logging a drink. Google may collect and
process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your drinks, your goal, your streak, your reminder
schedule or your preferences. Google's handling of the data above is governed
by Google's own policies:

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
  fetch ads. Disabling Wi-Fi/data simply means no ads load; logging, goals,
  reminders, history, export and import all still work fully offline.
- **Notifications (Android 13+)** — only if you turn reminders on. Reminders
  are generated entirely on your device, and the app only asks for the
  permission once you actually want to be reminded.
- **Run at startup (boot)** — solely so the reminder schedule you have set
  survives a restart. Nothing else runs in the background.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

Reminders are deliberately *inexact* (battery-friendly); the app never
requests Android's exact-alarm permission. The app does **not** hold access
to your location, contacts, camera, microphone, files, or any health or
fitness data on your device, and it does not read from or write to Health
Connect. Choosing where to save a backup, or which file to import, uses
Android's own file picker — the app only ever sees the single file you pick.

## Children

List Water is not directed to children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without
  ads. Nothing else in the app is behind an ad: reminders, history, streaks,
  export and import are free either way
- **Reminders** — turn them off entirely, or set the waking window and
  interval that suit you, in Settings → Reminders
- **Export your data** — Settings → Export a backup (writes a JSON file you
  control)
- **Delete your data** — delete entries inside the app, clear the app's
  storage from Android settings, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material
changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
