---
title: "Delete a Lead"
category: "Add and Manage Leads"
categories:
  - "PloverCRM Mobile App"
  - "Add and Manage Leads"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Add and Manage Leads"
  - "leads"
  - "lead management"
  - "lead deletion"
  - "data management"
platform: mobile
status: Draft
last_verified: ""
---
# Delete a Lead

Remove a lead from the active PloverCRM workspace when you are certain it is no longer needed.

> **Warning:** Deleting a lead is destructive and cannot be undone. Review the lead and confirm that you are deleting the correct record before continuing.

## Delete one lead

1. Open the lead's **Lead Details** screen.
2. Tap **Options**.
3. Tap **Delete Lead**.
4. Review the confirmation dialog.
5. Confirm the action by tapping **Delete**.

![Placeholder image of the PloverCRM Delete Lead confirmation](images/placeholder-mobile-delete-lead.png)

> **Image placeholder:** Replace this image path with the final Delete Lead screenshot when it is available.

The confirmation dialog is titled **Delete Lead** and says:

> **Are you sure you want to delete this lead? This action cannot be undone.**

Tap **Cancel** if you are not certain.

## Delete multiple leads at once

You can delete several leads from **All Leads** by using bulk actions:

1. Open **All Leads**.
2. Tap a row number, or long-press a lead row, to enter selection mode.
3. Select each lead you want to remove.
4. Review the selected count in the bulk-actions bar.
5. Tap **Actions**.
6. Choose **Delete leads**.
7. Review the number of selected leads and the warning.
8. Tap **Delete** only after confirming that the selection is correct.

When a filtered list offers **Select all [number] leads matching this filter**, choose it only when you intend to delete every lead that matches the current search or filter, including leads on other pages.

### Select 100 rows on one page

Use the rows-per-page control when you want to review and select a large group from the current page:

1. Open **All Leads**.
2. Open the rows-per-page control at the bottom of the table.
3. Select **100**.
4. Review the leads displayed on the page.
5. Use the header selection control or select the leads individually.
6. Tap **Actions**.
7. Choose **Delete leads**.
8. Review the selected count and confirmation warning.
9. Tap **Delete** only after confirming the selection.

The rows-per-page options can include **10**, **20**, **50**, and **100**. Selecting **100** displays up to 100 leads on the current page; it does not automatically select or delete them. You must still review and select the leads before using bulk deletion.

> **Warning:** Bulk deletion permanently removes the selected leads and their deals. This action cannot be undone. Review the selection count and query scope before confirming.

![Placeholder image of the PloverCRM rows-per-page and bulk-delete controls](images/placeholder-mobile-rows-per-page-bulk-delete.png)

> **Image placeholder:** Replace this image path with the final rows-per-page and bulk-delete screenshot when it is available.

For the complete selection and bulk-action workflow, see [Use Bulk Actions](../03-all-leads/07-use-bulk-actions.md).

## What happens next

For a single lead, PloverCRM shows **Deleting lead...** while the deletion is processing. After a successful deletion, it shows **Lead deleted successfully** and returns you to the leads list.

After bulk deletion, PloverCRM displays a completion message with the number of leads changed. If some leads fail or are skipped, the message includes that information.

Deleted leads cannot be restored through these workflows. If you need to retain the information, export or record the permitted details before deleting it.

## Troubleshooting

### Delete Lead is not available

Your role may not have permission to delete leads. Ask a workspace administrator to review your access.

### The lead is not deleted

PloverCRM can show **Failed to delete lead** when the request does not complete. Review the message and try again only after confirming that the correct lead is still open.

### Bulk deletion removes fewer leads than expected

Review the selected count and whether you selected visible leads or all leads matching the current filter. If some leads fail or are skipped, review the completion message and ask a workspace administrator to confirm your permissions.

### Bulk deletion is not available

Your role may not have permission to delete leads, or the bulk action may be unavailable for the selected records. Ask a workspace administrator to review your access.

## Related articles

- [View Lead Details](03-view-lead-details.md)
- [Find and Merge Duplicate Leads](12-find-and-merge-duplicate-leads.md)
- [Use Bulk Actions](../03-all-leads/07-use-bulk-actions.md)
