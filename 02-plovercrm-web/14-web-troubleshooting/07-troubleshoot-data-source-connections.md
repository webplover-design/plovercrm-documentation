---
title: "Troubleshoot Data Source Connections"
category: "Web Troubleshooting"
platform: web
status: Draft
last_verified: ""
---

# Troubleshoot Data Source Connections

A data source connects an external or website event to the selected workspace. Verify the destination, authorization, field mapping, and test result before making the source active.

The names of buttons and sections can vary with your PloverCRM plan, permissions, connected services, and current version. When a label differs, use the matching label displayed in your account and do not change an unrelated setting.

![Placeholder screenshot of troubleshoot data source connections](images/placeholder-troubleshoot-data-source-connections.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the troubleshoot data source connections workflow after review. Redact customer names, email addresses, phone numbers, private URLs, credentials, tokens, and other sensitive values before publishing the final image.

## Safe troubleshooting order`r`n`r`n1. Confirm the correct account, workspace, connected website, browser, and user role.`r`n2. Record the exact non-sensitive error, affected screen, approximate time, and last successful step.`r`n3. Check the relevant status page or log before changing configuration.`r`n4. Make one low-risk correction at a time and wait for the result.`r`n5. Verify the result before retrying or escalating.`r`n`r`nDo not delete records, reinstall plugins, reconnect integrations, or rerun imports merely because a page looks stale; these actions can change data or create duplicates.`r`n`r`n> **Security:** Never share passwords, tokens, private URLs, payment details, or identifiable customer data. Redact screenshots and exports.`r`n`r`n## Steps

1. Open **Data Sources and Imports** and choose the source or connection type.
2. Confirm the selected workspace and review any existing connection with the same purpose.
3. Enter only the required configuration values or continue through the approved authorization screen.
4. Set the destination, routing, lists, tags, and field mapping where those controls are available.
5. Run the connection test or send a safe test event.
6. Review the test result and source log for accepted, rejected, or unmapped data.
7. Save the configuration and enable the source only after the result is understood.
8. Monitor the first real event and confirm that it reached the intended lead or queue.

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

## Escalate safely`r`n`r`nIf the issue remains, contact support with the feature name, workspace identifier approved for sharing, exact non-sensitive error, approximate time, browser, reproduction steps, and whether another authorized user can reproduce it. Include only redacted screenshots. Do not send credentials or repeat an operation that could create records, send messages, or trigger an external service.`r`n`r`n## Related articles

- [Web Troubleshooting overview](README.md)

