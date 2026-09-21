---
layout: default
title: Pages Left — Privacy Policy
description: Privacy policy for the Pages Left Android app by Dash Fusion.
---

# Pages Left — Privacy Policy

**Effective date:** 2026-09-21
**Last updated:** 2026-09-21

## Summary

Pages Left is an offline-first reading log. We do **not** create accounts, do
**not** ask for your email, and do **not** ship any analytics or tracking SDK.
Your books, your sittings, your ratings and your notes never leave your device.
The app never looks a book up anywhere — you type each one in yourself — and it
contains no code that can reach a server at all, apart from the advertising SDK
described below.

If that's all you wanted to know, you're done. The sections below spell it out
in detail.

## Who we are

- **App name:** Pages Left (store listing: *Pages Left: Book Tracker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listbook`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device.

- **Your books:** title, author, page count, the tile colour you picked, your
  rating, your note, and the day you added it
- **Your readings:** which book, the day you started it, and — once it is over —
  the day it ended and whether you finished it or set it aside
- **Your sittings:** which reading, the day, the page you started on, the page
  you reached, and the minutes if you entered them
- **App preferences:** theme, wallpaper colours, how the library is ordered,
  your yearly goal, and the ad state described below

Dates are stored as calendar days. **No time of day is recorded anywhere in this
app** — a sitting knows the day it happened, not the hour.

Nothing is derived and stored: every count, every page total and every figure on
the goal screen is worked out from the sittings above, at the moment you look at
it.

There is no export and no backup file, because there is nothing to send anywhere
— and the app explicitly opts out of Android cloud backup and device-to-device
transfer. **That has a cost worth knowing: a new phone starts with an empty
library.** The app says so in Settings, in those words.

You can delete a single sitting or a single book inside the app, delete
everything with **Settings → Delete every book**, or uninstall the app — Android
removes the local database with it.

We have no servers and no cloud storage. We cannot see your library and we
cannot recover it if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only when you mark a book **finished** and then leave that
book's screen, never over the moment you finish reading — plus an optional
rewarded ad you can choose to watch to remove ads for 24 hours. There are no
banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your books, your sittings, your ratings, your notes
or your goal. Google's handling of the data above is governed by Google's own
policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed.
You can change your answer at any time from **Settings → Ad privacy options**
inside the app. You can also opt out of personalised advertising via your
device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter
that phones home, no Firebase, and no custom telemetry. There is no HTTP client
anywhere in the app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads. In airplane mode no ads load and every reading-log feature still works.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

**Those are the only permissions the app asks for, and none of them is a
run-time prompt.** Pages Left has no access to your location, contacts, camera,
microphone, photos, files or notifications, and it asks for none of them. A test
reads the built app's own merged manifest on every run and fails the build if
that list ever changes.

## Children

Pages Left is not directed to children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad: every book, every sitting and the yearly
  goal are free
- **Delete your data** — delete a sitting or a book inside the app, use
  Settings → Delete every book, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
