---
title: "Delete Leads in Bulk"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Delete Leads in Bulk

Use **Delete leads** from the **Bulk actions** menu to remove multiple lead records from the selected workspace. Because this action can be permanent, verify the selection, filters, and approval requirements before confirming.

![Placeholder screenshot of Delete leads in the Bulk actions menu](images/placeholder-delete-leads-in-bulk.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing a fictional selection and the **Delete leads** action. Never publish real names, email addresses, phone numbers, custom-field values, or private workspace information in the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads** and confirm the workspace and connected website.
- Confirm that your role permits deleting leads.
- Check your organization’s retention, approval, export, and recovery requirements.
- Confirm that the selected leads are not needed for active assignments, reminders, deals, imports, automations, or legal records.

> **Caution:** Bulk deletion can remove several lead records and their associated CRM context. Treat the action as permanent unless PloverCRM explicitly confirms that recovery is available.

## Filter the leads for deletion

1. Open **All Leads**.
2. Apply the required **Lists**, **Tags**, **Created**, or **Stages** filters.
3. Review every active filter chip.
4. Search for a safe identifier when you need to narrow the result further.
5. Check the result count and visible range in the table footer.
6. Clear filters only when you intentionally want to review a broader set.

Do not delete from an unfiltered list unless the entire result set has been reviewed and approved.

## Select the leads

1. Select the checkbox beside each lead approved for deletion.
2. Use the table-header checkbox only when all visible rows are approved.
3. Check whether PloverCRM offers a selection of all filtered results beyond the current page.
4. Review the selected-count banner, such as **9 leads selected**.
5. Compare the selected rows with the intended names, contact details, stages, lists, tags, and other visible fields.
6. Select **Clear** and begin again if the selection is not exact.

Changing pages, rows per page, filters, or search terms can change the records visible to you. Recheck the selected count after any change.

![Placeholder screenshot of selected leads before deletion](images/placeholder-selected-leads-before-deletion.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the selected-count banner and fictional lead rows before deletion.

## Delete the selected leads

1. Select **Bulk actions**.
2. Choose **Delete leads**.
3. Read the confirmation dialog from beginning to end.
4. Confirm the number of leads and the workspace named in the warning.
5. Check whether the dialog states that deletion is permanent or identifies related data that will be removed.
6. Complete any required export or approval step before returning to the dialog.
7. Confirm the deletion only when the target and consequence are understood.
8. Wait for the completion message; do not click the delete control repeatedly.
9. Refresh **All Leads** and verify that the intended records are no longer present.

![Placeholder screenshot of the delete leads confirmation](images/placeholder-delete-leads-confirmation.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the deletion confirmation using fictional data. Do not display a real customer record.

## After deletion

1. Review the final status or completion message.
2. Confirm that the deleted leads no longer appear in the same filtered search.
3. Clear filters and search for an approved non-deleted lead to confirm that unrelated records remain available.
4. Review assignments, reminders, deals, imports, or automations that depended on the deleted records when your organization requires it.
5. Securely dispose of any temporary export created for the approval process according to your retention policy.

PloverCRM may not provide a recovery option. Contact an administrator or support before taking any additional action if the wrong records were deleted.

## What to verify

Before closing the task, confirm:

- The workspace and connected website were correct.
- The filters and selected-count banner matched the approved deletion scope.
- The confirmation dialog was read and understood.
- Only the intended leads disappeared.
- No active follow-up, assignment, deal, or automation was unintentionally affected.
- Any approval record or export was handled securely.

## Troubleshooting

- If **Delete leads** is unavailable, check that rows are selected and that your role permits deletion.
- If the count is unexpected, cancel the dialog, clear the selection, and rebuild it using narrower filters.
- If deletion is still processing, wait for the status before refreshing or submitting another request.
- If some leads remain, review whether they were outside the selection, filtered out, or rejected by a validation or permission rule.
- If the wrong leads were deleted, stop immediately and contact the workspace administrator or PloverCRM Support with the time, workspace identifier safe to share, and non-sensitive operation details.

> **Security and privacy:** Deletion screens and exports contain customer information. Use approved devices, restrict access to the confirmation and audit material, and redact all personal information from screenshots and support requests.

## Related articles

- [Select Leads and Use Bulk Actions](08-select-leads-and-use-bulk-actions.md)
- [Filter Leads by List, Tag, Stage, or Date](03-filter-leads-by-list-tag-stage-or-date.md)
- [Understand Rows per Page and Pagination](05-understand-rows-per-page-and-pagination.md)
- [Export Leads to CSV](07-export-leads-to-csv.md)
