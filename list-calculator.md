---
layout: default
title: List Calculator — Privacy Policy
description: Privacy policy for the List Calculator Android app by Dash Fusion.
---

# List Calculator — Privacy Policy

**Effective date:** 2026-09-01
**Last updated:** 2026-09-01

## Summary

List Calculator is an offline-first calculating list: you build lists of
named amounts and it totals them, with quantities, groups, tax/tip/discount
adjustments and per-list currencies. We do **not** create accounts, do
**not** ask for your email, do **not** sync your lists to any server, and do
**not** ship any analytics or tracking SDK. The lists you build — names,
amounts, quantities, notes, photos, totals — never leave your device unless
you explicitly export or share them.

Three things do leave your device, and only these three: what Google AdMob
needs to serve ads, what Google Play needs to sell and verify the optional
Premium subscription, and a currency-rate request to a public exchange-rate
API that carries none of your data. Each is described below.

If that's all you wanted to know, you're done. The sections below spell it
out in detail.

## Who we are

- **App name:** List Calculator
- **Developer:** Dash Fusion
- **Support email:** dash.fusion@outlook.com
- **App listing:** Google Play (`com.dashfusion.listcalculator`)

## Data the app stores on your device

The following data is created and kept **locally** on your device. It never
leaves the device unless you explicitly export, share or print it.

- The lists you create: list name, an optional description, and an optional
  photo for the list
- The items in each list: item name, amount, quantity, whether the item adds
  to or subtracts from the total, its group, whether it is checked off, and
  the times it was created and last modified
- Per-list adjustments — the tax, tip, discount or other lines you add, each
  with the label you type and a percentage or fixed value
- Per-list settings: currency code and symbol, symbol placement and spacing,
  simple or detailed mode, check-off mode, grouping and group names, and
  whether the list counts toward the Grand Total
- App preferences: theme mode and default currency, default list mode,
  auto-decimal entry, modification-date display, and the Grand Total setting
- Ad-frequency counters (how many interstitials were shown today, and when
  the last one appeared) so the app can rate-limit its own ads
- A cached flag recording whether your Premium subscription is active, and a
  cached table of currency exchange rates

Everything is entered by hand. The app has no access to your location,
contacts, calendar, bank, cards or any other account, and it never reads
them.

**Photos.** If you add a photo to a list, you choose it either from your
device's photo picker or by taking a new one with the camera. The app copies
that single image into its own private storage and uses it only as that
list's picture. It is not uploaded anywhere. The app never browses your photo
library on its own — it only ever receives the one image you pick — and you
can remove a list's photo at any time.

**Getting your data out.** You can export every list as a portable JSON
backup via **Settings → Export all lists**, and any individual list as a
**PDF**, an **Excel** spreadsheet, or plain text. Each of those is handed to
Android's share sheet or saved to a location you choose — where it goes next
is entirely your decision. **Settings → Import lists from backup** reads a
JSON file you pick and either merges it with your lists or replaces them.

**Deleting your data.** You can delete individual items, delete lists one at
a time or several at once, remove a list's photo, replace everything by
importing a backup, or uninstall the app — Android removes the app's local
storage with it.

**Android backup.** Unlike some of our other apps, List Calculator does not
opt out of Android's system backup and device-to-device transfer. If you have
Android backup enabled, your lists may therefore be included in the backup
Android makes to your Google account and restored onto a new device. That
backup is between you, your device and Google; we have no access to it and
cannot read it. You can control it in your device's system settings under
Google → Backup.

We have no servers and no cloud storage of our own. We cannot see your lists
and we cannot recover your data if you lose your device.

## Third-party services we use

### Google AdMob (ads)

The app contains the Google Mobile Ads SDK. It shows occasional full-screen
interstitial ads when you open a list — never on the first couple of opens
each day, never twice within 90 seconds, and never more than six times a day.
There are no banner ads, and entering or calculating items is never
interrupted. Google may collect and process:

- Your device's **Advertising ID** (a resettable identifier that Android
  provides for ads)
- **Coarse location** (typically inferred from IP) and **device/network
  information** that AdMob needs to serve and measure ads
- **Ad interaction events** (impressions, clicks)

AdMob does **not** receive your lists, items, amounts, totals, photos or
preferences. Google's handling of the data above is governed by Google's own
policies:

