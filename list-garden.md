---
layout: default
title: Trugbook — Privacy Policy
description: Privacy policy for the Trugbook Android app by Dash Fusion.
---

# Trugbook — Privacy Policy

**Effective date:** 2026-10-17
**Last updated:** 2026-10-17

## Summary

Trugbook is a notebook for a vegetable garden that you fill in yourself: your beds, what you
sowed and planted in them, what you harvested, and a diary of the season with photos if you
add them. We do **not** create accounts, do **not** ask for your email, and do **not** ship
any analytics or tracking SDK. **Your beds, plantings, harvests, diary and photos stay on
your phone. Trugbook never sends them anywhere and never reads your location. They leave the
phone only if you save a backup or a CSV file where you choose.** A backup file and a CSV
file are plain files and are not encrypted.

**Trugbook has no location, camera or photo-library permission.** There is no weather in it
and it never knows where your garden is. A photo comes through Android's own photo picker,
which hands the app only the one picture you chose. Every total, season report and rotation
note is worked out on the phone, so keeping the notebook never uses the internet. The app
contains no code that can reach a server at all, apart from the advertising SDK described
below, which receives nothing from your garden.

If that's all you wanted to know, you're done. The sections below spell it out in detail.

## Who we are

- **App name:** Trugbook (store listing: *Trugbook: Vegetable Garden Log*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listgarden`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your beds:** each bed's name, an optional note in your own words, and whether it is
  archived.
- **Your plantings:** each crop in your own words, its bed, how it started (sown indoors,
  sown direct or bought plants) and its dates — when it was sown or planted, came up, was
  planted out and finished — and, if you add them, its plant family, how much you planted,
  your own days to harvest from the seed packet, the words a harvest of it is counted in, and
  a note.
- **Your harvests:** each harvest's date, its planting, its weight in grams and/or its count,
  and an optional note.
- **Your diary:** each entry's date, what it is about — the whole garden, a bed or a
  planting — and your words.
- **Your photos:** a photo you add to a diary entry is kept as the app's own smaller copy, a
  JPEG of at most 1,024 pixels on its longer side, beside its entry. **The original picture
  is never stored, copied or changed**, and the app keeps no access to it after reading it.
- **Your settings for the garden:** the month your season starts, how many seasons a
  rotation note looks back, and whether weights are shown in kilograms and grams or pounds
  and ounces.
- **App preferences:** the theme, wallpaper colours, and the ad state: when a 24-hour
  ad-free period ends, and a count that decides when the next ad may show.

**Your garden, your diary and your photos are kept here and nowhere else.** They leave the
phone only when you act: a backup you save carries your whole garden and every photo, and a
CSV file carries the harvests or plantings you chose. Trugbook never sends them anywhere
itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so
Android never copies your garden to Google Drive or to another phone. **A new phone starts
with an empty garden unless you restore a backup you saved.** The app says so in Settings.

You can delete a harvest, a diary entry, a planting with its harvests and diary, or a bed
with everything in it; use **Settings → Delete everything**; or uninstall the app — Android
removes the local data with it. Delete everything keeps only the month your season starts,
how weights are shown, the rotation setting and your app preferences. We have no servers and
no cloud storage. We
cannot see your garden and we cannot recover it if you lose your device.

## Photos

- **Adding a photo** opens Android's own photo picker. You choose one picture; Android hands
  the app that picture and nothing else. **The app asks for no photo, media, storage or
  camera permission**, on any version of Android, and cannot see your other pictures.
- The picture is read once, turned upright, made smaller and kept as described above. A
  photo is never sent anywhere, and never shown to the advertising SDK.

## CSV files and backups

- **Harvests as CSV** and **Plantings as CSV** write a CSV file of the season you chose, or
  of every season, for a spreadsheet, where you choose, through Android's own file picker.
  **A CSV file is plain text and is not encrypted**: anyone who can open the file can read
  it. The app says so beside the buttons.
- **Save a backup** writes your whole garden — beds, plantings, harvests, the diary and
  every photo — to a file where you choose, the same way. **A backup is a plain JSON file and
  is not encrypted**: anyone who can open the file can read it. The app says so beside the
  button.
- **Restore a backup** reads a file you choose, the same way, and asks before it replaces
  your garden. The file is read, not kept, and the app keeps no access to it afterwards.

Trugbook asks for **no storage permission** for any of this: files go through Android's own
file picker.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen interstitial
ad — only after you save a new harvest or a new diary entry, once its form has closed,
**never while you type** and never as the app opens — plus an optional rewarded ad you can
choose to watch to remove ads for 24 hours. There are no banner ads. Google may collect and
process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for ads)
  and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your garden**: no bed, no crop, no harvest, no diary word, no
photo, no keyword and no content URL. Like any ad in any app, an ad request does name the app
it comes from. The approximate location above is Google's estimate from your internet
address; it is never your phone's location, which Trugbook cannot read. Google's handling of
the data above is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's certified
consent form, and you choose whether personalised ads are allowed. You can change your answer
at any time from **Settings → Advert privacy options** inside the app. You can also opt out
of personalised advertising via your device's system settings (Android: **Settings → Privacy
→ Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that phones
home, no Firebase, and no custom telemetry. There is no HTTP client anywhere in the app's own
code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads. With no
  connection no ads load, and your garden, reports, photos, backups and CSV files still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used by
  AdMob as described above.

That is all of them. **Trugbook asks for no permission at runtime: Android never stops to ask
you about one.** It has no access to your location — no GPS, no fine or approximate
location, no background location — and none to your camera, photos, media, files, contacts,
messages, calendar or microphone, and it asks for none of them. It sends no notifications
and asks for no notification permission: there is no reminder.

A few more permissions are merged into the final app package by the libraries the app is
built on, so the list Google Play shows you is slightly longer than the one above. They are
the Android Ad Services permissions, from the Google Mobile Ads SDK; wake-lock and
foreground-service, from the Android scheduling library the ads SDK brings in; and one
permission that only lets the app's own parts talk to each other. None is a permission
Android stops to ask you about, and none is used by any code we wrote: Trugbook holds no wake
lock and runs no foreground service of its own. A test reads the built app's own merged
manifest on every run and fails the build if that list ever changes, or if any location,
camera or media permission appears in it.

## Children

Trugbook is for adults who keep a vegetable garden or an allotment, and is intended for
adults. It is not directed to children under 13, and we do not knowingly collect data from
children — and, as above, we collect no personal data from anyone.

## A notebook, not advice

Trugbook writes down what you enter. It has no crop list and gives no growing advice: it
never says when to sow, what to plant where or what a crop will give. A rotation note says
which plant family grew in a bed in the seasons before, and never stops you saving. There is
no money in the app at all.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android system
  settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads. Nothing in
  the app is behind an ad
- **Photos** — add one to a diary entry only if you want to; remove it from the entry at any
  time
- **Delete your data** — delete a harvest, an entry, a planting or a bed, use Settings →
  Delete everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update
this page and bump the "Last updated" date above. Material changes will be flagged in the
app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
