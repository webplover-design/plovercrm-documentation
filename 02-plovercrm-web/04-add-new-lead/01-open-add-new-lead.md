---
title: "Open and Enter a New Lead"
category: "Add New Lead"
platform: web
status: Draft
last_verified: ""
---

# Open and Enter a New Lead

Use the **Add New Lead** dialog in the **PloverCRM Web Dashboard** to create a lead manually. The form starts with the fields enabled for the active workspace and can include workspace-specific custom fields.

![Placeholder screenshot of the Add New Lead dialog](images/placeholder-open-add-new-lead.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the **Add New Lead** dialog. Use fictional values or redact names, email addresses, phone numbers, private URLs, and custom-field data.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Confirm the active workspace and connected website in the dashboard header.
- Confirm that your role can create leads.
- Search **All Leads** first when there is any possibility that the person or organization already exists.
- Prepare only the approved lead information required for the record.

## Open the Add New Lead dialog

1. Open **All Leads** from the PloverCRM Web Dashboard navigation.
2. Confirm that the correct workspace is selected.
3. Select **Add New Lead**.
4. Wait for the dialog titled **Add New Lead** to open.
5. Confirm that the dialog displays the description **Fill in the details to create a new lead.**
6. Review the fields shown before entering information. The available fields depend on the active workspace and your permissions.

## Enter the lead information

1. Enter the available value in **Email**, **Full Name**, or **Phone** when that field is displayed.
2. Complete any other standard or custom fields shown for the workspace.
3. Use the field type provided by the form:
   - Text fields accept text values.
   - Email uses email-format validation.
   - Date and date-time fields use the date control when configured.
   - Select fields use the available options.
   - Multi-select fields use checkboxes.
   - A checkbox custom field is enabled or cleared directly.
4. Treat a label with an asterisk (`*`) as required.
5. Enter only the information needed for the lead and check each value before continuing.

![Placeholder screenshot of entered lead information](images/placeholder-enter-lead-information.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing fictional values in the lead fields. Do not publish real customer information.

The form can display only fields configured for the active workspace. If a field you expect is missing, do not add it as an unrelated custom field; check the workspace configuration or ask an administrator.

## Cancel without creating a lead

Select **Cancel** when you do not want to create the record. Cancel before switching workspaces or leaving the page if the information is not ready. Closing or cancelling the dialog does not create a lead.

## What to verify

Before submitting, confirm:

- The correct workspace is still active.
- The record is not already present in **All Leads**.
- The contact information is complete and correctly formatted.
- Required fields are filled.
- No password, token, payment detail, or unnecessary personal information was entered.

## Troubleshooting

- If **Add New Lead** is unavailable, confirm that you are in **All Leads** and ask an administrator to review your lead-creation permission.
- If the dialog shows fewer fields than expected, confirm the workspace and its field configuration.
- If a field is marked required, complete it and read the message shown below that field.
- If an email is rejected, correct its format before submitting.
- If the form remains open after submission, check the highlighted field messages and correct them.

> **Security and privacy:** Use approved accounts and devices. Redact all customer information from screenshots, examples, and support requests.

## Related articles

- [Add Lists, Tags, and Custom Fields](02-add-lists-tags-and-custom-fields.md)
- [Save a New Lead and Review Duplicates](05-save-a-new-lead-and-review-duplicates.md)
- [Understand the All Leads Screen](../03-all-leads/01-understand-the-all-leads-screen.md)
