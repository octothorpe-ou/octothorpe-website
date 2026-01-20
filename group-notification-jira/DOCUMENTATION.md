# Group Notification for Jira — Documentation

## Overview

Group Notification for Jira enables you to @mention all members of one or more groups at once in Jira issues. Instead of typing each name manually, select groups and create a comment that notifies everyone.

---

## Installation

1. Go to the [Atlassian Marketplace listing](https://marketplace.atlassian.com/apps/XXXXX)
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
| `read:group:jira` | To display available groups |
| `manage:jira-configuration` | To fetch group member lists |
| `storage:app` | To remember your preferences (recent groups, filters) |

---

## Usage

### Accessing the App

1. Open any Jira issue
2. Click the **...** (more actions) menu in the issue toolbar
3. Select **Notify Group** from the dropdown

### Creating a Group Notification

1. **Filter groups** (optional) — Type in the filter field to narrow down the list
   - Your last filter is remembered between sessions
2. **Select groups** from the multi-select dropdown
   - Select one or multiple groups at once
   - Recently used groups appear first for quick access
   - The app shows the total member count after selection
   - Groups with no active members will show a warning
3. **Add a message** (optional) — Use the rich text editor to include additional context
   - Supports markdown shortcuts: `**bold**`, `*italic*`, `` `code` ``, `- list`
4. **Include group name** (optional) — Check this box to prefix the comment with the group name(s)
5. Click **Notify X members** to create the comment

### After Sending

- A single comment is created mentioning all unique members from selected groups
- Duplicate members across groups are automatically removed
- Each member receives a notification based on their personal notification settings
- The modal auto-closes after successful notification

---

## Features

### Multi-Group Selection
Select multiple groups at once to notify all their members in a single comment. Members appearing in multiple groups are automatically deduplicated.

### Group Filtering
Use the filter field to quickly find groups by name. Your filter is remembered between sessions for convenience.

### Recent Groups
Groups you've recently notified appear at the top of the list, making it faster to notify the same groups again.

### Rich Text Messages
The message editor supports rich text formatting with markdown shortcuts:
- `**bold**` for **bold text**
- `*italic*` for *italic text*
- `` `code` `` for `inline code`
- `- item` for bullet lists

### Group Name Label
Enable "Include group name in comment" to prefix the comment with the group name(s), making it clear which groups were notified.

### Member Count Preview
After selecting groups, the button shows the exact number of unique members that will be notified. When multiple groups are selected, it shows "up to X members" to indicate deduplication.

### Large Group Handling
Groups with more than 1,000 members are truncated. The app displays a warning and mentions only the first 1,000 members per group.

---

## Frequently Asked Questions

### Which Atlassian products are supported?

This app supports **Jira Cloud** only. A separate app is available for Confluence Cloud.

### Does it work with Data Center or Server?

No, Group Notification is built on Atlassian Forge and only supports Cloud products.

### Can I notify multiple groups at once?

Yes! You can select multiple groups from the dropdown. All members will be mentioned in a single comment, and duplicates across groups are automatically removed.

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

- **Report a Bug:** [Create a bug report](https://github.com/octothorpe-ou/group-notification-jira-support/issues/new?template=bug_report.md)
- **Request a Feature:** [Create a feature request](https://github.com/octothorpe-ou/group-notification-jira-support/issues/new?template=feature_request.md)
- **Browse Issues:** [View all issues](https://github.com/octothorpe-ou/group-notification-jira-support/issues)
- **Email:** support@octothorpe.ee
- **Website:** https://octothorpe.ee

We typically respond within 1-2 business days.

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.1.0 | January 2026 | Multi-group selection, rich text editor, group filtering, recent groups |
| 1.0.0 | January 2026 | Initial release with optional messages and group labels |
