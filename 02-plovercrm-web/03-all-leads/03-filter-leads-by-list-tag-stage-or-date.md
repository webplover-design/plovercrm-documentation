---
title: "Filter Leads by List, Tag, Stage, or Date"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Filter Leads by List, Tag, Stage, or Date

Use the filter bar above the leads table to narrow the **All Leads** view by lists, tags, created dates, and pipeline stages. Filters help you review a focused group of leads without changing the underlying records.

![Placeholder screenshot of the All Leads filter bar](images/placeholder-filter-leads-by-list-tag-stage-or-date.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the All Leads filter bar and an open filter menu. Redact lead names, phone numbers, email addresses, custom-field values, and other customer information before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads** from the left navigation.
- Confirm the workspace name and connected website in the header.
- Know which list, tag, stage, or date range you want to review.
- Do not select a bulk action until you have checked the filtered result count.

## Understand the filter bar

The filter bar appears above the lead table. Depending on the workspace, it can include:

- **Lists** — limits results to leads assigned to selected lists.
- **Tags** — limits results to leads with selected tags.
- **Created** — limits results by when leads were created.
- **Stages** — limits results to selected pipeline stages.
- Active filter chips — show selected lists, tags, stages, or other conditions.
- **Clear all** — removes the active filters and returns to the unfiltered view.

A filter button can display a number, such as **Lists 2**, to show how many values are selected in that filter group.

## Filter by lists

1. Open **All Leads**.
2. Select **Lists** in the filter bar.
3. Review the list menu.
4. Select the checkbox beside each list you want to include.
5. Use the list search field when the workspace contains many lists.
6. Confirm the selected count on the **Lists** button.
7. Click outside the menu or select its completion control, if shown.
8. Review the active list chips and the rows displayed in the table.

For example, selecting **Facebook Lead Ads** and **Manual Leads** displays leads assigned to those selected lists. Check the filter behavior shown in your account if your workspace uses a different combination rule.

![Placeholder screenshot of the All Leads list filter menu](images/placeholder-all-leads-list-filter.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the **Lists** menu with fictional list names and selected checkboxes.

## Filter by tags

1. Select **Tags** in the filter bar.
2. Review the available tag values.
3. Select one or more tags.
4. Check the selected count or active tag chips.
5. Close the menu or choose **Apply** when the control is shown.
6. Review the table to confirm that the result set changed.

Remove a tag from the menu when it is no longer part of the review. Do not delete a tag from workspace settings simply because you want to remove it from the current view.

## Filter by created date

1. Select **Created**.
2. Review the available date options or date picker.
3. Choose the required date or date range.
4. Confirm the displayed date format and time zone.
5. Apply the date filter.
6. Check the active date chip and the result count above the table.
7. Open a result only after confirming that its **Created At** value falls within the intended period.

Use **Created** to find leads added during a period. It is different from **Submitted At**, which may describe when a lead was submitted through a source or form.

![Placeholder screenshot of the All Leads created-date filter](images/placeholder-all-leads-created-filter.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the **Created** date filter using a fictional date range.

## Filter by pipeline stage

1. Select **Stages**.
2. Review the available pipeline stages.
3. Select one or more stages.
4. Apply or close the filter menu as shown in your account.
5. Review the active stage chips.
6. Confirm that the visible leads have the expected stage before taking any follow-up action.

A stage filter does not change a lead’s stage. To change stages, open the lead or use an authorized bulk-update workflow after reviewing the selected records.

## Combine filters

You can combine filter groups to create a narrower view.

1. Select the first filter, such as **Lists**.
2. Choose the required values.
3. Select another filter, such as **Tags**, **Created**, or **Stages**.
4. Choose its values.
5. Review every active chip before interpreting the results.
6. Check the result count and visible rows.
7. Remove one condition at a time if the result is empty or too narrow.

For example, you can select **Manual Leads**, a **Prospect** tag, a created-date range, and the **New** stage to review only that group. Verify the actual filter chips in your workspace because available values and matching behavior can vary.

## Remove one filter

1. Locate the active filter chip above the table.
2. Select the chip’s close or remove control.
3. Wait for the table to refresh.
4. Confirm that the other filters remain active.
5. Review the updated result count.

## Clear all filters

1. Select **Clear all** in the filter bar.
2. Wait for the table to refresh.
3. Confirm that the list, tag, date, and stage chips have been removed.
4. Check that the full lead view is displayed again.

> **Caution:** Clearing filters does not delete or edit leads. However, it changes the records visible on screen. Reapply the intended filters before using export or bulk actions.

## What to verify

After applying filters, confirm:

- The correct workspace is selected.
- Every active filter chip represents an intentional condition.
- The result count and visible rows match the review you planned.
- The table values, such as **Created At**, **Submitted At**, **Lists**, and **Stages**, support the result you expected.
- You have not selected a bulk action or export for a broader set of leads than intended.

## Troubleshooting

- If no leads appear, remove one filter at a time and check for conflicting conditions.
- If a list or tag is missing, confirm its spelling, workspace, and your permission scope.
- If a date result looks wrong, check whether you filtered by **Created** while expecting **Submitted At**, and verify the displayed time zone.
- If the result count does not update, wait for the table to finish loading and refresh once.
- If **Clear all** is not visible, close an open filter menu or widen the browser window.
- If a filter control is unavailable, ask an administrator to confirm that the workspace feature and your role support it.

> **Security and privacy:** Filters can reveal customer groups through names, counts, tags, stages, and custom values. Use approved screenshots and redact customer information before sharing the view.

## Related articles

- [Understand the All Leads Screen](01-understand-the-all-leads-screen.md)
- [Search for Leads](02-search-for-leads.md)
- [Select and Rearrange Lead Columns](04-select-and-rearrange-lead-columns.md)
- [Select Leads and Use Bulk Actions](08-select-leads-and-use-bulk-actions.md)
