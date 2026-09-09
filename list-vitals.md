---
layout: default
title: Blood Pressure Log — Privacy Policy
description: Privacy policy for the Blood Pressure Log Android app by Dash Fusion.
---

# Blood Pressure Log — Privacy Policy

**Effective date:** 2026-09-09
**Last updated:** 2026-09-09

## Summary

Blood Pressure Log keeps the record a doctor asks for: a sitting a morning and a
sitting an evening, two or three readings each, averaged, and handed over as a
file at the end of the week.

**This app holds health information, and it is the only Dash Fusion app that
does.** Your readings are health data. They are written to this app's private
storage on your phone, they are never uploaded, and the only way they leave the
device is an export you perform yourself and choose the destination of.

There is no account, no sign-up, no cloud and no sync. There is nowhere for your
numbers to go, because the app has no server to send them to.

## Who we are

- **App name:** Blood Pressure Log (Google Play: *Blood Pressure Log & Pulse*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listvitals`)

## This app does not tell you what your numbers mean

This belongs in a privacy policy rather than only in the store listing, because
it is the most important thing to know about what the app does with your health
data: **it does not interpret it.**

- No thresholds, no colour that means bad, no category label, no arrows, no
  advice, no verdict of any kind on any reading.
- **It is not a medical device**, it does not diagnose anything, and it makes no
  claim about your health.
- Nothing it stores is analysed, scored, profiled or compared against anybody
  else, on your phone or anywhere else.

It records, it arranges, and it hands over. What the numbers mean is a
conversation for you and a clinician, and this app deliberately stays out of it.

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Sittings** — a date, whether it was the morning or the evening one, and an
  optional note and arm (left or right) if you record them.
- **Readings** — the systolic and diastolic figures and the pulse, exactly as
  you typed them, with the average computed from them rather than stored
  separately.
- **App preferences** — theme, Material You colour, whether to hide the app from
  the recents screen, whether each reminder is on and at what time, the chart
  window you last chose, when the rewarded ad-free window runs out, and a count
  of how many sittings you have completed, which is used only to decide how
  rarely to show an ad.

That is the whole list. There is no name, no date of birth, no email, no
address, no phone number, no contact, no photograph and no location anywhere in
it, because the app never asks for any of them. It supports **one person's
record per installation** and has no concept of a second profile, so there is no
way to file a reading against the wrong body.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind. Nobody at Dash Fusion
can see a single number you have entered.

There is **no Health Connect, no sensor, no wearable and no import of any
kind**. Every figure in this app was typed by the person it belongs to.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your readings are never copied into Google's backup service. That is what makes
the sentence at the top of this page true rather than merely well-meant. The
honest cost: uninstalling the app, or losing the phone, loses your history. The
**export** described below is the intended way to keep a copy.

## Handing your record over, and what that file is

The whole point of the app is the moment you give the record to somebody, so it
is worth being exact about it.

- The app writes a **CSV file** with one row per reading, and a **plain-text
  summary** you can read aloud. Both carry every individual reading as well as
  the average, so nothing you entered is summarised away.
- You choose where the file goes, through Android's own file picker. The app has
  no storage permission and cannot write anywhere you have not pointed it.
- **That file is an ordinary readable file with no encryption.** This is
  deliberate — it is your data, a clinician has to be able to open it, and a
  format only this app can read would defeat the purpose. It does mean that
  where you save it, and who you send it to, is your decision and worth a
  moment's thought.

## Who can see the app on your phone

**There is no PIN, password or biometric lock, and this policy will not imply
one.** Anyone who can unlock your phone can open the app and read your readings.

What the app does do is set Android's `FLAG_SECURE` on its own window, **on by
default**. Its contents do not appear in the app-switcher preview, and
screenshots and screen recordings of it are blocked by the operating system.
That is a measure against somebody glancing at your phone on a desk or a train.
It is not a security boundary. You can switch it off in Settings if you would
rather be able to screenshot your own log.

The optional reminders are also written with this in mind: **the notification
says nothing about any reading**. It says a sitting is due and nothing else,
because a notification is a lock screen and a lock screen is read by whoever is
standing there.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; every reading, average, chart and
export works fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **when you finish a sitting** —
that is, when you close the sitting screen having recorded a second reading in
it — and not every time even then. It never appears while you are typing a
reading, never on the chart, and **never on an export**, because the moment you
are handing your health record to a doctor is not a moment to interrupt.

There is also an optional rewarded video you can choose to watch, which removes
ads for 24 hours. It is offered from one row in Settings, nothing in the app is
locked behind it, and it never interrupts anything.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any reading, any average, any note or anything else from inside the
app.** Your blood pressure is not sent to an advertiser, or to us, or to
anybody. Google's processing is done as an independent controller under its own
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
database with your name in it, no health record of yours, and no way to identify
you or your device. We do not sell or share personal information, and we do not
sell or share health information, because we do not have any.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.
- **Notifications** — only if you switch a reminder on. Nothing is scheduled and
  the permission is never requested until you do, and the notification's text
  says nothing about your readings.
- **Run at startup** — so a reminder you have already set survives the phone
  being restarted. It does nothing else and runs no code at boot beyond
  re-registering that reminder.

That is the whole list. The app requests **no camera, no microphone, no photos
or media access, no storage permission, no location, no contacts, no calendar
and no body-sensor or activity-recognition permission of any kind.** The absence
of the last one is deliberate and worth stating: a blood-pressure app is an
obvious place to ask for health sensors, and this one has no use for them
because you type the numbers off your own cuff.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the ones
above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all from the Google Mobile Ads SDK. None is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect personal information from
children — as described above, we hold no personal data at all.

## Your choices

- **Hide from recents:** on by default, and switchable in Settings.
- **Reminders:** both off until you turn one on, and switchable back off at any
  time.
- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete anything** in the app — a reading, a whole sitting — or **delete it
  all** by clearing the app's storage or uninstalling it. Because your readings
  live only on your device, that removes them completely: there is no copy
  anywhere else, and no deletion request to send us. Any file you exported
  earlier is yours and stays wherever you put it.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
