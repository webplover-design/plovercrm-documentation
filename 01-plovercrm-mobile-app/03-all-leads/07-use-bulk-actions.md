---
title: "Use Bulk Actions"
category: "All Leads"
categories:
  - "PloverCRM Mobile App"
  - "All Leads"
tags:
  - "PloverCRM"
  - "mobile app"
  - "All Leads"
  - "leads"
  - "lead management"
  - "bulk actions"
  - "data management"
platform: mobile
status: Draft
last_verified: ""
---
# Use Bulk Actions

Use bulk actions to update or delete several leads at once from **All Leads**. Available actions depend on your workspace configuration and permissions.

## Select leads

1. Open **All Leads**.
2. Tap a row number, or long-press a lead row to enter selection mode.
3. Select additional leads as needed.
4. Review the selected count in the bulk-actions bar.
5. Tap **Actions**.

![Placeholder image of the PloverCRM bulk-actions bar](images/placeholder-mobile-bulk-actions.png)

> **Image placeholder:** Replace this image path with the final bulk-actions screenshot when it is available.

## Select all leads matching a filter

When all visible rows are selected and more matching leads exist, PloverCRM can show **Select all [number] leads matching this filter**.

Tap this option only when you want the action to apply to every lead matching the current search or filter, including leads on other pages.

## Available bulk actions

Depending on your permissions and workspace configuration, the Actions menu can include:

- **Change stage** — Apply a pipeline stage to the selected leads.
- **Change assignee** — Assign the selected leads to a teammate.
- **Add tags** — Add one or more tags.
- **Remove tags** — Remove one or more tags.
- **Add lists** — Add the selected leads to one or more lists.
- **Remove lists** — Remove the selected leads from one or more lists.
- **Update custom field** — Set a value for a writable custom field.
- **Delete leads** — Permanently remove the selected leads and their deals.

## Apply an update

1. Tap **Actions**.
2. Choose the update you want to make.
3. Select or enter the value to apply.
4. Tap **Apply**.
5. Review the completion message.

Some updates allow multiple tags or lists to be selected. Custom-field input depends on the selected field type.

## Delete selected leads

1. Select the leads you want to remove.
2. Tap **Actions**.
3. Choose **Delete leads**.
4. Review the number of selected leads and the warning.
5. Tap **Delete** only if you are certain.

Deleting leads and their deals is destructive and cannot be undone.

## Clear the selection

Tap **Clear** in the bulk-actions bar to leave selection mode without applying an action.

## What happens next

PloverCRM displays a completion message with the number of leads changed. If some leads fail or are skipped, the message includes that information.

## Troubleshooting

### An action is not available

The action may be hidden because your account does not have the required permission, the workspace has no available values, or the action is not supported for the selected records.

### The action changes fewer leads than expected

Review the selected count and whether you selected visible leads or the full query scope. A filtered selection may include fewer records than the total workspace lead count.

### A bulk action fails

Review the error message, close the action panel, and try again with a smaller selection if appropriate. Ask your workspace administrator to confirm your permissions if the action remains unavailable.

## Related articles

- [Search for Leads and Understand Search Results](02-search-for-leads.md)
- [Customize Lead Columns](05-customize-lead-columns.md)
- [All Leads Screen Overview](01-all-leads-screen-overview.md)
- [View Lead Details](../04-add-and-manage-leads/03-view-lead-details.md)
