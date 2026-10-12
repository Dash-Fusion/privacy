---
layout: default
title: Hedgerow — Privacy Policy
description: Privacy policy for the Hedgerow Android app by Dash Fusion.
---

# Hedgerow — Privacy Policy

**Effective date:** 2026-10-12
**Last updated:** 2026-10-12

## Summary

Hedgerow is an offline maze game: every maze is made on your phone, in three
shapes and four sizes, and a daily maze is made from the date alone. We do
**not** create accounts, do **not** ask for your email, and do **not** ship any
analytics or tracking SDK. Your mazes, your paths and your best times never
leave your device. The app contains no code that can reach a server at all,
apart from the advertising SDK described below.

If that's all you wanted to know, you're done. The sections below spell it out
in detail.

## Who we are

- **App name:** Hedgerow (store listing: *Hedgerow: Maze Puzzles Offline*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.maze`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device.

- **Your mazes in progress:** up to one for each shape and size, and the daily
  maze - each kept as the number it is made from, the path you have drawn, the
  time it has taken so far, the zoom, and whether its solution was shown, so
  that a call, a restart or closing the app never loses a maze
- **Your records:** for each shape and size, how many mazes you have solved, how
  many of those with the solution shown, and your best time; for the daily
  maze, the days you solved it and its best time
- **App preferences:** theme, wallpaper colours, Draw or Buttons, the shape and
  size you last chose, and the ad state described below

There is no account, no location and no contact information anywhere in the
app. The app explicitly opts out of Android cloud backup and device-to-device
transfer. **That has a cost worth knowing: a new phone starts Hedgerow at its
defaults, and your mazes and best times stay behind.** The app says so in
Settings.

To delete everything, clear the app's storage (Android **Settings → Apps →
Hedgerow → Storage → Clear storage**) or uninstall the app — Android removes the
app's private storage with it.

We have no servers and no cloud storage. We cannot see your mazes or your times
and we cannot recover them if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — at most one after every third maze you solve and leave, never
while you are drawing, never for the first maze you solve each time you open
the app, never for a maze whose solution you watched a video for, and never two
within ten minutes — plus an optional rewarded ad you can choose to watch to
see the solution of the maze on screen. There are no banner ads. Google may
collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your mazes, your paths or your times. Google's
handling of the data above is governed by Google's own policies:

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
  ads. In airplane mode no ads load and every shape, every size, the daily maze,
  the timer and your best times still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

**Those are the only permissions the app asks for, and none of them is a
run-time prompt.** Hedgerow has no access to your location, contacts, camera,
microphone, photos, files or notifications, and it asks for none of them. When
your path meets a wall, the tick is the screen's own touch feedback, which
needs no permission. A test reads the built app's own merged manifest on every
run and fails the build if that list ever changes.

## Children

Hedgerow is not directed to children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **The solution of a maze** — the optional rewarded ad on the maze screen.
  Nothing else in the game is behind an ad: every shape, every size and the
  daily maze are free
- **Delete your data** — clear the app's storage in Android settings, or
  uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
