---
title: "Troubleshoot Csv Imports and Failed Leads"
category: "Web Troubleshooting"
platform: web
status: Draft
last_verified: ""
---

# Troubleshoot Csv Imports and Failed Leads

Imports can create or update many records at once. A preview, field mapping, and error review are essential before you start an import.

The names of buttons and sections can vary with your PloverCRM plan, permissions, connected services, and current version. When a label differs, use the matching label displayed in your account and do not change an unrelated setting.

![Placeholder screenshot of troubleshoot csv imports and failed leads](images/placeholder-troubleshoot-csv-imports-and-failed-leads.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the troubleshoot csv imports and failed leads workflow after review. Redact customer names, email addresses, phone numbers, private URLs, credentials, tokens, and other sensitive values before publishing the final image.

## Safe troubleshooting order`r`n`r`n1. Confirm the correct account, workspace, connected website, browser, and user role.`r`n2. Record the exact non-sensitive error, affected screen, approximate time, and last successful step.`r`n3. Check the relevant status page or log before changing configuration.`r`n4. Make one low-risk correction at a time and wait for the result.`r`n5. Verify the result before retrying or escalating.`r`n`r`nDo not delete records, reinstall plugins, reconnect integrations, or rerun imports merely because a page looks stale; these actions can change data or create duplicates.`r`n`r`n> **Security:** Never share passwords, tokens, private URLs, payment details, or identifiable customer data. Redact screenshots and exports.`r`n`r`n## Steps

1. Open **Data Sources and Imports** and select the CSV import workflow.
2. Choose the approved CSV file and confirm that it belongs to the intended workspace.
3. Review the delimiter, header-row, encoding, and duplicate-handling options.
4. Map each incoming column to the correct PloverCRM field; leave unknown columns unmapped rather than guessing.
5. Apply lists, tags, routing, or default values only when they match the import plan.
6. Run the preview or validation step and resolve every required-field or format error that you understand.
7. Start the import once the row count, mapping, and destination are correct.
8. Monitor the progress and review failed rows after processing finishes.

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

