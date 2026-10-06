---
title: "Troubleshoot Data Refresh"
category: "Mobile Troubleshooting"
categories:
  - "PloverCRM Mobile App"
  - "Mobile Troubleshooting"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Mobile Troubleshooting"
  - "data refresh"
  - "workspace data"
  - "troubleshooting"
  - "mobile support"
platform: mobile
status: Draft
last_verified: ""
---
# Troubleshoot Data Refresh

Use this guide when PloverCRM Mobile shows old workspace information or cannot complete a data refresh.

## Refresh workspace data

1. Open PloverCRM.
2. Tap **Settings**.
3. Under **App preferences**, tap **Data & Sync**.
4. Confirm that the intended workspace is selected.
5. Review **Sync Status**.
6. Tap **Refresh Workspace Data**.
7. Wait for PloverCRM to finish.

PloverCRM can show **Refreshing Data...** while the refresh is running and **Workspace data refreshed successfully** when it finishes.

![Placeholder image of the PloverCRM Data and Sync troubleshooting screen](images/placeholder-mobile-data-sync-troubleshooting.png)

> **Image placeholder:** Replace this image path with the final Data & Sync troubleshooting screenshot when it is available.

## Check Sync Status

Review these values before and after refreshing:

- **Workspace** — The workspace being refreshed.
- **Last Sync** — The most recent completed refresh.
- **Next Auto-Refresh** — The next scheduled refresh, when available.
- **Connected** — The displayed connection status.
- **Update Available** — A newer workspace update is available.

If the app has never completed a refresh, Last Sync can show **Never synced**.

## No workspace is selected

If PloverCRM shows **No workspace selected**:

1. Open [Manage Workspaces](../05-settings-and-preferences/04-manage-workspaces.md).
2. Select a saved workspace or add a workspace.
3. Return to **Data & Sync**.
4. Try the refresh again.

## Refresh fails

If PloverCRM shows **Failed to refresh workspace data**:

1. Confirm that the intended workspace is selected.
2. Check the workspace connection status.
3. Open [Manage Workspaces](../05-settings-and-preferences/04-manage-workspaces.md) and reconnect if required.
4. Return to Data & Sync and try again.

## Information still looks old

1. Confirm that you are viewing the same workspace shown in Sync Status.
2. Wait for the success message before leaving Data & Sync.
3. Return to the affected screen and allow it to reload.
4. Refresh again if the information is still outdated.

Workspace information remains separate between saved workspaces. A refresh for one workspace does not update another workspace.

## Refresh the Dashboard

Pull down on the Dashboard to request updated Dashboard statistics, stages, and reminders. Use **Data & Sync** when you need to refresh the broader local workspace data.

## Troubleshooting

### Refresh remains in progress

Wait for the current refresh to finish before starting another one. If it does not finish, leave Data & Sync, reopen it, and try again later.

### The connection is unavailable

Resolve the workspace connection issue first. See [Troubleshoot Workspace Connection](02-troubleshoot-workspace-connection.md).

### Refresh succeeds but a record is missing

Confirm that the record belongs to the selected workspace and that your role can view it. Then refresh again and check the relevant list or filter.

## Related articles

- [Refresh Workspace Data](../05-settings-and-preferences/12-refresh-workspace-data.md)
- [Troubleshoot Workspace Connection](02-troubleshoot-workspace-connection.md)
- [Dashboard](../02-navigation-and-dashboard/02-dashboard.md)
- [Mobile App Navigation](../02-navigation-and-dashboard/01-mobile-app-navigation.md)
