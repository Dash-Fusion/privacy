---
layout: default
title: Pencil In — Privacy Policy
description: Privacy policy for the Pencil In Android app by Dash Fusion.
---

# Pencil In — Privacy Policy

**Effective date:** 2026-09-25
**Last updated:** 2026-09-25

## Summary

Pencil In is an offline appointment book for people who work for themselves. We
do **not** create accounts, do **not** ask for your email, and do **not** ship any
analytics or tracking SDK. **Client names, phone numbers and notes are personal
data about your clients. Pencil In stores them only on your phone and never sends
them anywhere.** Your services, appointments and earnings stay on your phone too.
The app contains no code that can reach a server at all, apart from the advertising
SDK described below.

It is not an online booking system: your clients never see it, and nothing is
synced anywhere.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Pencil In (store listing: *Pencil In: Appointment Book*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listappointments`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device unless you save a backup or a CSV yourself.

- **Your clients:** name, phone number if you add one, and your notes about them
- **Your services:** name, usual length, and usual price with its currency
- **Your appointments:** which client and service, a copy of the service's name,
  length and price at the moment you booked it, the start time and the time zone
  it was booked in, the length, the price, the status (booked, done, no-show or
  cancelled), and your note
- **App preferences:** theme, the currency you chose, your opening hours, whether
  reminders are on and how long before, and the ad state described below

Earnings, no-show counts and every other total are worked out from the
appointments at the moment you look at them; nothing derived is stored.

**About your clients' details.** A client's name, phone number and notes are
personal data about someone other than you. You type them in, or copy them from
one contact you pick yourself in Android's own contact picker. Pencil In keeps
them only in its private database on your phone and never transmits them. It is
your responsibility, as the person keeping the book, to hold them the way your
clients would expect.

The app explicitly opts out of Android cloud backup and device-to-device
transfer. **That has a cost worth knowing: a new phone starts with an empty book
unless you restore a backup.** The app says so in Settings.

You can delete a client, a service or an appointment inside the app, delete
everything with **Settings → Delete everything**, or uninstall the app — Android
removes the local database with it. A backup or CSV file you saved elsewhere is
yours, and is not touched by either.

We have no servers and no cloud storage. We cannot see your book and we cannot
recover it if you lose your device.

## What the app reads, and does not keep

- **One contact, when you pick one.** Android's contact picker gives the app the
  name and phone number of the one contact you chose, which it copies into the
  client form. It keeps no link to the contact. Pencil In never asks for
  permission to read your contacts, so it cannot see any other contact.
- **A backup file, when you restore one**, chosen by you in Android's own file
  picker. Access ends when the restore is done.

## What the app hands to other apps, only when you ask

- **Confirm by message** opens your phone's own messaging app with a short
  confirmation already written. You decide whether to send it. Pencil In sends
  nothing itself and cannot send a message.
- **Save a backup** and **Save these appointments as a CSV** write a file where you
  choose, through Android's own file picker.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only as you leave the Earnings screen, never while you book,
confirm or mark an appointment — plus an optional rewarded ad you can choose to
watch to remove ads for 24 hours. There are no banner ads. Google may collect and
process:

- Your device's **Advertising ID** (a resettable identifier that Android provides
  for ads) and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network
  and performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your clients, their phone numbers or notes, your
services, your appointments or your earnings. Google's handling of the data above
is governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed. You
can change your answer at any time from **Settings → Advert privacy options**
inside the app. You can also opt out of personalised advertising via your
device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter
that phones home, no Firebase, and no custom telemetry. There is no HTTP client
anywhere in the app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads. In airplane mode no ads load and every appointment-book feature still
  works.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads;
  used by AdMob as described above.
- **Notifications** — asked for only if you switch on **Remind me before
  appointments**, and used only to show those reminders on this phone. Reminders
  are off until you turn them on.
- **Run at startup** (`RECEIVE_BOOT_COMPLETED`) — only so reminders you switched
  on are set again after your phone restarts.

Pencil In has no access to your contacts list, messages, calendar, location,
camera, microphone, photos or files, and it asks for none of them. A test reads
the built app's own merged manifest on every run and fails the build if that list
ever changes.

## Children

Pencil In is a business tool for adults and is not directed to children under 13.
It is not designed for use under the COPPA framework. We do not knowingly collect
data from children.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **Reminders** — Settings → Remind me before appointments, off until you turn it
  on
- **Delete your data** — delete a client, service or appointment inside the app,
  use Settings → Delete everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
