---
layout: default
title: Rentquill — Privacy Policy
description: Privacy policy for the Rentquill Android app by Dash Fusion.
---

# Rentquill — Privacy Policy

**Effective date:** 2026-09-30
**Last updated:** 2026-09-30

## Summary

Rentquill is a rent tracker for landlords with a handful of units. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any analytics
or tracking SDK. **Your properties, tenants, leases, payments and receipts stay on
your phone. Rentquill never sends them anywhere. They leave the phone only if you
share a receipt through Android's share menu, to an app you choose, or save a
backup or CSV file where you choose.** A backup file and a CSV file are plain files
and are not encrypted.

Every rent period, balance and receipt is worked out on the phone, so recording rent
never uses the internet. Rentquill keeps a record of rent and never moves money. The
app contains no code that can reach a server at all, apart from the advertising SDK
described below, which receives nothing from your record.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Rentquill (store listing: *Rentquill: Rent Tracker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listrent`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your record:** your properties (a name and an optional address) and their units
  (a name and a note); each lease — the tenant's name, and a phone number and an
  email address if you add them, the rent, monthly or weekly, the due day, the start
  and end dates, a note, and any rent changes; each payment — its date, amount, how
  it was paid (cash, transfer, cheque or other) and a note; and each receipt number,
  with what it was made for and when.
- **Your receipt details:** the currency, your name as it appears on receipts, and
  the next receipt number.
- **Receipts you make:** each one is a PDF written to the app's own cache when you
  make it, and deleted once it is a day old, the next time you open the app.
- **App preferences:** the theme, wallpaper colours, and the ad state: when a
  24-hour ad-free period ends, and a count that decides when the next ad may show.

**Your tenants' names, phone numbers and email addresses are kept here and nowhere
else.** They leave the phone only when you act: a tenant's name is on a receipt you
share and in a CSV file you save, and a backup you save carries names, phone numbers
and email addresses alike. Rentquill never sends them anywhere itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer,
so Android never copies your record to Google Drive or to another phone. **A new
phone starts with an empty record unless you restore a backup you saved.** The app
says so in Settings.

You can delete a payment, a lease, a unit or a property, use **Settings → Delete
everything**, or uninstall the app — Android removes the local data with it. Delete
everything keeps only your currency, your name on receipts and the next receipt
number, so a receipt number already given to a tenant is never given again. We have
no servers and no cloud storage. We cannot see your record and we cannot recover it
if you lose your device.

## Receipts, backups and CSV files

- **Share a receipt** makes a PDF for a payment or for a rent period — your name as
  you entered it, the tenant's name, the unit and property (with its address, if you
  added one), the amounts and dates, how the rent was paid and, on a payment's
  receipt, its note — and hands it to Android's share menu. You pick the app it goes
  to. A receipt never carries a tenant's phone number or email address. Rentquill
  sends nothing itself, and sharing needs no permission.
- **Save a backup** writes your whole record, your tenants' names, phone numbers and
  email addresses included, to a file where you choose, through Android's own file
  picker. **A backup is a plain JSON file and is not encrypted**: anyone who can open
  the file can read it. The app says so beside the button.
- **Export payments as CSV** and **Export rent periods as CSV** write a CSV file, for
  a spreadsheet or your accountant, where you choose, the same way. Each row names the
  property, the unit and the tenant, and no phone number or email address is in it.
  **A CSV file is plain text and is not encrypted either**: anyone who can open the
  file can read it. The app says so beside each button.
- **Restore a backup** reads a file you choose, the same way. The file is read, not
  kept, and the app keeps no access to it afterwards.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only as you leave a lease after recording a payment on it,
**never while you type** — plus an optional rewarded ad you can choose to watch to
remove ads for 24 hours. There are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for
  ads) and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your record**: no tenant, no amount, no address, no
note and no keywords. Like any ad in any app, an ad request does name the app it
comes from. Google's handling of the data above is governed by Google's own
policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed. You can
change your answer at any time from **Settings → Advert privacy options** inside the
app. You can also opt out of personalised advertising via your device's system
settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that
phones home, no Firebase, and no custom telemetry. There is no HTTP client anywhere in
the app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads.
  With no connection no ads load, and your record, receipts, backups and CSV files
  still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used
  by AdMob as described above.

That is all of them. **Rentquill asks for no runtime permission at all**: Android
never stops to ask you about any permission for it. Receipts go through Android's
share menu, and backups and CSV files through Android's own file picker, and none of
them needs one. Rentquill has no access to your location, contacts, messages,
calendar, camera, microphone, photos or files, and it asks for none of them. A
tenant's phone number and email address are typed by you, never read from your
contacts, and Rentquill never uses them to contact anyone.

A few more permissions are merged into the final app package by the libraries the app
is built on, so the list Google Play shows you is slightly longer than the one above.
They are the Android Ad Services permissions plus wake-lock and foreground-service, all
from the Google Mobile Ads SDK, and one permission that only lets the app's own parts
talk to each other. None is a permission Android stops to ask you about, and none is
used by any code we wrote. A test reads the built app's own merged manifest on every
run and fails the build if that list ever changes.

## Children

Rentquill is for landlords keeping their own record of rent, and is intended for
adults. It is not directed to children under 13, and we do not knowingly collect
data from children — and, as above, we collect no personal data from anyone.

## A record, not a payment

Rentquill writes down what you say was paid. **It never charges anyone, never moves
money and never connects to a bank**: there is no payment processing in the app, and
it never contacts a tenant. Every receipt it makes ends with the same line: *A record
of rent received, kept by the landlord. It is not a tax document.*

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android
  system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **Your name on receipts** — can be changed in Settings at any time
- **Delete your data** — delete a payment, a lease, a unit or a property, use Settings
  → Delete everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will
update this page and bump the "Last updated" date above. Material changes will be
flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
