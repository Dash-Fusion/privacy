---
layout: default
title: Pourbook — Privacy Policy
description: Privacy policy for the Pourbook Android app by Dash Fusion.
---

# Pourbook — Privacy Policy

**Effective date:** 2026-10-19
**Last updated:** 2026-10-19

## Summary

Pourbook is a coffee journal that you fill in yourself: the coffees you buy, with a photo of the
bag if you add one, each brew you make with them, and the recipes worth repeating. We do **not**
create accounts, do **not** ask for your email, and do **not** ship any analytics or tracking SDK.
**Your coffees, brews, recipes and photos stay on your phone. Pourbook never sends them anywhere
and never reads your location. They leave the phone only if you save a backup or a CSV file where
you choose.** A backup file and a CSV file are plain files and are not encrypted.

**Pourbook has no location, camera or photo-library permission.** A photo comes through Android's
own photo picker, which hands the app only the picture you chose. Every number — ratios, how much
of a bag is left, cost per cup, averages — is worked out on the phone, so keeping the journal never
uses the internet. The app contains no code that can reach a server at all, apart from the
advertising SDK described below, which receives nothing from your journal.

If that's all you wanted to know, you're done. The sections below spell it out in detail.

## Who we are

- **App name:** Pourbook (store listing: *Pourbook: Coffee Brew Journal*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listcoffee`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your coffees:** each coffee's name and, if you add them, its roaster, origin, process, roast
  level, roast date, bag weight, the price you paid and a note; whether it is not opened yet, open
  or finished, and since when; the day you added it; and the photo of its bag.
- **Your brewers and grinders:** the names you give them.
- **Your recipes:** each recipe's name, method, weights, grind, temperature, time, its pours, the
  gear it uses, the coffee it is tied to if you tie it to one, and a note.
- **Your brews:** each brew's day, coffee, method and gear, the weights, grind, temperature and
  time, your rating, your tasting notes, whether you would make it again, and the recipe it came
  from.
- **Your photos:** a photo you add to a coffee is kept as the app's own smaller copy, a JPEG of at
  most 1,024 pixels on its longer side and at most 400,000 bytes. **The original picture is never
  stored, copied or changed**, and the app keeps no access to it after reading it.
- **The currency** your prices are written in.
- **App preferences:** the theme, wallpaper colours, the temperature unit, and the ad state: when
  a 24-hour ad-free period ends, and a count that decides when the next ad may show.
- **A form you are filling in** — what you typed and when a running brew timer was started — is
  kept by Android for the app if the phone closes it in the background, so you come back to it as
  it was. Android drops it when you close the app's task.

**Your journal, its numbers and its photos are kept here and nowhere else.** They leave the phone
only when you act: a backup you save carries your whole journal and every photo, and a CSV file
carries your brews or your coffees. Pourbook never sends them anywhere itself.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so Android
never copies your journal to Google Drive or to another phone. **A new phone starts with an empty
journal unless you restore a backup you saved.** The app says so in Settings.

You can delete a coffee (its photo and its brews go with it), a brew, a recipe or a piece of gear;
use **Settings → Delete everything**; or uninstall the app — Android removes the local data with
it. We have no servers and no cloud storage. We cannot see your journal and we cannot recover it
if you lose your device.

## Photos

- **Adding a photo** opens Android's own photo picker. You choose one picture; Android hands the
  app that picture and nothing else. **The app asks for no photo, media, storage or camera
  permission**, on any version of Android, and cannot see your other pictures. It has no camera of
  its own: your phone's camera app takes the photos, and the picker offers them.
- Each picture is read once, turned upright, made smaller and kept as described above. A copy
  picked on a form you then discarded is deleted with the form, and one left behind by a form that
  never came back is deleted a week later. A photo is never sent anywhere, and never shown to the
  advertising SDK.

## The brew timer

The stopwatch on the brew form runs inside the app only. It needs **no notification, no
background service, no wake lock and no permission**. While it runs, the app asks Android to keep
the screen on through the app's own window — a setting that ends the moment you leave the form or
stop the timer, and lets the phone sleep as soon as the app is not in front.

## CSV files and backups

- **A CSV of your brews** and **a CSV of your coffees** are written for a spreadsheet, where you
  choose, through Android's own file picker. **A CSV file is plain text and is not encrypted**:
  anyone who can open the file can read it. The app says so beside the buttons.
- **Save a backup** writes your whole journal — coffees, brews, recipes, gear and every photo — to
  a file where you choose, the same way. **A backup is a plain JSON file and is not encrypted**:
  anyone who can open the file can read it. The app says so beside the button.
- **Restore a backup** reads a file you choose, the same way, and asks before it replaces your
  journal. The file is read, not kept, and the app keeps no access to it afterwards.

Pourbook asks for **no storage permission** for any of this: files go through Android's own file
picker.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen interstitial ad —
only after you save a new brew or a new coffee, once its form has closed, **never while you type**,
never on the ratio calculator and never as the app opens — plus an optional rewarded ad you can
choose to watch to remove ads for 24 hours. There are no banner ads. Google may collect and
process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for ads) and
  other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and performance
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your journal**: no coffee, no roaster, no brew, no rating, no note,
no photo, no keyword and no content URL. Like any ad in any app, an ad request does name the app it
comes from. The approximate location above is Google's estimate from your internet address; it is
never your phone's location, which Pourbook cannot read. Google's handling of the data above is
governed by Google's own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's certified consent
form, and you choose whether personalised ads are allowed. You can change your answer at any time
from **Settings → Advert privacy options** inside the app. You can also opt out of personalised
advertising via your device's system settings (Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that phones home,
no Firebase, and no custom telemetry. There is no HTTP client anywhere in the app's own code, and
the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads. With no
  connection no ads load, and your coffees, brews, recipes, photos, the calculator, backups and CSV
  files still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used by AdMob as
  described above.

That is all of them. **Pourbook asks for no permission at runtime: Android never stops to ask you
about one.** It has no access to your location — no GPS, no fine or approximate location, no
background location — and none to your camera, photos, media, files, contacts, messages, calendar
or microphone, and it asks for none of them. It sends no notifications and asks for no
notification permission: there is no reminder.

A few more permissions are merged into the final app package by the libraries the app is built
on, so the list Google Play shows you is slightly longer than the one above. They are the Android
Ad Services permissions, from the Google Mobile Ads SDK; wake-lock and foreground-service, from
the Android scheduling library the ads SDK brings in; and one permission that only lets the app's
own parts talk to each other. None is a permission Android stops to ask you about, and none is
used by any code we wrote: Pourbook holds no wake lock and runs no foreground service of its own.
A test reads the built app's own merged manifest on every run and fails the build if that list
ever changes, or if any location, camera, media or notification permission appears in it.

## Children

Pourbook is a journal for adults who make coffee at home, and is intended for adults. It is not
directed to children under 13, and we do not knowingly collect data from children — and, as above,
we collect no personal data from anyone.

## A record, not advice

Pourbook writes down what you enter. It never tells you how a coffee should taste, whether a bag
is too fresh or past its best — it says only how long ago it was roasted — or how much coffee you
should drink; it counts no caffeine and makes no health claim of any kind; it has no "AI" and no
shop in it. A price is your own note of what you paid: the one thing done with it is that coffee's
own cost per cup, the price multiplied by the dose and divided by the bag's weight. The app never
adds prices together, never totals your spending and never buys or sells anything.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android system
  settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads. Nothing in the app
  is behind an ad
- **Photos** — add one to a coffee only if you want to; change or remove it at any time
- **Delete your data** — delete a coffee, a brew, a recipe or a piece of gear, use Settings →
  Delete everything, or uninstall the app
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update this
page and bump the "Last updated" date above. Material changes will be flagged in the app's release
notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
