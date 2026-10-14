---
layout: default
title: Spellwick — Privacy Policy
description: Privacy policy for the Spellwick Android app by Dash Fusion.
---

# Spellwick — Privacy Policy

**Effective date:** 2026-10-14
**Last updated:** 2026-10-14

## Summary

Spellwick is an offline hangman word game: guess a word letter by letter before
the candle burns out, from word lists written for the app, with a daily word made
from the date alone and a mode for two players on one phone. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any
analytics or tracking SDK. Your rounds, your guesses and your records never
leave your device. The app contains no code that can reach a server at all,
apart from the advertising SDK described below.

If that's all you wanted to know, you're done. The sections below spell it out
in detail.

## Who we are

- **App name:** Spellwick (store listing: *Spellwick: Hangman Word Game*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.hangman`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device.

- **Your rounds in progress:** up to three - a dealt round, today's word and a
  round of two players - each with its guesses and any letter revealed, so that a
  call, a restart or closing the app never loses a round
- **Your records:** for each difficulty, the rounds you have played, won, and won
  with a letter revealed, and your current and best run; for the daily word, the
  days you solved it, solved it with a letter revealed, or lost it
- **Where each category's words have been dealt**, and **this install's dealing
  seed** - a random number made on your phone to shuffle the words, so that no
  word comes back before its category is used up. It identifies nobody and never
  leaves the phone
- **App preferences:** theme, wallpaper colours, the category and difficulty you
  last chose, and the ad state described below

The word lists themselves are shipped inside the app and only ever read.

There is no account, no location and no contact information anywhere in the
app. The app explicitly opts out of Android cloud backup and device-to-device
transfer. **That has a cost worth knowing: a new phone starts Spellwick at its
defaults, and your records stay behind.** The app says so in Settings.

To delete everything, clear the app's storage (Android **Settings → Apps →
Spellwick → Storage → Clear storage**) or uninstall the app — Android removes the
app's private storage with it.

We have no servers and no cloud storage. We cannot see your rounds or your
records and we cannot recover them if you lose your device.

## Two players: the word you write

In the two-player mode, one person writes a word and hands the phone to the
other, who guesses it. That word is treated as a secret:

- It is typed on the app's own letter board, never in a text field, so no
  keyboard app sees it, learns it or suggests it.
- While it is on screen, the app blocks screenshots and blanks its picture in the
  recent-apps switcher.
- It is kept only in the app's memory until the phone is handed over, then in the
  app's private storage only until that round ends, and then it is removed in the
  same write that ends the round.
- It is never logged, never recorded in your records, and never sent anywhere.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — at most one after every third round you finish and leave,
never while you are guessing, never for the first round you finish each time you
open the app, never for a round with a letter revealed, never for a round of two
players, and never two within ten minutes — plus an optional rewarded ad you can
choose to watch to reveal one letter of the word on screen. There are no banner
ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your words, your guesses or your records. Google's
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
  ads. In airplane mode no ads load, and every category, every difficulty, the
  daily word, the two-player mode and your records still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

**Those are the only permissions the app asks for, and none of them is a
run-time prompt.** Spellwick has no access to your location, contacts, camera,
microphone, photos, files or notifications, and it asks for none of them;
nothing in it vibrates. A test reads the built app's own merged manifest on
every run and fails the build if that list ever changes.

## Children

Spellwick is not directed to children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **A letter revealed** — the optional rewarded ad on the round screen. Nothing
  else in the game is behind an ad: every category, every difficulty, the daily
  word and the two-player mode are free, and every round can be played without
  one
- **Delete your data** — clear the app's storage in Android settings, or
  uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
