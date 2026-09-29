---
layout: default
title: Nametide — Privacy Policy
description: Privacy policy for the Nametide Android app by Dash Fusion.
---

# Nametide — Privacy Policy

**Effective date:** 2026-09-29
**Last updated:** 2026-09-29

## Summary

Nametide is a baby name finder built on the US baby-name records. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any analytics
or tracking SDK. **Your shortlist, ratings, notes and No thanks list stay on your
phone. Nametide never sends them anywhere. They leave the phone only if you share
your shortlist through Android's share menu, to an app you choose, or save a
backup file where you choose.** A backup file is plain JSON and is not encrypted.

Every name and every number is inside the app, so searching, browsing and rating
never use the internet. The app contains no code that can reach a server at all,
apart from the advertising SDK described below, which receives nothing from your
lists.

If that's all you wanted to know, you're done. The sections below spell it out in
detail.

## Who we are

- **App name:** Nametide (store listing: *Nametide: Baby Names & Ideas*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listbabynames`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your lists:** for each name on your shortlist or your No thanks list, the name,
  which list it is on, the first person's rating, the second person's rating, your
  note, and when it was added and last changed. Nothing else.
- **App preferences:** the theme, wallpaper colours, whether two people rate names,
  the two people's names, the surname you add, the shortlist's order, and the ad
  state: when a 24-hour ad-free period ends, and a count that decides when the
  next ad may show.

**The names and their yearly counts** are part of the app itself: read-only, the
same for everyone who installs it, and never changed by anything you do.

The app explicitly opts out of Android cloud backup and device-to-device transfer,
so Android never copies your lists to Google Drive or to another phone. **A new
phone starts with an empty shortlist unless you restore a backup you saved.** The
app says so in Settings.

You can take a name off your shortlist or off No thanks, use **Settings → Delete
your lists**, or uninstall the app — Android removes the local data with it. We
have no servers and no cloud storage. We cannot see your lists and we cannot
recover them if you lose your device.

## Sharing and backups

- **Share the shortlist** builds plain text — your shortlisted names, with the
  surname if you added one, their ratings (under the two people's names, if two of
  you rate) and your notes — and hands it to Android's share menu. You pick the app
  it goes to. Nametide sends nothing itself, and sharing needs no permission.
- **Save a backup** writes both lists, every rating and note, and the settings that
  belong with them (whether two people rate, their names and the surname) to a file
  where you choose, through Android's own file picker. **A backup is a plain JSON
  file and is not encrypted**: anyone who can open the file can read it. The app
  says so beside the button.
- **Restore a backup** reads a file you choose, the same way. The file is read, not
  kept, and the app keeps no access to it afterwards.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen
interstitial ad — only as you go back from a name you have read, **never while you
search, browse or rate** — plus an optional rewarded ad you can choose to watch to
remove ads for 24 hours. There are no banner ads. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for
  ads) and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your lists**: no name you looked at, no shortlist, no
rating, no note and no keywords. Like any ad in any app, an ad request does name the
app it comes from. Google's handling of the data above is governed by Google's own
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
  With no connection no ads load, and searching, browsing and rating still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used
  by AdMob as described above.

That is all of them. **Nametide asks for no runtime permission at all**: Android
never stops to ask you about any permission for it. Sharing goes through Android's
share menu and backups through Android's own file picker, and neither needs one.
Nametide has no access to your location, contacts, messages, calendar, camera,
microphone, photos or files, and it asks for none of them.

A few more permissions are merged into the final app package by the libraries the app
is built on, so the list Google Play shows you is slightly longer than the one above.
They are the Android Ad Services permissions plus wake-lock and foreground-service, all
from the Google Mobile Ads SDK, and one permission that only lets the app's own parts
talk to each other. None is a permission Android stops to ask you about, and none is
used by any code we wrote. A test reads the built app's own merged manifest on every
run and fails the build if that list ever changes.

## Children

Nametide is for parents choosing a name, and is intended for adults. It is not
directed to children under 13, and we do not knowingly collect data from children —
and, as above, we collect no personal data from anyone.

## Where the names come from

The names and their counts are US baby-name data from the Social Security
Administration: babies born in the US, counted from applications for Social Security
cards by year of birth, 1880 to 2025. **Nametide is not affiliated with or endorsed
by the Social Security Administration.** The data ships inside the app, so Nametide
never downloads it and never asks anybody for it. The records are counts, not people:
to protect privacy, they leave out a name in any year it was given to fewer than 5
babies of one sex.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android
  system settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads.
  Nothing in the app is behind an ad
- **Your names in the app** — the surname and the two people's names can be changed
  in Settings at any time
- **Delete your data** — take a name off your shortlist or off No thanks, use Settings
  → Delete your lists, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will
update this page and bump the "Last updated" date above. Material changes will be
flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
