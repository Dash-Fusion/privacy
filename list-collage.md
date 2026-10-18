---
layout: default
title: Muntin — Privacy Policy
description: Privacy policy for the Muntin Android app by Dash Fusion.
---

# Muntin — Privacy Policy

**Effective date:** 2026-10-17
**Last updated:** 2026-10-18

## Summary

Muntin puts two to nine of your photos together into one picture: a layout made for that many,
each photo framed in its cell, and the shape, spacing, border, corners and background you
choose. We do **not** create accounts, do **not** ask for your email, and do **not** ship any
analytics or tracking SDK. **Your photos stay on your phone. Muntin keeps its own copies of the
photos in your collage in progress, in its private storage, until you start a new collage, and
never sends them anywhere. A picture leaves the phone only if you save it or share it.**

**Muntin has no photo-library, storage, camera or location permission.** Photos come through
Android's own photo picker, which hands the app only the pictures you chose. Every collage is
drawn on the phone, so making one never uses the internet. The app contains no code that can
reach a server at all, apart from the advertising SDK described below, which receives nothing
from your photos.

If that's all you wanted to know, you're done. The sections below spell it out in detail.

## Who we are

- **App name:** Muntin (store listing: *Muntin: Photo Collage Maker*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listcollage`)

## Data the app stores on your device

The following is created and kept **locally**, in the app's private storage:

- **Your collage in progress:** its layout; its shape and style (the shape, spacing, border,
  corners, background colour, picture size and file type); each cell's photo and how it is
  framed (moved, zoomed, turned or flipped); and whether it has been saved or shared since it
  last changed. There is one collage in progress at a time.
- **The app's own copy of each photo in it:** the picture turned upright and made no larger than
  the largest picture the app makes (3,600 pixels on its longer side), kept as a JPEG. **The copy
  carries no EXIF data and no location**: it is a new file made from the picture's pixels. **The
  original photo is never changed**, and the app keeps no access to it after reading it once.
- **Copies handed to the share sheet:** when you share a collage, the picture is written to the
  app's own cache so that the app you choose can read it. Each of these copies is deleted about
  an hour after it was made, at your next share or the next time the app starts.
- **App preferences:** the theme, wallpaper colours, and the ad state: when a 24-hour ad-free
  period ends, and a count that decides when the next ad may show.

**How long they stay:** your collage in progress and the copies of its photos stay until you
start a new collage (Muntin asks first) or uninstall the app. A photo you take out of the
collage, or replace with another, keeps its copy until the app next starts or you start a new
collage, so that its Undo always has the photo to put back; at those moments the app removes every
copy the collage no longer uses.

The app explicitly opts out of Android cloud backup and device-to-device transfer, so Android
never copies your collage or its photos to Google Drive or to another phone. **A new phone
starts with no collage in progress**; the pictures you saved are in your gallery, where your own
backup finds them.

We have no servers and no cloud storage. We cannot see your photos or your collages, and we
cannot recover them if you lose your device.

## Photos

- **Choosing photos** opens Android's own photo picker. Android hands the app the pictures you
  chose and nothing else. **The app asks for no photo, media, storage or camera permission**, on
  any version of Android, and cannot see your other pictures.
- Each picture is read once, turned upright, made smaller where it is larger than the app needs,
  and kept as described above. A picture that cannot be read is left out, and the app says so.
- A photo is never sent anywhere, and never shown to the advertising SDK.

## Saving and sharing

- **Save** writes your collage as a new picture into your phone's gallery: on Android 10 and
  later into its own *Muntin* folder in Pictures, and on Android 7 to 9 where you choose,
  through Android's own file picker. Neither needs a permission.
- **Share** hands a copy of the picture to the app you choose in Android's share sheet. Muntin
  sends it nowhere else.
- **A saved or shared picture is a new file** — a JPEG or a PNG drawn from your collage — with
  **no EXIF data, no location and no camera details** from the photos in it.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows an occasional full-screen interstitial ad
— only after you have saved or shared a collage, once the app has said where it went, **never
while you are making a collage** and never as the app opens — plus an optional rewarded ad you
can choose to watch to remove ads for 24 hours. There are no banner ads. Google may collect and
process:

- Your device's **Advertising ID** (a resettable identifier that Android provides for ads)
  and other device identifiers
- **Approximate location** (inferred from your IP address) and **device, network and
  performance information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing from your collages**: no photo, no layout, no keyword and no content
URL. Like any ad in any app, an ad request does name the app it comes from. The approximate
location above is Google's estimate from your internet address; it is never your phone's
location, which Muntin cannot read. Google's handling of the data above is governed by Google's
own policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's certified consent
form, and you choose whether personalised ads are allowed. You can change your answer at any
time from **Settings → Advert privacy options** inside the app. You can also opt out of
personalised advertising via your device's system settings (Android: **Settings → Privacy →
Ads**).

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash reporter that phones
home, no Firebase, and no custom telemetry. There is no HTTP client anywhere in the app's own
code, and the build fails if one is ever added.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch ads. With no
  connection no ads load, and making, saving and sharing collages still work.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads; used by
  AdMob as described above.

That is all of them. **Muntin asks for no permission at runtime: Android never stops to ask you
about one.** It has no access to your location — no GPS, no fine or approximate location, no
background location — and none to your camera, photo library, media, files, contacts,
messages, calendar or microphone, and it asks for none of them. It sends no notifications and
asks for no notification permission.

A few more permissions are merged into the final app package by the libraries the app is built
on, so the list Google Play shows you is slightly longer than the one above. They are the
Android Ad Services permissions, from the Google Mobile Ads SDK; wake-lock and
foreground-service, from the Android scheduling library the ads SDK brings in; and one
permission that only lets the app's own parts talk to each other. None is a permission Android
stops to ask you about, and none is used by any code we wrote: Muntin holds no wake lock and
runs no foreground service of its own. A test reads the built app's own merged manifest on
every run and fails the build if that list ever changes, or if any location, camera, storage or
media permission appears in it.

## Children

Muntin is a tool for adults who put their own photos together into one picture, and is intended
for adults. It is not directed to children under 13, and we do not knowingly collect data from
children — and, as above, we collect no personal data from anyone.

## Your choices

- **Ad consent** — Settings → Advert privacy options (EEA/UK/Switzerland), or Android system
  settings → Privacy → Ads
- **Ad-free period** — watch one optional rewarded ad for 24 hours without ads. Nothing in the
  app is behind an ad
- **Your collage** — take any photo out of it at any time; *New collage* removes the collage in
  progress and the app's copies of its photos (your original photos stay in your gallery)
- **Delete your data** — start a new collage, or uninstall the app: Android removes the app's
  local data with it. Pictures you saved stay in your gallery until you delete them there
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update this
page and bump the "Last updated" date above. Material changes will be flagged in the app's
release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
