# WattBoard Privacy Policy

*Last updated: 15 October 2026.*

## Who I am
WattBoard (iPhone, iPad, Apple Watch, Mac and Android) is created and maintained by **zerocoolspain** (independent project, not affiliated with Tesla, Inc.).
Privacy contact: **wattboardapp@gmail.com**.

## Summary
- Wattboard has **no accounts, no ads, no analytics and no tracking**.
- The app connects **only to your own server** (its REST API, Grafana or Postgres). Your driving data **never goes through any server of mine**.
- The only information that can reach the developer is the **feedback you choose to send** from “Send feedback”.

## Data the app handles on your device
- **Your car and trip data**, read from your server. It is shown on screen and a temporary copy is kept on your device so you can view it offline (removed when you uninstall the app).
- **Your server addresses and credentials.** Passwords and tokens are stored in the iOS/macOS Keychain, or encrypted with the Android Keystore on Android. On Apple devices the API address and token are shared with the app's widgets through a private container (App Group).
- **Settings** (language, appearance, alerts) and a **log of recent errors** with no addresses, usernames or passwords.
- **Local notifications** (charge finished, low battery) are computed on your device, with no server. The Face ID, Touch ID or fingerprint lock is handled by the operating system: the app never receives your biometric data.

## Third-party services used by the app
- **Apple Maps / MapKit** (iPhone, iPad and Mac), to show maps. Apple receives the coordinates needed to draw the map, under its own privacy policy.
- **Google Code Scanner (Google Play services)** on Android, only if you scan a setup QR code. The scan is processed on the device and the app does not receive your camera images.
- Your own server and the tools you host (private networks, reverse proxies, etc.) are governed by their own terms.

## Feedback sent by the user (optional)
Only if you tap **Send** in “Send feedback” (available in the iPhone/iPad/Mac app; the Android app has no feedback form for now):
- What is sent: the text you write, any screenshots you attach, your email (if you provide it) and, if you leave it on, **technical information** (app and system version, settings, connection type and recent errors). It does **not** include your server addresses, usernames, passwords or driving data.
- How it travels: the app sends it to a **relay hosted on Cloudflare (Workers)** operated by the developer, which forwards it to a **private Telegram chat** of the developer through a bot. The relay does not store the content; Cloudflare may process your IP address to deliver the request and to limit the number of submissions (kept for at most one hour).
- Why: only to read, reproduce and fix the problem or consider your suggestion, and to reply if you left an email.
- How long: the message stays in the developer's Telegram chat until it is deleted; it will be removed when no longer needed, and you can ask for it to be deleted at any time.
- Providers: **Cloudflare, Inc.** and **Telegram Messenger Inc.** act as service providers under their own privacy policies.
- Alternatives: you can use “Send by email” or “Share report” to send it another way.

## Your rights
You can request access, correction or deletion of anything you sent in a comment, and withdraw consent at any time, by writing to the contact address. If you are in the EU/EEA you may complain to your data protection authority.

## Children
Wattboard is not aimed at children under 14 and does not knowingly collect their data.

## Changes
If this policy changes, it will be updated here and in the app with a new date.
