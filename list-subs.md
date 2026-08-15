---
layout: default
title: List Subs — Privacy Policy
description: Privacy policy for the List Subs Android app by Dash Fusion.
---

# List Subs — Privacy Policy

**Effective date:** 2026-08-15
**Last updated:** 2026-08-15

## Summary

List Subs is an offline-first subscription tracker. We do **not** create
accounts, do **not** ask for your email, do **not** connect to any bank,
card issuer or app store account, and do **not** ship any analytics or
tracking SDK. The subscriptions you enter — names, prices, renewal dates,
categories, notes — never leave your device. The only data that leaves your
device is what Google AdMob needs to serve ads.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Subs
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listsubscriptions`)

## Data the app stores on your device

The following data is created and kept **locally** on your device. It never
leaves the device unless you explicitly export it.

- The subscriptions you type in: name, price and currency, billing cycle,
  first/next billing date, category, color and icon, an optional
  payment-method label (free text you choose, e.g. "Visa •••• 1234"),
  optional notes, an optional free-trial end date, and the status you set
  (active, paused, or cancelled with the cancellation date)
- Values the app computes from that data — next renewals, monthly and yearly
  totals, category breakdown, lifetime spend, and savings from cancelling
- App preferences: theme, default currency, reminder settings, and the
  ad-free window state

Everything is entered by hand. The app has no access to your bank, cards,
Google Play purchases or any other account, and it never reads them.

You can export this data at any time via **Settings → Export backup (JSON)**
or **Export spreadsheet (CSV)**; the file is written where you choose and is
entirely under your control. You can delete individual subscriptions inside
the app, or uninstall the app — Android removes the local database with it.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so your subscription data is not copied into Google's backup
service.

We have no servers and no cloud storage. We cannot see your subscriptions
and we cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads, plus an optional rewarded ad that you can choose to watch
to remove ads for 24 hours. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your subscriptions, prices, notes, or
preferences. Google's handling of the data above is governed by Google's
own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows
Google's certified consent form, and you choose whether personalised ads
are allowed. You can change your answer at any time from
**Settings → Ad privacy options** inside the app. You can also opt out of
personalized advertising via your device's system settings
(Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash
reporter that phones home, no Firebase, and no custom telemetry. We don't
log app usage anywhere we can read it.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can
  fetch ads. Disabling Wi-Fi/data simply means no ads load; every
  subscription feature still works fully offline.
- **Notifications (Android 13+)** — only if you keep renewal reminders on.
  Reminders are generated entirely on your device: one heads-up before a
  renewal or a free-trial end, on the schedule you choose.
- **Run at startup (boot)** — solely to re-arm the once-a-day reminder check
  after the phone restarts. Nothing else runs in the background.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that
  serve ads; used by AdMob as described above.

The reminder check is deliberately *inexact* (battery-friendly); the app
never requests Android's exact-alarm permission. The app does **not** hold
access to your location, contacts, camera, microphone, files, SMS or any
financial account.

## Children

List Subs is not directed to children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without
  ads
- **Export your data** — Settings → Export backup (JSON) or Export
  spreadsheet (CSV); both write a file you control
- **Delete your data** — delete subscriptions inside the app, or uninstall
  the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate,
we will update this page and bump the "Last updated" date above. Material
changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
