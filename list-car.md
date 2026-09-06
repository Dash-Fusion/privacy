---
layout: default
title: Car Log — Privacy Policy
description: Privacy policy for the Car Log Android app by Dash Fusion.
---

# Car Log — Privacy Policy

**Effective date:** 2026-09-06
**Last updated:** 2026-09-06

## Summary

Car Log keeps a service history for your vehicles. That history stays on your
phone.

There is no account, no sign-up, no cloud, and no server of ours anywhere. We
never see your vehicles, your mileage or what you paid.

**The app does not know where your car is.** It asks for no location permission
and has none. It also has no Bluetooth permission, so it cannot talk to an
OBD-II dongle or any other device in the car, and no camera or photo access.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything from your log.

## Who we are

- **App name:** Car Log (Google Play: *Car Log: Service & Mileage*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listcar`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your vehicles** — the name you gave each one and any note you wrote
- **Your service records** — the date, what was done, the odometer reading if
  you entered one, the cost if you entered one, and any note
- **Your schedules** — the intervals you set, in months and/or distance
- **App preferences:** theme, Material You colour, distance unit, reminder
  settings, and when the rewarded ad-free window runs out

That is the whole list. There is no registration number, no VIN, no photograph
and no location anywhere in it, because the app never asks for any of them.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your log is never copied into Google's backup service. That is a
deliberate trade and you should know which way it cuts: nothing about your
vehicles is stored off your phone, and **uninstalling the app, or losing the
phone, loses the log**. Use **Save a copy** before you switch phones — it is
the intended way to move your data, and it is never behind an ad.

## What the app deliberately cannot do

Worth stating plainly, because most apps in this category do these things:

- **It does not read your location.** A service log has no use for where the
  car is, and the permission is not in the app.
- **It does not connect to your car.** No Bluetooth, no OBD-II, no dongle, no
  telemetry.
- **It does not look up your registration or VIN.** Those are network calls, and
  this app has no network client at all beyond the ads library.
- **It does not take photographs of receipts.** That would need camera or media
  access for a feature a written log already covers.

## Saving and restoring

You can save a copy of your log to a file you choose, and restore one back. **A
saved file leaves the app's protection**: it is written where you point it, in a
readable JSON form other apps can open. The app tells you this before it writes
anything.

The file is chosen through Android's own document picker, which hands the app
that one file and grants it nothing else. The app holds **no storage
permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; logging services, reading your history
and receiving reminders all work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. The only
moment an occasional full-screen ad can appear is **after you have saved a
service record**, which is the point at which you are finished. There is also an
optional rewarded video you can choose to watch to switch ads off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive anything from your log.** Google's processing is done as an independent
controller under its own policies:

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

Reminders are scheduled and shown **by your phone**, from data already on it.
Nothing is sent to us or through us to deliver one, and no reminder ever leaves
the device. If you deny the notification permission, the app keeps working and
simply does not post reminders.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.
- **Notifications** — to tell you when a service is due.
- **Run at startup** — so reminders you have already set survive a reboot.
  Without it, restarting your phone would silently cancel them.

It requests **no location, no Bluetooth, no camera, no photo or media access, no
storage permission, no contacts and no calendar.**

Five more permissions are merged into the final app package by the libraries the
app is built on, so the list Google Play shows you is longer than the four
above. They are the three Android Ad Services permissions, which come from the
Google Mobile Ads SDK, plus wake-lock and foreground-service, which come from
**both** that SDK and from AndroidX WorkManager — the component that runs the
daily due-date check. None of them is a permission Android stops to ask you
about, and none is used by any code we wrote.

## Children

This app is not directed at children and is intended for users aged 13 and over.
We do not knowingly collect personal information from children — as described
above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete your data** by clearing the app's storage or uninstalling it. Because
  the log lives only on your device, that removes it completely — there is no
  copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
