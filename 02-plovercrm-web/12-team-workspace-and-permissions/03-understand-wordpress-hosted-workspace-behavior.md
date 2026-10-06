---
title: "Understand WordPress-Hosted Workspace Behavior"
category: "Team, Workspace, and Permissions"
platform: web
status: Draft
last_verified: ""
---

# Understand WordPress-Hosted Workspace Behavior

A WordPress-hosted workspace uses a connected WordPress website as the source of its PloverCRM data and configuration. This affects where administrators make changes and how those changes appear in the PloverCRM Web Dashboard.

![Placeholder screenshot of a WordPress-hosted workspace in PloverCRM](images/placeholder-wordpress-hosted-workspace.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the relationship between a connected website and its PloverCRM workspace after the workflow and privacy review are complete.

## How the workspace works

- The WordPress website hosts the connected PloverCRM plugin.
- The plugin provides the connection between the website and the PloverCRM workspace.
- The PloverCRM Web Dashboard displays the workspace data available through that connection.
- Website administrators manage WordPress and plugin settings from the WordPress dashboard.
- CRM users manage leads and CRM settings from the PloverCRM Web Dashboard when their role allows it.

The available features depend on the connection, workspace configuration, user role, and enabled PloverCRM features.

## Identify the correct workspace

1. Sign in to the PloverCRM Web Dashboard.
2. Open the workspace or website selector.
3. Review the workspace name and connected website.
4. Select the workspace you intend to manage.
5. Check the connection status before editing records or settings.

If you manage multiple websites, do not assume that the workspace currently open in your browser is the one you need.

## Know where to make a change

Use the **PloverCRM Web Dashboard** for tasks such as:

- Reviewing and updating leads.
- Managing activities, reminders, lists, tags, and pipeline stages.
- Configuring workspace-level CRM preferences.
- Reviewing data sources and workspace connection notices.

Use the **WordPress dashboard** for tasks such as:

- Installing or activating the PloverCRM plugin.
- Reviewing plugin settings.
- Managing WordPress users and site administration.
- Checking whether the website is online and accessible.

If a setting is not visible in one dashboard, it may belong to the other administration area. Ask a site or workspace administrator before changing it.

## After a WordPress change

1. Save the change in WordPress.
2. Return to the PloverCRM Web Dashboard.
3. Select the connected workspace again.
4. Check the connection status.
5. Refresh workspace data when the feature is available.
6. Confirm the expected result with approved test data if needed.

> **Caution:** Changes made in WordPress can affect the connection and the CRM experience for the whole workspace. Coordinate plugin, user, and site changes with the website administrator.

## Related articles

- [Understand Workspace Connection Status](02-understand-workspace-connection-status.md)
- [Download, Install, and Connect the PloverCRM Plugin](../01-getting-started/03-download-the-plovercrm-plugin.md)
