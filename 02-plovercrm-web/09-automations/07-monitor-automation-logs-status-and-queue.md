---
title: "Monitor Automation Logs, Status, and Queue"
category: "Automations"
platform: web
status: Draft
last_verified: ""
---

# Monitor Automation Logs, Status, and Queue

Use the automation status, queue, and logs to confirm whether a workflow is enabled, waiting to run, processing, completed, skipped, or failed.

> **Image:** `[Add screenshot here]`

## Review automation status

1. Open **Automations**.
2. Select the automation.
3. Review its current status.
4. Enable it only after the trigger, actions, recipients, and connections are complete.
5. Disable or pause it when you need to stop new runs.

Disabling an automation prevents new matching events from starting it. Review any work already in the queue before assuming that all processing has stopped.

## Review logs

1. Open the automation's **Logs** or **Activity** view.
2. Review the newest run or event.
3. Open a run to view its trigger, action results, timestamp, and error details.
4. Compare the result with the expected trigger and action sequence.

Statuses may indicate that work is queued, processing, completed, skipped, or failed. Use the exact status shown in the application when diagnosing a run.

## Review the queue

Open the queue or pending-work view when a run has not completed. Check whether it is waiting, currently processing, retrying, or blocked by a provider or validation error.

Do not submit the same lead or event repeatedly while the original run is queued or processing.

## Resolve a failed run

1. Open the failed log entry.
2. Read the error message.
3. Check the trigger data, action settings, recipient details, and required provider connection.
4. Correct the automation configuration or connection.
5. Run a new approved test when appropriate.
6. Confirm the new result in the logs.

## Related articles

- [Understand Automations and Browse Templates](01-understand-automations-and-browse-templates.md)
- [Configure Automation Triggers and Actions](03-configure-automation-triggers-and-actions.md)
- [Connect Google Ads and Meta CAPI](06-connect-google-ads-and-meta-capi.md)
