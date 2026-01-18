# Group Notification for Jira — Documentation

## Overview

Group Notification for Jira enables you to @mention all members of a group at once in Jira issues. Instead of typing each name manually, select a group and create a comment that notifies everyone.

---

## Installation

1. Go to the [Atlassian Marketplace listing](https://marketplace.atlassian.com/apps/group-notification-jira)
2. Click **Get it now** or **Try it free**
3. Select the Jira Cloud instance where you want to install the app
4. Confirm the installation and approve the required permissions

The app will be available immediately after installation.

---

## Required Permissions

The app requests the following permissions:

| Permission | Why It's Needed |
|------------|-----------------|
| `read:jira-work` | To access issue context for creating comments |
| `write:jira-work` | To create comments with @mentions on issues |
| `read:group:jira` | To display available groups and fetch member lists |
| `manage:jira-configuration` | To access group management APIs |

---

## Usage

### Accessing the App

1. Open any Jira issue
2. Click the **...** (more actions) menu in the issue toolbar
3. Select **Notify Group** from the dropdown

### Creating a Group Notification

1. **Select a group** from the dropdown menu
   - The app shows the member count after selection
   - Groups with no active members will show a warning
2. **Add a message** (optional) — Include additional context with the notification
3. **Include group name** (optional) — Check this box to prefix the comment with the group name
4. Click **Notify X members** to create the comment

### After Sending

- A comment is created on the issue mentioning all group members
- Each member receives a notification based on their personal notification settings
- The modal auto-closes after successful notification

---

## Features

### Optional Message
Add custom text to accompany the @mentions. The message appears before the member mentions in the comment.

### Group Name Label
Enable "Include group name in comment" to prefix the comment with the group name, making it clear which group was notified.

### Member Count Preview
After selecting a group, the button shows the exact number of members that will be notified.

### Large Group Handling
Groups with more than 1,000 members are truncated. The app displays a warning and mentions only the first 1,000 members.

---

## Supported Group Types

Group Notification works with any group in your Jira Cloud instance:

- ✓ Manually created groups
- ✓ LDAP-synced groups
- ✓ Active Directory groups
- ✓ SCIM-provisioned groups

---

## Frequently Asked Questions

### Which Atlassian products are supported?

This app supports **Jira Cloud** only. A separate app is available for Confluence Cloud.

### Does it work with Data Center or Server?

No, Group Notification is built on Atlassian Forge and only supports Cloud products.

### Can I notify multiple groups at once?

Currently, you can select one group at a time. Run the action multiple times for multiple groups.

### What happens if a group has many members?

Groups are limited to 1,000 members per notification. If a group exceeds this limit, only the first 1,000 members will be @mentioned and you'll see a warning indicator.

### Will group members receive email notifications?

Members receive notifications based on their personal notification settings in Jira. If they have email notifications enabled for @mentions, they will receive an email.

### Where is my data stored?

Group Notification runs entirely on Atlassian's Forge platform. No data leaves Atlassian's infrastructure and no data is stored by the app.

### Can I customize the comment format?

You can add an optional message and choose whether to include the group name. The @mentions format follows Jira's standard mention syntax.

---

## Troubleshooting

### I don't see any groups in the dropdown

- Ensure groups exist in your Jira instance
- Check that you have permission to view groups
- Try refreshing the page

### "Notify Group" doesn't appear in the issue menu

- Ensure the app is installed on your Jira instance
- Check that you have the necessary permissions to use apps
- Try refreshing the issue page

### The comment wasn't created

- Ensure you have permission to comment on the issue
- Check that the issue is not restricted or archived
- Try again or contact support if the issue persists

### Some group members weren't notified

- Verify those users are actually members of the group
- Check that the users have active Atlassian accounts
- For large groups (1,000+ members), only the first 1,000 are mentioned
- Users may have disabled notifications in their settings

### The app shows "Group has no active members"

- The group may be empty
- All members may have inactive or deactivated accounts
- Check the group membership in Jira's group management

---

## Privacy & Security

- **No external servers** — Runs entirely on Atlassian's Forge platform
- **No data storage** — The app does not store any personal data
- **No data export** — Data never leaves Atlassian's infrastructure

For full details, see our [Privacy Policy](PRIVACY_POLICY.md).

---

## Support

Having issues or questions?

- **Email:** info@octothorpe.ee
- **Website:** https://octothorpe.ee

We typically respond within 1-2 business days.

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 2.0.0 | January 2026 | Production release with optional messages and group labels |
| 1.0.0 | January 2026 | Initial release |
