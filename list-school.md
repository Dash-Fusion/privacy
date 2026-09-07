---
layout: default
title: School — Privacy Policy
description: Privacy policy for the School Android app by Dash Fusion.
---

# School — Privacy Policy

**Effective date:** 2026-09-08
**Last updated:** 2026-09-08

## Summary

School is a planner: your timetable, your homework and exams, and your grades,
in one app. Everything you enter stays on your phone.

There is no account, no sign-up, no cloud, no sync and no server of ours
anywhere. **Nothing you type is uploaded** — not a subject name, not a teacher's
name, not a room number, not an assignment and not a single mark. There is
nowhere for any of it to go.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it comes from anything you entered.

## Who we are

- **App name:** School (Google Play: *School Planner: Timetable*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listschool`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Subjects** — their names, colours and any teacher or room you chose to note
  against them.
- **Your timetable** — the periods of your school day, and which subject is in
  which slot. Timetable changes are stored **with the date they take effect**,
  so switching to a new timetable next term does not rewrite what last term
  actually looked like. One-off changes to a single day are stored separately
  again, as overrides.
- **Terms and holidays** — the date ranges you entered.
- **Homework and exams** — their titles, any notes you wrote, which subject they
  belong to, when they are due, and when you ticked them off.
- **Grades** — your marks, the categories you put them in, their weights and
  their dates. **The averages are computed from those marks every time they are
  shown, never stored**, so correcting one mark corrects everything that depends
  on it and there is no second copy to go stale.
- **App preferences:** theme, Material You colour, which day your week starts
  on, your reminder setting, and when the rewarded ad-free window runs out.

That is the whole list. There is no name, no email, no school, no student
number, no contact and no location anywhere in it, because the app never asks
for any of them. If you type a teacher's name into a subject, it is stored
exactly as privately as everything else and is never transmitted.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind. Nobody at Dash Fusion
can see your timetable, your homework or your marks.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your school data is never copied into Google's backup service. The honest cost:
uninstalling the app, or losing the phone, loses it. The app has an **export**
that writes everything to a readable file you choose the location of — that file
is yours, and it is the intended way to keep a copy or move to a new phone.

## Reminders

The app can post **one optional reminder**, in the evening by default, about
what is due tomorrow. It is off until you switch it on, and switching it on is
what triggers Android's notification permission request. You choose the time.

To schedule it the app needs to run briefly when your phone restarts, which is
why it declares **`RECEIVE_BOOT_COMPLETED`**. That is all that permission does
here: without it, the reminder would stop after the first reboot and the switch
in Settings would go on claiming it was on.

The reminder is built on the device from your own homework list. Nothing about
it leaves the phone.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; the timetable, the homework list and
every grade calculation work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **when the last thing due today
has been ticked off**, so the screen behind it says you are finished — and not
every time even then. Ticking one of several is deliberately not that moment:
with four things due, finishing the first is the middle of your evening, not the
end of it. There is also an optional rewarded video you can choose to watch,
which removes ads for 24 hours; it is never forced and never interrupts
anything.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any subject, assignment, mark, note or anything else from inside the
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

- **Notifications (`POST_NOTIFICATIONS`)** — only if you switch the reminder on.
  Optional.
- **Run at startup (`RECEIVE_BOOT_COMPLETED`)** — so a reminder you switched on
  survives a reboot. Not a permission Android asks you about.
- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is all of them. The app requests **no camera, no microphone, no photo or
media access, no storage permission, no location, no contacts and no calendar**.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the ones
above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all from the Google Mobile Ads SDK. None is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is written for secondary-school students and older. It is not directed
at children under 13 and is not designed for use under the COPPA framework, and
it is listed on Google Play accordingly. We do not knowingly collect personal
information from children — as described above, we hold no personal data at all,
and nothing a student types into this app reaches us or anyone else.

## Your choices

- **Reminders:** off until you turn them on, and can be turned off again in
  Settings or in Android's own notification settings.
- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete anything** in the app — a mark, an assignment, a subject — or
  **delete everything** by clearing the app's storage or uninstalling it.
  Because your data lives only on your device, that removes it completely —
  there is no copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
