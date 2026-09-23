---
layout: default
title: Fairgrid — Privacy Policy
description: Privacy policy for the Fairgrid Android app by Dash Fusion.
---

# Fairgrid — Privacy Policy

**Effective date:** 2026-09-23
**Last updated:** 2026-09-23

## Summary

Fairgrid is an offline sudoku game. We do **not** create accounts, do **not**
ask for your email, and do **not** ship any analytics or tracking SDK. Your
games, your notes on the grid and your statistics never leave your device.
Every puzzle ships inside the app, the daily puzzle is chosen from your phone's
own date, and the app contains no code that can reach a server at all, apart
from the advertising SDK described below.

If that's all you wanted to know, you're done. The sections below spell it out
in detail.

## Who we are

- **App name:** Fairgrid (store listing: *Fairgrid: Sudoku Offline*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.sudoku`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device.

- **Your games in progress:** up to one per difficulty and one daily puzzle —
  the digits you have placed, your pencil notes, your undo history and the time
  on the clock
- **Your statistics:** puzzles solved, best and average times for each
  difficulty, and your daily streak, kept as running totals
- **Your hints:** how many you have, and the day they were last topped up
- **Which puzzles you have been dealt:** how far this install has moved through
  each difficulty's puzzles, and one random number that sets the order they
  come in
- **App preferences:** theme, wallpaper colours, whether mistakes are marked,
  and the ad state described below

The puzzles themselves ship inside the app and are only ever read.

There is no account, no name, no location and no contact information anywhere
in the app. The app explicitly opts out of Android cloud backup and
device-to-device transfer. **That has a cost worth knowing: a new phone starts
Fairgrid fresh, and your games and statistics stay behind.** The app says so in
Settings.

To delete everything, clear the app's storage (Android **Settings → Apps →
Fairgrid → Storage → Clear storage**) or uninstall the app — Android removes the
app's private storage with it.

We have no servers and no cloud storage. We cannot see your games and we cannot
recover them if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — at most after every third puzzle you **solve**, only once you
have left the solved puzzle, and never over a grid you are playing — plus an
optional rewarded ad you can choose to watch for three more hints when you have
none left. There are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your games, your notes, your times or your
statistics. Google's handling of the data above is governed by Google's own
policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed.
You can change your answer at any time from **Settings → Advert privacy options**
inside the app. You can also opt out of personalised advertising via your
device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter
that phones home, no Firebase, and no custom telemetry. There is no HTTP client
anywhere in the app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads. In airplane mode no ads load and every puzzle, every difficulty, the
  daily puzzle, notes, undo and mistake marking still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

**Those are the only permissions the app asks for, and none of them is a
run-time prompt.** Fairgrid has no access to your location, contacts, camera,
microphone, photos, files or notifications, and it asks for none of them. A test
reads the built app's own merged manifest on every run and fails the build if
that list ever changes.

## Children

Fairgrid is not directed to children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Hints** — three free hints come back every day with no ad and no
  connection; the optional rewarded ad adds three more. No puzzle needs a hint
  to be finished, and nothing in the app is behind an ad
- **Delete your data** — clear the app's storage in Android settings, or
  uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
