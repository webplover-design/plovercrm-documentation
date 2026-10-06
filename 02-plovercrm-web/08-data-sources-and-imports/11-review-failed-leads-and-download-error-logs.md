---
title: "Review Failed Leads and Download Error Logs"
category: "Data Sources and Imports"
platform: web
status: Draft
last_verified: ""
---

# Review Failed Leads and Download Error Logs

Use the failed-lead view or error log to find rows that PloverCRM could not import or source submissions that could not be processed.

> **Image:** `[Add screenshot here]`

## Review failed rows

1. Open **Data Sources**.
2. Open the relevant import or source log.
3. Filter for failed or rejected entries.
4. Open an entry to read its error message and row or submission details.
5. Identify whether the problem is a missing field, invalid format, duplicate, mapping error, or source connection issue.

## Download an error log

Select **Download Error Log** or the matching download action when it is available. Store the file securely because it may contain lead information and error details.

## Correct and retry

Correct the source data or mapping based on the error message. For a CSV import, correct the affected rows and repeat the import only for the rows that need processing when the workflow supports that option. Avoid creating duplicate leads by reimporting the complete file without checking what already succeeded.

## Related articles

- [Review Data Source Logs](02-review-data-source-logs.md)
- [Import Leads from a CSV File](08-import-leads-from-a-csv-file.md)
- [Resume a Historical Import](10-resume-a-historical-import.md)
