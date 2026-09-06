---
layout: default
title: Pantry — Privacy Policy
description: Privacy policy for the Pantry Android app by Dash Fusion.
---

# Pantry — Privacy Policy

**Effective date:** 2026-09-06
**Last updated:** 2026-09-06

## Summary

Pantry keeps track of the dates on the food you already own and tells you what
needs using. All of that stays on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere. We
never see what is in your fridge.

**The app does not use your camera.** Barcode scanning is a common feature in
this category and this app deliberately does not have it: a barcode identifies
the product, never the date, so the scan would fill in the one field you did
not need help with. It also has no contacts, photo, location or calendar
access.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything from your kitchen.

## Who we are

- **App name:** Pantry (Google Play: *Pantry: Food Expiry Tracker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listpantry`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your items** — the name, how much of it there is, any note, and the shelf
  or drawer you typed
- **The dates** — the date printed on the packet and whether it is a use-by or
  a best-before, the day you opened it if you said so, and how long the packet
  keeps once opened
- **Where each item is kept** — cupboard, fridge or freezer, plus the days that
  were left on the clock when something went into the freezer
- **App preferences:** theme, Material You colour, whether the daily notice is
  on, at what time, how many days ahead it looks, and when the rewarded ad-free
  window runs out

That is the whole list. There is no address, no photograph, no location and no
contact anywhere in it, because the app never asks for any of them.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your pantry is never copied into Google's backup service. That
is a deliberate trade and you should know which way it cuts: nothing about your
food is stored off your phone, and **uninstalling the app, or losing the phone,
loses it**. Use **Save a copy** before you switch phones — it is the intended
way to move your data, and it is never behind an ad.

## One phone, and we say so

This app is **one kitchen kept on one device**. Nothing syncs. The other people
in your household do not get a copy, are not invited, and do not need an
account — because there are no accounts at all.

That is a real limit and it is stated in the app as well as here, because
finding it out after installing would be worse.

## What the app deliberately cannot do

Worth stating plainly, because apps in this category commonly do these things:

- **It does not use your camera.** No barcode scanning, and therefore no camera
  permission. See the summary above for why that is a deliberate choice rather
  than a missing feature.
- **It does not use your photos.** A tin of tomatoes does not need a portrait.
- **It does not have any accounts**, so there is nothing to sign up for,
  nothing to sign in to, and no password of yours anywhere.
- **It does not know where you are.** There is no location permission, so it
  cannot offer "you are at the supermarket, here is what ran out" and does not
  pretend to.
- **It does not touch your calendar.** The dates here are the app's own.
- **It does not read your contacts.**

## Saving and restoring

You can save a copy of your pantry to a file you choose, and restore one back.
**A saved file leaves the app's protection**: it is written where you point it,
in a readable JSON form other apps can open. The app tells you this before it
writes anything.

Restoring **replaces** what is in the app — it does not merge — and the
confirmation says so before anything is overwritten.

The file is chosen through Android's own document picker, which hands the app
that one file and grants it nothing else. The app holds **no storage
permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; adding items, reading the dates, the
freezer maths and the daily notice all work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. The only
moment an occasional full-screen ad can appear is **after you take the last
thing off the list that needed using** — which happens at most once a day.
There is also an optional rewarded video you can choose to watch to switch ads
off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any item, any date, or anything else from your pantry.** Google's
processing is done as an independent controller under its own policies:

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

It is **one notification a day**, naming what needs using within the number of
days you chose. If you deny the notification permission, the app keeps working
and simply does not post anything.

## Health and food safety

The app repeats the date printed on the packet and the rule you typed. It
distinguishes **use by** (a safety date) from **best before** (a quality date)
because they mean different things, and it never calls a passed best-before
"expired".

That is information, not advice. The app cannot see, smell or test your food,
and nothing in it is a medical or food-safety judgement about a particular
item. Use your own judgement, and follow the packet.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.
- **Notifications** — to post the daily notice.
- **Run at startup** — so the daily check survives a reboot. Without it,
  restarting your phone would silently stop the notices.

It requests **no camera, no contacts, no location, no photo or media access, no
storage permission and no calendar** — and no exact-alarm permission either,
because a date on a packet is a day-level thing and does not need to wake your
device at a particular second.

Five more permissions are merged into the final app package by the libraries the
app is built on, so the list Google Play shows you is longer than the four
above. They are the three Android Ad Services permissions, which come from the
Google Mobile Ads SDK, plus wake-lock and foreground-service, which come from
**both** that SDK and from AndroidX WorkManager — the component that runs the
daily check. None of them is a permission Android stops to ask you about, and
none is used by any code we wrote.

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
  the pantry lives only on your device, that removes it completely — there is
  no copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
