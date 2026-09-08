---
layout: default
title: Boxes — Privacy Policy
description: Privacy policy for the Boxes Android app by Dash Fusion.
---

# Boxes — Privacy Policy

**Effective date:** 2026-09-08
**Last updated:** 2026-09-08

## Summary

Boxes is a moving and storage inventory. You number your boxes, list what went
in each one, print a QR label for each, and later scan or search to find out
which box the kettle is in.

Everything you enter stays on your phone. There is no account, no sign-up, no
cloud and no sync. **Nothing you type is uploaded** — not a box, not an item,
not a room name. There is nowhere for it to go.

**The app holds no camera permission**, even though it reads QR codes. Scanning
is handed to Google Play services' own scanner, which runs in its own process
and returns a string. You can check that on the Google Play listing before you
install: there is no camera in the permission list.

## Who we are

- **App name:** Boxes (Google Play: *Boxes: Moving Inventory Labels*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listboxes`)

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **Your boxes** — the number, the label code, the room or origin, the
  destination, the status, and any note you added.
- **Your items** — the things you listed inside each box.
- **App preferences:** theme, Material You colour, your paper size for label
  sheets, and when the rewarded ad-free window runs out.

That is the whole list. There is no name, no email, no address, no phone
number, no contact and no location anywhere in it, because the app never asks
for any of them. A room called *Mum's spare room* or a note about what is
fragile is stored exactly as privately as everything else and is never
transmitted.

We hold **no copy of any of it**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind. Nobody at Dash Fusion
can see what you own or where it is going.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your inventory is never copied into Google's backup service. The honest cost:
uninstalling the app, or losing the phone, loses it. The app has an **export**
that writes everything to a readable file you choose the location of — that file
is yours, and it is the intended way to keep a copy or move to a new phone.

## The QR labels, and what is actually on them

This is the part worth reading, because it is a deliberate design decision
rather than an implementation detail.

**A label encodes only an identifier** — the letters `BOX-` followed by eight
characters. It does **not** encode what is in the box. Anyone who photographs a
label on the side of a box in a van, a corridor or a storage unit learns a
twelve-character code and nothing else; they cannot read your contents from it,
because your contents are not in it.

What the label *prints* in ink — the box number, the room, the destination and
as many items as fit — is your choice of what to show, and you can see exactly
what it says before you print it.

The identifier is generated on your device at random. It is not derived from
your name, your phone, your account or anything about you, and it is not sent
anywhere.

## Scanning, printing and sharing

- **Scanning** opens Google Play services' own barcode scanner. While it is
  open you are in Google's component, under Google's privacy policy linked
  below; it hands this app back the scanned text and nothing else. **This app
  never has access to your camera**, and it holds no camera permission for
  Android to grant.
- **Label sheets** are made into a PDF on your device. Saving one goes through
  **Android's own document picker**: you choose where the file goes and the app
  is granted that one location. Sharing uses the standard share sheet. Once a
  file leaves the app it is outside this policy, and where it goes is your
  choice.
- The app holds **no storage permission**.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. Ads are the only reason the
app needs an internet connection at all; listing, labelling, searching, scanning
and building the PDF all work fully offline — which matters, because a storage
unit is exactly the kind of place with no signal.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **after you have finished a box** —
sealed it, or unpacked it — and not every time even then. Looking a box up,
scanning one, searching, or printing labels never shows one.

There is also an optional rewarded video you can choose to watch, which removes
ads for 24 hours; it is never forced and never interrupts anything.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive any box, any item, any label code or anything else from inside the
app.** Google's processing is done as an independent controller under its own
policies:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from partner sites and apps:
  <https://policies.google.com/technologies/partner-sites>

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

That is the whole list. The app requests **no camera, no microphone, no photo or
media access, no storage permission, no location, no contacts, no calendar and
no notifications**.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the two
above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all from the Google Mobile Ads SDK. None is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect personal information from
children — as described above, we hold no personal data at all.

## Your choices

- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete anything** in the app — an item, a box, everything — or **delete it
  all** by clearing the app's storage or uninstalling it. Because your inventory
  lives only on your device, that removes it completely: there is no copy
  anywhere else, and no deletion request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
