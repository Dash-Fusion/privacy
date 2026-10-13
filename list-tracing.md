---
layout: default
title: Underdraw — Privacy Policy
description: Privacy policy for the Underdraw Android app by Dash Fusion.
---

# Underdraw — Privacy Policy

**Effective date:** 2026-10-13
**Last updated:** 2026-10-13

## Summary

Underdraw helps you trace a picture onto paper, in one of two ways: under the phone's camera with the picture over
the live view, or on the screen as a lightbox under thin paper. We do **not** create accounts, do **not** ask for
your email, and do **not** ship any analytics or tracking SDK.
- **The pictures you pick are copied into the app's private storage and never leave your phone.**
- **The camera's live picture is shown on your screen and never recorded, saved or sent.**

The app has no code that can reach a server at all, except the advertising SDK described below, and that SDK receives
nothing about your pictures or what the camera sees.

If that's all you wanted to know, you're done. The sections below spell it out in detail.

## Who we are

- **App name:** Underdraw (store listing: *Underdraw: Trace Drawing*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.tracing`)

## Data the app stores on your device

The following data is created and kept **locally**, in the app's private storage. The app never sends it anywhere.

- **Your pictures:** a copy of each picture you pick, at most 2,048 pixels on its longest side, and a small
  thumbnail for the list.
  - **Each copy is a fresh image.** From the original, the app reads only its orientation, so that a photo shows
    upright. Nothing else from the original's metadata is copied, such as where or with what camera it was taken.
- **Each picture's settings:** its name, when you added it and last opened it, its size, where you placed it, its
  opacity for each way of tracing, its grid, and its outline.
- **A removed picture** is kept aside until the next time the app starts, so its *Undo* can put it back. It is then
  deleted.
- **App preferences:**
  - the theme;
  - the way of tracing you used last;
  - whether you have already answered the camera question;
  - full brightness on or off;
  - the advert state described below.

There is no account and no contact information of yours anywhere in the app. The app turns off Android cloud backup
and device-to-device transfer, so that no picture can leave the phone that way. **That has a cost worth knowing: a
new phone starts Underdraw with no pictures.** The app says so in Settings.

To delete everything, you can:
- remove pictures in the app;
- clear the app's storage (Android **Settings → Apps → Underdraw → Storage → Clear storage**);
- or uninstall the app. Android removes the app's private storage with it.

We have no servers and no cloud storage. We cannot see your pictures, and we cannot recover them if you lose your
device.

## The pictures you pick

You choose a picture with **Android's own photo picker**. Phones without it use Android's document picker instead.
- The app sees only the one picture you choose. It copies that picture at once and keeps no access to the original
  afterwards.
- It needs no storage or photos permission, and it cannot browse your gallery.

Only trace pictures you have the right to copy: your own photos and drawings, or pictures whose owner allows it.

## The camera

The camera is used only if you choose to trace **Under the camera**, and only after you allow it.
- **It shows its live picture on your screen, under your picture, and that is all.** The app sets the camera up
  only for showing on the screen. It takes no photos, records no video, and does not analyse the camera's picture.
  The app never receives a frame, so nothing the camera sees can be kept or sent.
- The camera turns off when you leave the tracing screen.
- **The torch** comes on only when you switch it on, and goes off when you leave the screen.
- **On the screen**, the app raises the screen's brightness for that screen only, so the picture shows through
  your paper. Your phone's own brightness setting is not changed.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It may show an occasional full-screen ad:
- **only when you go back to your pictures from a picture you traced for two minutes or more**;
- never while you trace;
- never for the first picture you trace after opening the app;
- at most once for every third such return;
- never two within a quarter of an hour.

There is also an optional rewarded ad in Settings that turns full-screen ads off for 24 hours. There are no banner
ads, and nothing in the app is locked behind an ad.

Google may collect and process:
- Your device's **Advertising ID** (a resettable identifier that Android provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network information** that AdMob needs to serve
  and measure ads
- **Ad interaction events** (impressions, clicks)

**AdMob receives nothing about your pictures**: no picture, no picture's name, and nothing the camera sees. An ad
request carries no information from the app. Google's handling of the data above is governed by Google's own
policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's certified consent form, where you
choose whether personalised ads are allowed. You can change your answer at any time from **Settings → Advert
privacy options** in the app. You can also opt out of personalised advertising in your device's system settings
(Android: **Settings → Privacy → Ads**).

## Data we collect ourselves

**None.** We run no backend, and the app has no analytics SDK, no crash reporter that phones home, no Firebase and no
custom telemetry. The app also has no share or upload feature. There is no HTTP client anywhere in the app's own
code, and the app's tests fail if one is ever added.

## Permissions the app requests

- **Camera** - only for tracing *Under the camera*.
  - It is the only permission you are ever asked for. Android asks only when you first choose that way, after the
    app has said why.
  - If you refuse, the app traces on the screen instead, and it does not keep asking.
  - A phone without a back camera can still install the app and trace on the screen.
- **Internet / network state** - only so the Google Mobile Ads SDK can fetch ads. Without a connection no ads load,
  and both ways of tracing still work.
- **Advertising ID (`AD_ID`)** - required by Google Play for apps that serve ads; used by AdMob as described above.

**Those are the only permissions the app asks for.** Underdraw has no access to your location, microphone,
contacts, files or notifications, and it asks for none of them. A test reads the built app's merged manifest on every
run, and fails the build if that list ever changes.

## Children

Underdraw is not directed to children under 13 and is not designed for use under the COPPA framework. We do not
knowingly collect data from children.

## Your choices

- **Ad consent** - Settings → Advert privacy options (EEA/UK/Switzerland), or Android system settings → Privacy → Ads
- **A day without adverts** - the optional rewarded ad in Settings. Nothing else in the app is behind an ad
- **The camera** - allow or refuse it at any time in Android's app settings. Tracing on the screen never needs it
- **Delete your data** - remove pictures in the app, clear the app's storage in Android settings, or uninstall the
  app
- **Contact us** - dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we will update this page and bump the
"Last updated" date above. Material changes will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
