---
title: MemoryVeil Privacy Policy
---

<img src="../logo.svg" alt="Octothorpe" width="260" />

# Privacy Policy for MemoryVeil

**Effective Date:** January 15, 2026
**Last Updated:** February 28, 2026

## Introduction

MemoryVeil is committed to protecting your privacy. This Privacy Policy explains how MemoryVeil ("we", "our", or "the app") handles your information.

**The short version:** MemoryVeil stores everything locally on your device by default. We don't collect, transmit, or store any of your data on external servers. Your photos, videos, and personal information never leave your device unless you explicitly enable optional iCloud backup.

## Information We Collect

### Photos and Videos
- **What:** Images and videos you choose to add to your vault
- **How:** Imported from your Photos library or Files app
- **Storage:** Encrypted using AES-256-GCM encryption and stored locally on your device
- **Purpose:** To provide the core functionality of the app (delayed access to media)

### Journal Entries
- **What:** Text entries you write when requesting access to your content
- **Storage:** Stored locally on your device (and optionally backed up to iCloud if enabled)
- **Purpose:** To encourage mindful reflection before accessing your vault content

### Usage Data
- **What:** Your app settings (delay times, preview preferences), access request history, vault metadata, and usage statistics (completion rates, streaks)
- **Storage:** Stored locally on your device
- **Purpose:** To provide app functionality, maintain your preferences, and show you your progress

### Biometric Data
- **What:** Face ID or Touch ID authentication
- **How:** Handled entirely by iOS Secure Enclave
- **Storage:** Never accessed or stored by MemoryVeil. Apple's biometric data never leaves your device's Secure Enclave
- **Purpose:** To protect access to your vault

## How We Use Your Information

All information is used solely to provide app functionality:
- **Photos/Videos:** Encrypted storage and delayed access according to your settings
- **Journal Entries:** Stored with access requests to help you reflect on your usage patterns
- **Settings:** Remember your preferences between app sessions
- **Access History:** Track your usage patterns and statistics within the app
- **Notifications:** Alert you when content is ready to view or when the vault relocks

## Data Storage and Security

### Local Storage (Default)
- **All data is stored on your device by default**
- No data transmission to external services
- No analytics or tracking services

