---
layout: default
title: Gift — Privacy Policy
description: Privacy policy for the Gift Android app by Dash Fusion.
---

# Gift — Privacy Policy

**Effective date:** 2026-09-08
**Last updated:** 2026-09-08

## Summary

Gift remembers what you gave, to whom, and in which year. You keep a plan per
person per occasion, jot down ideas, mark what you picked and bought, set a
budget, and next December you can see what you gave last time.

Everything you enter stays on your phone. There is no account, no sign-up, no
cloud and no sync. **Nothing you type is uploaded** — not a name, not a gift,
not a price. There is nowhere for it to go.

**A gift list is a secret**, and this app treats it as one. It hides its own
contents from Android's app-switcher by default, so the person you are buying
for cannot read your ideas over your shoulder when you swap apps. The
[What this app can and cannot protect you from](#what-this-app-can-and-cannot-protect-you-from)
section is honest about how far that goes.

## Who we are

- **App name:** Gift (Google Play: *Gift List Planner & Budget*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listgift`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **People** — the names you type. Only what you type: the app never reads your
  contacts, and it holds no contacts permission for Android to grant.
- **Occasions** — Christmas, a birthday, whatever you add.
- **Plans** — a person, an occasion and a year together, with a budget and the
  currency you chose for it.
- **Gifts** — the idea, its state (idea, picked, bought, given), an optional
  price, and any note.
- **App preferences:** theme, Material You colour, your default currency,
  whether to hide the app from the recents screen, and when the rewarded ad-free
  window runs out.

That is the whole list. There is no email, no address, no phone number, no
contact and no location anywhere in it, because the app never asks for any of
them. A price is stored as a whole number of minor units — pence, cents — so it
is exactly the figure you typed and nothing is silently rounded.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind. Nobody at Dash Fusion
can see who you buy for or what you spend.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your lists are never copied into Google's backup service. The honest cost:
uninstalling the app, or losing the phone, loses them. The app has an **export**
that writes everything to a readable file you choose the location of — that file
is yours, and it is the intended way to keep a copy or move to a new phone.

## What this app can and cannot protect you from

This is the section worth reading, because a gift list has a threat model most
apps do not: **the person it is about may pick up your phone.**

**What it does.** The app sets Android's `FLAG_SECURE` on its own window by
default. That means its contents do not appear in the app-switcher preview, and
screenshots and screen recordings of it are blocked by the operating system. You
can turn this off in Settings if you would rather be able to screenshot your own
list.

**What it does not do, and will not pretend to.**

- **There is no PIN, password or biometric lock.** Anyone who can unlock your
  phone can open the app and read everything in it.
- `FLAG_SECURE` is a **shoulder-surfing** measure, not a security boundary. It
  stops a glance at the recents screen; it does not stop somebody who has your
  unlocked phone in their hand.
- The export file you create is **an ordinary readable file** wherever you put
  it, with no encryption. That is deliberate — it is your data and you should be
  able to open it — but it means where you save it matters.

If you need your list to survive somebody actively looking for it, this app is
not the tool for that, and we would rather say so than imply protection it does
not provide.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; every list, budget, total and year of
history works fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **when a gift stops being a
maybe** — the first time you mark one as picked or beyond — and not every time
even then. It never appears twice for the same gift, never when you are simply
looking something up, and never when you record a purchase.

There is also an optional rewarded video you can choose to watch, which removes
ads for 24 hours; it is never forced and never interrupts anything.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any name, any gift, any price or anything else from inside the app.**
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

That is the whole list. The app requests **no contacts, no calendar, no camera,
no microphone, no photo or media access, no storage permission, no location and
no notifications**. The absence of contacts is deliberate and worth stating: a
gift app is the obvious place to ask for your address book, and this one does
not.

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

- **Hide from recents:** on by default, and switchable in Settings.
- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete anything** in the app — a gift, a plan, a person — or **delete it
  all** by clearing the app's storage or uninstalling it. Because your lists
  live only on your device, that removes them completely: there is no copy
  anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
