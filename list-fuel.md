---
layout: default
title: Fuel Log — Privacy Policy
description: Privacy policy for the Fuel Log Android app by Dash Fusion.
---

# Fuel Log — Privacy Policy

**Effective date:** 2026-09-10
**Last updated:** 2026-09-10

## Summary

Fuel Log answers one question: is this car drinking more than it used to. You
record a fill-up — the odometer, the litres, the cost — and the app works out
the consumption between one full tank and the next.

Everything you enter stays on your phone. There is no account, no sign-up, no
cloud and no sync. **Nothing you log is uploaded** — not a reading, not a price,
not a vehicle.

The app asks for **three permissions and no more**, and all three exist only so
ads can be fetched. **There is no location permission of any kind**, which is
worth saying plainly for a driving app.

## Who we are

- **App name:** Fuel Log (Google Play: *Fuel Log: MPG & Cost Tracker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listfuel`)

## This app does not know where you are

Most apps in this category ask for location, to find stations or fetch local
fuel prices. This one does not, and cannot:

- **No location permission** is declared, so Android has nothing to grant.
- **No GPS, no trip tracking, no journey recording, no background activity.**
- **No station finder and no price lookup**, which are the features that would
  need it.

Your odometer readings are numbers you typed. The app has no idea where they
were taken.

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Vehicles** — the name you give each one, and the units you want it thought
  about in: kilometres or miles, litres or either gallon.
- **Fill-ups** — the date, the odometer reading, the volume, the cost, whether
  it was a full tank or a part fill, whether a fill-up was missed before it, and
  any note you typed.
- **App preferences** — theme, Material You colour, which vehicle you last
  looked at, the window the summary covers, when the rewarded ad-free period
  runs out, and a count of finished tanks used only to decide how rarely to show
  an ad.

That is the whole list. There is no name, no email, no address, no registration
or number plate, no VIN and no location anywhere in it, because the app never
asks for any of them.

**Consumption figures are not stored at all.** They are worked out from your log
each time they are shown, which is why correcting an old odometer reading fixes
everything after it instead of leaving a stale number behind.

We hold **no copy of any of it**. There is no analytics SDK, no crash reporter
of our own, and no telemetry of any kind.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your log is never copied into Google's backup service. The honest cost:
uninstalling the app, or losing the phone, loses it. The export below is the
intended way to keep a copy.

## Your export

The app writes a **CSV file** of your fill-ups, and a full backup for moving to
a new phone. You choose where they go through Android's own file picker; the app
has no storage permission and cannot write anywhere you have not pointed it.

Those files are **ordinary readable files with no encryption**, deliberately, so
you can open them in a spreadsheet.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason it
needs an internet connection at all; every fill-up, figure, total and chart
works fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **when you close the tank summary
after logging a fill-up that produced a new consumption figure** — and not every
time even then. It never appears while you are entering numbers, and never on
the summary that explains why a figure could not be worked out.

There is also an optional rewarded video you can choose to watch, which removes
ads for 24 hours. Nothing in the app is locked behind it.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any reading, any price, any vehicle or anything else from inside the
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
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is the entire list. The app requests **no location, no camera, no
microphone, no photos or media, no storage permission, no contacts and no
activity recognition.** For an app about driving, the absence of the first one
is the point.

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

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete anything** in the app — a fill-up, a whole vehicle — or **delete it
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
