---
layout: default
title: List Savings — Privacy Policy
description: Privacy policy for the List Savings Android app by Dash Fusion.
---

# List Savings — Privacy Policy

**Effective date:** 2026-09-02
**Last updated:** 2026-09-02

## Summary

List Savings is an offline-first savings-goal tracker: name a goal, set a
target, log what you put aside, and the app shows how far along you are and
what you need to save each week or month to get there on time. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any
analytics or tracking SDK. Your goals, your deposits and every amount you
enter never leave your device. The only data that leaves your device is what
Google AdMob needs to serve ads.

The app has no connection to any bank, card or payment provider. It never
asks for an account number and has no way to see, move or verify any real
money — a goal is a number you typed and a log of amounts you typed.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Savings
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listsavings`)

## Data the app stores on your device

The following data is created and kept **locally** on your device, in a
database only this app can read. It never leaves the device unless you
explicitly export it.

- **Goals:** the name you typed, the target amount, the currency you chose for
  that goal, an optional start and target date, an optional note, a colour
  accent, and whether you have archived it
- **Deposits and withdrawals:** the amount, the date, and an optional note for
  each entry you log against a goal
- **App preferences:** theme and Material You colours, the currency to offer
  by default on the next goal, whether you pace by week or by month, whether
  archived goals are shown, and when the rewarded ad-free window runs out

Everything the app shows you — the running balance, percent complete, amount
remaining, the required-per-period figure and the ahead-of-plan or
behind-plan read — is calculated on the device from that data. Nothing is
uploaded, and no amount is sent anywhere.

You can export all of it as a JSON backup file at any time via
**Settings → Your data → Export backup**; you pick where the file goes with
Android's own file picker, and it is entirely under your control. Import
reads a file you choose, and nothing else.

The app explicitly opts out of Android cloud backup and device-to-device
transfer (`allowBackup="false"`), so your goals and deposits are not copied
into Google's backup service.

We have no servers and no cloud storage. We cannot see your goals and we
cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason
the app needs an internet connection at all; every savings feature works
fully offline.

The app shows **no banner ads and no ads inside your goal list**. What it
shows is an occasional full-screen ad between actions, and an optional
rewarded ad you can choose to watch to switch ads off for 24 hours. Nothing
plays uninvited.

To serve those ads, Google receives data from your device, which may include
your device's advertising identifier (`AD_ID`), coarse location inferred from
your IP address, device and app information, and ad-interaction data. This
processing is done by Google as an independent controller under its own
policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

We never send Google — or anyone else — your goals, your deposit amounts,
your notes or anything else you type into the app.

### Consent (UMP)

Where required by law, the app shows Google's User Messaging Platform consent
form before ads are initialised, and it records your choice. In the EEA and
the UK you are asked about personalised advertising; in covered US states you
are offered the opt-out required there. You can change your decision at any
time from **Settings → Ad privacy options**, and if you decline, the app
continues to work exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no
database with your name in it, no crash-reporting SDK of our own and no way
to identify you or your device. We do not sell or share personal information,
because we do not have any.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can
  fetch ads. Turning off Wi-Fi and mobile data simply means no ads load;
  every savings feature still works fully offline.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

Those are the only permissions the app itself declares. The Google Mobile Ads
SDK adds a small number of its own standard entries to the final installed
manifest (an ad-services group, a job-service binding, a wake lock and a
foreground-service declaration) which the SDK uses for ad delivery. The app
requests **no** camera, no storage, no contacts, no location and no
notification permission.

## Children

List Savings is not directed at children and is intended for users aged 13
and over. We do not knowingly collect personal information from children. If
you believe a child has provided us with personal information, contact us and
we will act on it — though as described above, we hold no personal data at
all.

## Your choices

- **Ad personalisation:** change your consent decision at any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's
  own settings, under **Settings → Google → Ads**.
- **Export your data** at any time via **Settings → Your data → Export
  backup**.
- **Delete your data** by deleting goals in the app, or by clearing the app's
  storage or uninstalling it. Because the data lives only on your device,
  that removes it completely and irreversibly — there is no copy anywhere
  else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in
the app's release notes on Google Play. This policy is versioned publicly in
the Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
