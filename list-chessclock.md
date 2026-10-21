---
layout: default
title: Twindial — Privacy Policy
description: Privacy policy for the Twindial Android app by Dash Fusion.
---

# Twindial — Privacy Policy

**Effective date:** 2026-10-21
**Last updated:** 2026-10-21

## Summary

Twindial is a chess clock for two players at a real board: it times each side's moves under the time
control you choose, and keeps each finished game with every move's time. We do **not** create accounts,
do **not** ask for your email, and do **not** ship any analytics or tracking SDK. **Your time controls,
your games and their move times stay on your phone. Twindial never sends them anywhere and never reads
your location. They leave the phone only if you share a game's text, or save a backup where you
choose.** A backup file is a plain file and is not encrypted.

**Twindial asks for no permission at runtime** - no location, camera, microphone, contacts, photos,
media, storage or notification permission. The clock, the time controls and the history all work on
the phone, so timing a game never uses the internet. The app contains no code that can reach a server
at all, apart from the advertising SDK described below, which receives nothing from your games.

If that's all you wanted to know, you're done. The sections below spell it out in detail.

## Who we are

- **App name:** Twindial (store listing: *Twindial: Chess Clock & Timer*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listchessclock`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your time controls:** each preset's kind and numbers - its base time, its increment, delay or time
  back, its stages and their moves, its byo-yomi periods or its Canadian block, each side's own numbers
  under time odds - its place in the list, and which of the built-in ones it was. A preset's name is not
  stored: it is worked out from its numbers whenever it is shown.
- **The game at the table:** the game you are playing or have paused - its time control, each side's
  colour and the name you typed for it, if any, who moves first, and every press with its moment on the
  phone's own clock, so the game can be shown exactly as it was if the app is closed in the background.
- **Your finished games:** for each game, its day, its time control, both sides' colours and names, who
  moved first, how it ended - whose time ran out, or that the players ended it - each side's moves and
  time left, and the time of every move. The history keeps your last 2,000 games; the oldest goes when a
  new one comes. **No result is stored**: the app never records who won.
- **App preferences:** the sounds and vibrations, the low-time warning, whether the halves face each
  other, which colour moves first, the names at the table and which half has which colour, the time
  control played last, the theme, and the ad state: when a 24-hour ad-free period ends, and a count that
  decides when the next ad may show.
- **A form you are filling in**, while it is open - a time control, a correction, the names - which
  Android keeps for the app if it is closed in the background, and drops when you close the app.

**Your games are kept here and nowhere else.** They leave the phone only when you act: a game's text
you share goes to the app you choose in Android's share sheet; a backup you save goes where you choose.
Twindial never sends them anywhere itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so Android never
copies your time controls or your games to Google Drive or to another phone. **A new phone starts with
no time controls of your own and no history unless you restore a backup you saved.** The app says so in
Settings.

You can delete a time control or a finished game, use **Settings → Delete the history**, or uninstall
the app — Android removes the local data with it. We have no servers and no cloud storage. We cannot see
your games and we cannot recover them if you lose your device.

## Sharing and saving

- **Share as text** turns one finished game into plain text - its time control, its day, both sides'
  names, how it ended and one line a move - and hands it to Android's own share sheet, to the app you
  choose. No file is written for it.
- **Save a backup** writes your time controls, your settings and every finished game to a file where you
  choose, through Android's own file picker. **A backup is a plain JSON file and is not encrypted**:
  anyone who can open the file can read it, names included. The app says so beside the button. The game
  at the table is not in it.
- **Restore a backup** reads a file you choose, the same way, and asks before it replaces your time
  controls, your settings and your history. The file is read, not kept, and the app keeps no access to it
  afterwards. A game at the table is left as it is.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen interstitial ad — only
after a finished game is left for the home screen, **never during a game**, a pause or a rematch, never
on the way into a game and never as the app opens — plus an optional rewarded ad you can choose to watch
to remove ads for 24 hours, which is not offered while a game is at the table. There are no banner ads.
Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for ads) and other
  device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and performance
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your games**: no name, no game, no time, no keyword and no content URL.
Like any ad in any app, an ad request does name the app it comes from. The approximate location above is
Google's estimate from your internet address; it is never your phone's location, which Twindial cannot
read. Google's handling of the data above is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's certified consent form,
and you choose whether personalised ads are allowed. You can change your answer at any time from
**Settings → Advert privacy options** inside the app. You can also opt out of personalised advertising
via your device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that phones home, no
Firebase, and no custom telemetry. There is no HTTP client anywhere in the app's own code, and the build
fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads. With no connection
  no ads load, and the clock, your time controls, your history, sharing and backups still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used by AdMob as
  described above.
- **Vibrate** — for the tap on a press, the buzz at the low-time warning and at the flag, each a switch
  in Settings. Android never asks you about it.

That is all of them. **Twindial asks for no permission at runtime: Android never stops to ask you about
one.** It has no access to your location — no GPS, no fine or approximate location, no background
location — and none to your camera, microphone, photos, media, files, contacts, messages or calendar,
and it asks for none of them. It sends no notifications and asks for no notification permission: the
clock runs only while the app is on the screen, and a running game pauses when you leave it. The screen
is kept on during a game by the app's own window, which needs no permission.

A few more permissions are merged into the final app package by the libraries the app is built on, so
the list Google Play shows you is slightly longer than the one above. They are the Android Ad Services
permissions, from the Google Mobile Ads SDK; wake-lock and foreground-service, from the Android
scheduling library the ads SDK brings in; and one permission that only lets the app's own parts talk to
each other. None is a permission Android stops to ask you about, and none is used by any code we wrote:
Twindial holds no wake lock and runs no foreground service of its own. A test reads the built app's own
merged manifest on every run and fails the build if that list ever changes, or if any location, camera,
microphone, media, storage or notification permission appears in it.

## Children

Twindial is for adults who time a game between two players at a board - a club's blitz evening, a weekly
game, a Go match - and is intended for adults. It is not directed to children under 13, and we do not
knowingly collect data from children — and, as above, we collect no personal data from anyone.

## A clock, not a referee

Twindial measures time and says whose time is up. It decides no result - a flag, a draw or an arbiter's
call is the players' - predicts nothing, plays no game and records no money: no stake, no prize and no
bet.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android system settings →
  Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads. Nothing in the app is
  behind an ad
- **Delete your data** — delete a time control or a game, use Settings → Delete the history, or uninstall
  the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update this page and
bump the "Last updated" date above. Material changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
