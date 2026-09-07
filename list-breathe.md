---
layout: default
title: Breathe — Privacy Policy
description: Privacy policy for the Breathe Android app by Dash Fusion.
---

# Breathe — Privacy Policy

**Effective date:** 2026-09-07
**Last updated:** 2026-09-07

## Summary

Breathe is a guided breathing timer. You pick a pattern — box, 4-7-8, coherent,
or one you build yourself — choose how long, and follow a circle that expands
and contracts. It keeps a short record of the sessions you finished. All of
that stays on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere.

**This app is not a medical device.** It does not diagnose anything, it does not
treat anything, and it makes no claim about your health. It is a timer with a
circle on it. If you feel unwell, or breathing exercises make you feel unwell,
stop and speak to a doctor rather than to an app.

**It does not listen to you.** There is no microphone permission, so nothing
measures your actual breathing, your heart rate or anything else about your
body. The app knows only what you tapped.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything about your sessions.

## Who we are

- **App name:** Breathe (Google Play: *Breathe: Breathing Exercises*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listbreathe`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Patterns you build** — the name you typed and the four phase lengths
- **Sessions you finished** — which pattern, how many cycles, how long, and
  when. A session you stop early is **not** recorded, and the app says so
  before it stops
- **App preferences:** the session length you last chose, whether the phone
  buzzes on each phase change, whether the screen stays awake during a session,
  your daily reminder time if you set one, theme, Material You colour, and when
  the rewarded ad-free window runs out

That is the whole list. There is no name, no email, no location, no photograph
and no contact anywhere in it, because the app never asks for any of them. A
pattern name is a word you typed for your own benefit and the app has no idea
what it refers to.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your sessions are never copied into Google's backup service. That
is a deliberate trade and you should know which way it cuts: nothing is stored
off your phone, and **uninstalling the app, or losing the phone, loses it**. Use
**Save a copy** before you switch phones.

## Everything in it is free

There is no paid tier, no subscription and nothing locked. Every built-in
pattern, every pattern you build, every length, the history, the streak, the
reminder and the export are all available to everyone, always. The optional
rewarded video switches ads off for a day; it does not unlock anything, because
there is nothing to unlock.

## What the app deliberately cannot do

Worth stating plainly, because apps in this category commonly do these things:

- **It does not listen.** No microphone permission, so it cannot hear your
  breathing and does not try to.
- **It does not know where you are.** No location permission of any kind.
- **It does not measure your body.** No heart rate, no Health Connect, no
  wearable, no sensor of any sort. Nothing in this app is a measurement.
- **It does not use your camera and holds no photos.**
- **It does not have any accounts**, so there is nothing to sign up for and no
  password of yours anywhere.
- **It does not read your contacts or your calendar.**
- **It has no social features.** Nothing is shared, posted, compared with anyone
  or sent anywhere.

## The daily reminder

The reminder is **off until you switch it on**, and until you do, the app
schedules nothing and asks for no notification permission at all.

If you switch it on, the app asks Android for permission to post notifications,
schedules one reminder a day at the time you chose, and re-schedules it after
the phone restarts — which is the only reason the app is told the phone has
booted. The reminder is a single line inviting you to breathe. It contains
nothing about your history and is not sent anywhere; it is created on your phone
by your phone.

Switching the reminder off cancels it. Denying or revoking the notification
permission in Android's settings also stops it, and the app says so on the
settings screen rather than failing silently.

## Saving and restoring

You can save a copy of your patterns and sessions to a file you choose, and
restore one back. **A saved file leaves the app's protection**: it is written
where you point it, in a readable JSON form other apps can open.

Restoring **replaces** what is in the app — it does not merge — and the
confirmation says so before anything is overwritten.

The file is chosen through Android's own document picker, which hands the app
that one file and grants it nothing else. The app holds **no storage
permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; every pattern, every session, the
history and the export all work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. An
occasional full-screen ad can appear at exactly one moment: **after a session
has run to its end**, once the summary is already on screen. It never appears
when you start a session, never during one, and never when you stop one early.
There is also an optional rewarded video you can choose to watch to switch ads
off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any session, any pattern, any streak or anything else from inside the
app.** Google's processing is done as an independent controller under its own
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
- **Delete your data** by clearing the app's storage or uninstalling it. Because
  your record lives only on your device, that removes it completely — there is
  no copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
