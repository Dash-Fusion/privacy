---
layout: default
title: Chores — Privacy Policy
description: Privacy policy for the Chores Android app by Dash Fusion.
---

# Chores — Privacy Policy

**Effective date:** 2026-09-06
**Last updated:** 2026-09-06

## Summary

Chores keeps a household's cleaning schedule and works out whose turn it is.
All of that stays on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere. We
never see your chores, the people you live with, or who did what.

**The app does not read your contacts.** Every rival in this category wants your
address book so it can invite the rest of the household; this app has no
accounts to invite anyone to, so it asks for no contacts permission and has
none. It also has no camera, photo, location or calendar access.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything from your household.

## Who we are

- **App name:** Chores (Google Play: *Chores: Cleaning Schedule*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listchores`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your chores** — the name, any note, how often it comes round, the day it
  starts from, and whether it takes turns
- **Your household** — the names you typed and the day each was added
- **Your log** — for each time a chore got done: which chore, who did it (if
  anyone was named), the day it happened, and the occurrence it settled
- **App preferences:** theme, Material You colour, whether the daily notice is
  on and at what time, whether that notice names whose turn it is, and when the
  rewarded ad-free window runs out

That is the whole list. There is no address, no photograph, no location and no
contact anywhere in it, because the app never asks for any of them.

The names in your household are **names you typed on this phone**. The app does
not look them up, match them to anybody, or send them anywhere.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your household is never copied into Google's backup service.
That is a deliberate trade and you should know which way it cuts: nothing about
your household is stored off your phone, and **uninstalling the app, or losing
the phone, loses it**. Use **Save a copy** before you switch phones — it is the
intended way to move your data, and it is never behind an ad.

## One phone, and we say so

This app is **one household's rota kept on one device**. Nothing syncs. Your
flatmates do not get a copy, are not invited, and do not need an account —
because there are no accounts at all.

That is a real limit and it is stated in the app as well as here, because
finding it out after installing would be worse.

## What the app deliberately cannot do

Worth stating plainly, because most apps in this category do these things:

- **It does not read your contacts.** Members are names you type.
- **It does not have any accounts**, so there is nothing to sign up for, nothing
  to sign in to, and no password of yours anywhere.
- **It does not know where you are.** There is no location permission, so it
  cannot offer "remind me when I get home" and does not pretend to.
- **It does not use your camera or your photos.**
- **It does not touch your calendar.** The dates here are the app's own.

## Saving and restoring

You can save a copy of your household to a file you choose, and restore one
back. **A saved file leaves the app's protection**: it is written where you
point it, in a readable JSON form other apps can open. The app tells you this
before it writes anything.

Restoring **replaces** what is in the app — it does not merge — and the
confirmation says so before anything is overwritten.

The file is chosen through Android's own document picker, which hands the app
that one file and grants it nothing else. The app holds **no storage
permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; adding chores, ticking them off, the
fair-share maths and the daily reminder all work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. The only
moment an occasional full-screen ad can appear is **after you clear the board**
— the tick that takes the last outstanding chore to none — which happens at most
once a day. There is also an optional rewarded video you can choose to watch to
switch ads off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any chore, any name from your household, or anything from your log.**
Google's processing is done as an independent controller under its own policies:

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

## Notifications

The daily notice is scheduled and shown **by your phone**, from data already on
it. Nothing is sent to us or through us to deliver one, and no notice ever
leaves the device.

It is **one notification a day**, listing what is due. It can name whose turn it
is; if you would rather it did not — a phone other people can see — there is a
switch in Settings that keeps it to the chore itself. If you deny the
notification permission, the app keeps working and simply does not post
anything.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.
- **Notifications** — to post the daily notice.
- **Run at startup** — so the daily check survives a reboot. Without it,
  restarting your phone would silently stop the notices.

It requests **no contacts, no location, no camera, no photo or media access, no
storage permission and no calendar** — and no exact-alarm permission either,
because a chore being due is a day-level thing and does not need to wake your
device at a particular second.

Five more permissions are merged into the final app package by the libraries the
app is built on, so the list Google Play shows you is longer than the four
above. They are the three Android Ad Services permissions, which come from the
Google Mobile Ads SDK, plus wake-lock and foreground-service, which come from
**both** that SDK and from AndroidX WorkManager — the component that runs the
daily due check. None of them is a permission Android stops to ask you about,
and none is used by any code we wrote.

## Children

This app is not directed at children and is intended for users aged 18 and
over. We do not knowingly collect personal information from children — as
described above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete your data** by clearing the app's storage or uninstalling it. Because
  the household lives only on your device, that removes it completely — there is
  no copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
