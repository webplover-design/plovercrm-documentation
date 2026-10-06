---
title: "Understand Workspace Connection Status"
category: "Team, Workspace, and Permissions"
platform: web
status: Draft
last_verified: ""
---

# Understand Workspace Connection Status

The workspace connection status tells you whether PloverCRM can communicate with the selected WordPress website and load its CRM data. Check this status before troubleshooting missing leads, unavailable settings, or failed updates.

![Placeholder screenshot of workspace connection status](images/placeholder-workspace-connection-status.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing a connected, unavailable, or attention-required status after the workflow and privacy review are complete.

## Before you begin

- Sign in to the PloverCRM Web Dashboard.
- Select the website or workspace you want to check.
- Make sure you are allowed to view connection details.
- Do not copy private URLs, credentials, or connection tokens into notes or screenshots.

## Check the connection status

1. Open the workspace or website selector.
2. Select the affected workspace.
3. Open **Workspace Settings**, **Connection**, or the status area shown by PloverCRM.
4. Review the connection label, status indicator, and most recent message.
5. Check whether PloverCRM reports the workspace as connected, unavailable, disconnected, or requiring attention.
6. If a **Test Connection**, **Reconnect**, or **Refresh** action is available, use it once.
7. Wait for the result before leaving the page.

The exact status labels can vary by PloverCRM version and workspace configuration. Treat the message beside the status as the primary guidance.

## What the status means

### Connected or available

PloverCRM can reach the connected website. If data is still missing, check the selected workspace, data refresh status, source configuration, and your permissions.

### Disconnected or unavailable

PloverCRM cannot use the website connection at this time. Confirm that the PloverCRM plugin is installed and active, the website is online, and the connection details have not changed.

### Action required

The workspace may need setup, plugin activation, administrator approval, or a plan-related action. Follow the instruction shown in the notice rather than changing unrelated settings.

### Checking or syncing

PloverCRM is still testing or updating the connection. Wait for the operation to finish. Avoid repeatedly clicking the action or closing the page during the check.

## If the status is not connected

1. Confirm that you selected the intended website.
2. Check that the PloverCRM plugin is active in WordPress.
3. Confirm that the website is online and accessible to your administrator.
4. Ask a WordPress administrator to review the plugin connection settings.
5. Return to PloverCRM and run the connection test again.
6. If the test fails, record the non-sensitive message and use [Troubleshoot Workspace Connection](../14-web-troubleshooting/04-troubleshoot-workspace-connection.md).

> **Security note:** Never send passwords, tokens, private URLs, or full connection details in a support request. Use the approved PloverCRM credential or support flow.

## Related articles

- [Understand WordPress-Hosted Workspace Behavior](03-understand-wordpress-hosted-workspace-behavior.md)
- [Manage Saved Browser Workspaces](01-manage-saved-browser-workspaces.md)
