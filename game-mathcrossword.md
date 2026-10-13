---
layout: default
title: Abacist — Privacy Policy
description: Privacy policy for the Abacist Android app by Dash Fusion.
---

# Abacist — Privacy Policy

**Effective date:** 2026-10-14
**Last updated:** 2026-10-14

## Summary

Abacist is an offline math crossword game: every puzzle is made on your phone,
at four sizes, and a daily puzzle is made from the date alone. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any
analytics or tracking SDK. Your puzzles, your placements and your best times
never leave your device. The app contains no code that can reach a server at
all, apart from the advertising SDK described below.

If that's all you wanted to know, you're done. The sections below spell it out
in detail.

## Who we are

- **App name:** Abacist (store listing: *Abacist: Math Crossword Puzzle*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.mathcrossword`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device.

- **Your puzzles in progress:** up to one for each size, and the daily puzzle -
  each kept as the number it is made from, the numbers you have placed, any
  number revealed, your Undo steps, the time it has taken so far and the zoom,
  so that a call, a restart or closing the app never loses a puzzle
- **Your records:** for each size, how many puzzles you have solved, how many of
  those with a number revealed, and your best time; for the daily puzzle, the
  days you solved it, those solved with a number revealed, and its best time
- **App preferences:** theme, wallpaper colours, the size you last chose, and the
  ad state described below

There is no account, no location and no contact information anywhere in the
app. The app explicitly opts out of Android cloud backup and device-to-device
transfer. **That has a cost worth knowing: a new phone starts Abacist at its
defaults, and your puzzles and best times stay behind.** The app says so in
Settings.

To delete everything, clear the app's storage (Android **Settings → Apps →
Abacist → Storage → Clear storage**) or uninstall the app — Android removes the
app's private storage with it.

We have no servers and no cloud storage. We cannot see your puzzles or your
times and we cannot recover them if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — at most one after every third puzzle you solve and leave,
never while you are placing numbers, never for the first puzzle you solve each
time you open the app, never for a puzzle with a number revealed, and never two
within ten minutes — plus an optional rewarded ad you can choose to watch to
reveal one number of the puzzle on screen. There are no banner ads. Google may
collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your puzzles, your placements or your times. Google's
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
  ads. In airplane mode no ads load and every size, the daily puzzle, the timer
  and your best times still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

**Those are the only permissions the app asks for, and none of them is a
run-time prompt.** Abacist has no access to your location, contacts, camera,
microphone, photos, files or notifications, and it asks for none of them;
nothing in it vibrates. A test reads the built app's own merged manifest on
every run and fails the build if that list ever changes.

## Children

Abacist is not directed to children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **A number revealed** — the optional rewarded ad on the puzzle screen. Nothing
  else in the game is behind an ad: every size and the daily puzzle are free,
  and every puzzle can be solved without one
- **Delete your data** — clear the app's storage in Android settings, or
  uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
