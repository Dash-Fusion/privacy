---
layout: default
title: Rootward — Privacy Policy
description: Privacy policy for the Rootward Android app by Dash Fusion.
---

# Rootward — Privacy Policy

**Effective date:** 2026-10-13
**Last updated:** 2026-10-13

## Summary

Rootward is a family tree you build yourself: people, their parents, partners and
children, with dates and places, and GEDCOM files imported and exported. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any analytics or
tracking SDK. **Your trees - the people in them, their names, dates, places and notes -
stay on your phone. Rootward never sends them anywhere. They leave the phone only if you
export a tree as a GEDCOM file and save it where you choose; that file is plain text and
is not encrypted.**

The app contains no code that can reach a server at all, apart from the advertising SDK
described below, which receives nothing from your trees.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Rootward (store listing: *Rootward: Private Family Tree*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.familytree`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private storage. It
never leaves the device on the app's own.

- **Your trees:** each tree's name and the person it opens on; the people in it - their
  names, sex, whether they are living, their birth, death and burial dates and places, and
  your notes about them; the families - two partners, a marriage, partnership or divorce
  with its date and place, and notes; and which family each person is a child of, and how
  (by birth, adopted, fostered, a stepchild)
- **A search index** of the words in people's names, so the people list can find them
- **App preferences:** theme, wallpaper colours, the tree you have open, the name you want
  written into exported files (if you give one), and the ad state described below

**A family tree holds other people's personal data**: your relatives' names, dates and
places of birth - living relatives' among them - and anything you write about them. In
Rootward it stays on your phone, in the app's private storage.

There is no account and no contact information of yours anywhere in the app. The app
explicitly opts out of Android cloud backup and device-to-device transfer. **That has a
cost worth knowing: a new phone starts Rootward with no trees.** The app says so in
Settings and suggests exporting each tree as a GEDCOM file and keeping it somewhere safe.

To delete everything, delete a tree from within the app, clear the app's storage (Android
**Settings → Apps → Rootward → Storage → Clear storage**) or uninstall the app - Android
removes the app's private storage with it.

We have no servers and no cloud storage. We cannot see your trees and we cannot recover
them if you lose your device.

## Files you import and export

- **Import:** when you import a GEDCOM file, you pick it with Android's own file picker.
  Rootward reads that one file, once, and turns what it holds into a new tree on your phone.
  It keeps no access to the file afterwards and needs no storage permission.
- **Export:** when you export a tree, you choose where the GEDCOM file is saved, with
  Android's own file picker. **The file is plain text and is not encrypted**: anyone who
  has it can read every name, date, place and note in it. It also carries the name you
  gave for exported files, if you gave one.
- **Leaving out the living:** you can export with living people's details left out, for
  sharing with relatives. People who count as living are written as *Living* with their
  surname only - their dates, places and how they are a child of their family are left
  out - and no notes are written for anyone. The export screen says who counts as living.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad - only after you have added and saved a new person, never for the first
new person each time you open the app, never after you have deleted something in that
visit, at most after every third counted person, and never two within thirty minutes -
plus an optional rewarded ad in Settings that turns adverts off for 24 hours. There are no
banner ads, and nothing in the app is locked behind an ad. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network information**
  that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your trees**: no name, no surname, no place, no date and no
keyword. Google's handling of the data above is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's certified
consent form, and you choose whether personalised ads are allowed. You can change your
answer at any time from **Settings → Advert privacy options** inside the app. You can also
opt out of personalised advertising via your device's system settings (Android:
**Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that
phones home, no Firebase, and no custom telemetry. There is no HTTP client anywhere in the
app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** - solely so the Google Mobile Ads SDK can fetch ads.
  Without a connection no ads load, and every tree, chart, search, import and export still
  works.
- **Advertising ID (`AD_ID`)** - required by Google Play for apps that serve ads; used by
  AdMob as described above.

**Those are the only permissions the app asks for, and none of them is a run-time
prompt.** Rootward has no access to your contacts, location, camera, microphone, photos,
files or notifications, and it asks for none of them: a tree is typed in or read from a
file you pick, never filled from your address book. A test reads the built app's own
merged manifest on every run and fails the build if that list ever changes.

## Children

Rootward is not directed to children under 13 and is not designed for use under the COPPA
framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** - Settings → Advert privacy options (EEA/UK/Switzerland), or Android
  system settings → Privacy → Ads
- **A day without adverts** - the optional rewarded ad in Settings. Nothing else in the
  app is behind an ad
- **Sharing a tree** - export it, with or without living people's details, and save the
  file where you choose
- **Delete your data** - delete a tree in the app, clear the app's storage in Android
  settings, or uninstall the app
- **Contact us** - dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update
this page and bump the "Last updated" date above. Material changes will be flagged in the
app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
