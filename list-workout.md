---
layout: default
title: Workout Log — Privacy Policy
description: Privacy policy for the Workout Log Android app by Dash Fusion.
---

# Workout Log — Privacy Policy

**Effective date:** 2026-09-09
**Last updated:** 2026-09-09

## Summary

Workout Log tells you what you lifted last time, before you lift it this time.
You keep your own list of exercises, log sets with their reps and load, and open
an exercise to see what you did last session before you see an empty form.

Everything you enter stays on your phone. There is no account, no sign-up, no
cloud and no sync. **Nothing you log is uploaded** — not an exercise, not a set,
not a number. There is nowhere for it to go.

The app asks for **three permissions and no more**, and all three exist only so
ads can be fetched. It has no notifications, no camera, no microphone, no
sensors and no location.

## Who we are

- **App name:** Workout Log (Google Play: *Workout Log: Gym Tracker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listworkout`)

## This app does not coach you

It is worth saying plainly, because most apps in this category do the opposite.

- **It never prescribes.** No recommended weights, no target reps, no programme
  it generates for you, no "you should be lifting X".
- **No readiness score, no recovery score, no form advice, no estimated
  one-rep-max presented as a goal.**
- It knows nothing about you — not your injuries, not your experience, not what
  you ate — and an app that knows none of that has no business telling you what
  to do with a loaded bar.

It records what you did and arranges it so you can find it. The judgement stays
with you and whoever actually trains you.

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Exercises** — the ones you add or keep from the starting list, with the name
  you gave them.
- **Sessions and sets** — a date, and for each set the exercise, the reps, the
  load and its unit, plus any note you typed.
- **Records** — nothing extra is stored. Your best lifts are **computed from the
  log every time they are shown**, so correcting a typo in an old session
  corrects the record with it.
- **App preferences** — theme, Material You colour, your default unit, your
  default rest length, whether the screen is kept awake during a rest, whether
  the rest end buzzes, which progress metric the chart shows, and a count of
  finished workouts used only to decide how rarely to show an ad.

That is the whole list. There is **no name, no age, no email, no address, no
location and no body measurement of any kind** anywhere in it, because the app
never asks for any of them.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your training history is never copied into Google's backup service. The honest
cost: uninstalling the app, or losing the phone, loses it. The **export**
described below is the intended way to keep a copy.

## What this app is not, and does not measure

This is a log of what you lifted. It is **not a body tracker and not a health
monitor**, and the distinction is enforced in the app's own test suite rather
than left to intention:

- **No body weight, no BMI, no body fat, no measurements.**
- **No nutrition, no calories, no macros.**
- **No heart rate, no step count, no sensors, no wearables, no Health Connect.**
- **No camera and no video.**

The only weight in this app is the one on the bar, and it is a number you typed.

## The rest timer, and what it will and will not do

The rest timer **stores the moment it ends** and shows you the difference
between that and now. It is not a background service and it does not schedule an
alarm.

- Leave the app and come back and the timer is still right, because it was never
  counting — it is a subtraction.
- While the timer is running the app can keep the screen awake, which you can
  switch off in Settings.
- **It will not alert you from another app or from a locked phone.** That is a
  real limitation and it is stated here rather than implied away. Doing it would
  mean either a foreground service or a restricted alarm permission, and neither
  is worth taking from you for a ninety-second countdown.

## Your export

The app writes a **CSV file** of your log, and you choose where it goes through
Android's own file picker. The app has no storage permission and cannot write
anywhere you have not pointed it. There is also a full backup and restore for
moving to a new phone.

Those files are **ordinary readable files with no encryption**, which is
deliberate — they are your data and you should be able to open them in anything.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; every exercise, set, record, chart and
export works fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **when you finish a workout that
actually had sets in it** — and not every time even then. It never appears
between sets, never while a rest timer is running, and never when you are
looking something up mid-session.

There is also an optional rewarded video you can choose to watch, which removes
ads for 24 hours. Nothing in the app is locked behind it.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any exercise, any set, any load or anything else from inside the app.**
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

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is the entire list, and it is worth reading twice: **the app requests no
notifications, no camera, no microphone, no photos or media, no storage
permission, no location, no contacts, no body sensors and no activity
recognition.** A gym app is an obvious place to ask for activity recognition and
this one has no use for it, because every number here was typed by the person
who lifted it.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the two
above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all from the Google Mobile Ads SDK. None is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect personal information from
children — as described above, we hold no personal data at all.

## Your choices

- **Keep the screen awake during a rest:** on by default, switchable in Settings.
- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete anything** in the app — a set, a session, an exercise — or **delete it
  all** by clearing the app's storage or uninstalling it. Because your log lives
  only on your device, that removes it completely: there is no copy anywhere
  else, and no deletion request to send us. Any file you exported earlier is
  yours and stays wherever you put it.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
