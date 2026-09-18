---
layout: default
title: Photo OCR — Privacy Policy
description: Privacy policy for the Photo OCR Android app by Dash Fusion.
---

# Photo OCR — Privacy Policy

**Effective date:** 2026-09-19
**Last updated:** 2026-09-19

## Summary

Photo OCR turns a picture of printed text into text you can copy, edit, share and
save. The text is read **on your phone**, by Google's ML Kit text recognizer, which is
built into the app.

**Your pictures and your text stay on your phone.** The app never sends a picture
anywhere. The text leaves the app only when you copy it, share it to an app you choose,
or save it as a file in a folder you pick.

Two things do use the internet, and this policy names both exactly:

- **Google ML Kit**, the recognizer, sends Google diagnostics about how it runs - device
  and app details, an identifier for this installation, how long reading took, the
  picture's format and size, and error codes. **It does not send the picture or the
  text.**
- **Google AdMob** shows the app's ads, and receives what an ads SDK receives.

There is no account, no sign-up, no cloud and no server of ours anywhere.

## Who we are

- **App name:** Photo OCR (listed on Google Play as *Photo OCR: Image to Text*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listocr`)

## Your pictures

- **Choosing a picture** uses Android's photo picker, which hands the app only the
  picture you choose. The app has no permission to see your photos or files.
- **Taking a photo** opens your phone's own camera app, which takes the photo and hands
  it back. The app has no camera permission. That photo is written to the app's private
  cache, read, and deleted straight after; one left behind by a cancelled or
  interrupted capture is deleted an hour later.
- **Sharing a picture to Photo OCR** from another app hands over only that picture.
- Each reading keeps **a smaller copy of its picture** (at most 2560 pixels on its
  longest side) in the app's private storage, so a line of text can be checked against
  the picture later. It stays until you delete the reading.

## What the app stores on your device

- **Your readings:** for each one, the text as you last left it, the layout you chose
  (paragraphs or the page's own lines), when it was made, where the picture came from
  (chosen, taken or shared), the smaller copy of the picture, and each line as it was
  read with its position on the picture and the positions of any words the recognizer
  was unsure of.
- **App preferences:** your theme and wallpaper-colour choice, the last layout you
  chose, when the rewarded ad-free day runs out, and a count the app uses to space out
  ads.

We hold **no copy of any of it**: there is no analytics SDK of ours in this app, no
crash reporter of our own and no telemetry of our own. Deleting a reading deletes its
text, its lines and its picture; *Delete every reading* in Settings deletes all of them.

The app **opts out of Android cloud backup and device-to-device transfer**, so none of
this is copied into Google's backup service.

## Third-party services we use

### Google ML Kit (text recognition)

The text is read by Google's ML Kit Text Recognition, Latin script, **built into the
app**: the recognizer and its model are part of the app, so reading a picture needs no
internet connection and nothing is downloaded first. The picture is processed on your
device.

Google states that ML Kit collects the following, **for diagnostics and usage
analytics**, encrypted in transit, and that it does not transfer this data to third
parties:

- device information: manufacturer, model, operating-system version and build, and the
  machine-learning hardware available;
- application information: the package name and app version;
- a per-installation identifier, which Google says is not meant to identify a user or a
  physical device;
- performance metrics, such as how long reading took;
- the API configuration, such as the picture's format and resolution;
- the size of the feature's input and output, the feature's version, the type of event
  (for example starting up or reading a picture) and error codes.

**The picture and the text are not on that list.** There is no setting in the app that
turns ML Kit's diagnostics off.

- Google's ML Kit data disclosure:
  <https://developers.google.com/ml-kit/android-data-disclosure>
- Google Privacy Policy: <https://policies.google.com/privacy>

### Google AdMob (ads)

The app is supported by ads served by Google AdMob.

The app shows **no banner ads, no native ads and no ad on launch**. What it shows is an
occasional full-screen ad when you leave a result after copying, sharing or saving its
text - **never while a picture is being read and never while you are editing**. There
is also an optional rewarded ad you can choose to watch, in Settings, to switch ads off
for 24 hours.

To serve ads, Google receives data from your device, which may include your device's
advertising identifier (`AD_ID`), coarse location inferred from your IP address, device
and app information, and ad-interaction data. **It does not receive your pictures or
your text** - the app never sends those anywhere, and no ad targeting here is based on
them. Google's processing is done as an independent controller under its own policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

### Consent (UMP)

Where required by law, the app shows Google's User Messaging Platform consent form
before ads are initialised, and records your choice. In the EEA and the UK you are
asked about personalised advertising; in covered US states you are offered the opt-out
required there. You can change your decision at any time from **Settings → Advert
privacy options**, and if you decline, reading pictures works exactly as before.

## Data we collect ourselves

**None.** We operate no servers, no accounts and no analytics. We have no database
with your name in it, and no way to identify you or your device. We do not sell or
share personal information, because we do not have any.

## Permissions the app requests

- **Internet / network state** - so the Google Mobile Ads SDK can fetch ads, and so
  Google's ML Kit can send the diagnostics described above. Reading a picture does not
  need a connection.
- **Advertising ID (`AD_ID`)** - required by Google Play for apps that serve ads; used
  by AdMob as described above.

**The app asks for no camera, photo, storage, microphone or location permission**, and
Android never stops to ask you about any permission for it.

A few more permissions are merged into the final app package by the libraries the app
is built on, so the list Google Play shows you is slightly longer than the one above.
They are the Android Ad Services permissions plus wake-lock and foreground-service, all
from the Google Mobile Ads SDK, and one permission that only lets the app's own parts
talk to each other. None is a permission Android stops to ask you about, and none is
used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use under the
COPPA framework. We do not knowingly collect personal information from children - as
described above, we hold no personal data at all.

## Your choices

- **Delete a reading**, or **every reading** from Settings. Its text, lines and picture
  are removed from your phone.
- **Ad personalisation:** change your consent decision any time via **Settings → Advert
  privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete everything the app stores** by clearing the app's storage or uninstalling it.
  Because everything lives only on your device, that removes it completely and
  irreversibly - there is no copy anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and publish the
new version at this URL. Material changes will also be noted in the app's release notes
on Google Play. This policy is versioned publicly in the Dash Fusion privacy
repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
