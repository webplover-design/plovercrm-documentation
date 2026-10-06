---
title: "Change Stage, Assignee, Lists, Tags, or Custom Fields in Bulk"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Change Stage, Assignee, Lists, Tags, or Custom Fields in Bulk

Use **Bulk actions** in **All Leads** to update the same field on several selected leads. The available actions include **Change stage**, **Change assignee**, **Add to tags**, **Add to lists**, **Remove from tags**, **Remove from lists**, and **Update custom field**.

![Placeholder screenshot of bulk lead field actions](images/placeholder-change-stage-assignee-lists-tags-or-custom-fields-in-bulk.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the bulk-action menu and a fictional selection. Redact names, email addresses, phone numbers, custom values, and other customer information before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads** and confirm the selected workspace.
- Filter the table before selecting leads when the update should target a specific group.
- Confirm that your role allows bulk updates.
- Write down the intended old and new values before starting.
- Check whether changing the field can trigger an automation, assignment, report, or notification.

> **Caution:** A bulk update changes every selected lead. Review the selection count, filters, and confirmation text before applying the action.

## Select the leads

1. Open **All Leads**.
2. Apply **Lists**, **Tags**, **Created**, or **Stages** filters when needed.
3. Review the active filter chips and result count.
4. Select individual row checkboxes, or use the header checkbox for the visible rows.
5. Confirm the selected-count banner, such as **9 leads selected**.
6. Review the visible names and current values before opening **Bulk actions**.

## Open the bulk-action menu

1. Select **Bulk actions** in the selected-count banner.
2. Review the available actions:
   - **Change stage**
   - **Change assignee**
   - **Add to tags**
   - **Add to lists**
   - **Remove from tags**
   - **Remove from lists**
   - **Update custom field**
3. Choose the action that matches the intended field change.
4. Stop if the action or selected count is not what you expected.

![Placeholder screenshot of the Bulk actions menu](images/placeholder-bulk-actions-menu.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the available menu actions using fictional lead rows.

## Change the stage

1. Select **Change stage**.
2. Review the current selection and destination stage.
3. Choose the new stage, such as **New**, **Contacted**, **Qualified**, **Quotation Sent**, **Won**, **Lost**, or **Not answered**, when those stages are available.
4. Read the confirmation or preview message.
5. Confirm that the stage change applies only to the selected leads.
6. Submit the update once.
7. Wait for completion.
8. Refresh the table and verify the **Stage** value on several selected leads.

Moving a lead to a new stage can affect dashboard summaries, pipeline reports, and automations. Choose the stage that reflects the actual status of the selected leads.

![Placeholder screenshot of the Change stage action](images/placeholder-bulk-change-stage.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the stage selector and fictional stage values.

## Change the assignee

1. Open **Bulk actions** and select **Change assignee**.
2. Review the selected lead count.
3. Choose the teammate who should own the selected leads.
4. Confirm that the teammate belongs to the current workspace and can access the leads.
5. Review the reassignment warning or preview.
6. Confirm the change.
7. Refresh the table and verify the assignee on the updated records.

Reassign leads only when the receiving teammate is ready to handle the follow-up. If assignment affects reminders or automations, review those dependencies first.

## Add leads to lists

1. Open **Bulk actions**.
2. Select **Add to lists**.
3. Choose one or more destination lists.
4. Confirm that the selected lists belong to the current workspace.
5. Review the selected lead count and list names.
6. Confirm the update.
7. Verify the list values in the **Lists** column or on a lead detail page.

Adding a lead to a list does not remove its existing list membership unless you separately choose a remove action.

## Remove leads from lists

1. Open **Bulk actions**.
2. Select **Remove from lists**.
3. Choose the list or lists to remove.
4. Review the selected lead count.
5. Confirm that the removal is intentional and will not interrupt routing or follow-up.
6. Confirm the action.
7. Verify that the selected list no longer appears on the affected leads.

> **Caution:** Removing list membership can affect saved views, routing, reports, and team workflows. Check dependencies before confirming.

## Add tags to leads

1. Open **Bulk actions**.
2. Select **Add to tags**.
3. Choose the tag or tags to apply.
4. Review the selected lead count and tag names.
5. Confirm the update.
6. Refresh the table when needed.
7. Verify the tags on the selected leads or filter by the new tag.

Adding a tag preserves existing tags unless the action explicitly replaces them.

## Remove tags from leads

1. Open **Bulk actions**.
2. Select **Remove from tags**.
3. Choose the tag or tags to remove.
4. Confirm that the tags are outdated or no longer appropriate.
5. Review the selected lead count.
6. Confirm the removal.
7. Verify that the selected tags no longer appear.

## Update a custom field

1. Open **Bulk actions**.
2. Select **Update custom field**.
3. Choose the custom field to update.
4. Enter or select the new value using the field’s configured type and format.
5. Review whether the action replaces the existing value or adds to it.
6. Confirm the selected lead count and field value.
7. Submit the update.
8. Open several affected leads and verify the custom-field value.

> **Caution:** A custom-field update can replace information across every selected record. Export or preserve data only when your organization’s policy permits it, and verify the value before confirming.

## What to verify

After any bulk update, confirm:

- The correct workspace and filters were active.
- The selected count matched the intended records.
- The new stage, assignee, list, tag, or custom-field value is correct.
- Several affected records show the expected result.
- Unselected leads were not changed.
- Any related assignment, report, notification, or automation behaved as expected.

## Troubleshooting

- If a menu action is unavailable, check your role and whether the selected records are editable.
- If the selected count is wrong, choose **Clear**, reset filters, and select the records again.
- If a teammate is missing from **Change assignee**, confirm their workspace membership and access.
- If a list or tag is missing, confirm that it exists in the current workspace.
- If a custom-field value is rejected, follow the field’s configured type and validation message.
- If some records do not update, review their permissions, locked state, and individual validation messages.
- If an automation or notification starts unexpectedly, pause further changes and review the affected workflow.

> **Security and privacy:** Bulk changes can expose or overwrite customer information. Use the smallest possible selection, approved accounts, and redacted screenshots.

## Related articles

- [Select Leads and Use Bulk Actions](08-select-leads-and-use-bulk-actions.md)
- [Filter Leads by List, Tag, Stage, or Date](03-filter-leads-by-list-tag-stage-or-date.md)
- [Understand Pipeline Stage and Value](../05-lead-details/12-understand-pipeline-stage-and-value.md)
- [Manage Lists](../11-custom-fields-lists-and-tags/07-manage-lists.md)
- [Manage Tags](../11-custom-fields-lists-and-tags/08-manage-tags.md)
