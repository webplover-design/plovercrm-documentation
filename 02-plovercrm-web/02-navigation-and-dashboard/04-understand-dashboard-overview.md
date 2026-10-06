---
title: "Understand the Dashboard Overview"
category: "Navigation and Dashboard"
platform: web
status: Draft
last_verified: ""
---

# Understand the Dashboard Overview

The dashboard gives you a quick view of the selected PloverCRM workspace. It brings together headline statistics, pipeline stage summaries, lead growth, reminders, and lists so you can understand current activity before opening individual records.

Use the dashboard as an overview, not as a substitute for checking the underlying leads and date ranges. Each panel reflects the selected workspace, available data, filters, permissions, and enabled features.

![Placeholder screenshot of the PloverCRM dashboard overview](images/placeholder-dashboard-overview.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the dashboard statistics, pipeline summaries, lead growth chart, reminders, and lists. Redact customer names, email addresses, phone numbers, private URLs, credentials, tokens, and other sensitive values before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Select the workspace or connected website you want to review.
- Confirm that your role allows you to view dashboard information.
- Know the reporting period or comparison you want to examine.
- Refresh the workspace only after saving or canceling unsaved work elsewhere.

## Open the dashboard

1. Sign in to the PloverCRM Web Dashboard.
2. Confirm the workspace name and connected website in the header.
3. Select **Dashboard** from the left navigation.
4. Wait for the dashboard panels to finish loading.
5. Check whether the dashboard displays a last-updated time, loading state, or connection notice.
6. If the page is still loading, wait before interpreting a zero, blank, or partial value.

## Understand dashboard statistics

Dashboard statistic cards summarize key workspace totals. Depending on your account, they may include lead counts, new leads, activities, reminders, deals, pipeline value, or other enabled metrics.

1. Read the title of each statistic card before interpreting its number.
2. Check the date period or filter applied to the card, if shown.
3. Compare the value with the previous period only when both periods use the same definition.
4. Select a card when it is interactive and review the filtered records behind the total.
5. Use the underlying lead list to confirm unusual increases or decreases.
6. Do not treat a missing panel as a zero until loading and permission checks are complete.

A statistic can change when records are added, edited, deleted, reassigned, moved between stages, or filtered by date. The number is meaningful only in the context of its label and period.

![Placeholder screenshot of dashboard statistics](images/placeholder-dashboard-statistics.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the dashboard statistic cards and their labels. Redact customer information before publishing it.

## Understand pipeline stage summaries

The pipeline summary groups leads or deals by their current stage. It helps you see where work is concentrated and where follow-up may be needed.

1. Locate the pipeline or stage summary panel.
2. Read the pipeline name and reporting period, if shown.
3. Review each stage label and its record count or value.
4. Compare stage totals with the total leads or deals expected for the same scope.
5. Select a stage when it opens a filtered list.
6. Review the matching records before changing a stage or assigning follow-up work.
7. Open [Manage Pipeline Stages](../10-settings-and-preferences/11-manage-pipeline-stages.md) when the stage definitions themselves need review.

A stage summary is not necessarily a forecast. It reflects the records currently assigned to each stage and may not include records outside your permission scope.

![Placeholder screenshot of pipeline stage summaries](images/placeholder-dashboard-pipeline-stage-summaries.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing stage labels, counts, and values. Redact customer information before publishing it.

## Read the lead growth chart

The lead growth chart shows how lead volume changes over a selected period. Use it to identify patterns and then inspect the leads that produced the change.

1. Locate the lead growth or trend chart.
2. Read the chart title, date range, and interval shown on the axis.
3. Hover over a data point to view its exact value when the chart supports hover details.
4. Compare peaks and drops with known campaigns, imports, form changes, or routing changes.
5. Select a point or chart segment when it opens a filtered lead list.
6. Confirm the result count and date filter in the linked list.
7. Check the data source or import history when the trend does not match expectations.

The chart may show created leads, updated leads, or another defined measure. Read its label carefully before comparing it with a different report.

![Placeholder screenshot of the lead growth chart](images/placeholder-dashboard-lead-growth-chart.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the chart title, period, and hover details without exposing customer data.

## Use dashboard reminders

The reminders panel highlights follow-up tasks associated with leads in the selected workspace.

1. Locate the reminders panel.
2. Review the reminder title, lead association, scheduled time, and status.
3. Select a reminder to open its lead or reminder details when available.
4. Complete the follow-up from the linked lead record.
5. Mark the reminder complete only after the work is actually finished.
6. Snooze or reschedule it when the follow-up is still required but the time has changed.
7. Use [Use the Global Reminders Page](../06-activities-and-reminders/09-use-the-global-reminders-page.md) for a broader review.

Check the displayed time zone before acting on a reminder. Avoid creating a second reminder when an existing item already covers the same follow-up.

## Use dashboard lists

The lists panel provides a quick way to open lead groups organized by saved lists or other workspace categories.

1. Locate the lists panel.
2. Read the list name and lead count.
3. Select a list to open the matching lead records.
4. Confirm that the list filter is visible in the destination page.
5. Review the records before applying an edit or bulk action.
6. Return to the dashboard when you have finished reviewing the list.

A list count can change as leads are added, removed, reassigned, or updated. Do not assume that a count represents the entire workspace.

![Placeholder screenshot of dashboard reminders and lists](images/placeholder-dashboard-reminders-and-lists.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the reminders and lists panels. Redact lead names and contact details before publishing it.

## Refresh dashboard data

1. Confirm that there are no unsaved changes on the current page.
2. Select **Refresh**, **Reload**, or the dashboard refresh control.
3. Wait for all panels to finish loading.
4. Check the updated timestamp or status message.
5. Compare the panels again using the same workspace and reporting period.
6. If the values remain stale, review the workspace connection and data source logs before refreshing repeatedly.

## What to verify

After reviewing the dashboard, confirm:

- The workspace and connected website are correct.
- Every statistic is interpreted with its displayed label and period.
- Pipeline totals, chart values, reminders, and list counts are not still loading.
- Any drill-down list contains the expected filters.
- You reviewed the underlying records before taking a bulk or destructive action.

## Troubleshooting

- If panels are blank, wait for loading to finish, refresh once, and check the workspace connection.
- If totals look wrong, confirm the date range, filters, selected workspace, and your permission scope.
- If a panel is missing, ask an administrator to check whether the feature is enabled for your plan and role.
- If a chart does not match an import or campaign, review the source logs and the chart’s measurement definition.
- If reminders appear at the wrong time, check the account or browser time zone and reminder settings.
- If a drill-down list is empty, clear inherited filters and confirm that the underlying records are within your scope.

> **Security and privacy:** Dashboard screenshots can still reveal customer information through counts, names, chart tooltips, reminders, and list labels. Redact sensitive values and never include passwords, one-time codes, API keys, connection tokens, or private URLs in shared material.

## Related articles

- [Understand the PloverCRM Web Dashboard Layout](01-understand-the-web-app-layout.md)
- [Use Navigation and Header Controls](02-use-navigation-and-header-controls.md)
- [Switch Workspaces or Websites](03-switch-workspaces-or-websites.md)
- [Refresh Workspace Data](06-refresh-workspace-data.md)
