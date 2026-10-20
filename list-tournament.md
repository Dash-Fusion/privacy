---
layout: default
title: Drawsheet — Privacy Policy
description: Privacy policy for the Drawsheet Android app by Dash Fusion.
---

# Drawsheet — Privacy Policy

**Effective date:** 2026-10-20
**Last updated:** 2026-10-20

## Summary

Drawsheet is a tournament bracket maker that you fill in yourself: a tournament's name, day and
format, its players or teams by the names you type, the draw, and each result as it happens. We do
**not** create accounts, do **not** ask for your email, and do **not** ship any analytics or tracking
SDK. **Your tournaments, their players and their results stay on your phone. Drawsheet never sends
them anywhere and never reads your location. They leave the phone only if you share a picture, a
text or a file, or save one where you choose.** A backup file and a CSV file are plain files and are
not encrypted.

**Drawsheet asks for no permission at runtime** - no location, camera, contacts, photos, media or
storage permission. Who plays next, the bracket, the table and the champion are all worked out on
the phone, so running a tournament never uses the internet. The app contains no code that can
reach a server at all, apart from the advertising SDK described below, which receives nothing from
your tournaments.

If that's all you wanted to know, you're done. The sections below spell it out in detail.

## Who we are

- **App name:** Drawsheet (store listing: *Drawsheet: Tournament Bracket*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listtournament`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your tournaments:** each tournament's name, day, format and its settings (a match for third
  place, a second final, meeting twice, draws allowed, the points for a win, a draw and a loss),
  whether it is played by players or teams, and the day you set it up.
- **The entrants:** the name of each player or team you type, and their order - the seeding, or the
  random draw you asked for.
- **The results:** for each match played, who won or that it was a draw, the final scores if you gave
  them, how a level match was decided if you said, and the two entrants it was between. **No table,
  point total or champion is stored**: each is worked out from the results every time it is shown.
- **App preferences:** the theme, wallpaper colours, and the ad state: when a 24-hour ad-free period
  ends, and a count that decides when the next ad may show.
- **A form you are filling in**, while it is open, which Android keeps for the app if it is closed in
  the background, and drops when you close the app.
- **A picture or a CSV file you have just shared**, in the app's own cache, for an hour at most.

**Your tournaments are kept here and nowhere else.** They leave the phone only when you act: a picture,
a text or a CSV file you share goes to the app you choose in Android's share sheet; a picture, a CSV
file or a backup you save goes where you choose. Drawsheet never sends them anywhere itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so Android never
copies your tournaments to Google Drive or to another phone. **A new phone starts with no tournaments
unless you restore a backup you saved.** The app says so in Settings.

You can remove a result, delete a tournament with its entrants and results, use **Settings → Delete
everything**, or uninstall the app — Android removes the local data with it. We have no servers and no
cloud storage. We cannot see your tournaments and we cannot recover them if you lose your device.

## Sharing and saving

- **Sharing** a tournament - the bracket or the table as a picture, the results as text, or the matches
  as a CSV file - opens Android's own share sheet. A picture or a CSV file is written into the app's own
  cache first and handed to the app you choose with permission to read that one file; nothing else in
  the app can be reached through it.
- **Saving a picture** puts it into your phone's Pictures, in a Drawsheet folder, on Android 10 and
  later, or where you choose through Android's own file picker on earlier versions. **No storage or
  media permission is asked for, on any version.**
- **Save the matches as a CSV file** and **Every match, as a CSV file** write a CSV file for a spreadsheet,
  where you choose, through the file picker. **A CSV file is plain text and is not encrypted**: anyone
  who can open the file can read it. The app says so in Settings.
- **Save a backup** writes every tournament, its entrants and its results to a file where you choose,
  the same way. **A backup is a plain JSON file and is not encrypted**: anyone who can open the file
  can read it. The app says so beside the button.
- **Restore a backup** reads a file you choose, the same way, and asks before it replaces your
  tournaments. The file is read, not kept, and the app keeps no access to it afterwards.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen interstitial ad —
only after you set up a new tournament or a tournament finishes, once its form has closed, **never
while you enter results** and never as the app opens — plus an optional rewarded ad you can choose to
watch to remove ads for 24 hours. There are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for ads) and other
  device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and performance
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your tournaments**: no tournament, no name, no result, no keyword and no
content URL. Like any ad in any app, an ad request does name the app it comes from. The approximate
location above is Google's estimate from your internet address; it is never your phone's location,
which Drawsheet cannot read. Google's handling of the data above is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's certified consent
form, and you choose whether personalised ads are allowed. You can change your answer at any time
from **Settings → Advert privacy options** inside the app. You can also opt out of personalised
advertising via your device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that phones home, no
Firebase, and no custom telemetry. There is no HTTP client anywhere in the app's own code, and the
build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads. With no
  connection no ads load, and your tournaments, the bracket, the table, sharing, backups and CSV files
  still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used by AdMob as
  described above.

That is all of them. **Drawsheet asks for no permission at runtime: Android never stops to ask you
about one.** It has no access to your location — no GPS, no fine or approximate location, no
background location — and none to your camera, photos, media, files, contacts, messages, calendar
or microphone, and it asks for none of them. It sends no notifications and asks for no
notification permission: there is no reminder and no match timer.

A few more permissions are merged into the final app package by the libraries the app is built on,
so the list Google Play shows you is slightly longer than the one above. They are the Android Ad
Services permissions, from the Google Mobile Ads SDK; wake-lock and foreground-service, from the
Android scheduling library the ads SDK brings in; and one permission that only lets the app's own
parts talk to each other. None is a permission Android stops to ask you about, and none is used by
any code we wrote: Drawsheet holds no wake lock and runs no foreground service of its own. A test
reads the built app's own merged manifest on every run and fails the build if that list ever changes,
or if any location, camera, media, storage or notification permission appears in it.

## Children

Drawsheet is for adults who run tournaments for others - a club night, an office competition, a league
among friends - and is intended for adults. It is not directed to children under 13, and we do not
knowingly collect data from children — and, as above, we collect no personal data from anyone.

## A record, not a prediction

Drawsheet writes down what you enter. It decides no winner from a score - who won is your word - keeps
no live score, predicts no winner, and records no money: no entry fee, no prize and no bet. A random
draw happens only when you ask for one, and only shuffles that tournament's own entrants.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android system
  settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads. Nothing in the app is
  behind an ad
- **Delete your data** — remove a result, delete a tournament, use Settings → Delete everything, or
  uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update this page
and bump the "Last updated" date above. Material changes will be flagged in the app's release notes
as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
