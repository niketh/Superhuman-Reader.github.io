# Privacy Policy for Superhuman Reader

**Last Updated:** 11/27/2025

## Overview

Superhuman Reader ("the Extension") is a Chrome browser extension that enables fast, focused reading using Rapid Serial Visual Presentation (RSVP) technology. This Privacy Policy explains what data we collect, how we use it, and your rights regarding your information.

We are committed to protecting your privacy. The Extension is designed with privacy in mind—all processing happens locally in your browser, and no personal data is transmitted to external servers.

## Data Collection

### Information We Store Locally

The Extension stores minimal data locally on your device using Chrome's built-in storage API:

- **Reading Speed Preference**: Your configured words per minute (WPM) setting (a numeric value between 50-1000)
- **Display Preference**: Your preferred words-per-chunk setting (1 or 2 words)

### Default Settings

When you first install the Extension, default settings are automatically configured:
- Default WPM: 300
- Default words per chunk: 1

You can modify or delete these settings at any time through the extension popup interface.

### Data We Do NOT Collect

The Extension does **not** collect, store, or transmit:
- Personal identification information (names, email addresses, etc.)
- Browsing history or visited URLs
- Page content or extracted text
- Search queries
- Location data
- Device information
- Cookies or tracking data
- Any other personal or sensitive information

## Data Storage

### Chrome Storage Sync

Your reading preferences are stored using `chrome.storage.sync`, which:
- Stores data locally on your device
- Optionally syncs your settings across your Chrome browsers if you're signed into Chrome Sync
- Follows Chrome's built-in security and encryption standards

If you disable Chrome Sync, your preferences will only be stored locally on the device where you configured them.

## Permissions Used

The Extension requests the following permissions, each used for essential functionality:

### 1. **activeTab**
- **Purpose**: Accesses the currently active tab only when you explicitly click the extension icon
- **Usage**: Identifies the active webpage and enables communication with content scripts
- **Privacy**: Only grants access on user interaction, not automatically

### 2. **storage**
- **Purpose**: Persists your reading preferences (WPM and words-per-chunk settings)
- **Usage**: Saves and retrieves your settings so you don't need to reconfigure each time
- **Privacy**: Stores only configuration values, no personal data

### 3. **scripting**
- **Purpose**: Injects content scripts to extract readable text from web pages
- **Usage**: Dynamically injects scripts when needed to enable RSVP reading functionality
- **Privacy**: Scripts only run when you explicitly activate reading mode

### 4. **Content Scripts Access (all URLs)**
- **Purpose**: Enables the Extension to work on any website you visit
- **Usage**: Allows extraction of main content from web pages for RSVP reading
- **Privacy**: Scripts are user-triggered only and process content locally

## Data Processing

All data processing occurs **locally in your browser**:

- Content extraction happens in real-time on the page you're viewing
- Text parsing and RSVP display occur entirely within your browser
- No data is sent to external servers or third-party services
- No analytics or tracking is performed

## Data Sharing and Disclosure

We do **not** share, sell, trade, or otherwise transfer your information to any external parties because:
- We do not collect personal data
- All processing happens locally in your browser
- We do not operate any external servers or services
- We do not use third-party analytics or tracking services

## User Rights and Control

You have complete control over your data:

- **View Settings**: Access your stored preferences through the extension popup
- **Modify Settings**: Change your WPM or words-per-chunk preferences at any time
- **Delete Settings**: Remove stored preferences by resetting them or uninstalling the extension
- **Disable Sync**: Prevent cross-device synchronization by disabling Chrome Sync in your browser settings

To delete all stored data:
1. Uninstall the Extension from Chrome, or
2. Manually clear extension data via Chrome's settings: `chrome://settings/content/all`

## Third-Party Services

The Extension does not integrate with any third-party services, APIs, or external servers. All functionality is self-contained within the extension itself.

## Security

While the Extension does not transmit data externally, we recommend:
- Keeping your Chrome browser updated to the latest version
- Using Chrome Sync only if you trust Google's security practices
- Reviewing your browser's privacy settings regularly

## Children's Privacy

The Extension does not knowingly collect any information from children. If you believe a child has provided us with personal information, please contact us, and we will take steps to remove such information.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify users of any material changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting the updated policy on the Chrome Web Store listing

## Your Consent

By using the Extension, you consent to this Privacy Policy and agree to its terms.

## Contact Information

If you have questions or concerns about this Privacy Policy or the Extension's data practices, please contact us through:
- The Chrome Web Store listing's support section
- contactsuperhumanreader@gmail.com

## Compliance

This Extension complies with:
- Google Chrome Web Store's Developer Program Policies
- General data protection principles
- Manifest V3 requirements and best practices

---

*This Privacy Policy applies solely to the Superhuman Reader Chrome Extension and does not cover any third-party websites or services you may access while using the Extension.*
