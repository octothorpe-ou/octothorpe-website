# Group Notification — Documentation

## Overview

Group Notification enables you to @mention all members of a group at once in Confluence and Jira. Instead of typing each name manually, select a group and create a comment that notifies everyone.

---

## Installation

1. Go to the [Atlassian Marketplace listing](https://octothorpe.ee)
2. Click **Get it now** or **Try it free**
3. Select the Confluence or Jira instance where you want to install the app
4. Confirm the installation and approve the required permissions

The app will be available immediately after installation.

---

## Required Permissions

The app requests the following permissions:

| Permission | Why It's Needed |
|------------|-----------------|
| Read groups | To display available groups for selection |
| Read group members | To get the list of members to @mention |
| Read user information | To create properly formatted @mentions |
| Write content | To create comments with @mentions |

---

## Usage

### In Confluence

1. Navigate to any Confluence page
2. Open the **Group Notification** panel *(location depends on your UI configuration)*
3. Select a group from the dropdown
4. Click to create a comment
5. All group members will receive a notification

### In Jira

1. Open any Jira issue
2. Open the **Group Notification** panel
3. Select a group from the dropdown
4. Click to create a comment
5. All group members will receive a notification

---

## Supported Group Types

Group Notification works with any group in your Atlassian instance:

- ✓ Manually created groups
- ✓ LDAP-synced groups
- ✓ Active Directory groups
- ✓ SCIM-provisioned groups

---

## Frequently Asked Questions

### Which Atlassian products are supported?

Confluence Cloud and Jira Cloud.

### Does it work with Data Center or Server?

No, Group Notification is built on Atlassian Forge and only supports Cloud products.

### Can I notify multiple groups at once?

Currently, you can select one group at a time. Run the action multiple times for multiple groups.

### What happens if a group has many members?

All members will be @mentioned in the comment. Be mindful when notifying very large groups.

### Will group members receive email notifications?

Members will receive notifications based on their personal notification settings in Confluence or Jira. If they have email notifications enabled for @mentions, they will receive an email.

### Where is my data stored?

Group Notification runs entirely on Atlassian's Forge platform. No data leaves Atlassian's infrastructure and no data is stored by the app.

---

## Troubleshooting

### I don't see any groups in the dropdown

- Ensure groups exist in your Atlassian instance
- Check that you have permission to view groups
- Try refreshing the page

### The comment wasn't created

- Ensure you have permission to comment on the page or issue
- Check your browser console for any error messages
- Try again or contact support if the issue persists

### Some group members weren't notified

- Verify those users are actually members of the group
- Check that the users have active Atlassian accounts
- Users may have disabled notifications in their settings

---

## Privacy & Security

- **No external servers** — Runs entirely on Atlassian's Forge platform
- **No data storage** — The app does not store any personal data
- **No data export** — Data never leaves Atlassian's infrastructure

For full details, see our [Privacy Policy](PRIVACY_POLICY.md).

---

## Support

Having issues or questions?

- **Email:** support@octothorpe.ee
- **Website:** https://octothorpe.ee

We typically respond within 1-2 business days.

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | January 2026 | Initial release |

