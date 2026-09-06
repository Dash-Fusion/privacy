---
layout: default
title: Hours — Privacy Policy
description: Privacy policy for the Hours Android app by Dash Fusion.
---

# Hours — Privacy Policy

**Effective date:** 2026-09-06
**Last updated:** 2026-09-06

## Summary

Hours is a timesheet for people who are paid by the hour. You clock in and out,
or type shifts in afterwards, and the app works out your week. All of that stays
on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere. We
never see where you work, when you work or what you are paid.

**The app does not know where you are.** Geofenced clock-in — starting the shift
when you arrive at work — is the flagship feature of the paid apps in this
category, and it is deliberately absent. It would need background location, the
most invasive permission Android grants, and your employer's address, which is
the one genuinely identifying thing a timesheet could hold. It also gets the
edges wrong in both directions, which for a timesheet means being paid for the
wrong number. Pressing a button takes half a second.

**The app never sends you a notification.** There is no notification permission
at all — see *What the app deliberately cannot do*.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything about your work.

## Who we are

- **App name:** Hours (Google Play: *Hours: Work Timesheet Log*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listhours`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your jobs** — the name you typed, an optional hourly rate and its currency
- **Your shifts** — when each one started and ended, as points in time; the
  unpaid break in minutes; and any note you added
- **App preferences:** which day your week starts on, your daily and weekly
  overtime thresholds, your overtime multiplier, your rounding rule, theme,
  Material You colour, and when the rewarded ad-free window runs out

That is the whole list. There is no name, no employer, no address, no
photograph, no location and no contact anywhere in it, because the app never
asks for any of them. The job name is a word you typed for your own benefit —
*The Anchor*, *Saturday market* — and the app has no idea what it refers to.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app also **opts out of Android's cloud backup and device-to-device
transfer**, so your hours are never copied into Google's backup service. That is
a deliberate trade and you should know which way it cuts: nothing about your
work is stored off your phone, and **uninstalling the app, or losing the phone,
loses it**. Use **Save a copy** before you switch phones — it is the intended
way to move your data, it is never behind an ad, and it is the file to attach to
an email if payroll ever disagrees with you.

## One phone, and we say so

This app is **one record kept on one device**. Nothing syncs. No manager can see
it, no colleague is invited, and nobody needs an account — because there are no
accounts at all.

That is a real limit and it is stated in the app as well as here, because
finding it out after installing would be worse.

## What the app deliberately cannot do

Worth stating plainly, because apps in this category commonly do these things:

- **It does not know where you are.** No location permission of any kind, and
  therefore no geofenced clock-in, no map of your week, and no record of your
  employer's address. See the summary for why that is a decision rather than a
  missing feature.
- **It never notifies you.** There is no notification permission, no channel and
  no scheduled work. The problem a reminder would solve — a clock you forgot to
  stop — is answered in the data instead: past sixteen hours the app stops
  believing a running shift and says so, which works with the app closed, with
  notifications denied, and on a phone that was switched off all night. The
  honest cost is that nothing taps you on the shoulder at half past five.
- **It does not use your camera and holds no photos.**
- **It does not have any accounts**, so there is nothing to sign up for, nothing
  to sign in to, and no password of yours anywhere.
- **It does not touch your calendar.** A shift is not an appointment.
- **It does not read your contacts.**
- **It does not talk to your employer, your payroll system or anyone else.**
  Nothing here is submitted anywhere. It is your own record, for your own use.

## Saving and restoring

You can save a copy of your jobs and shifts to a file you choose, and restore
one back. **A saved file leaves the app's protection**: it is written where you
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
app needs an internet connection at all; clocking in and out, the timesheet, the
overtime arithmetic and the pay estimate all work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. The only
moment an occasional full-screen ad can appear is **after you clock out** — the
end of a shift, and never the beginning of one. There is also an optional
rewarded video you can choose to watch to switch ads off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any shift, any rate, any job name or anything else about your work.**
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

## About the numbers in the app

The app adds up the times you recorded and applies the thresholds and the rate
you typed. That is arithmetic on your own figures, not employment advice and not
a legal document.

Overtime rules, break entitlements and rounding practices differ by country, by
industry and by contract. This app lets you describe yours; it does not know
what yours is, and it cannot tell you whether your employer is applying it
correctly. What it can do is show you your own record, in a form you can compare
with a payslip.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is all three of them, and there is no fourth. The app requests **no
location, no notifications, no camera, no contacts, no photo or media access, no
storage permission, no calendar and no exact-alarm permission**.

Five more permissions are merged into the final app package by the libraries the
app is built on, so the list Google Play shows you is longer than the three
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
