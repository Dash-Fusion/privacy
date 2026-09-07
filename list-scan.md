---
layout: default
title: Scan — Privacy Policy
description: Privacy policy for the Scan Android app by Dash Fusion.
---

# Scan — Privacy Policy

**Effective date:** 2026-09-08
**Last updated:** 2026-09-08

## Summary

Scan turns pages into PDFs. You scan or import a page, crop and straighten it,
put the pages in order, and save a PDF. All of that happens on your phone.

There is no account, no sign-up, no cloud and no server of ours anywhere.
**Your documents are never uploaded**, and there is nowhere for them to go.

**The app itself holds no camera permission.** Scanning is handed to Google
Play services' own document scanner, which runs in its own screen and returns
the finished images to this app. So the permission list you see on Google Play
has no camera, no photos and no storage in it — you can check that before you
install.

The only data that leaves your device is what Google AdMob needs to show ads,
and none of it is anything you scanned.

## Who we are

- **App name:** Scan (Google Play: *Scan: PDF Document Scanner*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listscan`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **The pages you scanned or imported**, as image files
- **What you did to each page** — the crop corners, the rotation and the colour
  mode. These are stored *separately* from the image, so the original is never
  overwritten and every edit stays reversible
- **Your documents** — their names, the order of their pages, and when they
  were made
- **App preferences:** default colour mode and page size, theme, Material You
  colour, and when the rewarded ad-free window runs out

That is the whole list. There is no name, no email, no location and no contact
anywhere in it, because the app never asks for any of them.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry. Nothing you scan is read,
uploaded, indexed or looked at by us or by anyone else.

The app **opts out of Android's cloud backup and device-to-device transfer**,
so your scans are never copied into Google's backup service. The honest cost:
uninstalling the app, or losing the phone, loses them. Export the PDFs you want
to keep.

## What the app deliberately cannot do

Worth stating plainly, because apps in this category commonly do these things:

- **It does not hold the camera permission.** The scanner is Google Play
  services' own; this app receives the finished page and never has access to
  the camera itself.
- **It does not read your photo library.** Importing a picture goes through
  Android's own picker, which hands this app the one file you chose and nothing
  else.
- **It does not upload documents** for OCR, "enhancement", storage or any other
  purpose. There is no server.
- **It has no OCR at all** in this version, so nothing reads the words on your
  pages.
- **It has no accounts**, no sync, and no sharing except the share sheet you
  invoke yourself.
- **It does not watermark your PDFs, limit the number of pages, or charge for
  export.** Those are the three things rivals charge for, and none of them is
  here.

## Saving and sharing

Exporting a PDF or an image goes through **Android's own document picker**: you
choose where the file goes, and the app is granted that one location and
nothing else. Sharing uses the standard share sheet, so the file goes wherever
you send it — **once it leaves the app it is outside this policy**, and where
it ends up is your choice.

The app holds **no storage permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; scanning, cropping, building the PDF
and exporting it all work fully offline.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **after a PDF has been written**,
once the file exists and the screen still shows that it succeeded. It never
appears before a scan, between pages, or when something failed.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any page, any document, any file name or anything else from inside the
app.** Google's processing is done as an independent controller under its own
policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

### Google Play services (the scanner)

The document scanner screen is provided by Google Play services and delivered
by it at runtime. While it is open you are in Google's component, under
Google's own privacy policy above; it returns the captured pages to this app
and this app stores them privately as described.

### Consent (UMP)

Where required by law, the app shows Google's User Messaging Platform consent
form before ads are initialised, and records your choice. In the EEA and the UK
you are asked about personalised advertising; in covered US states you are
offered the opt-out required there. You can change your decision at any time
from **Settings → Ad privacy options**, and if you decline, every feature of the
app continues to work exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no
database with your name in it and no way to identify you or your device. We do
not sell or share personal information, because we do not have any.

## Permissions the app requests

- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is all of them. The app requests **no camera, no photo or media access, no
storage permission, no location, no microphone, no contacts and no calendar**.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the two
above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all from the Google Mobile Ads SDK. None is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use
under the COPPA framework. We do not knowingly collect personal information
from children — as described above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete a document** in the app, or **delete everything** by clearing the
  app's storage or uninstalling it. Because your scans live only on your
  device, that removes them completely — there is no copy anywhere else, and no
  deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
