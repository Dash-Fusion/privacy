---
layout: default
title: Red Letter — Privacy Policy
description: Privacy policy for the Red Letter Android app by Dash Fusion.
---

# Red Letter — Privacy Policy

**Effective date:** 2026-09-26
**Last updated:** 2026-09-26

## Summary

Red Letter is a period tracker that keeps your log on your phone. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any analytics
or tracking SDK. **Your period dates, flow, symptoms and notes are health
information. Red Letter stores them only on your phone and never sends them
anywhere** — not to us, not to Google, not to anyone. **A backup or CSV file you
save yourself is not encrypted**, so keep it somewhere private.

The app contains no code that can reach a server at all, apart from the
advertising SDK described below, which receives nothing from your log.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Red Letter (store listing: *Red Letter: Period Tracker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listperiod`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private
storage. It never leaves the device unless you save a backup or a CSV yourself.

- **Your periods:** the first day and the last day of each one (or no last day,
  while one is still going)
- **Your days:** for any day you log, the flow (spotting, light, medium or
  heavy), the symptoms you tapped, and your note
- **App preferences:** theme, wallpaper colours, whether reminders are on and
  when, whether the lock is on, and the ad state described below

Your cycle lengths, the estimate of your next period and every statistic are
worked out from your log at the moment you look at them; nothing derived is
stored.

**About this information.** Everything above is health information about you.
You type it in yourself. Red Letter keeps it only in its private database on
your phone and never transmits it.

The app explicitly opts out of Android cloud backup and device-to-device
transfer, so Android never copies your log to Google Drive or to another phone
without you choosing it. **That has a cost worth knowing: a new phone starts with
an empty log unless you restore a backup you saved.** The app says so in
Settings.

You can delete any period, change or remove what you logged on any day, use
**Settings → Delete everything**, or uninstall the app — Android removes the local database with it. A
backup or CSV file you saved elsewhere is yours, and is not touched by either.

We have no servers and no cloud storage. We cannot see your log and we cannot
recover it if you lose your device.

## Backups and CSV files

**Save a backup** and **Save as a CSV file** write a file where you choose, through
Android's own file picker. **These files are not encrypted**: anyone who can open
the file can read the health information in it, so keep it somewhere private.
**Restore a backup** reads a file you choose, the same way; the app keeps no
access to it afterwards.

## Privacy on the phone itself

- **Recent apps:** on Android 13 and later, the recent-apps screen never shows
  what is in Red Letter.
- **The optional lock** asks for your phone's own screen lock or fingerprint.
  The fingerprint never reaches the app — Android only tells it yes or no. While
  the lock is on, screenshots are blocked and the app is hidden in recent apps on
  every Android version. **The lock hides the app; it does not encrypt your log.**
- **Reminders** are off until you turn them on. On the lock screen they say only
  that your period may start in about 2 days, or "A reminder to log today" —
  never your symptoms, flow or notes.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only as you leave the History screen, never while you log —
plus an optional rewarded ad you can choose to watch to remove ads for 24 hours.
There are no banner ads. Ads are limited to content rated for teens. Google may
collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides
  for ads) and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network
  and performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your log**: no dates, no flow, no symptoms, no
notes and no keywords. Like any ad in any app, an ad request does name the app
it comes from. Google's handling of the data above is governed by Google's own
policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed. You
can change your answer at any time from **Settings → Advert privacy options**
inside the app. You can also opt out of personalised advertising via your
device's system settings (Android: **Settings → Privacy → Ads**).

## Consumer health data

Some laws — for example Washington's My Health My Data Act — give you rights
over health data that a business collects about you. **Dash Fusion collects no
consumer health data.** Your period dates, flow, symptoms and notes never leave
your phone through the app, so we never receive, share or sell them, and there
is nothing of yours on any server of ours to access, correct or delete.

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter
that phones home, no Firebase, and no custom telemetry. There is no HTTP client
anywhere in the app's own code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads. In airplane mode no ads load and every tracking feature still works.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads;
  used by AdMob as described above.
- **Notifications** — asked for only if you switch on a reminder, and used only to
  show those reminders on this phone.
- **Run at startup** (`RECEIVE_BOOT_COMPLETED`) — only so reminders you switched
  on are set again after your phone restarts.
- **Biometric** (`USE_BIOMETRIC`) — only for the optional lock. It reads nothing:
  Android checks your fingerprint or screen lock and tells the app yes or no.

Red Letter has no access to your location, contacts, messages, calendar, camera,
microphone, photos, files or health-platform data, and it asks for none of them. A
test reads the built app's own merged manifest on every run and fails the build
if that list ever changes.

## Children

Red Letter is not directed to children under 13. We do not knowingly collect data
from children — and, as above, we collect no personal data from anyone.

## Not medical advice

Red Letter is not a medical device and does not diagnose, treat, cure, or prevent
any medical condition. Consult a healthcare professional for medical advice,
diagnosis, or treatment.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **Reminders and lock** — Settings, both off until you turn them on
- **Delete your data** — delete a period or change a day inside the app, use
  Settings → Delete everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
