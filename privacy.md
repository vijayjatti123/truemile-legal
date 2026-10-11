---
title: TrueMile Privacy Policy
permalink: /privacy/
---

# TrueMile Privacy Policy

**Last updated: 11 October 2026 (draft — final version published before release)**

TrueMile is an Android app that automatically logs drives and produces mileage reports for the United States, United Kingdom, Canada and Australia. It is published by **VJ Softworks** (proprietor: Vijaykumar Jatti), India. Contact: **[connect@vjsoftworks.com](mailto:connect@vjsoftworks.com)**.

## The short version

- **Your trips are never uploaded to our servers.** We do not run any server that stores your trips, routes or locations.
- **Addresses and maps are looked up with Google.** To show addresses and maps, TrueMile sends only what each lookup needs to Google, as described below.
- No ads. No analytics or tracking SDKs. We never sell or share your data for advertising.
- You can export all your trips as a CSV file at any time, free, and delete them whenever you want.

## What TrueMile records, and where it stays

All of the following is stored **only on your phone**, in TrueMile's private app storage:

| Data | Why |
|---|---|
| Precise location while a drive is detected, including when the app is closed | To measure each drive's route and distance automatically |
| Physical activity (for example "in a vehicle") | To detect when a drive starts and ends without keeping GPS on all day |
| The Bluetooth device you choose as your car (its name and address) | To start and end drives when your phone connects to or disconnects from your car |
| Trips: start and end times, route points, distance, start and end addresses, classification (business, personal, etc.), purpose, notes, tags, vehicle | To show your drives and build your mileage reports |
| Vehicles and odometer readings you enter | For per-vehicle records required by some tax authorities |
| Settings (country, units, rules, home and saved places, work hours) | So the app works the way you set it up |
| A technical log of tracking events (for example "drive started", "permission removed") | So the Tracking Health screen can show you why a drive might have been missed |

GPS is used only while a drive is being detected or recorded, not continuously.

## What is sent to Google, and why

TrueMile uses the following Google services. Each receives only the data listed.

| Service | What it receives | When |
|---|---|---|
| Android's built-in address lookup (Geocoder) and, if it fails, the Google Geocoding API | The start and end coordinates of a trip — never the full route | When TrueMile fills in a trip's start and end addresses |
| Google Maps SDK for Android | Requests for map images of the area you are viewing. Your route itself is drawn on your phone and is not sent | When you open a map in the app |
| Google Places API (Autocomplete) | The address text you type | Only when you add a manual trip and search for an address (Pro) |
| Google Routes API | The two places you chose for a manual trip | Once, when you save a manual trip (Pro), to calculate its driving distance |
| Firebase Remote Config | A random app-installation identifier, app version and basic device information | Periodically, to download up-to-date mileage rates |
| Firebase Crashlytics | Crash details: the error, device model, Android version, app version and a random app-installation identifier. **No locations, addresses or trip details** | Only if the app crashes |
| Google Play Billing | Purchases are handled entirely by Google Play. We receive only the purchase status, never your payment details | When you buy or restore TrueMile Pro |
| Android Backup to your Google account | If backup is turned on in your phone's settings, Android may back up TrueMile's data to **your own** Google account, encrypted by Android. We cannot access these backups | Automatically, as managed by Android |

Google processes this data under its own terms and privacy policy: [policies.google.com/privacy](https://policies.google.com/privacy).

## What we never do

- We do not upload your trips, routes or location history to our own servers.
- We do not sell your data or share it for advertising.
- We do not use advertising, analytics or cross-app tracking SDKs.
- We do not require an account. You never give us your name or email to use the app.

## When data leaves your phone because you choose it

- **Exports and reports:** CSV files and PDF reports are created on your phone. They leave it only when you share or save them somewhere, using an app of your choice.
- **Backup file:** if you create a TrueMile backup file, it is protected with a password you choose and stored wherever you decide.

## How long data is kept

- Trips and settings stay on your phone until you delete them or uninstall the app.
- Deleted trips go to a "Recently deleted" bin and are permanently removed after 30 days.
- To save space, detailed route points of trips older than 30 days may be simplified. Each trip's distance, times and classification are never changed by this.
- Crash reports are kept by Firebase Crashlytics for up to 90 days.
- A backup in your Google account is kept and deleted according to Android and Google's backup rules.

## Your choices and rights

- **See and export your data:** Export CSV is always available, free.
- **Correct it:** edit any trip; every edit is recorded in the trip's history.
- **Delete it:** delete individual trips, or delete all data from Settings. Uninstalling the app removes all data stored on the phone.
- **Stop collection:** pause tracking in the app, or remove TrueMile's location, activity or nearby-devices permissions in Android settings at any time.

Because your trips are stored only on your phone, we cannot see, retrieve or delete them for you. For anything else, including questions about the limited data Google services receive on TrueMile's behalf, email [connect@vjsoftworks.com](mailto:connect@vjsoftworks.com). We aim to reply within 30 days.

Depending on where you live, you may have specific legal rights over your personal information:

- **United Kingdom:** rights under the UK GDPR, including access, correction, deletion and objection, and the right to complain to the Information Commissioner's Office ([ico.org.uk](https://ico.org.uk)). We process location to provide the service you asked for and only with the permissions you grant.
- **United States (including California):** we do not sell or share personal information as defined by the CCPA/CPRA.
- **Canada:** rights under PIPEDA, including access and correction, and the right to complain to the Office of the Privacy Commissioner of Canada.
- **Australia:** rights under the Privacy Act 1988 and the Australian Privacy Principles, including access and correction, and the right to complain to the Office of the Australian Information Commissioner.

## Permissions TrueMile asks for

| Permission | Why |
|---|---|
| Location (precise, and "Allow all the time") | To record drives automatically, including when the app is closed |
| Physical activity | To detect when you start and stop driving |
| Nearby devices (optional) | To recognise your car's Bluetooth connection |
| Notifications | To show the recording notification and alerts about tracking problems |

## Children

TrueMile is not directed at children and is not intended for anyone under 16.

## Security

Your data is protected by Android's app sandbox, which prevents other apps from reading it. Backup files are encrypted with your password. No method of storage is perfectly secure, so please keep your phone protected with a screen lock.

## Changes to this policy

If we change this policy, we will update the date at the top and, for significant changes, tell you in the app before the change applies.

## Contact

VJ Softworks (proprietor: Vijaykumar Jatti), India
Email: [connect@vjsoftworks.com](mailto:connect@vjsoftworks.com)
