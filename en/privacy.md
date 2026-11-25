---
lang: en
title: Privacy Policy
permalink: /en/privacy/
alt: /privacy/
description: What information the TripPhoto app handles, where it is stored and who receives it.
---
# Privacy Policy

<p class="meta">Effective: November 25, 2026</p>

TripPhoto (the "app") is an iOS app that builds trip albums and travel routes from the photos in your library. The developer (JJ Lab) has no sign-up and runs no server that receives or stores your photos or trips.

## 1. Photos and location
The app reads capture times and locations (EXIF) from the photos you allow it to access, to build trip albums and routes. Photos and results (trips, places and edits such as renames and merges) are kept in the app's storage on your device and are never sent to the developer. Capture dates you change are also written to your photo library; iOS asks for your permission first.

## 2. iCloud sync
When iCloud sync is on (the default; you can turn it off in Settings), your trips (trip names and dates, places, edits, photo capture times and locations, identifiers that let iCloud Photos find the same photos, and for trips made from a travel plan the visits and visit records copied into them) are stored in **your own private iCloud database** (Apple CloudKit) to keep your other iPhone and iPad signed in to the same Apple Account in step. Photo files themselves are not uploaded. This data lives in your iCloud storage, the developer cannot see it, and Apple's [Privacy Policy](https://www.apple.com/legal/privacy/) applies. Deleting a trip also deletes it from iCloud.

When you make a trip from a travel plan, the app reads the travel plan (visit names, locations, place types and planned times) and the visit records (arrival and departure times, locations) that the developer's other travel apps, FlexTrip and TripRoute, keep on this device (an app group storage the three apps share) and in your own private iCloud database, and copies the visits and visit records as they are then into the trip. From then on it uses only that copy; the app never changes or sends the plan or the records. This information is never sent to the developer and is not shared with anyone else.

**Visit notes (from 1.4.0)**: for a trip made from a travel plan, the app reads the notes you left at visits in FlexTrip (text, the on-device transcript of a voice note, and its recording) from the same app group storage and your own private iCloud database, and shows and plays them with that place's photos and in slideshows. When the plan's notes change, the trip's copy of the notes (text and transcripts) follows, and that copy is part of the iCloud sync above. Recordings are kept only in the app's storage on this device; they are not synced to iCloud by the app or sent to a TV (voice notes play on the iPhone). When you watch on a Chromecast, text notes are drawn into the picture sent only to that TV. The app records nothing itself and has no microphone access. This information is not sent to the developer either.

## 3. Place names
To show place names, representative coordinates of places are sent to Apple's location services (reverse geocoding and map search), under Apple's [Privacy Policy](https://www.apple.com/legal/privacy/).

## 4. Sharing map files
When you choose to share, the app creates a KML, KMZ or GPX file on your device and hands it to the app or service you pick. KMZ files contain photo thumbnails. What happens after sharing follows the receiver's policies.

## 5. Slideshows and watching on a TV (Chromecast)
Slideshows load and show your photos on your device; slideshow settings (layout, transition, time per photo, whether place and time show, whether videos are included, whether visit notes show and voice notes play) and the layout of a place's photos (grid, justified rows, masonry columns or mosaic, and the number of columns) are stored only on your device. If you choose background music, iOS asks for **Media & Apple Music** access; the app keeps only the library identifiers of the songs you chose on your device and plays them there (never sent to the TV or to the developer).

When you open the slideshow's start screen to watch on a TV, the app asks for iOS **Local Network** access (once) to find Chromecast devices on the same Wi-Fi network. This feature uses Google's **Google Cast SDK**; as iOS requires, the app also states a **Bluetooth** purpose, which the SDK may use to find nearby devices.
- When you pick a Chromecast, images of the photos, collages and maps, and videos (converted to MP4), go directly from your device **only to that Chromecast on your network**. Nothing is sent to the developer or any other server, and the temporary files made on your device are deleted when the slideshow ends.
- For the reliability and performance of the feature, the Google Cast SDK may send **diagnostic data (performance and other diagnostics), coarse location and a device identifier** to Google. This data is not linked to your identity and is not used for tracking. The app turns the SDK's analytics logging off. Google's [Privacy Policy](https://policies.google.com/privacy) applies.
- The Google Cast SDK is prepared when the app starts, but it searches for and connects to Chromecasts only from the slideshow's start screen. The slideshow on your device works even if you deny Local Network access.
- If no Chromecast shows up or playback on the TV goes wrong, **Settings › Troubleshooting › Share Chromecast Diagnostics** in the app makes a search and playback log (app and iOS versions, device model, names and models of the devices found, the TV's requests and playback states). It contains no photos. The app never sends it itself; it goes only to the app you pick (Mail, for example).

## 6. Ads and tracking
The app shows no ads, uses no advertising, analytics or tracking SDKs, and does not track you across apps and websites owned by other companies. It never asks for tracking permission (ATT). (For the diagnostic data the Google Cast SDK of the Chromecast feature sends, see section 5.)

## 7. Donations
Every feature of the app is free. In **Settings › Support Development** you can make an optional donation (a consumable in-app purchase); it unlocks nothing. The Apple App Store handles payment, the developer never receives payment details, and the app keeps no record of donations.

## 8. Retention and deletion
Deleting a trip removes it from your device and iCloud. Deleting the app removes trips from the device; what remains in iCloud can be deleted in iOS **Settings › Apple Account › iCloud › Manage Storage**. Albums created in Photos are managed in the Photos app.

## 9. Children
The app is not directed at children and does not knowingly collect children's information.

## 10. Changes
Changes to this policy are posted on this page with a new effective date.

## 11. Contact
[jjlab-support@googlegroups.com](mailto:jjlab-support@googlegroups.com)
