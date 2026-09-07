---
layout: default
title: Mood — Privacy Policy
description: Privacy policy for the Mood Android app by Dash Fusion.
---

# Mood — Privacy Policy

**Effective date:** 2026-09-07
**Last updated:** 2026-09-07

## Summary

Mood is a ten-second daily check-in. You pick a word for the day, optionally
add a note and a tag or two, and the app shows you how the days have fallen
over the last month or three. All of it stays on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere.

**This is a notebook, not a medical device.** It records what you typed and
adds it up. It does not diagnose anything, does not treat anything, does not
give advice, and makes no claim about your health. If you are struggling,
please talk to a person — a doctor, or a helpline in your country — rather than
to an app that only knows what you tapped.

**A mood log is among the most personal things a phone can hold**, which is why
it is treated the way it is here: nothing about it is uploaded, nothing is
analysed on a server, and there is no account it could ever be attached to.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything you wrote.

## Who we are

- **App name:** Mood (Google Play: *Mood Tracker: Daily Check-In*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listmood`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **One entry per day** — the level you chose, the note you typed if you typed
  one, and any tags you attached. The entry is keyed by the **local date** it
  belongs to; there is no clock time in it, so the record says *which day*, not
  what hour you happened to open the app.
- **Your tags** — the words you made up
- **App preferences:** your daily reminder time if you set one, theme, Material
  You colour, and when the rewarded ad-free window runs out

That is the whole list. There is no name, no email, no location, no photograph
and no contact anywhere in it, because the app never asks for any of them. A
note is a sentence you wrote for yourself, and nothing in this app or outside
it reads it.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your diary is never copied into Google's backup service. That is
a deliberate trade and you should know which way it cuts: nothing is stored off
your phone, and **uninstalling the app, or losing the phone, loses it**. Use
**Save a copy** before you switch phones — it is the whole migration path, and
it is never behind an ad.

## What the app deliberately cannot do

Worth stating plainly, because apps in this category commonly do these things:

- **It does not analyse your notes.** No sentiment scoring, no keyword
  extraction, no AI reading your diary. The note is stored and shown back to
  you; nothing else happens to it.
- **It does not know where you are.** No location permission of any kind, so
  there is no map of your moods and no inference about the places you feel
  worst.
- **It does not measure your body.** No heart rate, no sleep tracking, no
  Health Connect, no wearable.
- **It does not use your microphone, your camera, your contacts or your
  calendar.**
- **It has no accounts and no social features.** Nothing is shared, compared,
  ranked against other people or sent anywhere.
- **It does not sell anything about you**, because it holds nothing about you
  to sell.

## The daily reminder

The reminder is **off until you switch it on**, and until you do, the app
schedules nothing and asks for no notification permission at all.

If you switch it on, the app asks Android for permission to post notifications,
schedules one reminder a day at the time you chose, and re-schedules it after
the phone restarts — which is the only reason the app is told the phone has
booted. The reminder is a single line inviting you to check in. **It never
contains anything you wrote**, and it is not sent anywhere; it is created on
your phone by your phone.

Switching the reminder off cancels it, and revoking the notification permission
in Android's settings also stops it.

## Saving and restoring

You can save a copy of your entries and tags to a file you choose, and restore
one back. **A saved file leaves the app's protection**: it is written where you
point it, in a readable JSON form other apps can open — so put it somewhere you
are content for it to be.

Restoring **replaces** what is in the app — it does not merge — and the
confirmation says so before anything is overwritten.

Days in the file keep the local date they were written with, and that date is
never recomputed on import. Restoring after moving country therefore leaves
your diary on the days it happened, rather than silently shifting a year of it.

The file is chosen through Android's own document picker, which hands the app
that one file and grants it nothing else. The app holds **no storage
permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; the check-in, the trends, the history
and the export all work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **after the first check-in of a
day**, once the day is recorded — never when you edit an entry, never while you
are typing a note, and never on the history or the trends. There is also an
optional rewarded video you can choose to watch to switch ads off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any entry, any note, any tag or anything else from inside the app.**
Google's processing is done as an independent controller under its own
policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

### Consent (UMP)

Where required by law, the app shows Google's User Messaging Platform consent
form before ads are initialised, and records your choice. In the EEA and the UK
you are asked about personalised advertising; in covered US states you are
offered the opt-out required there. You can change your decision at any time
from **Settings → Ad privacy options**, and if you decline, every feature of the
app continues to work exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no
database with your name in it and no way to identify you or your device. We do
not sell or share personal information, because we do not have any.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Notifications** — only if you switch the daily reminder on, and never asked
  for until you do.
- **Run at startup** — only so a reminder you set survives a restart.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is all of them. The app requests **no microphone, no location, no camera,
no contacts, no photo or media access, no storage permission, no calendar, no
body sensors and no exact-alarm permission**.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the ones
above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all of which come from the Google Mobile Ads SDK. None is a
permission Android stops to ask you about, and none is used by any code we
wrote.

## Children

This app is not directed at children and is intended for users aged 18 and
over. We do not knowingly collect personal information from children — as
described above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete a single day** from the history, or **delete everything** by clearing
  the app's storage or uninstalling it. Because your diary lives only on your
  device, that removes it completely — there is no copy anywhere else, and no
  deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
