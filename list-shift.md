---
layout: default
title: Shift — Privacy Policy
description: Privacy policy for the Shift Android app by Dash Fusion.
---

# Shift — Privacy Policy

**Effective date:** 2026-09-08
**Last updated:** 2026-09-08

## Summary

Shift is a rota calendar. You describe your shift pattern once — four on, four
off, or whatever yours is — and the app works out every day from it, forwards
and backwards, with your hours and your pay.

Everything you enter stays on your phone. There is no account, no sign-up, no
cloud and no sync. **Your rota, your hours and your pay rates are never
uploaded**, and there is nowhere for them to go.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it comes from anything you entered.

## Who we are

- **App name:** Shift (Google Play: *Shift Calendar: Work Rota*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listshift`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your shift types** — their names, colours, and the time each one starts and
  ends.
- **Your patterns** — the repeating cycle itself, as a list of which shift falls
  on which day of the cycle.
- **Which pattern you are on, and from when** — stored with the date it takes
  effect, so changing your rota from next month leaves last month reading
  exactly as it did.
- **One-off changes** — a swap, a day off, an extra shift. These are stored
  separately from the pattern, so a swap survives a later rota change instead of
  being overwritten by it.
- **Your pay settings** — your hourly rate, any night and weekend rates, the
  hours that count as night, your currency and your pay period.
- **App preferences:** theme, Material You colour, which day your week starts
  on, your reminder setting, and when the rewarded ad-free window runs out.

That is the whole list. **No day of your calendar is stored as a row.** The
shift you are on for any date is computed from the pattern and the date it was
anchored to, which is why the calendar can show you a year ago and a year ahead
without ever having generated them.

There is no name, no email, no employer, no workplace, no location and no
contact anywhere in it, because the app never asks for any of them. If you name
a shift type after your ward, your site or your team, that text is stored
exactly as privately as everything else and is never transmitted.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind. Nobody at Dash Fusion
can see your rota, your hours or what you earn.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your rota is never copied into Google's backup service. The honest cost:
uninstalling the app, or losing the phone, loses it. The app has an **export**
that writes everything to a readable file you choose the location of — that file
is yours, and it is the intended way to keep a copy or move to a new phone.

## Sharing your rota

The calendar and the pay screen each offer **Copy** and **Share**, which put a
plain-text version of the period on screen onto your clipboard or into
Android's own share sheet. That happens only when you tap it, it contains only
what is already on the screen in front of you, and it goes wherever *you* send
it. **Once it leaves the app it is outside this policy.** Nothing is shared
automatically, and nothing is sent to us.

## Reminders

The app can post **one optional reminder** before a shift, at a lead time you
choose. It is off until you switch it on, and switching it on is what triggers
Android's notification permission request.

To schedule it the app needs to run briefly when your phone restarts, which is
why it declares **`RECEIVE_BOOT_COMPLETED`**. That is all that permission does
here: without it, the reminder would stop after the first reboot and the switch
in Settings would go on claiming it was on.

The reminder is worked out on the device from your own rota. Nothing about it
leaves the phone.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; the calendar, the hours and every pay
calculation work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **after you have copied or shared
a rota** — after the text is on your clipboard or the share sheet has opened,
never between the tap and the copy — and not every time even then. Simply
looking at your calendar, paging between months, or saving a rota never shows
one. There is also an optional rewarded video you can choose to watch, which
removes ads for 24 hours; it is never forced and never interrupts anything.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive your rota, your hours, your pay rates or anything else from inside the
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

- **Notifications (`POST_NOTIFICATIONS`)** — only if you switch the shift
  reminder on. Optional.
- **Run at startup (`RECEIVE_BOOT_COMPLETED`)** — so a reminder you switched on
  survives a reboot. Not a permission Android asks you about.
- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is all of them. The app requests **no calendar access, no camera, no
microphone, no photo or media access, no storage permission, no location and no
contacts**. In particular it does **not** read or write your device's calendar:
your rota lives inside this app only.

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

- **Reminders:** off until you turn them on, and can be turned off again in
  Settings or in Android's own notification settings.
- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete anything** in the app — a shift type, a pattern, a single day's
  change — or **delete everything** by clearing the app's storage or
  uninstalling it. Because your data lives only on your device, that removes it
  completely — there is no copy anywhere else, and no deletion request to send
  us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
