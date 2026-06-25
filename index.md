---
layout: default
title: Privacy Policy — StarGaze: Night Sky
---

# Privacy Policy — StarGaze: Night Sky

**Last updated:** 2026-06-25

StarGaze: Night Sky ("we", "our", "the app") is an astronomy and stargazing app developed for iOS and iPadOS. This privacy policy explains what data the app collects, how it is used, and your rights as a user.

## Short version

**StarGaze does not collect, sell, or share any personal data. The app uses your device's location and motion sensors only on-device to render the visible sky, and makes a single outbound HTTPS request to a public satellite-tracking API to show the International Space Station (ISS). No data about you is ever transmitted or stored on a server under our control.**

---

## 1. Data we do NOT collect

The app does **not** collect, store on any remote server, or sell:

- Your name, email, phone number, or any contact information
- Your device identifiers, advertising IDs, or analytics IDs
- Your usage patterns, behavior analytics, or crash reports
- Your stargazing history, favorites, or any in-app activity
- Any form of payment information (the app has no in-app purchases and no login)

The app has **no user accounts, no login, no sign-up, and no authentication** of any kind.

## 2. Permissions the app requests and why

StarGaze uses two iOS system permissions. Both are required for the core sky-viewing feature, and both can be revoked at any time in iOS Settings → Privacy & Security.

### Location (When In Use) — `NSLocationWhenInUseUsageDescription`

- **What we access:** your device's geographic latitude and longitude.
- **Why:** to compute which stars, constellations, the Moon, and planets are visible from your location on Earth. The sky you see depends on where you are.
- **Where it is processed:** entirely on your device. Your latitude/longitude is used inside the app's astronomical calculations and is **never transmitted to us**.
- **When:** only while the app is in the foreground.

The app does **not** request "Always" location, does not request background location, and does not use your location for advertising.

### Motion (Device Attitude) — `NSMotionUsageDescription`

- **What we access:** the device's attitude/orientation (heading, pitch, roll) from the gyroscope, accelerometer, and magnetometer.
- **Why:** so the sky on screen rotates to match the direction you point your phone — turning the phone into a "window" onto the real sky.
- **Where it is processed:** entirely on your device. Motion data is never transmitted.

The app does **not** request fitness, step counting, or health-related motion data.

## 3. The only outbound network request

StarGaze makes **one** kind of outbound network request:

| Endpoint | Method | Purpose | What is sent |
|---|---|---|---|
| `https://api.wheretheiss.at/v1/satellites/25544` | HTTPS GET | Fetch the current latitude/longitude of the International Space Station so it can be shown on the in-app map | Nothing — this is a plain GET request with no parameters, no headers identifying you, and no cookies |

**Important notes:**

- This request is made only when you open the **ISS Tracker** tab.
- The request is made directly from your device to the third-party API.
- We do not operate this API, and we do not control what data its operator (Wheretheiss.at) logs. Their privacy practices are governed by their own policy.
- No information about you (no device ID, no user ID, no location) is included in this request.

All other app features (Star Map, Moon Calendar, Best Times) work fully offline after first launch.

## 4. Where your data is stored

- **Star Map settings** (brightness filter, zoom, manual rotation) — stored in app memory only; reset when the app closes.
- **Location & motion data** — used in memory for rendering; not persisted to disk.
- **No files are written to your device's Documents or Library directories by the app itself.**

The app does not use iCloud Drive, CloudKit, Firebase, or any cloud synchronization service.

## 5. Third-party services

The app does **not** integrate with any of the following:

- Analytics SDKs (Google Analytics, Firebase Analytics, Mixpanel, Amplitude, etc.)
- Crash reporters (Crashlytics, Sentry, Bugsnag, etc.)
- Advertising networks (AdMob, AdSense, Meta Audience Network, etc.)
- Social login (Sign in with Apple, Google, Facebook, etc.)
- In-app purchase SDKs (the app has no purchases)

The only third-party service contacted is the public ISS-tracking API described in section 3.

## 6. Children's privacy

The app does not collect personal data from anyone, including children under 13 (or the applicable age of digital consent in your country). The astronomy content is educational and safe for all ages. No age gate is required because no personal data is collected.

## 7. Your rights (GDPR / CCPA and similar)

Because the app does not collect or store any personal data on servers under our control:

- There is no account or identifier to look up, correct, export, or delete.
- You can erase all locally stored preferences at any time by deleting the app from your device.

For the one outbound request to the ISS-tracking API, the operator of that API may have its own obligations; please contact them directly regarding any logs they keep.

## 8. Data security

- The app runs inside the iOS app sandbox, isolated from other apps.
- The single outbound request uses HTTPS (encrypted in transit).
- No secrets, tokens, or passwords are stored by the app.

## 9. Changes to this policy

We may update this privacy policy from time to time. Any changes will be posted on this page with an updated "Last updated" date. Material changes will also be mentioned in the app's release notes.

## 10. Contact

If you have any questions about this privacy policy or the app's data practices, please contact us:

- **Email:** halohaotianwu@gmail.com
- **GitHub:** [github.com/halohaotian](https://github.com/halohaotian)

## 11. Effective date

This privacy policy is effective as of **2026-06-25** and applies to all versions of StarGaze: Night Sky from 1.0.0 onward.

---

*This privacy policy is provided in English. Translations to other languages may be made available in the future.*
