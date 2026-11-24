# BeenThere Privacy Policy

_Last updated: **24.11.2026**_

BeenThere ("the app") is a map and navigation app that clears a "fog of war" over the places you have been. It is made by Kristijan Vidojkovic ("I", "we", "us"). This policy explains what the app does with your information, why, and what rights you have.

**Short version:** BeenThere has no accounts, no ads, no analytics and no tracking. Your explored map and everything else you do in the app stay on your phone, and we never receive them. To show the map, search and plan walking routes, the app talks directly to public map services, which see each request and your IP address like any website does. If you use backups, your progress also goes to your own Google backup or to a backup file you keep yourself.

## Who is responsible for your data

The developer and data controller for BeenThere is:

Kristijan Vidojkovic
Skopje, North Macedonia
Email: [beenthereapp.support@gmail.com](mailto:beenthereapp.support@gmail.com)

You can contact us at that address about anything in this policy, including to use your rights below. There is no separate data protection officer, because we do not process personal data on a large scale.

This policy is written to meet the EU General Data Protection Regulation (GDPR) and North Macedonia's Law on Personal Data Protection (Official Gazette no. 42/2020), which follows the GDPR.

## What stays on your phone

These are stored only on your device, in the app's private storage. We never receive them:

- Your explored map (which areas you have cleared of fog) and your progress per city and neighbourhood
- Places you have discovered, distance travelled, achievements and unlocked areas
- Your saved Home, your saved routes (with their stops) and which routes you have completed
- Your recent searches and recently opened places
- Your settings, including whether you allowed background location and when
- The saved copy of your progress (Menu > Progress: saved by itself when you leave the app, or when you tap Save now), which Restore merges back in
- The optional offline search index of places near you, and city and neighbourhood outlines the app has looked up

## Location

BeenThere uses your device's precise location to clear the fog where you go, show your position on the map, find places near you and give directions. Android asks you for this permission; you can change it at any time in Android Settings > Apps > BeenThere > Permissions. If you allow only approximate location, or none, the app explains what will not work and how to change it.

The location fix comes from Google Play services on your phone (the "fused location provider"). That is part of your phone's system software, and Google's own privacy policy and your device's location settings (such as Google Location Accuracy) apply to it. BeenThere does not send your location to Google.

Your location history is never sent to us or to anyone else. Single positions, often rounded, are sent to the services below only when a feature needs them, as listed in the table.

### Location in the background

Background location is **off** by default. BeenThere does not ask for, and does not use, the "Allow all the time" background location permission.

If you turn on **Menu > Background processes > Keep in background**, the app first shows a notice titled **"Clear fog in the background?"**. Only if you tap **Allow** does the app keep using your location while it is closed or the phone is locked, so the fog keeps clearing on a walk or drive. It does this through a foreground service that always shows a notification, **"Clearing fog in the background"**, in the "Location in use" notification channel. (While the app is open on screen, the notification may say "Going places" instead.)

You can stop it at any time, which withdraws your consent:

- tap **Turn off** on the "Clearing fog in the background" notification,
- switch off **Keep in background** in Menu > Background processes, or
- swipe BeenThere away from your recent apps (unless it is running in Android Auto at that moment).

If you tap **No thanks**, the fog only clears while BeenThere is open on screen. Background location does not send anything over the network by itself; it only updates the map stored on your phone.

### Android Auto

Android Auto is not part of the current Google Play version of BeenThere. When it is added, the following applies: while BeenThere is open in Android Auto, the same location service runs so the map follows you and the fog keeps clearing as you drive, and a notification says that your location is used for the map on Android Auto. When you leave BeenThere in the car, the service goes back to following your Keep in background setting. The data used is the same as on the phone; nothing extra is sent.

## Services the app contacts

To work, the app sends requests directly from your phone to the services below. We do not run them and we do not receive copies of the requests. Each of them decides for itself how it handles requests, as an independent controller under its own privacy policy and usage rules.

| Service | When | What it receives |
|---|---|---|
| **OpenFreeMap** (tiles.openfreemap.org) | Automatically, whenever the map is on screen | Map tiles and fonts for the area being viewed, which shows roughly where you are looking (often where you are) |
| **FOSSGIS routing** (routing.openstreetmap.de), run by FOSSGIS e.V. (OpenStreetMap Germany) | When you start a route with a walked part | The start, stops and destination of the route at about 1 m precision; the start is usually your current position |
| **Photon** by komoot (photon.komoot.io) | When you search (as you type), unless offline search already found enough | What you type, plus your position rounded to about 1 km so nearby results come first |
| | When you set Home, press and hold the map to drop a pin, or add a stop to a route | That one point, rounded to about 10 m, to look up its address |
| **Nominatim** (nominatim.openstreetmap.org), run by the OpenStreetMap Foundation | When you press Search and Photon found nothing | What you type, plus a box of about 35 km around you |
| | Automatically, when your city and neighbourhood progress is shown (skipped where the app already has the outline built in) | Your position rounded to about 1 km (city) or about 100 m (neighbourhood), to get the area's name and outline |
| | When you tap a city or neighbourhood name on the map | That name and the label's spot on the map, rounded to about 100 m |
| **Overpass API** (overpass-api.de, then overpass.kumi.systems if the first is busy) | When you search for a category such as fuel or pharmacy, unless offline search already found it | The category and your position rounded to about 1 km |
| | Only if you turn on offline search: first download, then filling gaps automatically as you travel | Map grid squares (about 11 by 8 km) around where you are, never your exact position |

Each of these services also sees your IP address and the app's name, version and a contact web address (the "User-Agent"), as any website would. Nothing in the requests contains an account, name, advertising ID or device ID. All connections use HTTPS.