- [AdMob privacy policy](https://policies.google.com/technologies/ads)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

**Consent (EEA, UK and Switzerland):** on first launch the app shows Google's
certified consent form, and you choose whether personalised ads are allowed.
You can change your answer at any time from **Settings → Ad privacy options**
inside the app. You can also opt out of personalised advertising via your
device's system settings (Android: **Settings → Privacy → Ads**).

### Google Play Billing (the optional Premium subscription)

List Calculator offers an optional **Premium** subscription (monthly or
yearly) whose only effect is to remove ads. Everything else in the app is
free.

The purchase is handled entirely by **Google Play**. When you subscribe, the
Play Store's own purchase sheet takes over — we never see, receive or store
your name, card number, billing address or any other payment detail. The app
only asks Play whether an active subscription exists and caches the yes/no
answer on your device. **Settings → Restore purchases** re-asks Play the same
question.

Google's handling of the purchase is governed by the
[Google Payments privacy notice](https://payments.google.com/legaldocument?family=0.privacynotice)
and the [Google privacy policy](https://policies.google.com/privacy). You
manage, change or cancel the subscription in the Play Store, not in this app.

### Frankfurter (currency exchange rates)

If you use more than one currency across your lists, the Grand Total needs
exchange rates to add them up. The app fetches those rates from
[Frankfurter](https://frankfurter.dev/), a free public API backed by European
Central Bank reference rates, at most once every 24 hours (or when you tap
**Refresh now** in Settings).

That request asks a single question — "what are today's rates against the US
dollar?" — and **carries none of your data**: no lists, no amounts, no
identifier, no account, and no API key. The reply is a table of currency
rates, which is cached on your device and used to do all conversion locally.
As with any network request, the service necessarily sees the IP address the
request comes from. If the request fails or you are offline, the app simply
uses the last rates it cached, and everything else keeps working.

## Data we collect ourselves

**None.** We don't run any backend. We have no analytics SDK, no crash
reporter that phones home, no Firebase, and no custom telemetry. We don't log
app usage anywhere we can read it.

## Permissions the app requests

- **Camera** — only so you can photograph a list's picture yourself, at the
  moment you choose "take a photo". The app never opens the camera on its
  own, and the image goes straight into the app's private storage. Picking an
  existing image instead goes through Android's photo picker, which hands
  over only the one file you select and needs no storage permission at all.
- **Internet / network state** — so the Google Mobile Ads SDK can fetch ads,
  Google Play can verify the subscription, and the exchange-rate table can
  refresh. With Wi-Fi and data off, no ads load and rates go stale, but every
  calculating feature — lists, items, groups, adjustments, totals, photos,
  PDF/Excel export, backup and import — still works fully offline.
- **Advertising ID (`AD_ID`)**, plus the Android **ad-services** permissions
  (`ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`,
  `ACCESS_ADSERVICES_TOPICS`) — required by Google Play and Android's Privacy
  Sandbox for apps that serve ads; used by AdMob as described above.
- **Billing (`com.android.vending.BILLING`)** — required by Google Play so
  the optional Premium subscription can be offered and verified.
- **Wake lock and foreground service** — declared by the Google libraries the
  app bundles, not used by any code of ours. List Calculator declares no
  service of its own, sets no alarms, and schedules no background work; it
  does nothing while you are not using it.

That is the complete list. The app does **not** hold access to your location,
contacts, calendar, microphone, SMS, notifications, or the general contents
of your files. Choosing where to save an export, or which backup to import,
uses Android's own file picker — the app only ever sees the single file you
pick.

## Children

List Calculator is not directed to children under 13 and is not designed for
use under the COPPA framework. We do not knowingly collect data from
children.

## Your choices

- **Ad consent** — Settings → Ad privacy options (EEA/UK/Switzerland), or
  Android system settings → Privacy → Ads
- **Remove ads** — the optional Premium subscription; nothing else is behind
  it. Every calculating feature, every export format, backup and import are
  free
- **Export your data** — Settings → Export all lists for a JSON backup of
  everything, or share/save any single list as PDF, Excel or text
- **Delete your data** — delete items, delete one or several lists, remove a
  list's photo, replace everything with an imported backup, or uninstall the
  app and Android removes its local storage with it
- **Android backup** — controlled in your device's system settings under
  Google → Backup, as described above
- **Contact us** — dash.fusion@outlook.com

## Changes to this policy

If we change the data we collect or the third-party services we integrate, we
will update this page and bump the "Last updated" date above. Material changes
will be flagged in the app's release notes as well.

## Contact

Questions, requests, complaints: **dash.fusion@outlook.com**.
