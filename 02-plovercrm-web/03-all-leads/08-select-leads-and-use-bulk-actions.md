---
title: "Select Leads and Use Bulk Actions"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Select Leads and Use Bulk Actions

Use row checkboxes in **All Leads** to select several leads and then apply one supported action to the selected records. The bulk-action menu can include stage changes, assignee changes, list and tag updates, custom-field updates, selected exports, and lead deletion.

![Placeholder screenshot of the All Leads bulk actions menu](images/placeholder-select-leads-and-use-bulk-actions.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing selected rows, the selected-count banner, and the **Bulk actions** menu. Use fictional data or redact all customer information before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads** and confirm the workspace.
- Apply filters before selecting records when the action should affect a specific group.
- Confirm that your role permits the intended bulk action.
- For changes or deletion, know how many records will be affected and whether the action can be reversed.

> **Caution:** Bulk actions can affect many leads at once. Filter the table first, review the selected-count banner, and read the action scope before confirming.

## Select individual leads

1. Open **All Leads**.
2. Locate the lead row you want to include.
3. Select the checkbox at the start of that row.
4. Repeat for each lead that should receive the same action.
5. Review the selected rows and the count in the selection banner.
6. Select a checked row again to remove it from the selection.

The selected rows are highlighted so you can compare the names, contact information, stage, lists, tags, and other visible fields before acting.

## Select all visible rows

1. Apply the intended filters and confirm the result count.
2. Select the checkbox in the table header.
3. Review how many rows PloverCRM selected.
4. Check whether the selection applies to the current page or offers an option to select all filtered results.
5. Do not continue if the selected count is broader than intended.

Changing **Rows per page**, moving between pages, or clearing filters can change what is visible. Recheck the selection after any table change.

![Placeholder screenshot of selected leads](images/placeholder-selected-leads-banner.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing a safe fictional selection and the selected-count banner.

## Open Bulk actions

1. Select the intended leads.
2. Confirm the selected-count banner, such as **9 leads selected**.
3. Select **Bulk actions**.
4. Review the menu items available to your role.
5. Choose an action only after checking its target and scope.

The menu can include:

- **Change stage**
- **Change assignee**
- **Add to tags**
- **Add to lists**
- **Remove from tags**
- **Remove from lists**
- **Update custom field**
- **Export selected**
- **Delete leads**

The menu can vary by workspace, permission, and enabled features.

## Cancel a selection

1. Select **Clear** in the selected-count banner.
2. Confirm that the banner disappears.
3. Check that no rows remain highlighted.
4. Reapply filters if you need to begin a new selection.

Clearing a selection does not change any lead records.

## Apply a safe bulk action

1. Select the leads that need the same update.
2. Open **Bulk actions**.
3. Choose the required action.
4. Select or enter the new stage, assignee, list, tag, or custom-field value.
5. Read the preview or confirmation text.
6. Confirm that the action applies only to the selected leads.
7. Submit the action once.
8. Wait for PloverCRM to display completion or processing status.
9. Refresh the table and spot-check several updated records.

Use a small approved selection first when you are learning a new bulk workflow.

## Export selected leads

1. Select the leads to include.
2. Open **Bulk actions**.
3. Choose **Export selected**.
4. Review the number of selected leads and fields in the export dialog.
5. Confirm the export through an approved device and location.
6. Store the CSV securely and follow your organization’s retention policy.

Refer to [Export Leads to CSV](07-export-leads-to-csv.md) for field and quantity guidance.

## Delete selected leads

1. Select only the leads approved for deletion.
2. Confirm the selected count and review each row.
3. Open **Bulk actions**.
4. Choose **Delete leads**.
5. Read the warning and confirm whether deletion is permanent.
6. Complete any required retention, export, or approval step.
7. Confirm the deletion once.
8. Wait for completion and refresh the list.
9. Verify that the intended leads are no longer shown.

> **Caution:** Deleting leads in bulk can remove multiple records and associated follow-up context. Stop if the count, filters, or confirmation wording is unclear.

## What to verify

After a bulk action, confirm:

- The expected number of leads was selected.
- The workspace and active filters were correct.
- The selected action matched the intended change.
- Several records show the expected result.
- No unselected records were changed.
- Any export or external file is protected.

## Troubleshooting

- If **Bulk actions** is unavailable, check that at least one row is selected and ask an administrator to review your permissions.
- If the selected count changes unexpectedly, clear the selection and begin again after checking filters and pagination.
- If an action is still processing, wait for its status instead of submitting it again.
- If some records did not update, review their permissions, validation messages, and individual record state.
- If deletion or another change was started with the wrong selection, stop and contact an administrator before taking another action.

> **Security and privacy:** Bulk selections and exports can expose large groups of customer records. Use the minimum necessary scope, approved devices, and redacted screenshots.

## Related articles

- [Filter Leads by List, Tag, Stage, or Date](03-filter-leads-by-list-tag-stage-or-date.md)
- [Understand Rows per Page and Pagination](05-understand-rows-per-page-and-pagination.md)
- [Change Lead Fields in Bulk](09-change-stage-assignee-lists-tags-or-custom-fields-in-bulk.md)
- [Delete Leads in Bulk](10-delete-leads-in-bulk.md)