**Google Places.** The Google Play version of BeenThere does not use Google Places or any other Google search service. <!-- If a Places API key is ever added to release builds, replace this with a table row: Google Places (places.googleapis.com), USA; receives the search text and your position rounded to about 1 km with a 30 km search radius; Google's privacy policy applies; it is a transfer to the USA under the EU-US Data Privacy Framework. -->

## Why we use your data (legal basis)

Under the GDPR and North Macedonia's Law on Personal Data Protection, every use of personal data needs a legal basis. These are ours:

| What | Legal basis |
|---|---|
| Using your location while the app is open, and sending searches, route points and pin addresses to the services above when you use those features | Providing the app and the feature you asked for (GDPR Art. 6(1)(b)) |
| Using your location in the background (Keep in background) | Your consent (GDPR Art. 6(1)(a)), given by tapping Allow on the notice. You can withdraw it at any time as described above; this does not affect what was done before you withdrew it |
| Requests the app makes by itself so the map works (map tiles, city and neighbourhood outlines, offline search updates) | Our legitimate interest in showing a working map, using only rounded positions and no identifiers (GDPR Art. 6(1)(f)) |
| Answering emails you send us | Our legitimate interest in answering you (GDPR Art. 6(1)(f)) |
| Google or file backups of your progress | Your own choice in Android settings or in the app; we do not receive them |

We do not make any automated decisions or profiles about you.

## Where data goes (international transfers)

The services in the table above are, to our knowledge, run from the European Union, mainly Germany. If you use BeenThere in the EU, your requests stay in the EU. If you use it in North Macedonia or elsewhere, requests go from your phone to these EU services, which are covered by EU data protection law. We do not send your data to any other country. Google's backup (if you turn it on) is handled by Google under its own terms.

## How long data is kept

- **On your phone:** until you delete it (see "Deleting your data").
- **By us:** we keep none of your app data. Emails you send us are kept only as long as needed to answer you, and at most 12 months after the conversation ends.
- **By the services above:** each keeps its own server logs for the time set out in its own privacy policy.

## Backups

You can keep a copy of your progress in two ways. Both are under your control, and we never receive either.

**Android / Google backup.** If backup is on for your phone (Android Settings > Google > Backup, or System > Backup, depending on the phone), Android includes BeenThere's progress in your device backup and when moving to a new phone. This backup is made and stored by Google under your Google account, under Google's terms, and we cannot see it. You can turn it off in Android settings at any time.

It includes: your explored map, discovered places, saved routes and completed routes, progress, unlocked areas, settings (including Home), recent searches and places, and the saved copy of your progress.

It leaves out: your background-location choice (you will be asked again on a new phone), the offline search index and area outlines (they download again), the account type shown on the Account screen, and Android Auto voice settings.

**A backup file you save yourself.** With **Menu > Progress > Export** you can save your progress to a file, and you choose where it goes (for example your phone's storage or a cloud drive of your choice). **Import** reads such a file back in. The file contains your explored map, discovered places, routes and settings. It is handled only by you and the place you save it; we never receive it. Anyone you give the file to can see the places you have explored, so keep it as private as you would a map of where you have been.

## Deleting your data

- **Menu > Reset fog** covers the whole map in fog again.
- **Uninstalling the app** or **Android Settings > Apps > BeenThere > Storage > Clear storage** deletes everything the app stores on your phone, including the saved copy of your progress.
- To remove your **Google backup**, turn off backup or delete the backup in your Google account settings (Google Drive > Backups on most phones).
- A **backup file you saved yourself** stays where you put it until you delete it.

Because we never receive your app data, there is nothing of it for us to delete on our side.

## Your rights

Under the GDPR and North Macedonia's Law on Personal Data Protection you have the right to:

- **access** the personal data we hold about you and get a copy of it,
- have it **corrected** if it is wrong,
- have it **erased**,
- **restrict** how it is used,
- **data portability**: receive your data in a common format (in the app, Menu > Progress > Export gives you all your progress as a file),
- **object** to uses based on our legitimate interest, and
- **withdraw your consent** at any time, for example by turning off Keep in background, without affecting what was done before.

Most of your data never leaves your phone, so you can see, export and delete it yourself in the app as described above. For anything we may hold (such as emails you sent us), write to the email address at the top of this policy. We will answer within one month. For requests you send to the map services in the table, contact them directly; we cannot see or delete their records.

**Right to complain.** If you think we have handled your data wrongly, you can complain to a data protection authority:

- in North Macedonia: the **Personal Data Protection Agency** (Агенција за заштита на личните податоци), [www.azlp.mk](https://www.azlp.mk);
- in the EU or EEA: the data protection authority of the country where you live or work, or where you think the problem happened (list at [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)).

We would be glad if you contacted us first so we can try to fix it.

## What we do not do

- No account, sign-in, name, email or phone number
- No advertising, advertising ID, analytics or crash-reporting SDKs
- No selling or sharing of your data with advertisers or data brokers
- No collection of contacts, photos, files, microphone or camera
- No automated decisions or profiling

## Children

BeenThere is not directed at children under 16 and is meant to be used by drivers and pedestrians. Drivers should only interact with the app when it is safe and legal to do so. If you believe a child has sent us personal data, contact us and we will delete it.

## Changes

If the app starts using other services, or this policy changes in any other way, the new version will be published at this address with a new "Last updated" date before the change reaches the app.

## Contact

Kristijan Vidojkovic
Email: [beenthereapp.support@gmail.com](mailto:beenthereapp.support@gmail.com)
