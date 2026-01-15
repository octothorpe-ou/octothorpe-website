<p align="center">
  <img src="../logo.svg" alt="Octothorpe" width="400" />
</p>

# Privacy Policy for Memoryveil

**Effective Date:** January 15, 2026
**Last Updated:** January 15, 2026

## Introduction

Memoryveil is committed to protecting your privacy. This Privacy Policy explains how Memoryveil ("we", "our", or "the app") handles your information.

**The short version:** Memoryveil stores everything locally on your device by default. We don't collect, transmit, or store any of your data on external servers. Your photos, videos, and personal information never leave your device unless you explicitly enable optional iCloud sync.

## Information We Collect

### Photos and Videos
- **What:** Images and videos you choose to add to your vault
- **How:** Imported from your Photos library, Files app, or shared from other apps
- **Storage:** Encrypted using AES-256-GCM encryption and stored locally on your device
- **Purpose:** To provide the core functionality of the app (delayed access to media)

### Journal Entries
- **What:** Text entries you write when requesting access to your content
- **Storage:** Stored locally on your device (and optionally synced to iCloud if enabled)
- **Purpose:** To encourage mindful reflection before accessing your vault content

### Usage Data
- **What:** Your app settings (delay times, preview preferences), access request history, vault metadata, and usage statistics (completion rates, streaks)
- **Storage:** Stored locally on your device
- **Purpose:** To provide app functionality, maintain your preferences, and show you your progress

### Biometric Data
- **What:** Face ID or Touch ID authentication
- **How:** Handled entirely by iOS Secure Enclave
- **Storage:** Never accessed or stored by Memoryveil. Apple's biometric data never leaves your device's Secure Enclave
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

