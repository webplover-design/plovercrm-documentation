---
title: "Set the Lead Stage and Value"
category: "Add New Lead"
platform: web
status: Draft
last_verified: ""
---

# Set the Lead Stage and Value

Set the new lead's pipeline **Stage** and expected **Value** when those controls are available in the creation workflow. Use the stage that reflects the lead's actual position, not the stage that gives the preferred report outcome.

![Placeholder screenshot of the lead stage and value controls](images/placeholder-set-the-lead-stage-and-value.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing fictional stage and value data. Redact all customer information before publishing.

## Before you begin

- Confirm the active workspace and its pipeline stages.
- Know the approved value and currency format used by your organization.
- Confirm that your role can change stage and value.
- Understand whether the chosen stage starts a reminder, assignment, notification, or automation.

## Choose the lead stage

1. Open **Add New Lead** from **All Leads**.
2. Complete the lead's information and organization details.
3. Open the **Stage** control when it is shown.
4. Choose the stage that matches the lead's current status.
5. Review the selected stage before saving.

Common stage names can include **New**, **Contacted**, **Qualified**, **Quotation Sent**, **Won**, **Lost**, and **Not answered**. Your workspace can use a different set or order.

## Enter the lead value

1. Locate the **Value** field when it is available.
2. Enter the approved numeric amount without explanatory text.
3. Follow the workspace's decimal and currency convention.
4. Check that the value belongs to this lead and is not a copied value from another record.
5. Review the value together with the selected stage.

If the Add New Lead form does not display **Stage** or **Value**, create the lead and update those fields from the lead details view instead. Do not store the value in an unrelated custom field merely because the expected control is absent.

## Verify after saving

1. Select **Create Lead**.
2. Wait for **Lead created successfully!** or the matching completion message.
3. Find the new lead in **All Leads**.
4. Open its lead details view.
5. Confirm the **Stage** and **Value** values.
6. Check the dashboard or pipeline view if the change should affect a summary.

## Troubleshooting

- If a stage is unavailable, confirm the active workspace and its pipeline configuration.
- If the value is rejected, remove currency symbols or text and follow the configured number format.
- If the stage or value is not shown, update the saved lead from its details view or ask an administrator about field access.
- If a stage change starts an unexpected automation, stop further edits and ask an administrator to review the workflow.

> **Security and privacy:** Pipeline values can be commercially sensitive. Use fictional values in documentation screenshots and restrict access to real pipeline data.

## Related articles

- [Open and Enter a New Lead](01-open-add-new-lead.md)
- [Assign a Lead to a Teammate](03-assign-a-lead-to-a-teammate.md)
- [Understand Pipeline Stage and Value](../05-lead-details/12-understand-pipeline-stage-and-value.md)
