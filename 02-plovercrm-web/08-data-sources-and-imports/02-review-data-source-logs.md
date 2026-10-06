---
title: "Review Data Source Logs"
category: "Data Sources and Imports"
platform: web
status: Draft
last_verified: ""
---

# Review Data Source Logs

Data-source logs help you check whether a source connected successfully, whether submissions were received, and whether a lead was accepted or rejected.

> **Image:** `[Add screenshot here]`

## Open the logs

1. Open **Data Sources**.
2. Select the source you want to investigate.
3. Open its **Logs**, **Activity**, or matching log view.
4. Review the newest entries first.

## What to review

Look for the source name, event time, processing status, lead or submission reference, and any error message. A successful entry indicates that the event was accepted for processing; it does not necessarily mean every field was populated correctly.

## Investigate a failed event

1. Open the failed log entry.
2. Read the non-sensitive error message.
3. Check the source connection and field mapping.
4. Check routing, required fields, and duplicate handling.
5. Correct the source configuration or source data, then submit a new test event when appropriate.

Do not repeatedly submit the same event while processing is still in progress.

## Related articles

- [Understand the Data Sources Hub](01-understand-the-data-sources-hub.md)
- [Configure CRM Routing](07-configure-crm-routing.md)
- [Review Failed Leads and Download Error Logs](11-review-failed-leads-and-download-error-logs.md)
