---
title: "Manage Workspaces"
category: "Settings and Preferences"
categories:
  - "PloverCRM Mobile App"
  - "Settings and Preferences"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Settings and Preferences"
  - "settings"
  - "preferences"
platform: mobile
status: Draft
last_verified: ""
---
# Manage Workspaces

Manage the PloverCRM workspaces saved on your mobile device. You can add a workspace, switch between saved workspaces, update its connection details, or remove it.

## Open Workspace Settings

1. Open PloverCRM.
2. Open **Settings**.
3. Tap **Workspace Settings**.

![Placeholder image of PloverCRM Workspace Settings](images/placeholder-mobile-workspace-settings.png)

> **Image placeholder:** Replace this image path with the final Workspace Settings screenshot when it is available.

## Add a workspace

1. Open **Workspace Settings**.
2. Tap **Add New Workspace**.
3. Sign in with the site URL, username, and password for the workspace you want to add.
4. Complete the connection or setup steps shown by PloverCRM.
5. Return to the app after the workspace has been added.

A workspace that is already saved on the device cannot be added again for the same site. Remove the saved workspace first if you need to sign in with another account for that site.

## Switch between saved workspaces

1. Open **Workspace Settings**.
2. Find the **Switch Workspace** section.
3. Review the saved workspace list.
4. Tap the workspace you want to use.
5. Wait for PloverCRM to finish switching.

The current workspace is marked **(Current)**. If a workspace needs updated credentials, PloverCRM shows **Reconnect required** beside it.

You can also switch workspaces from the app header:

1. Tap the current workspace name or the arrow beside it.
2. Review the saved workspaces.
3. Tap the workspace you want to open.

![Placeholder image of the PloverCRM saved workspace switcher](images/placeholder-mobile-switch-saved-workspaces.png)

> **Image placeholder:** Replace this image path with the final saved-workspace switcher screenshot when it is available.

After you switch, the Dashboard, leads, lists, tags, stages, reminders, and other workspace information update to match the selected workspace. Information from one workspace remains separate from information in another workspace.

## Edit workspace connection details

Use **Edit Credentials** when a saved workspace needs to reconnect or when its connection details have changed.

1. Open **Workspace Settings** for the workspace.
2. Tap **Edit Credentials**.
3. Update the **Site URL**, **Username**, or **Password**.
4. Tap **Test Connection** to verify the details.
5. Tap **Save Changes**.

PloverCRM can show **Connection successful!** after a successful test and **Credentials updated successfully!** after the changes are saved.

If the workspace needs reconnection, PloverCRM can show **Workspace selected. Update its credentials to reconnect.** Select **Edit Credentials** to update the connection.

## Remove a workspace

1. Open **Workspace Settings** for the workspace you want to remove.
2. Scroll to **Danger Zone**.
3. Tap **Remove Workspace**.
4. Review the confirmation dialog.
5. Tap **Delete** only when you are certain.

For a demo workspace, the action can be labeled **Leave Demo** instead.

> **Warning:** Removing a workspace is destructive. For a regular workspace, PloverCRM warns that all data associated with the workspace will be permanently deleted. Confirm that you no longer need the saved workspace before choosing **Delete**.

The confirmation message for a regular workspace includes:

> **Are you sure you want to delete the workspace? This action cannot be undone.**

A demo workspace uses a separate confirmation asking whether you want to leave the demo workspace.

## What happens next

- Adding saves another workspace for later use on the device.
- Switching changes the active workspace in the app.
- Updating credentials reconnects the saved workspace.
- Removing the current workspace selects another saved workspace when one is available.
- Removing the last saved workspace returns you to the login screen.

## Troubleshooting

### No other workspaces are available

The **Switch Workspace** section shows **No other workspaces available** when only one workspace is saved. Use **Add New Workspace** to connect another workspace.

### The workspace needs reconnection

Tap **Edit Credentials**, correct the connection details, use **Test Connection**, and then save the changes. If you do not have the correct credentials, contact the site administrator.

### The workspace cannot be added

Review the message shown by PloverCRM. The workspace may already be saved, the connection details may be invalid, or your account may not have CRM access.

### Switching fails

PloverCRM can show **Failed to switch workspace. Please try again.** Try again and select the workspace once more. If the issue continues, update the workspace connection details.

## Related articles

- [Mobile App Navigation](../02-navigation-and-dashboard/01-mobile-app-navigation.md)
- [Create a PloverCRM Account and Log In](../01-getting-started/02-create-a-plovercrm-account-and-log-in.md)
- [Settings Overview](01-settings-overview.md)
