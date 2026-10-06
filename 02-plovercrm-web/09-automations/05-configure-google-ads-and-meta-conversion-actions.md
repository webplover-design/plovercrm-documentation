---
title: "Configure Google Ads and Meta Conversion Actions"
category: "Automations"
platform: web
status: Draft
last_verified: ""
---

# Configure Google Ads and Meta Conversion Actions

Conversion actions send an automation result to a connected advertising provider. Use them only after the required provider connection is authorized and the event details are understood.

> **Image:** `[Add screenshot here]`

## Add a conversion action

1. Open the automation.
2. Open **Actions** and select **Add action**.
3. Choose the Google Ads conversion or Meta CAPI action.
4. Select the connected provider account or connection.
5. Choose the event or conversion type shown.
6. Complete the required settings.
7. Save the action.

## Google Ads actions

Review the selected Google Ads connection, conversion action, and lead data sent to Google. If no Google Ads connection is available, connect it before completing the automation.

## Meta CAPI actions

Review the selected Meta connection, event name, and required event data. Confirm that the Meta CAPI connection is active and belongs to the intended business or account.

## Review and test

Check the action order and trigger conditions. Confirm that the event will be sent only for the intended leads. Use a supported test or preview process when available and review the automation log after the first run.

A provider may reject an event because the connection is expired, the event is incomplete, or the provider settings are invalid.

## Related articles

- [Connect Google Ads and Meta CAPI](06-connect-google-ads-and-meta-capi.md)
- [Configure Automation Triggers and Actions](03-configure-automation-triggers-and-actions.md)
- [Monitor Automation Logs, Status, and Queue](07-monitor-automation-logs-status-and-queue.md)
