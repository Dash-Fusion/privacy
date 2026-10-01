---
layout: default
title: Tailbook — Privacy Policy
description: Privacy policy for the Tailbook Android app by Dash Fusion.
---

# Tailbook — Privacy Policy

**Effective date:** 2026-10-01
**Last updated:** 2026-10-01

## Summary

Tailbook is a pet care log: every pet's vaccinations, treatments, medicines, vet visits
and weight, with what is due shown first. We do **not** create accounts, do **not** ask
for your email, and do **not** ship any analytics or tracking SDK. **Your pets, their
care, visits, weights and photos stay on your phone. Tailbook never sends them anywhere.
They leave the phone only if you share a care record through Android's share menu, to an
app you choose, or save a backup or CSV file where you choose.** A backup file and a CSV
file are plain files and are not encrypted.

Every due date, every overdue item and the daily reminder are worked out on the phone, so
keeping the record never uses the internet. Tailbook keeps your own record and gives no
veterinary advice. The app contains no code that can reach a server at all, apart from the
advertising SDK described below, which receives nothing from your record.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Tailbook (store listing: *Tailbook: Pet Care Log*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listpet`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your pets:** each pet's name and species, and, if you add them, its breed, sex,
  whether it is spayed or neutered, a microchip number, a colour, a birth date or an
  *about* age, the vet's name and phone, a note, and the unit its weights are shown in.
- **Each pet's photo, if you add one:** a small copy of the picture you chose — a JPEG
  at most 512 pixels on its longer side — kept in the app's database beside its pet.
  The original picture is never kept or copied.
- **Their care:** each care item — its kind (vaccination, flea and tick, worming,
  medicine, check-up, grooming or other), its name, its schedule, its next due date, a
  medicine's dose and how often in your own words, a start and an end, and a note — and
  every date it was done; each vet visit — its date, the clinic or vet, the reason,
  notes and the cost, if you add one; and each weighing — its date and weight.
- **Your currency**, for the costs of vet visits.
- **Care records you make:** each one is a PDF written to the app's own cache when you
  make it, and deleted once it is a day old, the next time you open the app.
- **App preferences:** the theme, wallpaper colours, the daily reminder's switch, hour
  and how far ahead it looks, the day it last posted, and the ad state: when a 24-hour
  ad-free period ends, and a count that decides when the next ad may show.

**Your pets' details, their photos and the vet's name and phone are kept here and
nowhere else.** They leave the phone only when you act: a care record you share carries
the pet's details and photo and the vet's name and phone, and a backup you save carries
your whole record, photos included. Tailbook never sends them anywhere itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so
Android never copies your record or your pets' photos to Google Drive or to another
phone. **A new phone starts with an empty record unless you restore a backup you
saved.** The app says so in Settings.

You can delete a weighing, a vet visit, a day a care item was done, a care item, or a pet
with everything under it, photo included; remove a pet's photo; use **Settings → Delete
everything**; or uninstall the app — Android removes the local data with it. Delete
everything keeps only your currency and your settings. We have no servers and no cloud
storage. We cannot see your record and we cannot recover it if you lose your device.

## Photos, care records, backups and CSV files

- **A pet's photo** comes through **Android's photo picker** (on older Android versions,
  Android's own document picker), which hands Tailbook only the one picture you pick.
  Tailbook holds **no storage, photo or media permission** on any Android version, so it
  cannot browse your photos or files. The picture is read once, turned upright, made
  smaller and kept as above, and the app keeps no access to it afterwards.
- **Share the care record** makes a PDF of one pet — its details, note and photo, the
  vet's name and phone if you entered them, its latest weight, and its vaccinations,
  treatments, medicine courses that have not ended and other care, with their dates — and
  hands it to Android's share menu, **only when you choose to**. You pick the app it goes
  to. A care record never carries a vet visit, a cost or another pet. Tailbook sends
  nothing itself, and sharing needs no permission.
- **Save a backup** writes your whole record — every pet with its photo, its care, visits
  and weights, and the vet's name and phone — to a file where you choose, through
  Android's own file picker. **A backup is a plain JSON file and is not encrypted**:
  anyone who can open the file can read it. The app says so beside the button.
- **Export care items as CSV**, **Export vet visits as CSV** and **Export weights as
  CSV** write a CSV file, for a spreadsheet, where you choose, the same way. Each row
  names its pet; no photo and no vet's phone number is in any of them. **A CSV file is
  plain text and is not encrypted either**: anyone who can open the file can read it.
  The app says so beside each button.
- **Restore a backup** reads a file you choose, the same way. The file is read, not
  kept, and the app keeps no access to it afterwards.

## The daily reminder

The reminder is **off until you turn it on**, and until you do, Tailbook schedules
nothing and never asks to send notifications — not at first launch, not ever.

When you turn on **Remind me each day** in Settings, and only then, Android asks whether
Tailbook may send notifications (on Android 13 and later; older versions do not ask). If
you allow it, Tailbook posts one notification a day at the hour you chose, listing what is
overdue, what is due today and what is due within the days you chose; on a day nothing is
due it posts nothing. If you refuse, the reminder stays off and every other part of the
app works exactly as before.

The notification is made on your phone by Android and is not sent anywhere. On an
unlocked screen it names your pets and their care items; on a locked screen it says only
*Pet care is due*. The reminder itself is one scheduled job, kept in the app's private
storage and with Android's job scheduler: its time, and nothing from your record.

**So that a reminder survives a restart**, Tailbook declares Android's run-at-startup
permission (`RECEIVE_BOOT_COMPLETED`): with it, Android keeps the reminder's job when the
phone restarts, and a reminder that fell due while the phone was off comes once, after it
starts. Without it, every restart would silently cancel the reminder. Android grants it
when the app is installed and never asks you about it, and Tailbook uses it for nothing
else.

Turning the reminder off cancels it, and turning off Tailbook's notifications in Android's
settings also stops it.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only as you leave a pet after recording its care, **never while you
type** and never from a reminder — plus an optional rewarded ad you can choose to watch
to remove ads for 24 hours. There are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for
  ads) and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your record**: no pet, no photo, no care item, no date, no
cost, no note and no keywords. Like any ad in any app, an ad request does name the app it
comes from. Google's handling of the data above is governed by Google's own policies:

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

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads.
  With no connection no ads load, and your record, the reminder, care records, backups
  and CSV files still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used
  by AdMob as described above.
- **Notifications** (`POST_NOTIFICATIONS`) — optional, and only for the daily reminder.
  Asked for only when you turn the reminder on, never at first launch; without it the
  reminder stays off and everything else works.
- **Run at startup** (`RECEIVE_BOOT_COMPLETED`) — only so the daily reminder survives a
  restart of your phone. Android grants it at install and never asks you about it.

That is all of them. **The notification permission is the only one Android ever stops
to ask you about**, and only when you turn the reminder on. Tailbook asks for **no
storage, photo or media permission**: a pet's photo comes through Android's photo
picker, care records go through Android's share menu, and backups and CSV files through
Android's own file picker, and none of them needs one. Tailbook has no access to your
location, contacts, messages, calendar, camera or microphone, it cannot browse your
photos or files, and it asks for none of them. It asks for no exact-alarm permission
either: the reminder is a daily list, not an alarm.

A few more permissions are merged into the final app package by the libraries the app is
built on, so the list Google Play shows you is slightly longer than the one above. They
are the Android Ad Services permissions, from the Google Mobile Ads SDK; wake-lock and
foreground-service, from the Android scheduling library the reminder runs on, which the
ads SDK brings in as well; and one permission that only lets the app's own parts talk to
each other. None is a permission Android stops to ask you about, and none is used by any
code we wrote: Tailbook holds no wake lock and runs no foreground service of its own. A
test reads the built app's own merged manifest on every run and fails the build if that
list ever changes.

## Children

Tailbook is for pet owners keeping their own record of their pets' care, and is intended
for adults. It is not directed to children under 13, and we do not knowingly collect
data from children — and, as above, we collect no personal data from anyone.

## A record, not advice

Tailbook writes down what you say was done and works out each next due date from the
dates and intervals you, or your vet, gave it. **It gives no veterinary advice**: it
makes no diagnosis and suggests no vaccine, treatment, dose or schedule. A vet visit's
cost is your own note of what you paid; Tailbook never charges anyone and moves no money.
Every page of a care record ends with the same line: *The owner's own record, kept in
Tailbook. It is not a veterinary certificate and has no official standing.*

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android
  system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **The daily reminder** — Settings → Remind me each day, off until you turn it on.
  Turning off Tailbook's notifications in Android's settings stops it too
- **A pet's photo** — change or remove it in the pet's details at any time
- **Delete your data** — delete a weighing, a vet visit, a care item or a pet, use
  Settings → Delete everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will
update this page and bump the "Last updated" date above. Material changes will be
flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
