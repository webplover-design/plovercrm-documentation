---
title: "Add Lists, Tags, and Custom Fields"
category: "Add New Lead"
platform: web
status: Draft
last_verified: ""
---

# Add Lists, Tags, and Custom Fields

Add list membership, tags, and workspace-configured custom-field values while the **Add New Lead** dialog is open. Lists and tags are selected independently, so adding one does not remove the other.

![Placeholder screenshot of lists, tags, and custom fields](images/placeholder-add-lists-tags-and-custom-fields.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the **Add New Lead** dialog showing fictional list, tag, and custom-field selections.

## Before you begin

- Open **All Leads** in the correct workspace.
- Select **Add New Lead**.
- Confirm that the lists, tags, and custom fields you need belong to the active workspace.
- Know whether your role can assign list and tag membership.

## Add the lead to lists

1. In the **Add New Lead** dialog, locate the **Lists** control at the top of the form.
2. Select **Lists** to open its menu.
3. Select the checkbox beside each list that should contain the new lead.
4. Use the list search field when the workspace has many lists.
5. Review the selected count displayed on the **Lists** control.
6. Select **Clear selection** in the menu if you need to remove every list choice and start again.

## Add tags

1. Select the **Tags** control beside **Lists**.
2. Select one or more tag checkboxes.
3. Search for a tag when the search field is displayed.
4. Review the selected count displayed on **Tags**.
5. Use **Clear selection** if the chosen tags are not correct.

The selected list and tag identifiers are submitted with the new lead when at least one item is selected. Do not select a similarly named item from another workspace.

## Complete custom fields

1. Review the fields below the **Lists** and **Tags** controls.
2. Enter a value in each custom field that is relevant to this lead.
3. For a select field, choose the value from the field's available options.
4. For a multi-select field, select the applicable checkboxes.
5. For a checkbox field, enable it only when the value is true for this lead.
6. Use the configured date or date-time control for date fields.
7. Check any required-field marker and correct the message shown below a field before saving.

Custom fields are configured per workspace. The form may display standard fields such as **Email**, **Full Name**, and **Phone**, followed by custom fields available to your role.

## Review before saving

- Confirm the list names and tag names, including the selected counts.
- Check that a list was not selected when a tag was intended, or vice versa.
- Review custom-field values for spelling, format, and sensitivity.
- Remove unnecessary personal information.
- Continue to [Save a New Lead and Review Duplicates](05-save-a-new-lead-and-review-duplicates.md) only after the selections are correct.

## Troubleshooting

- If a list or tag is missing, confirm the active workspace and ask an administrator to check its configuration.
- If search returns no result, clear the search text and verify the exact list or tag name.
- If the selected count is wrong, use **Clear selection** and select the items again.
- If a custom field does not accept the value, follow its configured type and the field-level message.
- If a selected field is not saved, review any warning after creation; an administrator may need to check field ownership or workspace permissions.

> **Security and privacy:** Do not use real customer details in documentation screenshots. Protect sensitive custom-field values and share them only through approved channels.

## Related articles

- [Open and Enter a New Lead](01-open-add-new-lead.md)
- [Manage Lists](../11-custom-fields-lists-and-tags/07-manage-lists.md)
- [Manage Tags](../11-custom-fields-lists-and-tags/08-manage-tags.md)
- [Understand Custom Fields](../11-custom-fields-lists-and-tags/01-understand-custom-fields.md)
