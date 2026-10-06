---
title: "Dashboard"
category: "Navigation and Dashboard"
categories:
  - "PloverCRM Mobile App"
  - "Navigation and Dashboard"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Navigation and Dashboard"
  - "navigation"
  - "workspaces"
  - "dashboard"
  - "workspace overview"
platform: mobile
status: Draft
last_verified: ""
---
# Dashboard

The PloverCRM mobile Dashboard gives you a quick view of the current workspace. It includes lead and workspace counts, pipeline stages, lead growth, pending reminders, saved lists, and workspace notices.

## Before you start

- Sign in to the PloverCRM mobile app.
- Select the workspace whose information you want to review.

## Open the Dashboard

1. Open PloverCRM.
2. Sign in if you are not already signed in.
3. Tap **Dashboard** in the bottom navigation bar.
4. Pull down on the Dashboard whenever you want to refresh the available workspace information.

![Placeholder image of the PloverCRM mobile Dashboard](images/placeholder-mobile-dashboard.png)

> **Image placeholder:** Replace this image path with the final mobile Dashboard screenshot when it is available.

## Review pipeline stages

The **Stages** section shows the stages configured for the current workspace. Each stage displays a count.

1. Review the stage names and counts.
2. Tap a stage to open **All Leads** filtered to that stage.
3. Review or manage the leads included in the selected stage.

The stages section may be unavailable if your account does not have permission to view deals, or if no stages have been configured.

![Placeholder image of the PloverCRM Dashboard stages](images/placeholder-mobile-dashboard-stages.png)

> **Image placeholder:** Replace this image path with the final Dashboard stages screenshot when it is available.

## Review lead, list, and tag counts

The summary cards show counts for the current workspace:

- **Leads** — The total number of leads. Tap this card to open **All Leads**.
- **Lists** — The number of lists available in the workspace.
- **Tags** — The number of tags available in the workspace.

These counts describe the selected workspace and can change when you switch workspaces or when workspace data changes.

## View the Lead Growth Graph

The **Lead Growth Graph** shows how the number of leads changes over time. Use it to review the overall direction of lead growth in the current workspace.

The graph is an overview and does not replace the lead list. Open **All Leads** when you need to search for individual leads or review their details.

![Placeholder image of the PloverCRM Lead Growth Graph](images/placeholder-mobile-lead-growth-graph.png)

> **Image placeholder:** Replace this image path with the final Lead Growth Graph screenshot when it is available.

## Review reminders

The **Reminders** section displays up to five pending reminders for the current workspace.

1. Review the reminder title, lead name, and scheduled date or time.
2. Look for the red count badge when one or more displayed reminders are overdue.
3. Tap a reminder to open its details.
4. From the reminder details, update it, mark it complete, delete it, or open the related lead when those actions are available.
5. Tap **See all** to open the complete reminders screen.

If there are no pending reminders, the section displays **No upcoming reminders**.

![Placeholder image of the PloverCRM Dashboard reminders](images/placeholder-mobile-dashboard-reminders.png)

> **Image placeholder:** Replace this image path with the final Dashboard reminders screenshot when it is available.

For more detailed reminder instructions, see [Manage Lead Reminders](../04-add-and-manage-leads/11-manage-lead-reminders.md).

## Filter leads by list

The **Lists** section shows the lists available in the current workspace and the number of leads in each list.

1. Find the list you want to review.
2. Tap the list name or row.
3. PloverCRM opens **All Leads** with that list selected as a filter.
4. Review the filtered leads or clear the filter to return to the full lead list.

Lists that do not contain leads can still appear with a count of zero.

![Placeholder image of the PloverCRM Dashboard lists](images/placeholder-mobile-dashboard-lists.png)

> **Image placeholder:** Replace this image path with the final Dashboard lists screenshot when it is available.

## Refresh Dashboard information

Pull down on the Dashboard to refresh the main Dashboard data. PloverCRM requests updated statistics, stages, and pending reminders for the active workspace.

If the refresh does not complete:

- Pull down again after a short wait.
- Open the relevant workspace settings if the connection problem continues.

## Open other areas

Use the bottom navigation bar to move from the Dashboard to **All Leads**, **Add New Lead**, or **Settings**.

## Troubleshooting

### Statistics or stages are still loading

Wait for the request to finish. If an error message includes **Try again**, tap it when available.

### The Dashboard shows no stages

The workspace may not have any stages configured, or your account may not have permission to view deals. Ask your workspace administrator to confirm the stage configuration and your permissions.

### A Dashboard count looks different from another screen

Confirm that both screens are using the same workspace. Then refresh the Dashboard and open **All Leads** to review the current records.

### A reminder is missing

The Dashboard shows pending reminders and only a limited number of reminders at a time. Tap **See all** to open the full reminders screen, and check the reminder status and scheduled date.

### A list is missing

The Dashboard hides certain system lists. Open **All Leads** or the list-management settings to review the lists available to your account.

### The Dashboard opens a setup or workspace screen

Follow the instructions shown by PloverCRM. First-time setup must be completed in the hosted WordPress app. If you cannot complete it, ask your site administrator for help.

## Related articles

- [Mobile App Navigation](01-mobile-app-navigation.md)
- [All Leads Screen Overview](../03-all-leads/01-all-leads-screen-overview.md)
- [Search for Leads](../03-all-leads/02-search-for-leads.md)
- [Manage Lead Reminders](../04-add-and-manage-leads/11-manage-lead-reminders.md)
- [Manage Workspaces](../05-settings-and-preferences/04-manage-workspaces.md)
