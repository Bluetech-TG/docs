---
layout: ../../layouts/Legal.astro
title: Privacy Policy — Deliv
project: Deliv
published: September 16, 2026
updated: November 9, 2026
description: Privacy Policy for the Deliv mobile application by Bluetech TG.
---

## About Us

Deliv is a mobile application published by Bluetech TG, built for independent couriers to organize their delivery runs.  
Contact: **bluetechtg@gmail.com**.

## What Deliv Does NOT Do

- Deliv **does not require a user account** and does not ask for your email address or password.
- Deliv **has no central backend**: there is no remote database belonging to Deliv that receives or stores your personal data.
- Deliv **contains no advertisements** and **never sells any data**.
- Deliv **does not track your continuous background location**: GPS location is only requested when you explicitly tap "My position" to autofill the location of a package or merchant.

## Data You Enter

All information entered into Deliv (names, phone numbers of clients and merchants, delivery addresses, amounts, notes, package photos, and proofs of delivery) is stored **locally on your device** in a private SQLite database. This information never leaves your device unless **you** explicitly choose to share it (for example, tapping "Share" to send a receipt or tour summary via WhatsApp using your phone's native share sheet).

If you uninstall the application or tap "Reset data" in Settings, your data is permanently erased from your device. Deliv cannot recover it, as no copies exist on external servers.

## External Services Used

Deliv communicates with external services exclusively to provide key functionalities:

- **Route Optimization** (OSRM, `router.project-osrm.org`): when requesting the best delivery order for your packages, geographic coordinates of delivery stops (latitude and longitude only — no customer names or phone numbers) are sent securely over HTTPS to calculate distances and times. This public routing service receives no personally identifiable information.
- **Short Google Maps Link Resolution**: when you paste a shortened maps link (e.g., `maps.app.goo.gl`), Deliv resolves the redirect to extract coordinates, just as a web browser would.
- **Over-The-Air Updates** (Expo): Deliv checks and downloads its own application updates via Expo infrastructure, like standard mobile applications.

None of these services receive your private client information (names, phone numbers, delivery photos).

## Device Permissions

- **Location (GPS)**: used to quickly fill in your current position for a package or merchant without having to paste a maps link. Optional — you can always paste a link manually.
- **Camera & Photos**: used to attach an optional photo of a parcel or proof of delivery. Optional.
- **Notifications**: used for an optional end-of-day reminder that you can toggle on or off in Settings. These notifications are scheduled locally on your device; nothing is sent to a server.

You can revoke any of these permissions at any time through your device settings; the app remains fully functional, minus the specific capability.

## Children's Privacy

Deliv is a professional tool built for delivery drivers; it is not intended for children and does not knowingly collect data from children under 13.

## Changes to this Policy

If this policy changes, the update date at the top of this page will be revised. No separate notification is sent since there are no user accounts.

## Contact

For any questions about this privacy policy or your data: **bluetechtg@gmail.com**.
