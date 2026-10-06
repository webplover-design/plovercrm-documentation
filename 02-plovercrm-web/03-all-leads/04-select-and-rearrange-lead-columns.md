---
title: "Select and Rearrange Lead Columns"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Select and Rearrange Lead Columns

Customize the **All Leads** table so the fields you use most often are visible in a practical order. Column preferences change the table view; they do not change, delete, or rearrange the data stored in a lead record.

![Placeholder screenshot of the Choose lead table columns dialog](images/placeholder-select-and-rearrange-lead-columns.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the **Choose lead table columns** dialog. Use fictional lead data and redact phone numbers, email addresses, names, custom values, private URLs, and other customer information before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads**.
- Confirm the workspace name and connected website in the header.
- Decide which fields you need for the current workflow.
- Remember that changing visible columns affects the table view, not the underlying lead records.

## Open the column chooser

1. Open **All Leads** from the left navigation.
2. Locate the toolbar above the table.
3. Select **Columns**.
4. Wait for the **Choose lead table columns** dialog to open.
5. Review the visible-column count, such as **10 visible**.
6. Review the **Search columns...** field and the **VISIBLE IN TABLE** list.

The table behind the dialog is dimmed while the chooser is open. The visible list shows the fields currently displayed in the lead table.

## Understand the column chooser

The dialog can contain these controls:

- **Search columns...** — finds a field in the available column list.
- **VISIBLE IN TABLE** — shows the columns currently enabled.
- **Drag handles to reorder** — indicates that visible columns can be rearranged by dragging.
- **Visible count** — shows how many columns are currently enabled.
- **X** beside a visible field — removes that field from the table.
- **Actions** — contains quick communication actions when enabled, such as **Call**, **SMS**, **Email**, **WhatsApp**, **Telegram**, and **Quick Reply**.
- **Cancel** — closes the dialog without saving the pending column changes.
- **Save columns** — applies the selected columns and their order.

Your account may display additional standard or custom fields. The available fields depend on workspace configuration and permissions.

![Placeholder screenshot of the visible columns list](images/placeholder-visible-lead-columns.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the visible-column list, drag handles, remove controls, and **Save columns** button using fictional data.

## Add a column to the table

1. Open the **Columns** dialog.
2. Select **Search columns...**.
3. Type part of the field name, such as `City`, `Created At`, `Submitted At`, or a custom field label.
4. Review the matching field.
5. Select the field’s checkbox or add control.
6. Confirm that the field appears in **VISIBLE IN TABLE**.
7. Check the visible count.
8. Select **Save columns**.
9. Confirm that the new column appears in the table.

Choose only fields needed for the task. Showing fewer columns can make the table easier to read and reduces the amount of customer information visible on screen.

## Remove a visible column

1. Open **Columns**.
2. Locate the field under **VISIBLE IN TABLE**.
3. Select the **X** beside the field.
4. Confirm that the field is removed from the visible list.
5. Select **Save columns**.
6. Check that the field is no longer shown in the table.

Removing a column from the table does not remove the field or its values from leads. You can add the field again later when your role and workspace allow it.

## Rearrange the column order

1. Open **Columns**.
2. Locate the field you want to move in **VISIBLE IN TABLE**.
3. Select and hold its drag handle.
4. Drag the field upward or downward to the desired position.
5. Release it when the insertion position is shown.
6. Repeat for other visible fields until the order supports your workflow.
7. Select **Save columns**.
8. Review the table from left to right and confirm the new order.

For example, place **Email**, **Phone**, **Created At**, **Submitted At**, **City**, **Average Monthly Electricity Bill**, **Expected budget**, **Lists**, and **Actions** in an order that helps your team review leads efficiently. The exact field names and available custom fields will differ by workspace.

![Placeholder screenshot of rearranging columns](images/placeholder-rearrange-lead-columns.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing a drag handle and reordered fields without exposing customer information.

## Configure the Actions column

The **Actions** column can provide quick communication controls. When the option is available:

1. Open **Columns**.
2. Locate **Actions** in the visible-column list.
3. Keep **Actions** visible when your workflow requires quick communication from the table.
4. Review the available action checkboxes, such as **Call**, **SMS**, **Email**, **WhatsApp**, **Telegram**, and **Quick Reply**.
5. Select only the communication actions approved for your team.
6. Save the columns.
7. Confirm that the expected action controls appear in each lead row.

Before selecting a communication action from the table, verify the lead’s phone number or email address. An action can open a browser, device, or external messaging application depending on your configuration.

## Cancel without saving

1. Make your pending column changes in the chooser.
2. Select **Cancel**.
3. Confirm that the dialog closes.
4. Check that the table retains the previously saved column selection and order.

Use **Cancel** when you are only reviewing available fields or are not ready to apply the new table view.

## What to verify

After saving columns, confirm:

- The **Columns** dialog closed successfully.
- The visible count matches the number of selected fields.
- The table shows the intended fields in the intended order.
- Custom fields display their configured labels.
- The **Actions** controls show only the communication actions you selected.
- No lead values or records were changed by the column update.

## Troubleshooting

- If a field cannot be found, search using a shorter part of its label and check whether your role can view it.
- If a field appears in the chooser but not in the table, save the columns and refresh the table once.
- If the order does not change, drag from the field’s handle and wait for the insertion indicator before releasing it.
- If the visible count is unexpected, review both added fields and fields removed with **X**.
- If **Save columns** is unavailable, wait for the chooser to finish loading or check for a permission or connection issue.
- If the table becomes too wide, remove unnecessary fields and keep only the columns needed for the current review.

> **Security and privacy:** Column choices can expose names, contact details, tracking information, and custom-field values to anyone viewing the screen. Use the minimum necessary fields and redact customer information from screenshots and support requests.

## Related articles

- [Understand the All Leads Screen](01-understand-the-all-leads-screen.md)
- [Filter Leads by List, Tag, Stage, or Date](03-filter-leads-by-list-tag-stage-or-date.md)
- [Configure Lead Table Columns](../10-settings-and-preferences/05-configure-lead-table-columns.md)
