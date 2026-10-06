---
title: "Enter and Validate Lead Information"
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
  - "create lead"
  - "lead validation"
platform: mobile
status: Draft
last_verified: ""
---
# Enter and Validate Lead Information

Use the lead form to provide the information required by your workspace. PloverCRM checks the values before creating or updating a lead.

## Understand the minimum information requirement

When creating a lead, enter at least one meaningful detail. The form can accept a name, email address, phone number, or another writable lead field, depending on the current workspace configuration.

A submission containing only lists or tags is not enough. Add a lead detail before saving.

## Complete the core fields

Depending on the workspace, the form can show:

- **Name**, **First Name**, or **Last Name**
- **Email**
- **Phone**
- **City**
- **Country**

Some fields may be required by the workspace or by your role's field settings. Required fields are identified in the form or in the validation message.

![Placeholder image of PloverCRM lead-field validation](images/placeholder-mobile-lead-field-validation.png)

> **Image placeholder:** Replace this image path with the final lead-field validation screenshot when it is available.

## Add additional and custom fields

1. Tap **More Fields** when it is available.
2. Open **Additional Fields**, **Core Fields**, or **Custom Fields**.
3. Enter values in the fields you can edit.
4. Review any highlighted field before saving.

Available fields, field types, and edit access depend on the active workspace.

## Correct validation messages

### No meaningful lead detail was entered

PloverCRM can show a message such as **Add at least one lead detail, not only lists or tags.** Enter a name, email, phone number, or another meaningful field value.

### A required field is empty

PloverCRM highlights the missing field and shows a message such as **[Field name] is required.** Complete the highlighted field and submit the form again.

### A phone number is not accepted

Use phone digits and common phone punctuation. Remove unsupported characters, then submit the form again.

### The form reports a server-side validation error

Read the message shown by PloverCRM and correct the field it identifies. Do not add private customer information that is not needed for the lead record.

## What happens next

If the values pass validation, PloverCRM saves the lead or applies the update. If validation fails, the form remains open so you can correct the information.

## Related articles

- [Add a New Lead](01-add-a-new-lead.md)
- [Edit Lead Information](04-edit-lead-information.md)
- [Understand Additional Lead Information](08-understand-additional-lead-information.md)
