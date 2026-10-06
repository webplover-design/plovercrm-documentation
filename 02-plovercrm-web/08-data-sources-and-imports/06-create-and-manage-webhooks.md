---
title: "Create and Manage Webhooks"
category: "Data Sources and Imports"
platform: web
status: Draft
last_verified: ""
---

# Create and Manage Webhooks

A webhook lets an external form or service send lead data to PloverCRM. Create one webhook for each intended source or mapping, then test it before relying on live submissions.

> **Image:** `[Add screenshot here]`

## Create a webhook

1. Open **Data Sources**.
2. Select **Add Source** or **Webhooks**.
3. Choose **Create Webhook**.
4. Enter a clear name for the source.
5. Save the webhook and copy its endpoint only into the approved external service.
6. Configure the destination and field mapping in PloverCRM.

Treat the webhook endpoint as sensitive. Do not publish it or include it in screenshots or support requests.

## Configure the mapping

Map incoming fields to standard or custom PloverCRM fields. Configure any available routing defaults, including lists, tags, assignee, pipeline stage, and deal value. Leave unsupported fields unmapped rather than guessing.

## Test a webhook

Send a safe test payload from the external service. Review the source log and resulting lead. Confirm that the expected fields and routing were applied before sending production data.

## Manage or remove a webhook

Open the webhook from **Data Sources** to edit its name or mapping, review status and logs, or disconnect it. Update the external service if the endpoint changes. Disconnecting stops future submissions but does not delete existing leads.

## Related articles

- [Configure CRM Routing](07-configure-crm-routing.md)
- [Review Data Source Logs](02-review-data-source-logs.md)
- [Repair or Disconnect a Data Source](12-repair-or-disconnect-a-data-source.md)
