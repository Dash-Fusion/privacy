---
layout: default
title: List Todo — Privacy Policy
description: Privacy policy for the List Todo Android app by Dash Fusion.
---

# List Todo — Privacy Policy

**Effective date:** 2026-08-26
**Last updated:** 2026-08-26

## Summary

List Todo is an offline-first to-do app built around unlimited nested
sub-tasks. We do **not** create accounts, do **not** ask for your email, and
do **not** ship any analytics or tracking SDK. Your lists, tasks, notes and
due dates never leave your device. The only data that leaves your device is
what Google AdMob needs to serve ads.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Todo
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listtodo`)

## Data the app stores on your device

The following data is created and kept **locally** on your device. It never
leaves the device unless you explicitly export it.

- The lists you create: name, colour and order
- Your tasks: title, optional note, completed state, and the position of each
  task inside the sub-task tree — including sub-tasks nested to any depth
- Optional due dates and reminder settings on any task
- Optional repeat rules on any task (daily, weekly, monthly, yearly, or every
  N units)
- Which branches you have collapsed, so a list reopens as you left it
- App preferences: theme, Material You colours, all-day reminder time, date
  reading in quick add, and the ad-free window state

You can export all of it as a JSON backup file at any time via
**Settings → Export to a file**; the file is written where you choose and is
entirely under your control. You can delete individual tasks or whole lists
inside the app, wipe everything with **Settings → Delete all data**, or
uninstall the app — Android removes the local database with it.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so your task data is not copied into Google's backup service.

We have no servers and no cloud storage. We cannot see your tasks and we
cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads after you complete a top-level task, plus an optional
rewarded ad that you can choose to watch to remove ads for 24 hours. There
are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your lists, your tasks, your notes, your due dates
or your preferences. Google's handling of the data above is governed by
Google's own policies:

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
  fetch ads. Disabling Wi-Fi/data simply means no ads load; every to-do
  feature still works fully offline.
- **Notifications (Android 13+)** — only if you turn on a reminder for a task
  with a due date. Reminders are generated entirely on your device, and the
  app only asks for the permission once you actually have a reminder set.
- **Run at startup (boot)** — solely so reminders you have already set
  survive a restart. Nothing else runs in the background.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

Reminders are deliberately *inexact* (battery-friendly); the app never
requests Android's exact-alarm permission. The app does **not** hold access
to your location, contacts, camera, microphone, or files. Choosing where to
save a backup, or which file to import, uses Android's own file picker — the
app only ever sees the single file you pick.

## Children

List Todo is not directed to children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without
  ads. Nothing else in the app is behind an ad: nesting depth, backup and
  every other feature are free
- **Export your data** — Settings → Export to a file (writes a JSON file you
  control)
- **Delete your data** — delete tasks or lists inside the app, use
  Settings → Delete all data, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material
changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
