---
layout: default
title: List Weight — Privacy Policy
description: Privacy policy for the List Weight Android app by Dash Fusion.
---

# List Weight — Privacy Policy

**Effective date:** 2026-08-31
**Last updated:** 2026-08-31

## Summary

List Weight is an offline-first weight log: one entry a day, a trend chart
with a goal line, and a rough BMI figure. We do **not** create accounts, do
**not** ask for your email, and do **not** ship any analytics or tracking
SDK. Your weigh-ins, goal and height never leave your device. The only data
that leaves your device is what Google AdMob needs to serve ads.

List Weight is a log, not a medical device: the BMI figure it can show is a
rough, general-purpose number, and the app gives no medical or dietary
advice.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Weight
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listweight`)

## Data the app stores on your device

The following data is created and kept **locally** on your device. It never
leaves the device unless you explicitly export it.

- Your weigh-ins: one weight per day, the date it belongs to, and an optional
  short note
- Your optional goal weight
- Your optional height (used only to compute the BMI figure on your device)
- App preferences: kilograms or pounds, theme and Material You colours, the
  daily reminder time (if you set one), and the ad-free window state

You can export all of it as a JSON backup file at any time via
**Settings → Export JSON backup**; the file is written where you choose and
is entirely under your control. You can delete individual entries inside the
app, replace the whole log by importing a backup file, or uninstall the app —
Android removes the local database with it.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so your weight data is not copied into Google's backup service.

We have no servers and no cloud storage. We cannot see your weight and we
cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads at natural endings — after a weigh-in was saved and its
screen closed, or after the history review was closed — plus an optional
rewarded ad that you can choose to watch to remove ads for 24 hours. There
are no banner ads, and logging itself is never interrupted. Google may
collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your weigh-ins, your goal, your height, your BMI
figure or your preferences. Google's handling of the data above is governed
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
  fetch ads. Disabling Wi-Fi/data simply means no ads load; logging, the
  chart, the goal line, the BMI figure, reminders, export and import still
  work fully offline.
- **Notifications (Android 13+)** — only if you turn on the optional daily
  weigh-in reminder. Reminders are generated entirely on your device, skip
  days you have already logged, and the app only asks for the permission
  when you actually enable the reminder.
- **Run at startup (boot)** — solely so a reminder you have already set
  survives a restart. Nothing else runs in the background.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

Reminders are deliberately *inexact* (battery-friendly); the app never
requests Android's exact-alarm permission. The app does **not** hold access
to your location, contacts, camera, microphone, or files. Choosing where to
save a backup, or which file to import, uses Android's own file picker — the
app only ever sees the single file you pick.

## Children

List Weight is not directed to children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without
  ads. Nothing else in the app is behind an ad: the chart, the goal line,
  backup and every other feature are free
- **Export your data** — Settings → Export JSON backup (writes a JSON file
  you control, carrying every entry, your goal and height)
- **Delete your data** — delete entries inside the app, or uninstall the
  app and Android removes the local database with it
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material
changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
