# Thenote — Privacy Policy

**Last updated:** March 15, 2026

Thenote is a time-locked messaging app developed by Octothorpe OÜ ("we", "us", "our"). We are committed to your privacy.

## Data We Collect

**None.** Thenote does not collect, store, or transmit any personal data.

- Messages are encrypted entirely on your device.
- No accounts, logins, or registrations are required.
- No analytics, tracking, or telemetry is used.
- No cookies are set by the Thenote website.

## How Encryption Works

Thenote uses [drand](https://drand.love) timelock encryption (tlock). Drand is a public, open-source randomness beacon operated by a decentralized network of organizations. Messages are encrypted locally on your device against a future drand round. No server — including ours — can read your messages.

## Network Requests

The app makes network requests only to the public drand beacon network (`api.drand.sh`, `drand.cloudflare.com`, `api2.drand.sh`) to fetch published randomness rounds needed for decryption. These requests contain no personal information.

## Local Storage

- **Messages:** Encrypted messages you create are stored locally on your device using SwiftData.
- **Preferences:** A single preference (`hasSeenOnboarding`) is stored via UserDefaults.
- No data is synced to iCloud or any remote server.

## Shared Links

When you share a sealed message, the encrypted content is embedded directly in the URL. No data is uploaded to any server. The recipient's browser decrypts the message locally using the drand beacon.

## Third-Party Services

Thenote does not integrate any third-party analytics, advertising, or tracking services.

## Children's Privacy

Thenote does not knowingly collect any information from children under 13.

## Changes to This Policy

We may update this policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this policy, contact us at [info@octothorpe.ee](mailto:info@octothorpe.ee).

---

Octothorpe OÜ — Tallinn, Estonia
