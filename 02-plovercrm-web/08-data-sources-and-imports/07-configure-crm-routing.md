---
title: "Configure CRM Routing"
category: "Data Sources and Imports"
platform: web
status: Draft
last_verified: ""
---

# Configure CRM Routing

Routing determines what PloverCRM does with a new lead received from a connected source. Use it to apply consistent defaults and send the lead to the correct team workflow.

> **Image:** `[Add screenshot here]`

## Open routing settings

1. Open **Data Sources**.
2. Select the source to configure.
3. Open its routing or CRM settings.
4. Review the current defaults before changing them.

## Configure available defaults

Depending on the source, routing may include:

- Destination workspace.
- Assignee or teammate.
- Pipeline stage.
- Lists and tags.
- Deal value or other source defaults.
- Field mappings.

Choose values that apply to every lead received from that source. Do not apply a list, tag, assignee, or stage merely because it is the current default.

## Test routing

Submit an approved test lead and confirm the resulting record, assignment, stage, lists, tags, and mapped fields. Correct the routing before sending live submissions.

## Related articles

- [Connect a Form Data Source](03-connect-a-form-data-source.md)
- [Create and Manage Webhooks](06-create-and-manage-webhooks.md)
- [Review Data Source Logs](02-review-data-source-logs.md)
