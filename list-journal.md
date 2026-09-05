---
layout: default
title: Diary with Lock — Privacy Policy
description: Privacy policy for the Diary with Lock Android app by Dash Fusion.
---

# Diary with Lock — Privacy Policy

**Effective date:** 2026-09-05
**Last updated:** 2026-09-05

## Summary

Diary with Lock is a diary. What you write stays on your phone, encrypted with
a key derived from your passphrase.

There is no account, no sign-up, no cloud, and no server of ours anywhere. We
cannot read your entries. That is not a promise about our intentions — we do
not have them, and there is nowhere for them to be sent.

The only data that leaves your device is what Google AdMob needs to show ads,
and **none of it is anything you wrote**.

## Who we are

- **App name:** Diary with Lock
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listjournal`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your entries** — the date, title, body, mood and tags
- **Photos you attach**, copied into the app's own storage
- **App preferences:** theme, Material You colour, whether writing prompts are
  shown, and when the rewarded ad-free window runs out

**Your entries and your attached photos are encrypted at rest**, with
AES-256-GCM. The key is derived from your passphrase (PBKDF2-HMAC-SHA256) and
is held **only in memory, only while the diary is unlocked**. It is not written
to a preference, not written to the database, and deliberately **not held in
the Android Keystore** — a key kept there would survive without your
passphrase, which would turn the passphrase back into a screen someone has to
get past rather than the thing your entries are encrypted with.

This is what makes the word "lock" mean something here: with the app locked,
the entries are unreadable to anyone holding the phone's file system.

**If you lose your passphrase, your entries cannot be recovered — by you or by
us.** There is deliberately no recovery question and no backdoor, because
either one would make the encryption worthless. The app says this plainly at
the moment you set the passphrase.

A photo you attach is **copied** into the app's private storage and encrypted
there. The app does not keep a reference to the picture in your gallery, so
deleting it from your gallery does not damage the entry, and no other app can
read the copy.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry.

The app opts out of Android cloud backup and device-to-device transfer, so your
diary is never copied into Google's backup service. Uninstalling the app
removes it completely.

## Exporting

You can export your diary to a file you choose. **An exported file leaves the
app's protection**: it is written where you point it, in a form other apps can
read. The app tells you this in the confirmation before it writes anything, so
the choice is yours and it is an informed one.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; writing, searching and reading your
diary work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**, and it
never interrupts you while you are writing. The only moment an occasional
full-screen ad can appear is **after you have saved an entry**, which is the
point at which you are finished. There is also an optional rewarded video you
can choose to watch to switch ads off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive anything you wrote, and it could not read it if it did** — the app never
sends your entries anywhere. Google's processing is done as an independent
controller under its own policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

### Consent (UMP)

Where required by law, the app shows Google's User Messaging Platform consent
form before ads are initialised, and records your choice. In the EEA and the UK
you are asked about personalised advertising; in covered US states you are
offered the opt-out required there. You can change your decision at any time
from **Settings → Ad privacy options**, and if you decline, every diary feature
continues to work exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no
database with your name in it and no way to identify you or your device. We do
not sell or share personal information, because we do not have any.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is everything the app itself asks for, and it requests **no storage
permission** — photos are chosen through Android's own photo picker, which
hands the app one picture and grants it nothing else — and **no camera, no
microphone, no contacts, no location, and no notifications**.

The Google Mobile Ads SDK merges a few more permissions into the final app
package: the Android Ad Services permissions, and the wake-lock and
foreground-service permissions its background worker declares. So the list
Google Play shows you is slightly longer than the two above. None of them is a
permission Android stops to ask you about, and none is used by anything we
wrote.

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
  the diary lives only on your device, that removes it completely — there is no
  copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
