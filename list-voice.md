---
layout: default
title: Voice Recorder — Privacy Policy
description: Privacy policy for the Voice Recorder Android app by Dash Fusion.
---

# Voice Recorder — Privacy Policy

**Effective date:** 2026-09-04
**Last updated:** 2026-09-04

## Summary

Voice Recorder records audio and keeps it on your phone.

**Nothing you record ever leaves your device.** There is no account, no
sign-up, no cloud, and no server of ours anywhere. Your recordings are not
uploaded, not analysed, not transcribed, and not used to train anything. We
cannot listen to them and we could not hand them to anyone if we were asked,
because we never receive them.

This matters more here than in most apps, so it is worth being exact: the
microphone is used **only while you are recording**, only after you have
granted the permission, and only into a file in this app's own private
storage. The app has no ability to record in the background without the
ongoing notification that Android requires and shows you.

The only data that leaves your device is what Google AdMob needs to show ads,
and **no audio is ever part of that**.

## Who we are

- **App name:** Voice Recorder
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listvoice`)

## What the app stores, and where

Your recordings are written to this app's **private storage**
(`filesDir/recordings`), a folder no other app on your phone can read. The
following is created and kept there and in a local database, and never leaves
your device unless you share a recording yourself:

- **The audio files themselves**
- **Recording names**, and the folder you filed each one in
- **Bookmarks** — the timestamps you marked, and their labels
- **Durations, sizes and dates**
- **App preferences:** recording quality, playback speed, theme, and when the
  rewarded ad-free window runs out

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry. Nothing you record is
transmitted anywhere, and none of it is used for advertising.

The app opts out of Android cloud backup and device-to-device transfer, so
your recordings are not copied into Google's backup service either.

**Consequence, stated honestly:** because the audio exists only on your phone,
we cannot recover it if you lose the device, and uninstalling the app deletes
every recording permanently. Share anything you cannot afford to lose to
somewhere else.

## Sharing a recording is something you do, not something we do

The app can share one recording at a time into whatever app you choose — a
message, an email, a cloud drive. That happens only when you tap share, the
destination is chosen by you in Android's own share sheet, and the file goes
directly from your phone to that app through Android's `FileProvider`, which
grants that one app access to that one file. It does not pass through us.

A temporary copy is made in the app's cache when you share, so the receiving
app sees the name you gave the recording rather than an internal filename.
That copy lives in this app's own cache and is cleared by Android.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason
the app needs an internet connection at all; recording, playback, trimming and
searching all work fully offline.

The app shows **no banner ads**, and **never shows an ad while you are
recording or listening**. What it shows is an occasional full-screen ad after
a recording has been saved, and an optional rewarded ad you can choose to
watch to switch ads off for 24 hours.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your
IP address, device and app information, and ad-interaction data. **It does not
receive your recordings, their names, your folders or your bookmarks** — the
app never sends those anywhere. Google's processing is done as an independent
controller under its own policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

### Consent (UMP)

Where required by law, the app shows Google's User Messaging Platform consent
form before ads are initialised, and records your choice. In the EEA and the
UK you are asked about personalised advertising; in covered US states you are
offered the opt-out required there. You can change your decision at any time
from **Settings → Ad privacy options**, and if you decline, every recording
feature continues to work exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no
database with your name in it and no way to identify you or your device. We do
not sell or share personal information, because we do not have any.

## Permissions the app requests

- **Microphone (`RECORD_AUDIO`)** — to record. Asked for the first time you
  press record, not when you open the app. Used only while a recording is
  running.
- **Foreground service (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MICROPHONE`)**
  — so a recording keeps running when you leave the app or the screen turns
  off. Android requires the ongoing notification you can see while this is
  active, and it carries a stop control.
- **Notifications (`POST_NOTIFICATIONS`)** — for that recording notification.
  Decline it and recording still works; you simply lose the controls in the
  shade.
- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads. Turning off Wi-Fi and mobile data means no ads load; every other
  feature still works.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

That is all. The app requests **no storage permission of any kind**, no
camera, no contacts, and no location. It cannot read your other files, and
your recordings are not visible to other apps.

## Children

This app is not directed at children and is intended for users aged 13 and
over. We do not knowingly collect personal information from children — as
described above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Revoke the microphone permission** at any time in Android's app settings.
  The app will ask again next time you press record.
- **Delete your data** by deleting recordings in the app, or by clearing the
  app's storage or uninstalling it. Because the audio lives only on your
  device, that removes it completely and irreversibly — there is no copy
  anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in
the app's release notes on Google Play. This policy is versioned publicly in
the Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
