---
title: "Manage Custom Fields"
category: "Custom Fields, Lists, and Tags"
platform: web
status: Draft
last_verified: ""
---

# Manage Custom Fields

Custom fields let your team store information that is not included in PloverCRM’s standard lead fields. Use them for business-specific information such as customer type, preferred service, account reference, qualification details, or any other value your team needs to search, display, import, or use in a workflow.

> **Image:** `[Add screenshot here]`

## Before you create a field

A custom field becomes part of your workspace’s data structure. Before creating one:

1. Open **Settings** and review the existing custom fields.
2. Check the standard lead fields and system-managed fields first.
3. Search for a field with the same purpose so you do not create duplicates.
4. Decide what information the field should store and who will use it.
5. Agree on a clear name, expected format, and meaning with your team.
6. Check whether the field will be used by forms, CSV imports, filters, automations, reports, or message templates.

Use a custom field only when the information belongs to an individual lead or contact. Use a **list** when you need a broad group of leads and a **tag** when you need flexible classification.

## Understand custom-field properties

Depending on the PloverCRM version and your permissions, a field may have some or all of these properties:

- **Name or label:** The text users see when viewing or editing a lead.
- **Field type:** Determines what values can be entered, such as text, number, date, checkbox, or a selectable option.
- **Options:** The allowed choices for a dropdown, radio, or multi-select field.
- **Group:** The section in which the field is displayed.
- **Order:** The field’s position within its group or field list.
- **Required status:** Determines whether users must provide a value before saving, when supported.
- **Visibility or availability:** Controls where the field can be used, when the account provides such settings.

Choose the narrowest field type that matches the data. A date should be a date field, a number should be a number field, and a controlled set of values should use selectable options rather than free text. Consistent types make filtering, imports, and automation more reliable.

## Open Custom Fields

1. Open **Settings** from the main navigation.
2. Select **Custom Fields**, or open the **Custom Fields, Lists, and Tags** settings area when that label is used.
3. Review the existing groups and fields.
4. Confirm that you are working in the intended workspace if the account supports multiple workspaces.

System-managed fields may appear alongside custom fields. These are provided by PloverCRM and may not be editable, reorderable, or deletable. Do not try to replace a system field with a custom field unless the standard field genuinely cannot store the required information.

## Create a custom field

1. Open the Custom Fields settings page.
2. Select **Add Custom Field**, **Create Field**, or the matching action.
3. Enter a clear field name.
4. Choose the field type that matches the value you intend to store.
5. If the field uses selectable options, add each allowed option and check the spelling and order.
6. Choose an existing group, or prepare to place the field in a new group.
7. Configure required, visibility, or other available options only when your workflow needs them.
8. Review the field summary before saving.
9. Select **Save**, **Create**, or the matching control.
10. Wait for the confirmation and locate the new field in the field list.
11. Open an approved test lead and confirm that the field appears and accepts the expected value.

### Name a field clearly

Use a name that explains the value without requiring a separate explanation. For example, **Preferred Contact Time** is clearer than **Preference**. Avoid names that differ only by punctuation or abbreviations. If the field will be used in imports or automations, document the intended values for your team.

### Configure selectable options

For a dropdown, radio, or multi-select field, keep options mutually understandable and consistent. Do not create separate options for accidental spelling variations such as `Enterprise`, `enterprise`, and `Ent.` unless they represent different values. If an option is removed later, check what happens to leads that already use it before confirming the change.

### Test the new field

Open a test lead, enter a representative value, save it, and reopen the lead. Confirm that the value remains correct and appears in the expected group. If the field will receive data from an import or integration, test that workflow separately because a field that works manually may still have a mapping or format problem.

## Create and manage field groups

Groups organize related fields into sections so users can find and complete them more easily. A group is an organizational container; creating a group does not create a lead, list, or tag.

### Create a group

1. Open the Custom Fields settings page.
2. Select **Add Group**, **Create Group**, or the matching action.
3. Enter a short, descriptive group name.
4. Review the name for clarity and duplicate groups.
5. Save the group.
6. Confirm that the group appears in the field layout.

Useful group names describe the subject of the fields, such as **Business Details**, **Qualification**, or **Preferences**. Avoid creating a separate group for one field unless that separation has a clear purpose.

### Place fields in a group

1. Locate the field you want to organize.
2. Select its edit or move control.
3. Choose the destination group, or drag the field into the group if drag-and-drop is supported.
4. Save or apply the layout change.
5. Open a lead and verify that the field appears under the intended group.

Moving a field changes its presentation and may affect where users look for it; it should not change the value already stored in that field. Still, verify forms, imports, and integrations if they depend on a specific layout or group setting.

