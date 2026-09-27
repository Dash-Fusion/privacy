---
layout: default
title: Roadglass — Privacy Policy
description: Privacy policy for the Roadglass Android app by Dash Fusion.
---

# Roadglass — Privacy Policy

**Effective date:** 2026-09-28
**Last updated:** 2026-09-28

## Summary

Roadglass is a GPS speedometer. We do **not** create accounts, do **not** ask for
your email, and do **not** ship any analytics or tracking SDK. **Roadglass uses
your precise location only on your phone, only while its speedometer, HUD mode or
a trip you just finished is on screen, to work out speed and distance. It never
stores, shows on a map, exports or sends your location.** A finished trip is kept
as numbers — time, distance, speed — and never as a place.

The app contains no code that can reach a server at all, apart from the
advertising SDK described below, which receives nothing from your trips.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Roadglass (store listing: *Roadglass: GPS Speedometer*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listspeed`)

## Your location

Roadglass asks for your **precise location** when you tap *Start the speedometer*,
not when the app opens. Android also asks for approximate location in the same
question; approximate location alone cannot measure speed, and the app says so.

- **When it is used:** only while the speedometer, HUD mode or the *Trip finished*
  screen is on screen. The moment none of them is showing, Roadglass lets go of the
  GPS; a running trip is paused and later says how long it was not measured.
  Roadglass has no background location permission and runs no background service.
- **What it is used for:** your speed, the distance of a trip, and — on *Trip
  finished* — whether the phone is standing still.
- **What is kept:** nothing positional. The last few seconds of GPS readings are held
  in memory to calculate speed, replaced as new ones arrive, and dropped the moment
  measuring stops. **No position is ever written to the phone's storage, to a file,
  or to a log, and none is sent anywhere.**

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your trips:** for each finished trip, when it started and finished, its distance,
  its moving time and measured time, its top speed, and how often measuring paused
  because Roadglass was not on screen. **No place, no route, no position.**
- **The running trip:** the same numbers for a trip in progress, so it survives
  Android closing the app.
- **App preferences:** the speed unit, HUD mirroring, the speed alert's switch, limit
  and vibration, the theme, whether the location question has been asked, and the ad
  state described below.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so
Android never copies your trips to Google Drive or to another phone. **A new phone
starts with no trips.**

You can delete a trip, use **Settings → Delete every trip**, or uninstall the app —
Android removes the local data with it. We have no servers and no cloud storage. We
cannot see your trips and we cannot recover them if you lose your device.

## CSV files

**Save as a CSV file** writes your trips — times, distances and speeds, never a place
— to a file where you choose, through Android's own file picker. The app keeps no
access to it afterwards. The file is not encrypted; keep it wherever you like.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only as you close the *Trip finished* screen with the phone
standing still, **never while you are moving, and never over the speedometer or HUD
mode** — plus an optional rewarded ad you can choose to watch to remove ads for 24
hours. There are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for
  ads) and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your trips**: no speed, no distance and no position.
Like any ad in any app, an ad request does name the app it comes from. Google's
handling of the data above is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed. You can
change your answer at any time from **Settings → Advert privacy options** inside the
app. You can also opt out of personalised advertising via your device's system
settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that
phones home, no Firebase, and no custom telemetry. There is no HTTP client anywhere in
the app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Precise and approximate location** — asked when you start the speedometer, used
  only while a measuring screen is showing, as described above. No background
  location.
- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads.
  With no connection no ads load and the speedometer still works: GPS needs no
  internet.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used
  by AdMob as described above.
- **Vibrate** — only for the optional speed alert's single buzz, off until you turn it
  on.

Roadglass has no access to your contacts, messages, calendar, camera, microphone,
photos, files or health data, and it asks for none of them. A test reads the built
app's own merged manifest on every run and fails the build if that list ever changes.

## Children

Roadglass is a tool for drivers and is meant for adults. It is not directed to
children, and we do not knowingly collect data from children — and, as above, we
collect no personal data from anyone.

## Not a certified instrument

Roadglass reads speed from GPS. GPS speed can lag, drop out in tunnels and under
bridges, and be wrong after a poor fix. Do not rely on it for anything legal or
safety-critical, and always follow your vehicle's own speedometer. Set the app up
before you drive, and never handle your phone while driving.

## Your choices

- **Location** — Android's settings for Roadglass, at any time
- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android
  system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **Delete your data** — delete a trip, use Settings → Delete every trip, or uninstall
  the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will
update this page and bump the "Last updated" date above. Material changes will be
flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
