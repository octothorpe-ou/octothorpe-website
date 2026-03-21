# Whetter — Privacy Policy

**Last updated:** March 21, 2026

Whetter is a time-locked messaging app developed by Octothorpe OÜ ("we", "us", "our"). We are committed to your privacy.

## Data We Collect

**None.** Whetter does not collect, store, or transmit any personal data to our servers.

- Messages are encrypted entirely on your device.
- No accounts, logins, or registrations are required.
- No analytics, tracking, or telemetry is used.
- No cookies are set by the Whetter website.

## How Encryption Works

Whetter uses [drand](https://drand.love) timelock encryption (tlock). Drand is a public, open-source randomness beacon operated by a decentralized network of organizations. Messages are encrypted locally on your device against a future drand round. No server — including ours — can read your messages.

## Network Requests

The app makes network requests only to:

- **Drand beacon network** (`api.drand.sh`, `drand.cloudflare.com`, `api2.drand.sh`) — to fetch published randomness rounds needed for decryption. These requests contain no personal information.
- **Apple's App Store servers** — for subscription management via StoreKit. This is handled entirely by Apple's frameworks and subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Local Storage

- **Messages:** Encrypted messages you create or receive are stored locally on your device using SwiftData.
- **Preferences:** App settings (such as onboarding completion) are stored via UserDefaults.
- **Free-tier counter:** The number of shared messages is stored in UserDefaults, Keychain, and iCloud Key-Value Store to sync across your devices and persist across reinstalls. This counter is a single integer — no message content is synced.
- **Deferred links:** If you open a Whetter link while another message is being viewed, the link URL is temporarily stored in UserDefaults until it can be displayed.

## iCloud

Whetter uses iCloud Key-Value Store solely to sync your free-tier message counter across devices signed into the same Apple Account. No message content, encryption keys, or personal data is stored in iCloud.

## Shared Links

When you share a sealed message, the encrypted content is embedded directly in the URL. No data is uploaded to any server. The recipient's browser decrypts the message locally using the drand beacon.

## Subscriptions

Whetter offers an optional monthly subscription for unlimited message sharing. Subscriptions are processed entirely by Apple through StoreKit. We do not receive or store any payment information.

## Third-Party Services

Whetter does not integrate any third-party analytics, advertising, or tracking services. The only external services used are the public drand beacon network (for encryption) and Apple's StoreKit (for subscriptions).

## Children's Privacy

Whetter does not knowingly collect any information from children under 13.

## Changes to This Policy

We may update this policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this policy, contact us at [info@octothorpe.ee](mailto:info@octothorpe.ee).

---

Octothorpe OÜ — Tallinn, Estonia