### Optional iCloud Backup
- **CloudKit Backup:** You can optionally enable iCloud backup in Settings to back up your vault to your private iCloud database
- **What Is Backed Up:** Encrypted vault items, vault metadata, and settings
- **Single-Device Ownership:** Only one device owns the backup at a time to prevent conflicts
- **Encryption Key Sync:** Your encryption key is stored in iCloud Keychain (Apple's secure, end-to-end encrypted service)
- **Control:** You can disable backup at any time in Settings; this is entirely optional
- **Privacy:** Even with backup enabled, Apple cannot read your encrypted media content

### Encryption
- **Algorithm:** AES-256-GCM (Advanced Encryption Standard with Galois/Counter Mode)
- **Key Storage:** iOS Keychain (hardware-backed when available), optionally synced via iCloud Keychain
- **File Storage:** Encrypted vault files stored in app's document directory with `.enc` extension
- **Thumbnails:** Blurred for privacy (normal or heavy blur)

## Third-Party Services

### Apple Services Used

**StoreKit 2 (In-App Purchases)**
- Used for the optional Pro lifetime upgrade and commitment seal packs
- Transactions processed entirely by Apple
- We do not receive or store your payment information
- Purchase status cached locally for offline access

**CloudKit (Optional)**
- Used only if you enable iCloud backup
- Stores encrypted vault data in your private iCloud database
- Apple cannot decrypt your encrypted media content

**iCloud Keychain (Optional)**
- Used to sync your encryption key across devices if iCloud backup is enabled
- End-to-end encrypted by Apple

### Services We Do NOT Use
- No analytics services (Google Analytics, Firebase, Mixpanel, etc.)
- No advertising networks
- No crash reporting services (Sentry, Bugsnag, etc.)
- No external cloud storage providers
- No social media integrations
- No custom backend servers

## In-App Purchases

MemoryVeil offers optional in-app purchases:

### Pro Lifetime (Non-Consumable)
- One-time purchase that unlocks: iCloud backup, extended delays up to 90 days, custom viewing windows per item (15 minutes to 8 hours), commitment lock, emergency access, and custom color tag names
- Includes Family Sharing support
- Includes 3 starter commitment seals and 1 Emergency Key
- No subscription; you own it forever

### Commitment Seal Packs (Consumable)
- Seals are tokens consumed when applying a commitment lock to a vault item
- Commitment lock makes an item completely inaccessible for the chosen duration with no bypass
- Available as packs: 1 seal, 5 seals, or 15 seals
- Seal balance is stored locally (and backed up to iCloud if backup is enabled)

### Emergency Key (Consumable)
- Emergency Keys instantly unlock all items in your vault (except commitment-locked items) in genuine emergencies
- Available as single keys
- Pro purchase includes 1 Emergency Key

**Privacy Note:** We do not receive your payment details. All transactions are processed by Apple through StoreKit. We only receive confirmation of purchase completion.

## Permissions

MemoryVeil requests the following permissions:

### Required Permissions
- **Photos Library Access:** To import photos and videos you choose to add to your vault
- **Save to Camera Roll:** To save unlocked photos and videos back to your Camera Roll when you choose
- **Biometric Authentication (Face ID/Touch ID):** To secure access to your vault
- **Notifications:** To alert you when your content is ready to view or when the vault relocks

### Optional Permissions
- **Files Access:** To import media from Files app, iCloud Drive, or other file providers

**Important:** You control which photos and files MemoryVeil can access. You can grant limited photo library access.

## Data Deletion

### Deleting Content
- Delete individual items: Swipe or use the menu in detail view
- Delete all content: Settings > Data > Delete All Data
- Deleted items enter a 30-day recovery bin before permanent deletion
- You can restore items from the recovery bin or permanently delete them immediately

### Deletion with iCloud Backup Enabled
- When you delete items, the corresponding backup is also deleted from iCloud
- Permanently deleted content is removed from both your device and your iCloud backup

### Uninstalling the App
- Uninstalling MemoryVeil permanently deletes all local app data from your device
- This includes all encrypted photos, videos, settings, and history
- If iCloud backup was enabled, data in iCloud follows Apple's standard deletion policies
- This action cannot be undone

## Data Sharing

**MemoryVeil does not share your data with anyone.** Specifically:
- No data is transmitted to us or any third party
- No data is sold or monetized
- No data is used for advertising or profiling
- Your photos and videos remain private on your device (or in your private iCloud if backup is enabled)

## Children's Privacy

MemoryVeil does not knowingly collect personal information from children under 13. The app is rated 17+ due to its intended use case (impulse control for sensitive content). If you believe a child under 13 has used MemoryVeil, please contact us.

## Data Portability

### Export Your Data
You can export your content at any time:
- Settings > Data > Export All Media
- Exports decrypted versions of your photos and videos
- No proprietary formats; standard image and video files

### No Lock-In
- Your content can be exported at any time
- Standard file formats (JPEG, PNG, HEIC, MP4, MOV, etc.)
- No vendor lock-in or proprietary encryption

## Session Management

MemoryVeil requires biometric re-authentication every time the app returns to the foreground (if biometric lock is enabled). Each unlocked item has an independent viewing window — after the window expires, the item automatically re-locks and requires a new access request with a full delay.

A privacy overlay hides vault content when the app is in the app switcher to prevent screenshot leakage.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be reflected by updating the "Last Updated" date at the top of this policy. Continued use of MemoryVeil after changes constitutes acceptance of the updated policy.

## International Users

MemoryVeil is designed for worldwide use. Since all data is stored locally on your device by default:
- No data crosses international borders (unless you enable iCloud backup, which uses Apple's global infrastructure)
- Your data remains under your control in your jurisdiction
- iCloud backup data is subject to Apple's privacy practices and regional data storage policies

## Your Rights

Since all data is stored locally on your device (or optionally backed up to your private iCloud), you have complete control:
- **Right to Access:** All your data is on your device
- **Right to Delete:** Delete items individually or all at once
- **Right to Export:** Export your content at any time
- **Right to Modify:** Change settings and content freely

## Legal Basis for Processing (GDPR)

For users in the European Economic Area:
- Processing is based on **consent** (you choose what to add to the vault)
- Processing is necessary for **contract performance** (providing the app service)
- All processing occurs locally on your device under your control
- Optional iCloud backup uses Apple's GDPR-compliant infrastructure

## California Privacy Rights (CCPA)

For California residents:
- **We do not sell personal information**
- **We do not share personal information with third parties**
- All data remains on your device (or in your private iCloud) under your control

## Technical Details

### Data We Do NOT Collect
- Name, email, phone number, or contact information
- Device identifiers for tracking
- IP addresses or location data
- Browsing history or app usage analytics
- Crash reports or diagnostic data
- Advertising identifiers

### Encryption Details
- **Algorithm:** AES-256-GCM (Authenticated Encryption with Associated Data)
- **Key Size:** 256-bit
- **Key Storage:** iOS Keychain (hardware-backed when available)
- **Key Sync:** Optional via iCloud Keychain (end-to-end encrypted)
- **File Storage:** Encrypted vault files stored in app's document directory
- **Content Hash:** SHA-256 used for duplicate detection (hash stored locally only)

## Contact Us

If you have questions about this Privacy Policy or MemoryVeil's privacy practices:

**Company:** Octothorpe OÜ
**Email:** info@octothorpe.ee
**Website:** https://octothorpe.ee

## Consent

By using MemoryVeil, you consent to this Privacy Policy.

---

**Summary:**
- All data stored locally on your device by default
- Optional iCloud backup available (you control it)
- No external servers, no tracking, no analytics
- AES-256-GCM encryption for your content
- You control your data completely
- In-app purchases processed by Apple only
- No third-party services
- Export your data anytime
- Delete your data anytime
