---
title: "Connect and Manage Google Ads Lead Forms"
category: "Data Sources and Imports"
platform: web
status: Draft
last_verified: ""
---

# Connect and Manage Google Ads Lead Forms

Connect Google Ads to receive leads from Google lead forms in PloverCRM. After connecting, choose the Google Ads account, review available forms, configure how submissions are routed, and monitor the connection.

> **Image:** `[Add screenshot here]`

## Before connecting

Make sure you can sign in to the Google account that has access to the required Google Ads customer account and lead forms. Use the correct Google account when the authorization window opens.

## Connect Google Ads

1. Open **Data Sources** from the main navigation.
2. Select the option to add or connect a data source.
3. Choose **Google Ads**.
4. Select **Connect** or the matching authorization button.
5. Sign in to Google when prompted.
6. Review the permissions requested by PloverCRM.
7. Approve the connection.
8. Return to PloverCRM and wait for the account-selection screen.

Do not share your Google password or authorization code. Complete authorization in the official Google window.

## Select the Google Ads account

1. Review the Google Ads accounts available to the connected Google identity.
2. Select the customer account that contains the lead forms.
3. Continue to the form-selection or source-configuration step.

If the expected account is missing, confirm that the signed-in Google user has access to it and reconnect using the correct Google identity if necessary.

## Select lead forms

1. Review the campaigns, forms, or lead-form sources shown by PloverCRM.
2. Select the forms whose submissions should create leads.
3. Review the selected forms before saving.
4. Save or connect the source.

The available forms depend on the Google Ads account and the permissions granted during authorization.

## Configure imported lead data

Review the fields that Google sends with each lead form submission. Where the data-source setup provides routing or default options, configure:

- The destination workspace.
- The default pipeline stage.
- The assignee.
- Lists and tags.
- Deal value or other supported defaults.

Review the configuration carefully because it can affect every lead received from the selected forms.

## Review the connection

After saving, review the Google Ads source in **Data Sources**. Check that it is connected, that the selected account and forms are correct, and that no repair action is required.

When a new lead arrives, open it in **Leads** and confirm that the source, mapped fields, routing, lists, tags, and stage are correct.

## Manage the connection

Open the Google Ads source to review its status and available management actions. Depending on the connection state, you may be able to refresh forms, change the selected forms, repair authorization, or disconnect the source.

Disconnect only when you no longer want submissions from that Google Ads connection to reach PloverCRM. Disconnecting the source does not delete leads that were already received.

## Troubleshooting

- **Google authorization fails:** restart the connection and use the Google identity with access to the Ads account.
- **The account is missing:** ask the Google Ads administrator to grant access to the signed-in user.
- **Forms are missing:** confirm that the forms exist and are available to the selected Ads account, then refresh the form list.
- **Leads are not arriving:** check the source status, selected forms, Google lead-form activity, and data-source logs.
- **Fields are incorrect:** review the source mapping and correct the destination fields before processing more submissions.
- **Authorization needs repair:** use the repair or reconnect action shown for the source rather than creating duplicate connections.

## Related articles

- [Understand the Data Sources Hub](01-understand-the-data-sources-hub.md)
- [Review Data Source Logs](02-review-data-source-logs.md)
- [Configure CRM Routing](07-configure-crm-routing.md)
- [Repair or Disconnect a Data Source](14-repair-or-disconnect-a-data-source.md)
