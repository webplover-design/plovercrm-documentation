---
title: "Save a New Lead and Review Duplicates"
category: "Add New Lead"
platform: web
status: Draft
last_verified: ""
---

# Save a New Lead and Review Duplicates

Review the completed **Add New Lead** form, create the record, and check the resulting lead for an existing duplicate. Creating a lead is a data-changing action, so do not submit the form until the workspace and contact identity are confirmed.

![Placeholder screenshot of saving a new lead](images/placeholder-save-a-new-lead-and-review-duplicates.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing fictional lead data and the **Create Lead** button. Redact all personal and workspace information.

## Review the form before saving

1. Confirm the active workspace in the dashboard header.
2. Review **Lists** and **Tags**, including their selected counts.
3. Check **Email**, **Full Name**, **Phone**, and every other visible field.
4. Confirm required fields are complete and email formatting is valid.
5. Review custom fields, assignment, stage, and value when those controls are available.
6. Search **All Leads** again if the information could match an existing record.

## Create the lead

1. Select **Create Lead** at the bottom of the **Add New Lead** dialog.
2. Wait while the button is disabled and the saving indicator is displayed.
3. Do not select **Create Lead** repeatedly while the request is processing.
4. Wait for the **Lead created successfully!** notification.
5. Confirm that the dialog closes and the form is cleared.
6. If PloverCRM displays a warning about fields that were not saved or fields claimed by others, record the field names and ask an administrator to review them.

## Find and review the new record

1. Return to **All Leads**.
2. Select **Refresh leads** if the new row is not immediately visible.
3. Search with a safe, approved identifier such as the lead's email address or name.
4. Confirm the new row belongs to the intended workspace.
5. Open the lead details drawer or page.
6. Check the contact information, lists, tags, custom fields, assignee, stage, and value.

## Review a possible duplicate

PloverCRM may show a **Possible duplicate** notice on the lead details view when a matching record is detected.

1. Read the notice without changing either record.
2. Select **Review** when the notice is present.
3. Compare the records using more than one identifier, such as name plus email or phone.
4. Confirm that both records represent the same person or organization before merging.
5. If the records are not the same, close the review and keep both records separate.
6. If they are the same and you are authorized to merge them, review which field values should be kept.
7. Read the merge warning carefully. The duplicate record can be removed and the action may be permanent.
8. Merge only after following your organization's approval and retention process.

Do not create a second record just because the first one is not visible yet. Refresh once, check filters, and search again before submitting another Add New Lead form.

## What to verify

- The success notification appeared.
- The new record is visible in the correct workspace.
- Lists, tags, custom fields, assignment, stage, and value were saved as intended.
- No duplicate record was created accidentally.
- Any merge decision was based on verified identity and authorized approval.

## Troubleshooting

- If **Create Lead** is disabled, complete the required fields and read the inline message below the affected field.
- If the request remains processing, wait for its status before trying again.
- If the success message appears but the row is missing, refresh **All Leads**, clear restrictive filters, and search again.
- If a warning lists ignored or claimed fields, preserve the warning text without including customer data and ask an administrator to check field permissions.
- If the wrong lead was created, stop before creating or deleting another record and contact the workspace administrator.
- If duplicate review is unavailable, confirm that a possible duplicate was detected and that your role permits merging.

> **Caution:** Merging or deleting a duplicate can permanently remove a lead record. Verify identity and obtain approval before confirming.

> **Security and privacy:** Never share unredacted lead records or duplicate-review screens. Protect names, email addresses, phone numbers, custom-field values, and exported data.

## Related articles

- [Open and Enter a New Lead](01-open-add-new-lead.md)
- [Find and Merge Duplicate Leads](../05-lead-details/14-find-and-merge-duplicate-leads.md)
- [Understand the Lead Detail Drawer](../05-lead-details/01-open-the-lead-detail-drawer-or-page.md)
- [Refresh and Load Leads](../03-all-leads/06-refresh-and-load-leads.md)