### Optional iCloud Sync
- **CloudKit Sync:** You can optionally enable iCloud sync in Settings to synchronize your vault across your Apple devices
- **What Syncs:** Encrypted vault items, access request history, journal entries, and settings
- **Encryption Key Sync:** Your encryption key is stored in iCloud Keychain (Apple's secure, end-to-end encrypted service)
- **Control:** You can disable sync at any time in Settings; this is entirely optional
- **Privacy:** Even with sync enabled, Apple cannot read your encrypted content

### Encryption
- **Algorithm:** AES-256-GCM (Advanced Encryption Standard with Galois/Counter Mode)
- **Key Storage:** iOS Keychain (hardware-backed when available), optionally synced via iCloud Keychain
- **File Storage:** Encrypted vault files stored in app's document directory with `.enc` extension
- **Thumbnails:** Blurred according to your privacy settings (light, medium, or heavy blur)

### App Groups
- Memoryveil uses App Groups to share data between the main app and Share Extension
- This data sharing occurs only on your device
- No data leaves your device through the Share Extension

## Third-Party Services

### Apple Services Used

**StoreKit 2 (In-App Purchases)**
- Used for optional skip timer purchases and Pro tier upgrade
- Transactions processed entirely by Apple
- We do not receive or store your payment information
- Purchase status cached locally for offline access

**CloudKit (Optional)**
- Used only if you enable iCloud sync
- Stores encrypted vault data in your private iCloud database
- Apple cannot decrypt your content

**iCloud Keychain (Optional)**
- Used to sync your encryption key across devices if iCloud sync is enabled
- End-to-end encrypted by Apple

### Services We Do NOT Use
- No analytics services (Google Analytics, Firebase, Mixpanel, etc.)
- No advertising networks
- No crash reporting services (Sentry, Bugsnag, etc.)
- No external cloud storage providers
- No social media integrations
- No custom backend servers

## In-App Purchases

Memoryveil offers optional in-app purchases:

### Skip Timer (Consumable)
- One-time purchases to skip the wait timer for a specific access request
- Tiered pricing based on remaining wait time
- Purchase status not tracked beyond the current session

### Pro Lifetime (Non-Consumable)
- One-time purchase for extended features (longer delay options, configurable background thresholds)
- Includes Family Sharing support
- No subscription; you own it forever

**Privacy Note:** We do not receive your payment details. All transactions are processed by Apple through StoreKit. We only receive confirmation of purchase completion.

## Permissions

Memoryveil requests the following permissions:

### Required Permissions
- **Photos Library Access:** To import photos and videos you choose to add to your vault
- **Biometric Authentication (Face ID/Touch ID):** To secure access to your vault
- **Notifications:** To alert you when your content is ready to view or when the vault relocks

### Optional Permissions
- **Files Access:** To import media from Files app, iCloud Drive, or other file providers

**Important:** You control which photos and files Memoryveil can access. On iOS 14 and later, you can grant limited photo library access.

## Data Deletion

### Deleting Content
- Delete individual items: Swipe or use the menu in detail view
- Delete all content: Settings > Data > Delete All Data
- Deleted content is permanently removed from your device

### Deletion with iCloud Sync Enabled
- When you delete items, "tombstone" records are kept for 30 days to prevent deleted items from re-syncing from other devices
- After 30 days, tombstone records are automatically removed
- Deleted content is removed from all synced devices

### Uninstalling the App
- Uninstalling Memoryveil permanently deletes all local app data from your device
- This includes all encrypted photos, videos, settings, and history
- If iCloud sync was enabled, data in iCloud follows Apple's standard deletion policies
- This action cannot be undone

## Data Sharing

**Memoryveil does not share your data with anyone.** Specifically:
- No data is transmitted to us or any third party
- No data is sold or monetized
- No data is used for advertising or profiling
- Your photos and videos remain private on your device (or in your private iCloud if sync is enabled)

## Children's Privacy

Memoryveil does not knowingly collect personal information from children under 13. The app is rated 17+ due to its intended use case (impulse control for sensitive content). If you believe a child under 13 has used Memoryveil, please contact us.

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

Memoryveil uses smart session management to balance security with usability:
- **Active Use:** No interruptions while viewing content
- **Quick Interruptions (< 5 minutes by default):** Seamless resume without re-authentication
- **Extended Breaks (5 minutes - 8 hours by default):** Biometric re-authentication required
- **Long Absence (> 8 hours by default):** Session ends; new access request required

Pro users can customize these thresholds in Settings.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be reflected by updating the "Last Updated" date at the top of this policy. Continued use of Memoryveil after changes constitutes acceptance of the updated policy.

## International Users

Memoryveil is designed for worldwide use. Since all data is stored locally on your device by default:
- No data crosses international borders (unless you enable iCloud sync, which uses Apple's global infrastructure)
- Your data remains under your control in your jurisdiction
- iCloud data is subject to Apple's privacy practices and regional data storage policies

## Your Rights

Since all data is stored locally on your device (or optionally in your private iCloud), you have complete control:
- **Right to Access:** All your data is on your device
- **Right to Delete:** Delete items individually or all at once
- **Right to Export:** Export your content at any time
- **Right to Modify:** Change settings and content freely

## Legal Basis for Processing (GDPR)

For users in the European Economic Area:
- Processing is based on **consent** (you choose what to add to the vault)
- Processing is necessary for **contract performance** (providing the app service)
- All processing occurs locally on your device under your control
- Optional iCloud sync uses Apple's GDPR-compliant infrastructure

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

If you have questions about this Privacy Policy or Memoryveil's privacy practices:

**Developer:** Andrus Suitsu
**Email:** andrus@suitsu.ee
**Website:** https://memoryveil.app

## Consent

By using Memoryveil, you consent to this Privacy Policy.

---

**Summary:**
- All data stored locally on your device by default
- Optional iCloud sync available (you control it)
- No external servers, no tracking, no analytics
- AES-256-GCM encryption for your content
- You control your data completely
- In-app purchases processed by Apple only
- No third-party services
- Export your data anytime
- Delete your data anytime
