---
layout: default
title: Ringsmith — Privacy Policy
description: Privacy policy for the Ringsmith Android app by Dash Fusion.
---

# Ringsmith — Privacy Policy

**Effective date:** 2026-09-21
**Last updated:** 2026-09-21

## Summary

Ringsmith cuts a piece out of an audio file you already have and saves it as a
ringtone, an alarm or a notification sound. We do **not** create accounts, do
**not** ask for your email, and do **not** ship any analytics or tracking SDK.

**Ringsmith never asks for permission to your music, your files or your
microphone.** It has no way to browse your storage. When you choose a sound, the
system's own file picker hands this app that one file and nothing else, and the
app forgets it as soon as you leave the screen. The only data that leaves your
device is what Google AdMob needs to serve ads.

If that's all you wanted to know, you're done. The sections below spell it out.

## Who we are

- **App name:** Ringsmith (store listing: *Ringsmith: Ringtone Maker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listringtone`)

## The file you pick

You choose a sound through **Android's own document picker**. That picker is part
of the system, not part of this app: it grants Ringsmith access to the single
file you tapped, and to nothing else on your phone.

From that one file the app reads its name, its size, how long it is and how it is
encoded, and copies the piece you selected. **The grant is never made
persistent**, so it lapses by itself; the app keeps no reference to the file
after you leave the screen, and it never uploads it, shares it or copies it
anywhere except into the clip you asked for.

## The sounds you save

A saved clip is written through Android's MediaStore into the phone's shared
**Ringtones**, **Alarms** or **Notifications** folder — the same places your
phone's own ringtone picker and clock app look.

That means a clip is **yours, not the app's**: your file manager can see it, other
apps can use it, and **uninstalling Ringsmith does not delete it**. Ringsmith
lists your clips back by asking MediaStore for the files it created, so deleting
one elsewhere makes it disappear here too.

## Data the app stores on your device

Only settings, kept in the app's private storage:

- your theme choice and whether to use your wallpaper colours
- which of the three destinations you used last
- the ad state described below

**There is no database in this app.** That is the whole list.

The app opts out of Android cloud backup and device-to-device transfer, so these
settings are not copied into Google's backup service. A new phone starts with
Ringsmith at its defaults — your saved sounds are separate, and live wherever you
saved them.

We have no servers and no cloud storage.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only after you have saved a sound, and never on the first one —
plus an optional rewarded ad you can choose to watch to remove ads for 24 hours.
There are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive the file you picked, the sounds you saved, their names
or your settings. Google's handling of the data above is governed by Google's own
policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed. You
can change your answer at any time from **Settings → Ad privacy options** inside
the app, or through your device's settings (Android: **Settings → Privacy →
Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter
that phones home, no Firebase, and no custom telemetry. There is no HTTP client
anywhere in the app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads. In airplane mode no ads load and every other feature still works.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads.
- **Modify system settings (`WRITE_SETTINGS`)** — a *special access*, not a
  normal permission, and **entirely optional**. It is used for one thing: the
  button that makes a clip your actual default ringtone. Ringsmith never asks for
  it at launch; you are only sent to Android's own screen if you press that
  button, and everything else in the app works whether you grant it or not.

**There is no permission for your music, your files, your storage, your camera,
your microphone, your location or your contacts, and no run-time permission
prompt anywhere in the app.**

## Children

Ringsmith is not directed to children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **Your saved sounds** — delete them in Ringsmith or in your file manager; they
  are ordinary files in your phone's ringtone folders
- **The app's settings** — clear the app's data, or uninstall it
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
