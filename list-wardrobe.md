---
layout: default
title: Coatstand — Privacy Policy
description: Privacy policy for the Coatstand Android app by Dash Fusion.
---

# Coatstand — Privacy Policy

**Effective date:** 2026-10-19
**Last updated:** 2026-10-19

## Summary

Coatstand is a record of your wardrobe that you fill in yourself: the pieces of clothing you
own, with a photo of each if you add one, the outfits you put together, and what you wore on
which day. We do **not** create accounts, do **not** ask for your email, and do **not** ship
any analytics or tracking SDK. **Your pieces, outfits, wears and photos stay on your phone.
Coatstand never sends them anywhere and never reads your location. They leave the phone only
if you save a backup or a CSV file where you choose.** A backup file and a CSV file are plain
files and are not encrypted.

**Coatstand has no location, camera or photo-library permission.** A photo comes through
Android's own photo picker, which hands the app only the pictures you chose. Every number —
times worn, last worn, cost per wear — is worked out on the phone, so keeping the record
never uses the internet. The app contains no code that can reach a server at all, apart from
the advertising SDK described below, which receives nothing from your wardrobe.

If that's all you wanted to know, you're done. The sections below spell it out in detail.

## Who we are

- **App name:** Coatstand (store listing: *Coatstand: Wardrobe & Outfits*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listwardrobe`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your pieces:** each piece's category, its one or two colours, the seasons it suits, and,
  if you add them, its name, brand, size, the price you paid, the date you bought it, where
  it is kept and a note; whether it is in the closet, away (with your own word for why) or
  gone, and since when; the day you added it; and its photo.
- **Your outfits:** each outfit's pieces, in order, with an optional name and note.
- **What you wore:** each wear's day, its pieces or its outfit, and an optional note.
- **Pieces to finish:** the pieces made from photos you added several at a time, until you
  save or drop each one.
- **Your photos:** a photo you add to a piece is kept as the app's own smaller copy, a JPEG
  of at most 1,024 pixels on its longer side and at most 400,000 bytes. **The original
  picture is never stored, copied or changed**, and the app keeps no access to it after
  reading it.
- **The currency** your prices are written in.
- **App preferences:** the theme, wallpaper colours, and the ad state: when a 24-hour
  ad-free period ends, and a count that decides when the next ad may show.

**Your wardrobe, its record and its photos are kept here and nowhere else.** They leave the
phone only when you act: a backup you save carries your whole wardrobe and every photo, and
a CSV file carries your pieces or the record of what you wore. Coatstand never sends them
anywhere itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so
Android never copies your wardrobe to Google Drive or to another phone. **A new phone starts
with an empty closet unless you restore a backup you saved.** The app says so in Settings.

You can delete a piece (its photo goes with it), an outfit or a wear; use **Settings →
Delete everything**; or uninstall the app — Android removes the local data with it. We have
no servers and no cloud storage. We cannot see your wardrobe and we cannot recover it if you
lose your device.

## Photos

- **Adding a photo** opens Android's own photo picker. You choose one picture, or several
  when you add several pieces at once; Android hands the app those pictures and nothing else.
  **The app asks for no photo, media, storage or camera permission**, on any version of
  Android, and cannot see your other pictures. It has no camera of its own: your phone's
  camera app takes the photos, and the picker offers them.
- Each picture is read once, turned upright, made smaller and kept as described above. A
  copy picked on a form you then discarded is deleted with the form, and one left behind by
  a form that never came back is deleted a week later. A photo is never sent anywhere, and
  never shown to the advertising SDK.

## CSV files and backups

- **A CSV of your pieces** and **a CSV of what you wore** are written for a spreadsheet,
  where you choose, through Android's own file picker. **A CSV file is plain text and is not
  encrypted**: anyone who can open the file can read it. The app says so beside the buttons.
- **Save a backup** writes your whole wardrobe — pieces, outfits, wears, pieces to finish
  and every photo — to a file where you choose, the same way. **A backup is a plain JSON file
  and is not encrypted**: anyone who can open the file can read it. The app says so beside
  the button.
- **Restore a backup** reads a file you choose, the same way, and asks before it replaces
  your wardrobe. The file is read, not kept, and the app keeps no access to it afterwards.

Coatstand asks for **no storage permission** for any of this: files go through Android's own
file picker.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen interstitial
ad — only after you save a new piece or a new wear, once its form has closed, **never while
you type** and never as the app opens; adding several pieces at once counts as one — plus an
optional rewarded ad you can choose to watch to remove ads for 24 hours. There are no banner
ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for ads)
  and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your wardrobe**: no piece, no colour, no brand, no price, no
wear, no photo, no keyword and no content URL. Like any ad in any app, an ad request does
name the app it comes from. The approximate location above is Google's estimate from your
internet address; it is never your phone's location, which Coatstand cannot read. Google's
handling of the data above is governed by Google's own policies:

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
  connection no ads load, and your closet, outfits, record, photos, backups and CSV files
  still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used by
  AdMob as described above.

That is all of them. **Coatstand asks for no permission at runtime: Android never stops to
ask you about one.** It has no access to your location — no GPS, no fine or approximate
location, no background location — and none to your camera, photos, media, files, contacts,
messages, calendar or microphone, and it asks for none of them. It sends no notifications
and asks for no notification permission: there is no reminder.

A few more permissions are merged into the final app package by the libraries the app is
built on, so the list Google Play shows you is slightly longer than the one above. They are
the Android Ad Services permissions, from the Google Mobile Ads SDK; wake-lock and
foreground-service, from the Android scheduling library the ads SDK brings in; and one
permission that only lets the app's own parts talk to each other. None is a permission
Android stops to ask you about, and none is used by any code we wrote: Coatstand holds no
wake lock and runs no foreground service of its own. A test reads the built app's own merged
manifest on every run and fails the build if that list ever changes, or if any location,
camera or media permission appears in it.

## Children

Coatstand is for adults who want a record of the clothes they own and wear, and is intended
for adults. It is not directed to children under 13, and we do not knowingly collect data
from children — and, as above, we collect no personal data from anyone.

## A record, not advice

Coatstand writes down what you enter. It never suggests what to wear, buy or give away; it
has no styling advice, no "AI" and no shop in it. A price is your own note of what you paid —
the app never buys, sells or totals your spending — and cost per wear is that price divided
by the times you logged wearing the piece.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android system
  settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads. Nothing in
  the app is behind an ad
- **Photos** — add one to a piece only if you want to; change or remove it at any time
- **Delete your data** — delete a piece, an outfit or a wear, use Settings → Delete
  everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update
this page and bump the "Last updated" date above. Material changes will be flagged in the
app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
