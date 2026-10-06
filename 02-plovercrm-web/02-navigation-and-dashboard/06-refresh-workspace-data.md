---
title: "Refresh Workspace Data"
category: "Navigation and Dashboard"
platform: web
status: Draft
last_verified: ""
---

# Refresh Workspace Data

Refresh the selected workspace when the PloverCRM Web Dashboard shows an older lead count, status, connection result, or setting than expected. Refreshing requests the latest available data; it does not repair a disconnected website or change any records.

The names of buttons and sections can vary with your PloverCRM plan, permissions, connected services, and current version. When a label differs, use the matching label displayed in your account.

![Placeholder screenshot of refresh workspace data](images/placeholder-refresh-workspace-data.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the refresh workspace data workflow after review. Redact customer names, email addresses, phone numbers, private URLs, credentials, tokens, and other sensitive values before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Select the workspace or connected website where you intend to work.
- Confirm that your role allows the screen and action described here.
- Prepare approved or fictional test data when the workflow changes records, sends messages, imports data, or triggers an automation.
- Finish or cancel unsaved edits before switching workspaces, refreshing, or leaving the page.

## Steps

1. Finish or cancel any unsaved edit on the current page.
2. Confirm the workspace name and connected website in the header.
3. Open the dashboard, lead list, settings page, or other area showing stale information.
4. Locate the **Sync workspace**, **Reload**, or workspace refresh control.
5. Select the control once.
6. Wait while PloverCRM requests the latest available data; do not repeatedly click refresh.
7. Review the updated timestamp, loading result, connection message, lead count, or status shown after the request finishes.
8. Compare the result with the source or record you expected to change.
9. If the data is still stale, check the workspace connection and relevant data-source logs before trying again.

## What to verify

After the final step, confirm:

- The workspace name and connected website still match the intended destination.
- The status, record, filter, setting, or result reflects the change you made.
- No unrelated lead, teammate, connection, message, or automation was changed.
- Any export, notification, file, or external action follows your organization's privacy and retention policy.

PloverCRM should display a confirmation, updated status, or refreshed record. If the workflow is asynchronous, use its progress or log view instead of submitting the same request again.

## Troubleshooting

- If the screen or control is missing, confirm the workspace and ask an administrator to review your role.
- If results are empty or stale, clear filters, refresh once, and check workspace connection status.
- If a value is rejected, read the field-level message and use the required format.
- If an operation is processing, wait for its status or log entry before trying again.
- If the result is unexpected, stop before making another change and record the exact non-sensitive message, approximate time, browser, and reproduction steps.

> **Security and privacy:** Never include passwords, one-time codes, API keys, connection tokens, private URLs, payment details, or identifiable customer data in screenshots, exports, notes, or support requests. Use approved support channels and redact diagnostic material before sharing it.

## Related articles

- [Navigation and Dashboard overview](README.md)
