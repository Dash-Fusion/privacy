---
layout: default
title: List Split — Privacy Policy
description: Privacy policy for the List Split Android app by Dash Fusion.
---

# List Split — Privacy Policy

**Effective date:** 2026-09-01
**Last updated:** 2026-09-01

## Summary

List Split is an offline-first group expense splitter: make a group, add the
people in it, log what each person paid, and the app works out the balances
and the shortest list of payments that clears everybody. We do **not** create
accounts, do **not** ask for your email, and do **not** ship any analytics or
tracking SDK. Your groups, the people in them and every amount you enter never
leave your device. The only data that leaves your device is what Google AdMob
needs to serve ads.

Nobody has to install anything to be *in* a group — a member is simply a name
you typed. The app never reads your contacts and never invites anyone.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Split
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listsplit`)

## Data the app stores on your device

The following data is created and kept **locally** on your device, in a
database only this app can read. It never leaves the device unless you
explicitly export it.

- **Groups:** the group name and the currency you chose for it
- **People in a group:** just the name you typed, and its position in the
  group. There is no field for an email address, a phone number or any other
  contact detail, and the app never reads them from anywhere else
- **Expenses:** a description, the amount, who paid, the date, whether it is a
  spend or a settlement transfer, which split mode was used (equally, exact
  amounts, shares or percentages) and the per-person figures you entered for
  that split
- **App preferences:** theme and Material You colours, the currency you last
  used when creating a group, and when the rewarded ad-free window runs out

Everything the app shows you — balances, the settle-up plan, totals — is
calculated on the device from that data. Nothing is uploaded, and no amount
is sent anywhere.

You can export all of it as a JSON backup file at any time via
**Settings → Your data → Export backup**; you pick where the file goes with
Android's own file picker, and it is entirely under your control.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so your groups and expenses are not copied into Google's backup
service.

We have no servers and no cloud storage. We cannot see your groups and we
cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads at two natural endings — after the expense editor was closed
back to the group, or after a group was closed back to the groups list — plus
an optional rewarded ad that you can choose to watch to remove ads for 24
hours. There are **no banner ads and no native ads**, nothing interrupts you
while you are entering an expense, and **no ad ever appears on the balances or
settle-up screen**. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your groups, the names of the people in them, your
expenses, your amounts or your preferences. Google's handling of the data
above is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed.
You can change your answer at any time from **Settings → Ads → Ad privacy
options** inside the app. You can also opt out of personalised advertising via
your device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash
reporter that phones home, no Firebase, and no custom telemetry. We don't log
app usage anywhere we can read it.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can
  fetch ads. Disabling Wi-Fi/data simply means no ads load; groups, people,
  expenses, every split mode, balances, the settlement, export and import all
  keep working in airplane mode.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is the complete list. The app requests **no notification permission**,
sets no alarms and schedules no background work — it has no reminders of any
kind. It does **not** hold access to your location, contacts, camera,
microphone, sensors or files. Choosing where to save a backup, or which file
to import, uses Android's own file picker — the app only ever sees the single
file you pick.

## Children

List Split is not directed to children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect data from children.

## Your choices

- **Ad consent** — Settings → Ads → Ad privacy options (EEA/UK/Switzerland),
  or Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without
  ads. Nothing else in the app is behind an ad: every split mode, the
  balances, the settle-up plan, export and import are all free
- **Export your data** — Settings → Your data → Export backup (writes a JSON
  file you control, carrying every group, person and expense)
- **Delete your data** — delete a single expense with **Delete expense**, or a
  whole group with **Delete group**, which removes that group together with
  everyone in it and every expense it holds. Importing a backup
  (**Settings → Your data → Import backup**) replaces every group currently on
  the device. To remove everything at once, uninstall the app — Android
  deletes the local database with it — or use Android's own
  **Settings → Apps → List Split → Storage → Clear data**
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material
changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
