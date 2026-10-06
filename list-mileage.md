---
layout: default
title: Mileroll — Privacy Policy
description: Privacy policy for the Mileroll Android app by Dash Fusion.
---

# Mileroll — Privacy Policy

**Effective date:** 2026-10-06
**Last updated:** 2026-10-06

## Summary

Mileroll is a mileage log you fill in yourself: each trip's date, vehicle, odometer
readings or distance, purpose and description, worked out at the rates you enter and
printed as a log for your tax year. We do **not** create accounts, do **not** ask for
your email, and do **not** ship any analytics or tracking SDK. **Your trips, vehicles,
rates and the places and clients you describe stay on your phone. Mileroll never sends
them anywhere and never reads your location. They leave the phone only if you share a
mileage log through Android's share menu, to an app you choose, or save a backup or CSV
file where you choose.** A backup file and a CSV file are plain files and are not
encrypted.

**Mileroll never uses GPS and has no location permission**: a trip is what you type. Every
total, every amount and every mileage log is worked out on the phone, so keeping the log
never uses the internet. The app contains no code that can reach a server at all, apart
from the advertising SDK described below, which receives nothing from your log.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Mileroll (store listing: *Mileroll: Mileage Log*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listmileage`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your vehicles:** each vehicle's name, an optional note (a plate or a model, if you
  add one), the unit its distances are kept in — kilometres or miles — and whether it is
  archived.
- **Your trips:** each trip's date, vehicle, start and end odometer readings or its
  distance alone, purpose, a short description in your own words — the client, the
  destination, the reason — and its parking and tolls, if you add them.
- **Your purposes, saved routes and rates:** the purposes you use and whether each one
  counts as deductible; each saved route's description, purpose, unit and distance; and
  each rate you enter, with its purpose, unit, first day, and an optional threshold and
  the rate after it.
- **Your settings for the log:** your name for the mileage log, if you enter one, your
  currency, and the first day of your tax year.
- **Mileage logs you make:** each one is a PDF written to the app's own cache when you
  make it, and deleted once it is a day old, the next time the app starts.
- **App preferences:** the theme, wallpaper colours, and the ad state: when a 24-hour
  ad-free period ends, and a count that decides when the next ad may show.

**Your trips, their descriptions — the places and clients you name — and your name are
kept here and nowhere else.** They leave the phone only when you act: a mileage log you
share carries your name, if you entered one, and every trip of the dates you chose, and a
backup you save carries your whole log. Mileroll never sends them anywhere itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so
Android never copies your log to Google Drive or to another phone. **A new phone starts
with an empty log unless you restore a backup you saved.** The app says so in Settings.

You can delete a trip, a saved route, a rate, a purpose that no trip uses, or a vehicle
with every trip on it; use **Settings → Delete everything**; or uninstall the app —
Android removes the local data with it. Delete everything keeps only your currency, your
name, the first day of your tax year and your settings. We have no servers and no cloud
storage. We cannot see your log and we cannot recover it if you lose your device.

## Mileage logs, CSV files and backups

- **Share the mileage log** makes a PDF for the dates you chose — your name if you
  entered one, the dates, each vehicle with every trip of those dates (its date,
  readings, distance, purpose, description, parking and tolls) and the totals — and
  hands it to Android's share menu, **only when you choose to**. You pick the app it goes
  to: your email, a messaging app, a printer, your accountant. Mileroll sends nothing
  itself, and sharing needs no permission.
- **Export the trips as CSV** writes a CSV file of every trip of the dates you chose, for
  a spreadsheet, where you choose, through Android's own file picker. **A CSV file is
  plain text and is not encrypted**: anyone who can open the file can read it. The app
  says so beside the button.
- **Save a backup** writes your whole log — vehicles, trips, routes, rates, purposes, your
  name, your currency and the first day of your tax year — to a file where you choose,
  the same way. **A backup is a plain JSON file
  and is not encrypted**: anyone who can open the file can read it. The app says so
  beside the button.
- **Restore a backup** reads a file you choose, the same way, and asks before it replaces
  your log. The file is read, not kept, and the app keeps no access to it afterwards.

Mileroll asks for **no storage permission** for any of this: a mileage log goes out through
Android's share menu, and CSV files and backups through Android's own file picker.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only after you save a new trip, once the trip form has closed, **never
while you type** and never as the app opens — plus an optional rewarded ad you can
choose to watch to remove ads for 24 hours. There are no banner ads. Google may collect
and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for
  ads) and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your log**: no trip, no place, no client, no distance, no
amount, no keyword and no content URL. Like any ad in any app, an ad request does name
the app it comes from. The approximate location above is Google's estimate from your
internet address; it is never your phone's location, which Mileroll cannot read. Google's
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

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads.
  With no connection no ads load, and your log, reports, mileage logs, backups and CSV
  files still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used
  by AdMob as described above.

That is all of them. **Mileroll asks for no permission at runtime: Android never stops to
ask you about one.** It has no access to your location — no GPS, no fine or approximate
location, no background location — and none to your contacts, messages, calendar, camera,
microphone, photos or files, and it asks for none of them. It sends no notifications and
asks for no notification permission: there is no reminder.

A few more permissions are merged into the final app package by the libraries the app is
built on, so the list Google Play shows you is slightly longer than the one above. They
are the Android Ad Services permissions, from the Google Mobile Ads SDK; wake-lock and
foreground-service, from the Android scheduling library the ads SDK brings in; and one
permission that only lets the app's own parts talk to each other. None is a permission
Android stops to ask you about, and none is used by any code we wrote: Mileroll holds no
wake lock and runs no foreground service of its own. A test reads the built app's own
merged manifest on every run and fails the build if that list ever changes, or if any
location permission appears in it.

## Children

Mileroll is for adults keeping a log of the trips they drive for work, and is intended
for adults. It is not directed to children under 13, and we do not knowingly collect
data from children — and, as above, we collect no personal data from anyone.

## A record, not tax advice

Mileroll writes down the trips you enter and works out amounts **only at the rates you
enter**: it ships no official rate and names no tax authority's number. **It gives no tax
advice**: it does not say what you may claim, and it files nothing for you. It never
moves money, links no account and makes no payment. Every page of a mileage log ends with
the same line: *The owner's own record of trips, kept in Mileroll. Amounts are worked out
at the rates the owner entered. It is not tax advice and has no official standing.*

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android
  system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **Your name on the mileage log** — enter, change or clear it in Settings at any time
- **Delete your data** — delete a trip, a route, a rate, a purpose or a vehicle, use
  Settings → Delete everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will
update this page and bump the "Last updated" date above. Material changes will be
flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