### Rename or reorganize a group

Open the group’s available actions, update its name, and save. Before moving several fields, plan the final structure so users are not repeatedly adjusting their workflow. Check the lead view afterward and confirm that no field was accidentally moved to the wrong group.

## Edit a custom field

Edit a field when its label, options, group, order, or supported configuration needs to change.

1. Open the Custom Fields settings page.
2. Locate the exact custom field.
3. Open **Edit** or the field’s action menu.
4. Review the current field type and existing values before changing anything.
5. Update the label, options, group, order, or other permitted property.
6. Check whether the change affects existing lead values, imports, forms, automations, filters, or reports.
7. Save the change.
8. Open a test lead and verify the updated field.

Be especially careful when changing the field type. A type change may be unavailable, may invalidate existing values, or may require recreating the field. Do not change a field type merely to correct a few bad values; correct the source data or use a separate field when appropriate.

### Edit selectable options safely

Before renaming or removing an option, find out whether existing leads use it. Renaming may update the displayed value or may create a new option, depending on the workflow. Removing an option may leave existing values unchanged, clear them, or require reassignment. Read the confirmation message and test with approved data before applying a destructive option change.

## Reorder custom fields

Reordering controls the order in which fields appear to users. It can make a lead form or detail view easier to complete without changing the stored data.

1. Open the Custom Fields settings page.
2. Identify the group or field list whose order you want to change.
3. Drag the field to its new position, or use the available move-up, move-down, or order control.
4. Repeat only for the fields that need to move.
5. Save or apply the new order when required.
6. Open a lead and verify the order in the actual lead view.

If a field does not move, it may be system-managed or fixed by PloverCRM. Do not create a duplicate field just to obtain a different position.

## Delete a custom field

Deleting a custom field can permanently remove the field definition and may remove or make inaccessible values stored in it. It can also break forms, imports, filters, automations, reports, templates, and integrations that reference the field. Treat deletion as a destructive administrative action.

### Review dependencies first

Before deleting:

- Identify the exact field and workspace.
- Check whether leads contain values in the field.
- Review forms, CSV mappings, data sources, automations, filters, reports, and message templates that reference it.
- Ask the team whether the information must be retained.
- Export or preserve information only through an approved process if retention is required.
- Decide whether disabling, hiding, renaming, or moving the field is safer than deletion.

Do not delete a field to correct a label typo if editing the label will solve the problem.

### Delete the field

1. Open the Custom Fields settings page.
2. Locate the exact custom field.
3. Open its action menu and select **Delete**, **Remove**, or the matching action.
4. Read the confirmation dialog carefully.
5. Confirm the field name, group, and warning about existing values or dependencies.
6. Complete any required confirmation or type-the-name step.
7. Confirm the deletion once.
8. Wait for completion; do not submit the request repeatedly.
9. Reopen the field list and confirm that only the intended field was removed.
10. Test affected forms, imports, filters, automations, and lead views before returning to normal use.

If deletion is unavailable, the field may be system-managed, protected by permissions, or referenced by another feature. Ask an administrator to review the dependency instead of trying to bypass the restriction.

## Troubleshooting custom fields

### The field is not visible on a lead

Confirm that you are viewing the correct workspace and lead layout. Check whether the field belongs to a collapsed group, is hidden by permissions, or has not been saved. Refresh once after confirming the change.

### The field cannot be created

Check required values, duplicate names, supported field types, option requirements, and your permissions. If the form rejects a value, follow the field-level validation message rather than guessing.

### Imported values do not appear correctly

Confirm that the import column is mapped to the correct custom field and that the source values match the field type and selectable options. Test with a small approved file before importing more data.

### An automation or form stopped working

Check whether the field was renamed, deleted, moved, or had its type or options changed. Restore the expected configuration or update the dependent workflow. Review its logs before retrying an operation that could create duplicate records or send messages.

## Final verification checklist

After creating or changing custom fields, confirm:

- The field name and type communicate the intended meaning.
- The field is in the correct group and order.
- Existing lead values remain available and accurate.
- Forms, imports, filters, automations, reports, and templates still work.
- Teammates know how and when to complete the field.
- No unrelated field, lead, group, list, tag, or workflow changed.

> **Security and privacy:** Do not include passwords, API keys, connection tokens, private URLs, or identifiable lead data in screenshots or support requests. Use approved export and retention procedures when preserving field data.

## Related articles

- [Review System-Managed Fields](06-review-system-managed-fields.md)
- [Manage Lists](07-manage-lists.md)
- [Manage Tags](08-manage-tags.md)
