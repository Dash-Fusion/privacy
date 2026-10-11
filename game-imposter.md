---
layout: default
title: Charlatan — Privacy Policy
description: Privacy policy for the Charlatan Android app by Dash Fusion.
---

# Charlatan — Privacy Policy

**Effective date:** 2026-10-11
**Last updated:** 2026-10-11

## Summary

Charlatan is an offline party word game played on one phone passed around the
table: everyone gets the same secret word except the imposter, who has to bluff.
We do **not** create accounts, do **not** ask for your email, and do **not**
ship any analytics or tracking SDK. Your players' names, your rounds, your
scores and your own categories never leave your device, unless you export your
own categories to a file yourself. Every word ships inside the app, and the app
contains no code that can reach a server at all, apart from the advertising SDK
described below.

If that's all you wanted to know, you're done. The sections below spell it out
in detail.

## Who we are

- **App name:** Charlatan (store listing: *Charlatan: Imposter Word Game*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.imposter`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device.

- **Your table:** the players' names as you typed them (names are optional, and
  the app calls them *Player 1*, *Player 2* and so on otherwise) and the order
  they sit in
- **Your setup:** the mode, the number of imposters, the imposter's help, the
  clue timer, whether scores are kept, and the categories chosen
- **The evening:** each player's score and the number of rounds played
- **The round in progress:** its words, who the imposters are, who has seen
  their card, the speaking order, the accusation and the timer, so that a call
  or a restart never loses a round. A card that is face up is never saved
- **Which words have been dealt:** for each category, so the table does not
  meet the same word again until that category's words run out, and one random
  number that sets the order they come in
- **Your own categories:** their names, words and hints
- **App preferences:** theme, wallpaper colours, and the ad state described
  below

The built-in words ship inside the app and are only ever read.

There is no account, no location and no contact information anywhere in the
app. The app explicitly opts out of Android cloud backup and device-to-device
transfer. **That has a cost worth knowing: a new phone starts Charlatan at its
defaults, and your players, scores and own categories stay behind - export your
own categories first to take them with you.** The app says so in Settings.

To delete everything, clear the app's storage (Android **Settings → Apps →
Charlatan → Storage → Clear storage**) or uninstall the app — Android removes the
app's private storage with it.

We have no servers and no cloud storage. We cannot see your games and we cannot
recover them if you lose your device.

## Exporting and importing your own categories

If you choose **Export to a file**, the app writes your own categories as a
plain text file to the place you pick in Android's own file picker, for example
your Downloads folder or a cloud drive. That file is yours: the app does not
send it anywhere, and who can see it afterwards depends on where you saved it
and who you share it with. **Import from a file** reads only the one file you
pick in the same picker. Neither needs a storage permission.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — at most one after every fourth round you finish, only once you
have left that round's result, and never on the evening's first round, never
while a card can be turned over, never between two players passing the phone
and never over the clue timer — plus an optional rewarded ad you can choose to
watch in Settings for four hours without full-screen ads. There are no banner
ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your words, your players' names, your scores or your
categories. Google's handling of the data above is governed by Google's own
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
  ads. In airplane mode no ads load and every category, both modes, the timer,
  the scores and your own categories still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

**Those are the only permissions the app asks for, and none of them is a
run-time prompt.** Charlatan has no access to your location, contacts, camera,
microphone, photos, files or notifications, and it asks for none of them. When
the clue timer runs out, the buzz is the screen's own touch feedback and the
tone is made by the app itself; neither needs a permission. A test reads the
built app's own merged manifest on every run and fails the build if that list
ever changes.

## Children

Charlatan is not directed to children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **An evening without full-screen ads** — the optional rewarded ad in Settings
  turns them off for four hours. Nothing in the game is behind an ad: every
  category and both modes are free
- **Delete your data** — clear the app's storage in Android settings, or
  uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
