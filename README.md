# StarGaze: Night Sky — Privacy Policy

> StarGaze does not collect, sell, or share any personal data.

**Live page:** <https://halohaotian.github.io/stargaze-privacy/>
**Support email:** [halohaotianwu@gmail.com](mailto:halohaotianwu@gmail.com)

---

## At a glance

| Item | Value |
|---|---|
| App | StarGaze: Night Sky |
| Platform | iOS / iPadOS |
| Version | 1.0.0+ |
| Last updated | 2026-06-25 |
| Contact | halohaotianwu@gmail.com |

## What the app does

StarGaze is an astronomy and stargazing app. It renders the visible sky, Moon phases, Best Times, and the International Space Station (ISS) position from your device's location.

## Data collected

**None.** The app has:

- No user accounts, no login, no sign-up
- No analytics SDKs
- No crash reporters
- No advertising networks
- No in-app purchases

## Permissions

| Permission | Why | Where processed | Leaves device? |
|---|---|---|---|
| Location (When In Use) | Compute visible stars/Moon/planets from your coordinates | On-device | **Never** |
| Motion (Device Attitude) | Sky rotates as you point your phone | On-device | **Never** |

Both can be revoked anytime in iOS Settings → Privacy & Security.

## Network

The app makes **one** outbound request:

- `GET https://api.wheretheiss.at/v1/satellites/25544`
- Triggered only when you open the **ISS Tracker** tab
- Plain HTTPS GET, no parameters, no identifying headers
- Used to fetch the ISS latitude/longitude for the in-app map

All other features work fully offline.

## Storage

- Star Map settings, location, and motion data live in memory only — not persisted to disk.
- No iCloud Drive, CloudKit, Firebase, or any sync service.

## Your rights

Because no personal data is collected on servers under our control:

- There is no account or identifier to look up, correct, export, or delete.
- Delete the app to erase all locally stored preferences.

## Children's privacy

No personal data is collected from anyone, including children under 13.

---

## Source files

- `index.html` — the privacy policy page served by GitHub Pages

## Deploying

This page is published via **GitHub Pages** from the `main` branch root.

1. Edit `index.html`.
2. Update the "Last updated" date inside.
3. Commit and push to `main`.
4. Wait ~30 seconds; the live page refreshes automatically.

## License

Privacy policy text © 2026 halohaotian. Provided as-is for the StarGaze: Night Sky app.

---

Links: [Live privacy policy](https://halohaotian.github.io/stargaze-privacy/) · [Author — github.com/halohaotian](https://github.com/halohaotian)
