---
title: "Repair or Disconnect a Data Source"
category: "Data Sources and Imports"
platform: web
status: Draft
last_verified: ""
---

# Repair or Disconnect a Data Source

Repair a source when its authorization or connection needs attention. Disconnect a source when it should no longer send new leads to PloverCRM.

> **Image:** `[Add screenshot here]`

## Repair a source

1. Open **Data Sources**.
2. Select the source with the warning or disconnected status.
3. Choose **Repair**, **Reconnect**, or the matching action.
4. Complete the provider authorization again when prompted.
5. Review the account, page, form, or source selection.
6. Save the repaired connection.
7. Review the source status and logs.

Use the provider identity that has access to the original account or form. Do not create a second connection unless the source is intentionally different.

## Disconnect a source

1. Open the source in **Data Sources**.
2. Select **Disconnect** or the matching action.
3. Review the warning and confirm the source name.
4. Confirm the disconnection.

Disconnecting prevents future submissions from that connection from entering PloverCRM. It does not delete leads already received from the source.

## After repair or disconnection

Check the source status and logs. For a repaired source, send an approved test event. For a disconnected source, confirm that it is no longer active and remove or update the source configuration in the external provider if necessary.

## Related articles

- [Understand the Data Sources Hub](01-understand-the-data-sources-hub.md)
- [Review Data Source Logs](02-review-data-source-logs.md)
- [Connect and Manage Google Ads Lead Forms](04-connect-google-ads-lead-forms.md)
