---
layout: default
title: Trip Planner — Privacy Policy
description: Privacy policy for the Trip Planner Android app by Dash Fusion.
---

# Trip Planner — Privacy Policy

**Effective date:** 2026-09-10
**Last updated:** 2026-09-10

## Summary

Trip Planner is an offline itinerary. You type your flights, trains, hotels and
bookings into it, attach the confirmations, and read the day back while you are
travelling. All of that stays on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere. We
never see where you are going, when, or with whom.

**Every time is shown in the zone of the place it happens in.** A 23:40
departure typed in Jakarta still reads 23:40 after you land in Tokyo. That is a
design decision about your data rather than about privacy, but it has a privacy
consequence worth stating: the app stores the zone you wrote a time in, and it
uses that zone for ordering and for working out how long something takes. **It
never asks the phone where you actually are.**

**Your documents are copied onto the phone, not linked.** A boarding pass you
attach is written into this app's private storage, so it opens at an airport
gate with no signal and no cloud account. The original stays where it was.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything about your trip.

## Who we are

- **App name:** Trip Planner (Google Play: *Trip Planner: Itinerary*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listtrip`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your trips** — the name you typed, the days it runs, a home zone, and any
  note you added
- **Your entries** — what kind each one is, its title, any detail and any
  reference or booking number you typed, the wall clock it happens at, and the
  IANA zone that clock was written in
- **Your documents** — a copy of each file you attached, plus its name and size
- **App preferences:** theme, Material You colour, and when the rewarded
  ad-free window runs out

That is the whole list. There is no name, no address, no photograph, no
location fix and no contact anywhere in it, because the app never asks for any
of them. A reference number is a string you typed for your own benefit, and the
app has no idea which airline or hotel it belongs to — it never contacts one.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your itinerary is never copied into Google's backup service. That
is a deliberate trade and you should know which way it cuts: nothing about your
travel is stored off your phone, and **uninstalling the app, or losing the
phone, loses it**. Use **Save a copy** before you switch phones — it is the
intended way to move your data, it is never behind an ad, and for an itinerary
typed off confirmation emails you may since have deleted it is the only copy
there is.

## About the documents you attach

This is the part most worth reading, because it is where a travel app usually
gets it wrong.

When you attach a file, the app **copies the bytes into its own private
storage** and uses the copy from then on. It does not keep a link into Google
Drive, Dropbox or your Downloads folder. Two consequences:

- **It opens with no signal.** A link into a cloud provider is unreadable at a
  gate with aeroplane mode on, which is exactly when a boarding pass is needed.
- **It survives.** Deleting the original, or signing out of the provider, does
  not empty your itinerary.

The copy lives inside the app, so **removing the entry removes the copy**, and
uninstalling the app removes all of them. The file is read once, through
Android's own document picker, which hands the app that single file and grants
it nothing else. The app holds **no storage permission** and cannot see anything
else on your phone.

## One phone, and we say so

This app is **one itinerary kept on one device**. Nothing syncs. No travelling
companion can see it, nobody is invited, and nobody needs an account — because
there are no accounts at all.

That is a real limit and it is stated in the app as well as here, because
finding it out after installing would be worse.

## What the app deliberately cannot do

Worth stating plainly, because apps in this category commonly do these things:

- **It does not know where you are.** No location permission of any kind, so no
  map, no "nearby", no automatic zone switching and no record of where you
  actually went. The zone attached to an entry is the one that entry was written
  in, not one the phone measured.
- **It does not read your email.** Rival apps forward confirmations to an
  address that parses them. That means handing a company your booking mail, and
  this app cannot do it: it has no server to forward anything to.
- **It never notifies you.** There is no notification permission and no channel.
- **It does not use your camera and holds no photos** beyond the files you
  attach yourself.
- **It does not have any accounts**, so there is nothing to sign up for,
  nothing to sign in to, and no password of yours anywhere.
- **It does not touch your calendar.**
- **It does not read your contacts.**
- **It does not talk to any airline, hotel or booking service.** Nothing here is
  submitted anywhere. It is your own record, for your own use.

## Saving and restoring

You can save a copy of your trips and entries to a file you choose, and restore
one back. **A saved file leaves the app's protection**: it is written where you
point it, in a readable JSON form other apps can open. The app tells you this
before it writes anything.

Restoring **replaces** what is in the app — it does not merge — and the
confirmation says so before anything is overwritten.

The file is chosen through Android's own document picker, which hands the app
that one file and grants it nothing else.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; typing an itinerary, reading it,
opening an attached document and working out how long a flight takes all work
fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. The only
moment an occasional full-screen ad can appear is **after you close an itinerary
you have been planning in** — never while you are reading one, and never on the
way into anything. There is also an optional rewarded video you can choose to
watch to switch ads off for 24 hours. **Nothing in this app is locked behind
it**, and that includes saving a copy of your data.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any trip, any entry, any reference number or any document.** Google's
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

## About the times and durations in the app

The app shows the clock times you typed, in the zones you typed them in, and
subtracts them to get a duration. That is arithmetic on your own figures. It is
not a booking, not a confirmation and not advice: it does not know whether your
flight is on time, whether it moved, or whether it exists.

Where it cannot honestly work a duration out, it says so rather than showing a
zero.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.

That is both of them, and there is no third. The app requests **no location, no
notifications, no camera, no contacts, no photo or media access, no storage
permission, no calendar and no exact-alarm permission**.

Seven more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the two
above: the advertising ID (`AD_ID`), the three Android Ad Services permissions,
and wake-lock, foreground-service and job-service, all of which come from the
Google Mobile Ads SDK and its scheduling library. None of them is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect personal information
from children — as described above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete your data** by removing a trip, clearing the app's storage, or
  uninstalling it. Because your itinerary lives only on your device, that
  removes it completely — including every document copy — with no copy anywhere
  else and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
