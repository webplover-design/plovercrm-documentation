---
title: "Refresh and Load Leads"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Refresh and Load Leads

Use **Refresh leads** at the top of the **All Leads** page when you want PloverCRM to request the latest lead data from the selected workspace. Refreshing can update the lead count, table rows, filters, and visible field values; it does not create, edit, or delete a lead.

![Placeholder screenshot of the Refresh leads button](images/placeholder-refresh-and-load-leads.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the **Refresh leads** button and the loading state. Redact customer names, contact details, and custom-field values before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads** and confirm the workspace and connected website.
- Finish or cancel unsaved edits before refreshing.
- Note any active search, list, tag, date, or stage filters so you can confirm they remain correct.

## Refresh the leads table

1. Open **All Leads**.
2. Check the workspace name in the header.
3. Review the current lead count, filters, and visible rows.
4. Select **Refresh leads** in the toolbar above the table.
5. Wait while PloverCRM loads the latest results.
6. Do not click **Refresh leads** repeatedly while the request is processing.
7. Review the updated count, table rows, and any status message.
8. Confirm that the active filters and selected columns still match your task.

## Understand what refresh can change

After a refresh, you may see:

- A new total lead count.
- Newly received leads from connected forms or advertising sources.
- Updated **Created At** or **Submitted At** values.
- Changed list, tag, stage, assignee, or custom-field values.
- Different rows on the current page because records were added or updated.
- A connection, loading, or error notice.

A refresh shows the latest available data. It does not guarantee that an external source has already delivered an event or that an asynchronous import has finished.

## Refresh after a new lead or source event

1. Wait for the form, data source, or import to report that the event was accepted.
2. Open **All Leads**.
3. Clear or adjust filters if the new lead may not match the current view.
4. Select **Refresh leads**.
5. Search for the lead using a safe, approved identifier.
6. Open the matching row and confirm its source, lists, stage, and other expected values.

## Refresh a filtered result

1. Review the active filter chips above the table.
2. Select **Refresh leads**.
3. Wait for the filtered table to reload.
4. Confirm that the same filters remain active.
5. Check the result count and visible range in the table footer.
6. Clear filters only when you intend to review a broader result set.

## What to verify

After refreshing, confirm:

- The workspace is still the intended workspace.
- The lead total and visible rows finished loading.
- Active filters, page size, page number, and visible columns are understood.
- A newly expected lead appears only if its source has completed processing.
- No pending edit or bulk selection was unintentionally submitted or lost.

## Troubleshooting

- If the count does not change, confirm that the source event or import completed and that filters are not hiding the record.
- If the table is blank, wait for loading to finish, clear filters, and check the workspace connection status.
- If the refresh button is unavailable, check your role, browser state, and whether another request is still running.
- If a lead appears with incomplete values, review the data-source log or import mapping rather than editing around the source problem.
- If results remain stale after one refresh, stop repeating the request and record the non-sensitive status message for an administrator or support.

> **Security and privacy:** Refreshing can reveal newly received customer information. Use approved accounts and devices, avoid screenshots containing real contact details, and redact customer data before sharing diagnostics.

## Related articles

- [Understand the All Leads Screen](01-understand-the-all-leads-screen.md)
- [Filter Leads by List, Tag, Stage, or Date](03-filter-leads-by-list-tag-stage-or-date.md)
- [Review Data Source Logs](../08-data-sources-and-imports/02-review-data-source-logs.md)
