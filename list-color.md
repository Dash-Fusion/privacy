---
layout: default
title: Color Patch — Privacy Policy
description: Privacy policy for the Color Patch Android app by Dash Fusion.
---

# Color Patch — Privacy Policy

**Effective date:** 2026-09-17
**Last updated:** 2026-09-17

## Summary

Color Patch reads a colour off a surface with your camera. It averages a small
square rather than a single pixel, tells you how much that square varied, and
can correct for the colour of the light if you show it a sheet of white paper.
You save colours into palettes and read them as HEX, RGB and HSL.

**The camera is used as an instrument, not as a camera.** Frames are read for
the colour of the square at the centre and thrown away: nothing is recorded, no
photo is taken, no file is written, and **no frame ever leaves the process** —
let alone the phone.

There is no account, no sign-up, no cloud and no server of ours anywhere. Your
palettes live on your phone. The only data that leaves your device is what
Google AdMob needs to show ads, and **no colour, palette or camera frame is any
part of that**.

It is **not a colorimeter**, and it does not claim to match a paint code. That
is a statement about what the app measures, not about privacy, but it is the
same habit: the app says what it actually does.

## Who we are

- **App name:** Color Patch (listed on Google Play as *Color Patch: Picker &
  Palette*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listcolor`)

## What the app stores on your device

All of the following is created and kept **locally**, in a database only this
app can read, and never leaves your device unless you export it yourself:

- **Your palettes:** the name you gave each one, the order you put them in, and
  when you made them
- **Your saved colours:** the red, green and blue values measured, when each
  one was taken, whether it came from the camera or from a picture, how much
  the patch varied, how much of it was clipped, which white reference was in
  force at the time, and any note you typed
- **App preferences:** your theme choice, when the app was first opened, when
  the rewarded ad-free window runs out, and a count the app uses to space out
  ads

That is the whole list. There is no name, no email, no location and no contact
anywhere in it, because the app never asks for any of them. Nothing the app can
work out is stored either — the HEX, the HSL, the nearest colour name and the
contrast ratio are all computed from the red, green and blue values when a
screen shows them.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind.

The app **opts out of Android cloud backup and device-to-device transfer**, so
your palettes are not copied into Google's backup service.

**Consequence, stated honestly:** because the data exists only on your phone, we
cannot recover it if you lose the device or uninstall the app. Use **Settings →
Save a backup file** to write a copy yourself; the file goes wherever you point
Android's own file picker, and it is then entirely under your control.

## The camera

The camera is the only runtime permission this app asks for, and it is asked
for only when you first open the picking screen.

- Frames are analysed **in memory, on your device**, for the average colour of
  a small square at the centre of the preview.
- **Nothing is recorded.** No photo is taken, no video is captured, no image
  file is written, and no frame is sent anywhere. What survives a reading is a
  set of numbers you chose to save.
- The preview stops when you leave the picking screen.
- The camera is declared **not required**, so the app installs and works on a
  device without one, through the picture path below.
- If you decline the permission, or withdraw it later in Android's settings,
  every other part of the app — pictures, palettes, HEX/RGB/HSL, the nearest
  colour name and the contrast check — still works.

## Pictures

You can also take a colour out of a picture you already have. That goes through
**Android's own photo picker**, which hands this app the single image you chose
and nothing else.

**The app holds no photo or storage permission on any API level.** It never
reads your gallery, and it cannot: a permission to read your photo library
would be a much larger request for a much smaller reason. The picked image is
decoded in memory to read the colour and is not kept.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; measuring, saving, converting and
comparing colours all work fully offline.

The app shows **no banner ads, no native ads and no ad on launch**. What it
shows is an occasional full-screen ad at one of three moments — closing a
colour's page back to its palette, closing a palette back to the palette list,
or closing the contrast check — all of which are putting saved work down.
**Measuring a colour is never interrupted, and neither is copying a value.**
There is also an optional rewarded ad you can choose to watch to switch ads off
for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any camera frame, any picture, any colour you measured, any palette or
any note** — the app never sends those anywhere, and no ad targeting here is
based on them. Google's processing is done as an independent controller under
its own policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

### Consent (UMP)

Where required by law, the app shows Google's User Messaging Platform consent
form before ads are initialised, and records your choice. In the EEA and the UK
you are asked about personalised advertising; in covered US states you are
offered the opt-out required there. You can change your decision at any time
from **Settings → Advert privacy options**, and if you decline, every measuring,
palette and contrast feature continues to work exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no
database with your name in it, and no way to identify you or your device. We do
not sell or share personal information, because we do not have any.

## Permissions the app requests

- **Camera** — the instrument. Used only while you are on the picking screen, to
  read the colour of the square at the centre of the preview. Frames are never
  stored, never written to a file and never transmitted. This is the **only**
  runtime permission in the app.
- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads. Turning off Wi-Fi and mobile data means no ads load; every colour feature
  still works.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve ads;
  used by AdMob as described above.

That is all four of them. The app requests **no photo or media access, no
storage permission, no location, no microphone, no contacts, no calendar and no
notification permission**. Nothing in it runs when the app is not in front of
you: there are no notifications, no alarms and no background work.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is slightly longer than
the four above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all from the Google Mobile Ads SDK. None is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect personal information from
children — as described above, we hold no personal data at all.

## Your choices

- **Camera access:** grant or withdraw it any time in Android's settings, under
  **Settings → Apps → Color Patch → Permissions**. The app keeps working without
  it.
- **Ad personalisation:** change your consent decision any time via **Settings →
  Advert privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Export your data** any time via **Settings → Save a backup file**, and bring
  it back with **Settings → Restore from a file**.
- **Delete your data** by deleting colours and palettes in the app, or by
  clearing the app's storage or uninstalling it. Because your palettes live only
  on your device, that removes them completely and irreversibly — there is no
  copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
