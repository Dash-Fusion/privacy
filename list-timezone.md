---
layout: default
title: Timezone — Privacy Policy
description: Privacy policy for the Timezone Android app by Dash Fusion.
---

# Timezone — Privacy Policy

**Effective date:** 2026-09-06
**Last updated:** 2026-09-06

## Summary

Timezone converts a moment between time zones, shows the zones you care about
as clocks, and finds the hours a meeting could actually happen in. All of it
runs on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere. We
never see which cities you added or who you are meeting.

**The app does not know where you are.** It has no location permission of any
kind. It reads your device's *time zone setting* — the one you or your phone
chose, which is a setting and not a position — so it can tell you what time it
is where you are. A time zone is a region the size of a country; it is not a
location, and the app never asks for one.

**The whole time-zone database is inside the app.** Nothing is looked up
online, so conversions work in airplane mode, on a plane, and in a country
where your data does not.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything about your zones or your meetings.

## Who we are

- **App name:** Timezone
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listtimezone`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **The zones you added** — for each one: a time-zone identifier such as
  `Europe/London`, the label you typed for it, its position in your list,
  whether it is included in the meeting view, and the working hours you set for
  it
- **App preferences:** which zone is home (or that home follows the phone),
  12- or 24-hour clock, the default working-hours window, theme, Material You
  colour, when you first opened the app, and when the rewarded ad-free window
  runs out

That is the whole list. There is no name, no email, no address, no photograph,
no location and no contact anywhere in it, because the app never asks for any
of them. A label is a word you typed for your own benefit — *Mum*, *the Berlin
office* — and the app has no idea what it refers to.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your list is never copied into Google's backup service. That is
a deliberate trade and you should know which way it cuts: nothing is stored off
your phone, and **uninstalling the app, or losing the phone, loses your list**.
Use **Save a copy** before you switch phones — it is the intended way to move
your data, and it is never behind an ad.

## What the app deliberately cannot do

Worth stating plainly, because apps in this category commonly do these things:

- **It does not know where you are.** No location permission, no GPS, no
  network-based location, and no map. It reads the device's time-zone setting,
  which you can change yourself in Android's settings and which names a region,
  not a place.
- **It never notifies you.** There is no notification permission, no channel
  and no scheduled work — so nothing in this app will ever interrupt you, and
  it cannot ring for a meeting. That is the cost of the choice, stated here
  rather than discovered later.
- **It does not use the internet for time zones.** The rules ship inside the
  app. Nothing about a conversion is ever sent anywhere.
- **It does not use your camera and holds no photos.**
- **It does not have any accounts**, so there is nothing to sign up for and no
  password of yours anywhere.
- **It does not touch your calendar or your contacts.** The meeting view is
  arithmetic on hours you chose; it does not know who is in the meeting.

## Saving and restoring

You can save a copy of your zones and settings to a file you choose, and
restore one back. **A saved file leaves the app's protection**: it is written
where you point it, in a readable JSON form other apps can open. The app tells
you this before it writes anything.

Restoring **replaces** what is in the app — it does not merge — and the
confirmation says so before anything is overwritten.

The file is chosen through Android's own document picker, which hands the app
that one file and grants it nothing else. The app holds **no storage
permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; every conversion, clock and meeting
calculation works fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. The only
moment an occasional full-screen ad can appear is **after you have copied or
shared an answer** — the point at which the thing you came for has already left
the app and is on your clipboard or in a message. Never while you are reading a
clock, never while a conversion is on screen, and never on the way into
anything. There is also an optional rewarded video you can choose to watch to
switch ads off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your
IP address, device and app information, and ad-interaction data. **It does not
receive your zone list, your labels or anything else from inside the app.**
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
from **Settings → Ad privacy options**, and if you decline, every feature of
the app continues to work exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no
database with your name in it and no way to identify you or your device. We do
not sell or share personal information, because we do not have any.

## About the times the app shows

The app applies the IANA time-zone rules that ship inside it to the moment you
picked. Those rules change when governments change them — a country moving its
clocks, or abolishing the change altogether — and an app can only be as current
as its last update. When a rule changes, the corrected rules arrive in an
update of the app.

The app also tells you when a local time you typed **does not exist** or
**happens twice**, which is what the clocks going forward and back actually
mean. That is information about the calendar, not advice: for anything that
matters legally or contractually, check the time with the person you are
meeting.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is all three of them, and there is no fourth. The app requests **no
location, no notifications, no camera, no contacts, no photo or media access,
no storage permission, no calendar and no exact-alarm permission**.

Five more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the three
above. They are the three Android Ad Services permissions, plus wake-lock and
foreground-service, all of which come from the Google Mobile Ads SDK. None of
them is a permission Android stops to ask you about, and none is used by any
code we wrote.

## Children

This app is not directed at children and is intended for users aged 18 and
over. We do not knowingly collect personal information from children — as
described above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete your data** by clearing the app's storage or uninstalling it.
  Because your list lives only on your device, that removes it completely —
  there is no copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
