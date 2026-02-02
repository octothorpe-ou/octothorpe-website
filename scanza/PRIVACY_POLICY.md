<img src="../logo.svg" alt="Octothorpe" width="260" />

# Privacy Policy for Scanza

**Effective Date:** February 2, 2026
**Last Updated:** February 2, 2026

## Introduction

Scanza is committed to protecting your privacy. This Privacy Policy explains how Scanza ("we", "our", or "the app") handles your information.

**The short version:** Scanza processes your ticket images using the Claude AI API to extract event details. Images are sent to Anthropic's servers for processing but are not stored by them. Your API key is stored securely on your device.

## Information We Collect

### Ticket Images
- **What:** Photos of tickets you scan using the camera or select from your photo library
- **How:** Captured via camera or imported from Photos
- **Transmission:** Sent to Anthropic's Claude API for text extraction and event parsing
- **Storage:** Images are not stored by Scanza after processing

### API Key
- **What:** Your personal Anthropic API key
- **Storage:** Stored securely in the iOS Keychain on your device
- **Purpose:** To authenticate requests to the Claude API

### Calendar Events
- **What:** Events created from your scanned tickets
- **Storage:** Stored in your device's calendar via EventKit
- **Purpose:** To create calendar events from ticket information

### App Settings
- **What:** Your preferences (default calendar, reminder settings, selected AI model)
- **Storage:** Stored locally on your device using UserDefaults
- **Purpose:** To remember your preferences between app sessions

### Usage Statistics
- **What:** API request counts, token usage, and estimated costs
- **Storage:** Stored locally on your device
- **Purpose:** To help you track your API usage and costs

## How We Use Your Information

All information is used solely to provide app functionality:
- **Ticket Images:** Sent to Claude API for event extraction, then discarded
- **API Key:** Used to authenticate your requests to Anthropic
- **Calendar Events:** Created in your calendar based on extracted ticket data
- **Settings:** Remember your preferences between sessions
- **Usage Statistics:** Display your API usage within the app

## Data Transmission

### Claude API (Anthropic)
- **What is sent:** Ticket images (as base64-encoded data) and text prompts
- **Why:** To extract event details (title, date, time, venue) from your tickets
- **Retention:** Anthropic processes images in real-time and does not store them for training. See [Anthropic's Privacy Policy](https://www.anthropic.com/privacy) for details.
- **Your control:** You provide your own API key; you can revoke it at any time via Anthropic's console

### No Other External Services
- No analytics services
- No advertising networks
- No crash reporting services
- No social media integrations
- No custom backend servers

## Data Storage and Security

### Local Storage
- **API Key:** Stored in iOS Keychain (hardware-backed encryption)
- **Settings:** Stored in UserDefaults
- **Usage Stats:** Stored in UserDefaults
- **Calendar Events:** Stored via iOS EventKit in your calendars

### App Groups
- Scanza uses App Groups to share data between the main app and Share Extension
- This allows you to share tickets from other apps (like Mail or Files)
- Shared files are processed and then deleted

## Permissions

Scanza requests the following permissions:

### Required Permissions
- **Camera:** To capture photos of tickets
- **Photo Library:** To select ticket images from your photos
- **Calendar:** To create events from scanned tickets

### Optional Permissions
- **Microphone:** For voice input (speech-to-text feature)

## Third-Party Services

### Anthropic (Claude API)
- Scanza uses the Claude API to process ticket images
- You must provide your own API key
- Images are processed in real-time
- Anthropic's data retention: See [Anthropic's Privacy Policy](https://www.anthropic.com/privacy)
- API usage is billed directly to your Anthropic account

### Apple Services
- **EventKit:** For calendar integration
- **AVFoundation:** For camera functionality
- **Speech Framework:** For voice input

## Data Deletion

### Removing Your API Key
- Go to Settings > Remove API Key
- Your API key will be deleted from the Keychain

### Deleting Usage Statistics
- Go to Settings > Reset Statistics
- All usage tracking data will be cleared

### Uninstalling the App
- Uninstalling Scanza deletes all local app data
- This includes your API key, settings, and usage statistics
- Calendar events you created remain in your calendar (managed by iOS)
- Your Anthropic account and API usage history remain with Anthropic

## Data Sharing

**Scanza does not share your data with anyone except Anthropic for processing.** Specifically:
- No data is sold or monetized
- No data is used for advertising or profiling
- Ticket images are only sent to Anthropic for processing

## Children's Privacy

Scanza does not knowingly collect personal information from children under 13. The app is not intended for use by children.

## International Users

- Your API key and settings are stored locally on your device
- Ticket images are transmitted to Anthropic's servers for processing
- Anthropic's servers may be located in various jurisdictions
- See [Anthropic's Privacy Policy](https://www.anthropic.com/privacy) for details on their data handling

## Your Rights

Since most data is stored locally on your device, you have complete control:
- **Right to Access:** View your settings and usage stats in the app
- **Right to Delete:** Remove your API key and reset statistics anytime
- **Right to Control:** You provide and control your own API key

## Legal Basis for Processing (GDPR)

For users in the European Economic Area:
- Processing is based on **consent** (you choose to scan tickets)
- Processing is necessary for **contract performance** (providing the app service)
- You control your API key and can revoke access at any time

## California Privacy Rights (CCPA)

For California residents:
- **We do not sell personal information**
- Ticket images are sent to Anthropic solely for processing
- All local data remains on your device under your control

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be reflected by updating the "Last Updated" date at the top of this policy. Continued use of Scanza after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy or Scanza's privacy practices:

**Company:** Octothorpe OÜ
**Email:** info@octothorpe.ee
**Website:** https://octothorpe.ee

## Consent

By using Scanza, you consent to this Privacy Policy.

---

**Summary:**
- Ticket images are sent to Anthropic's Claude API for processing
- Your API key is stored securely in iOS Keychain
- No images are stored after processing
- No analytics, advertising, or tracking
- All settings stored locally on your device
- You control your data completely
