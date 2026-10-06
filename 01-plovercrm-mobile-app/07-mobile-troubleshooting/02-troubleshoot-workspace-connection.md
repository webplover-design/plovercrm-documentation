---
title: "Troubleshoot Workspace Connection"
category: "Mobile Troubleshooting"
categories:
  - "PloverCRM Mobile App"
  - "Mobile Troubleshooting"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Mobile Troubleshooting"
  - "troubleshooting"
  - "mobile support"
platform: mobile
status: Draft
last_verified: ""
---
# Troubleshoot Workspace Connection

Use this guide when a saved PloverCRM workspace shows a connection warning, cannot switch, or needs updated credentials.

## Check the connection status

1. Open PloverCRM.
2. Tap **Settings**.
3. Tap **Workspace** or **Workspace Settings**.
4. Review the saved workspace list.

A workspace that needs attention can show **Reconnect required**.

![Placeholder image of the PloverCRM workspace connection warning](images/placeholder-mobile-workspace-connection-troubleshooting.png)

> **Image placeholder:** Replace this image path with the final workspace connection troubleshooting screenshot when it is available.

## Update saved credentials

1. Open **Workspace Settings**.
2. Select the affected workspace.
3. Tap **Edit Credentials**.
4. Check the **Site URL**, **Username**, and **Password**.
5. Tap **Test Connection**.
6. Tap **Save Changes** after the test succeeds.

PloverCRM can show **Connection successful!** after a successful test and **Credentials updated successfully!** after saving.

> **Security note:** Enter credentials only in the PloverCRM sign-in or credential screen. Do not share your password in support requests or screenshots.

## Common connection messages

### Invalid username or password

PloverCRM shows **Invalid username or password. Please try again.** Check the username and password for the selected workspace. If you recently reset the password, enter the new password.

### Site not found

PloverCRM shows **Site not found. Please check the URL.** Confirm the Site URL with your site administrator and correct it before testing again.

### Could not connect to the server

PloverCRM can show **Could not connect to the server. Please check the URL and your internet connection.** Confirm the website address and try again later. Ask your site administrator to confirm that the website is available.

### CRM service temporarily unavailable

PloverCRM can show **CRM service is temporarily unavailable. Please try again later.** Wait and test the connection again instead of repeatedly changing valid credentials.

## Switch to another workspace

If the current workspace cannot reconnect:

1. Open **Workspace Settings**.
2. Find another saved workspace.
3. Tap the workspace you want to use.
4. Wait for PloverCRM to switch.

If no other workspace is saved, PloverCRM can show **No other workspaces available**. Add another workspace or update the current credentials.

## Review setup requirements

If connection succeeds but setup is incomplete, PloverCRM can direct you to complete the required setup in the hosted WordPress app. Follow the setup message and contact your site administrator if you do not have permission to complete it.

## Troubleshooting

### Switching fails

PloverCRM can show **Failed to switch workspace. Please try again.** Try again, then update the selected workspace credentials if the warning continues.

### The workspace name or URL is wrong

Open the workspace settings and compare the saved Site URL with the address provided by your site administrator. Do not edit the URL unless you are sure the replacement is correct.

### Data from another workspace is displayed

Confirm the workspace marked **(Current)**. Switch to the intended workspace, then refresh workspace data.

## Related articles

- [Manage Workspaces](../05-settings-and-preferences/04-manage-workspaces.md)
- [Refresh Workspace Data](../05-settings-and-preferences/12-refresh-workspace-data.md)
- [Troubleshoot Mobile Login](01-troubleshoot-mobile-login.md)
- [Create a PloverCRM Account and Log In](../01-getting-started/02-create-a-plovercrm-account-and-log-in.md)
