---
layout: default
title: Sun — Privacy Policy
description: Privacy policy for the Sun Android app by Dash Fusion.
---

# Sun — Privacy Policy

**Effective date:** 2026-09-08
**Last updated:** 2026-09-08

## Summary

Sun tells you when the sun rises and sets, when the twilight bands begin and
end, and when the golden hour is, for any place and any date.

**Every one of those numbers is worked out on your phone**, from astronomical
formulae compiled into the app. Nothing is fetched. There is no server of ours,
no account, and no sign-up — and the app contains no HTTP client at all, so
there is nowhere for your places or your dates to be sent even by accident.

**This app can ask for your approximate location, and it is the only app we
publish that asks for any location permission.** It is used for one thing:
filling in the *Add place* form when you tap the locate button. The
[Location](#location-what-it-is-for-and-what-happens-to-it) section sets out
exactly what happens to that reading, because a sunrise app asking for location
is precisely the kind of request that deserves a straight answer rather than a
paragraph of reassurance.

## Who we are

- **App name:** Sun (Google Play: *Sun: Sunrise Sunset Times*)
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listsun`)

## Location: what it is for, and what happens to it

The app declares one location permission, **`ACCESS_COARSE_LOCATION`** —
approximate location, not precise. It never asks for `ACCESS_FINE_LOCATION`,
and it never asks for background location.

- **You are only asked when you tap the locate button** on the *Add place*
  screen. The app does not ask on launch, and it does not ask again later. If
  you never tap it, Android never shows you the dialog and the app never holds
  the permission.
- **Refusing costs you nothing.** The screen says so once, and every other way
  of adding a place still works: search the bundled place list, or type the
  coordinates yourself. There is no nag and no second ask.
- **One reading, on demand.** The app asks the Android platform's own location
  service for a single current fix at the moment you tap. It does not subscribe
  to updates, and **no fix is ever requested in the background** — there is no
  background location code in the app to run.
- **It goes into the form, not into a record.** The latitude and longitude fill
  in the two fields in front of you. If you then leave without saving, they are
  discarded with the screen. They are stored only if *you* save the place.
- **It is rounded to four decimal places** — about eleven metres — before it is
  shown or saved. That is the precision the astronomy actually needs; a
  kilometre of latitude moves sunrise by a couple of seconds.
- **It is never transmitted.** Not to us, not to Google, not to anyone. There is
  no networking code in this app outside the ads SDK, and the ads SDK is never
  handed anything from inside the app.
- The reading goes through the platform location service rather than Google Play
  services, so it also works on a device with no Google apps at all.

You can withdraw the permission at any time in Android's own settings, under
**Settings → Apps → Sun → Permissions**. The app keeps working; the locate
button simply reports that it could not get a fix.

## What the app stores, and where

Everything is written to this app's **private storage**, which no other app on
your phone can read:

- **The places you saved** — the name you gave each one, an optional country
  label, its latitude and longitude, the time zone the times are read in, and
  the order you put the list in.
- **App preferences:** theme, Material You colour, 12- or 24-hour clock, whether
  to show seconds, your notification choice, and when the rewarded ad-free
  window runs out.

That is the whole list, and the places table is **the only table in the app**.
No sunrise, sunset, twilight time or golden hour is ever stored, because each
one is a function of a place and a date and can be recomputed in a fraction of
a millisecond. There is no name, no email, no contact and no identifier in any
of it, because the app never asks for one.

The bundled place list you search when adding a place is **a data file inside
the app** — a few hundred cities, about 44 KB of text. Searching it is not a
network request, sends nothing, and works in aeroplane mode. There is no
geocoding service behind it.

We hold **no copy of any of this**. There is no analytics SDK in this app, no
crash reporter of our own, and no telemetry of any kind.

The app **opts out of Android's cloud backup and device-to-device transfer**, so
your places are never copied into Google's backup service. The honest cost:
uninstalling the app, or losing the phone, loses your list. The app has an
**export** that writes every saved place to a readable file you choose the
location of — that file is yours, and it is the intended way to keep a copy.

## Notifications

The app can post **one optional notification** — sunrise, sunset or the start of
the golden hour at a place you choose, optionally some minutes early. It is off
until you switch it on, and switching it on is what triggers Android's
notification permission request.

To schedule it the app needs to run briefly when your phone restarts, which is
why it declares **`RECEIVE_BOOT_COMPLETED`**. That is all that permission does
here: without it, the reminder would stop after the first reboot and the switch
in Settings would go on claiming it was on.

The notification is computed on the device from the place you picked. Nothing
about it leaves the phone.

## Third-party services we use

### Google AdMob (ads)

The app is supported by ads served by Google AdMob. **Ads are the only reason
this app needs an internet connection at all** — every sunrise, sunset, twilight
time and golden hour is computed offline, and the app answers just as well in
aeroplane mode.

The app shows **no banner ads, no native ads and no ads on launch**. A
full-screen ad can appear at one moment only: **after you have added a place to
your list**, and not every time. There is also an optional rewarded video you
can choose to watch, which removes ads for 24 hours; it is never forced and
never interrupts anything.

To serve ads, Google receives data from your device, which may include your
device's advertising identifier (`AD_ID`), coarse location inferred from your IP
address, device and app information, and ad-interaction data. **It does not
receive the location reading described above, any saved place, any coordinate or
anything else from inside the app** — the ads SDK is never passed data from the
app's own storage. Google's processing is done as an independent controller
under its own policies:

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

- **Approximate location (`ACCESS_COARSE_LOCATION`)** — only when you tap the
  locate button, and only as described above. Optional; the app works without
  it.
- **Notifications (`POST_NOTIFICATIONS`)** — only if you switch the reminder on.
  Optional.
- **Run at startup (`RECEIVE_BOOT_COMPLETED`)** — so a reminder you switched on
  survives a reboot. Not a permission Android asks you about.
- **Internet / network state** — solely so the Google Mobile Ads SDK can fetch
  ads.
- **Advertising ID (`AD_ID`)** — required by Google Play for apps that serve
  ads; used by AdMob as described above.

The app requests **no precise location, no background location, no camera, no
microphone, no photo or media access, no storage permission, no contacts and no
calendar**.

A few more permissions are merged into the final app package by the libraries
the app is built on, so the list Google Play shows you is longer than the ones
above. They are the Android Ad Services permissions plus wake-lock and
foreground-service, all from the Google Mobile Ads SDK. None is a permission
Android stops to ask you about, and none is used by any code we wrote.

## Children

This app is not directed at children under 13 and is not designed for use under
the COPPA framework. We do not knowingly collect personal information from
children — as described above, we hold no personal data at all.

## Your choices

- **Location:** grant it, refuse it, or withdraw it later in Android's settings.
  Nothing else in the app changes either way.
- **Notifications:** the reminder is off until you turn it on, and can be turned
  off again in Settings or in Android's own notification settings.
- **Ad personalisation:** change your consent decision any time via
  **Settings → Ad privacy options**.
- **Reset your advertising ID or opt out of personalised ads** in Android's own
  settings, under **Settings → Google → Ads**.
- **Delete a place** in the app, or **delete everything** by clearing the app's
  storage or uninstalling it. Because your places live only on your device, that
  removes them completely — there is no copy anywhere else, and no deletion
  request to send us.

## Changes to this policy

If we change this policy we will update the **Last updated** date above and
publish the new version at this URL. Material changes will also be noted in the
app's release notes on Google Play. This policy is versioned publicly in the
Dash Fusion privacy repository, so any change is visible in its history.

## Contact

Questions about this policy or about the app: **dash.fusion@outlook.com**
