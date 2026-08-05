# Privacy Policy for Lexicon

**Last updated: 31 July 2026**

## The short version

Lexicon collects nothing, transmits nothing, and stores nothing outside your
own device. It has no internet permission, so it is not able to send data
anywhere even if it were asked to.

## What this app does not do

Lexicon does not collect, transmit, sell, or share any personal information.
There are no analytics, no crash reporting, no advertising identifiers, no
tracking of any kind, and no accounts to create.

There is no server. Nothing is uploaded, because there is nowhere to upload it
to.

## How that is enforced

The release build of Lexicon has the Android `INTERNET` permission removed
from its manifest. This is stronger than a policy commitment: the operating
system itself prevents the app from opening a network connection. You can
confirm this yourself before trusting it — on Google Play, the app's
permissions list will show no network access, and the app works identically
with your phone in airplane mode.

## What stays on your device

The following is stored locally, in the app's private storage, and is visible
only to you:

- **The dictionary.** A copy of WordNet 3.0, shipped inside the app and
  unpacked on first launch.
- **Words you save.** Only the word itself and the time you saved it.
- **Pages you scan.** The recognised *text* of pages you have scanned, so you
  can reopen them. Photographs are not stored by this app.

## Camera and photos

When you photograph a page, Lexicon hands off to your device's own camera app,
which returns a single image. When you choose an existing image, Android's
photo picker returns only the one file you select — the app is never granted
access to your photo library.

The image is processed entirely on your device by Google's ML Kit text
recognition, using a model compiled into the app. The image is not stored by
Lexicon and is not transmitted anywhere.

## Deleting your data

Uninstalling the app removes everything: the dictionary, saved words, and scan
history. You can also clear individual saved words and scanned pages inside
the app by swiping them away. There is no copy held anywhere else, so there is
nothing further to request or delete.

## Children

Lexicon is a dictionary. It collects no data from anyone, including children,
and contains no advertising, no purchases, and no user-generated content.

## Third-party components

Lexicon uses Google's ML Kit text recognition library, running fully on-device
with a bundled model. Because the app has no network permission, this
component cannot transmit data even in principle. Google's ML Kit terms are at
https://developers.google.com/ml-kit/terms

Dictionary data is from WordNet 3.0, © 2006 Princeton University, used under
its licence. WordNet is a static data file with no service attached.

## Changes to this policy

If this policy changes, the date at the top will change with it. Any future
version that involved collecting data would require adding a network
permission, which would be visible in the app's Play Store permissions listing
before you updated.

## Contact

Questions about this policy: **nandkumar.jha2010@gmail.com**
