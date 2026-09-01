---
layout: default
title: List Fast — Privacy Policy
description: Privacy policy for the List Fast Android app by Dash Fusion.
---

# List Fast — Privacy Policy

**Effective date:** 2026-09-01
**Last updated:** 2026-09-01

## Summary

List Fast is an offline-first intermittent-fasting timer and log: pick a
protocol, start a fast, and watch a progress ring with a plain-language stage
timeline. We do **not** create accounts, do **not** ask for your email, and do
**not** ship any analytics or tracking SDK. Your fasts, your schedule and your
notes never leave your device. The only data that leaves your device is what
Google AdMob needs to serve ads.

List Fast is a timer and a log, not a medical device, and it gives no medical
or nutrition advice. The stage timeline is general background information, not
a statement about what your own body is doing. Fasting is not right for
everyone — the in-app **About fasting & your health** note explains this, and
you should check with a doctor if you are pregnant, have a history of an
eating disorder, have diabetes, or take regular medication.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Fast
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listfast`)

## Data the app stores on your device

The following data is created and kept **locally** on your device. It never
leaves the device unless you explicitly export it.

- Your fasts: the protocol you chose (16:8, 18:6, 20:4, OMAD or a custom
  length), the target length, the start time, the end time once the fast is
  finished, and an optional short note
- App preferences: the last protocol you used, theme and Material You
  colours, which reminders you switched on, and the ad-free window state

You can export all of it as a JSON backup file at any time via
**Settings → Your data → Export backup**; the file is written where you
choose and is entirely under your control. You can delete an individual fast
from its edit screen with **Delete this fast**, replace the whole log by
importing a backup file (**Settings → Your data → Import backup**, which
replaces every fast currently on the device), or uninstall the app — Android
removes the local database with it.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so your fasting log is not copied into Google's backup service.

We have no servers and no cloud storage. We cannot see your fasts and we
cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads at natural endings — after a fast was stopped and its
confirmation was closed, or after the history review was closed — plus an
optional rewarded ad that you can choose to watch to remove ads for 24 hours.
There are no banner ads, and **a running fast is never interrupted**. Google
may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your fasts, your fasting schedule, your notes or
your preferences. Google's handling of the data above is governed by Google's
own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed.
You can change your answer at any time from **Settings → Ads → Ad privacy
options** inside the app. You can also opt out of personalised advertising via
your device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash
reporter that phones home, no Firebase, and no custom telemetry. We don't log
app usage anywhere we can read it.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can
  fetch ads. Disabling Wi-Fi/data simply means no ads load; the timer, the
  stage timeline, history, streaks, reminders, export and import still work
  fully offline.
- **Notifications (Android 13+)** — only if you turn on the optional
  **Fast complete nudge** or **Eating window closing** reminders. Reminders
  are generated entirely on your device, and the app only asks for the
  permission when you actually enable one.
- **Run at startup (boot)** — solely so a reminder you have already set
  survives a restart, an app update, or a clock or timezone change. Nothing
  else runs in the background.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

Reminders are deliberately *inexact* (battery-friendly); the app never
requests Android's exact-alarm permission. The app does **not** hold access
to your location, contacts, camera, microphone, health sensors, or files, and
it does not read from or write to Health Connect. Choosing where to save a
backup, or which file to import, uses Android's own file picker — the app
only ever sees the single file you pick.

## Children

List Fast is not directed to children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ads → Ad privacy options (EEA/UK/Switzerland),
  or Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without
  ads. Nothing else in the app is behind an ad: the timer, the stage
  timeline, history, streaks, export and import are all free
- **Export your data** — Settings → Your data → Export backup (writes a JSON
  file you control, carrying every fast)
- **Delete your data** — delete an individual fast with **Delete this fast**
  on its edit screen, replace the entire log by importing a backup file, or
  uninstall the app and Android removes the local database with it. You can
  also clear everything from Android's own **Settings → Apps → List Fast →
  Storage → Clear data**
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material
changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
