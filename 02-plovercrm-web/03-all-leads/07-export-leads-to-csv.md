---
title: "Export Leads to CSV"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Export Leads to CSV

Export the current **All Leads** result set to a CSV file for an approved reporting, analysis, or backup workflow. The export dialog shows how many leads will be exported and lets you choose all fields, visible columns, or specific fields.

![Placeholder screenshot of the Export leads dialog](images/placeholder-export-leads-to-csv.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the **Export leads** dialog. Use fictional data or redact names, email addresses, phone numbers, custom values, account details, and private URLs before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads** and confirm the selected workspace.
- Apply the intended search and filters before selecting **Export**.
- Confirm that your role permits exporting lead data.
- Confirm where the CSV may be stored and who may access it.

> **Caution:** A CSV export can contain personal and custom-field data. Export only the required leads and fields, store the file securely, and follow your organization’s retention and sharing policy.

## Prepare the result set

1. Open **All Leads**.
2. Confirm the workspace and connected website in the header.
3. Search for leads or apply **Lists**, **Tags**, **Created**, and **Stages** filters when needed.
4. Review the active filter chips.
5. Check the result count and visible range in the table footer.
6. Clear filters only when you intend to export the full current lead result.

The export dialog uses the current result set. If no search or filters are active, PloverCRM can show a message such as **No search or filters are active, so all visible leads will be exported.** Read that message carefully before continuing.

## Open the export dialog

1. Select **Export** in the toolbar above the leads table.
2. Wait for the **Export leads** dialog to open.
3. Read the total shown in the result summary, such as **2,246 leads**.
4. Confirm that the dialog describes the same filtered or unfiltered result you prepared.
5. Stop and close the dialog if the count or workspace is not correct.

## Choose exported fields

The **Fields** section can provide three choices:

- **All fields (55)** — exports every available lead field shown by the dialog.
- **Visible columns (8)** — exports only the fields currently visible in the leads table.
- **Specific fields** — lets you choose the individual fields to include.

The exact field counts depend on your workspace configuration.

1. Select **All fields (number)** when the approved report requires every available field.
2. Select **Visible columns (number)** when the CSV should match the current table view.
3. Select **Specific fields** when the export should contain only selected fields.
4. Review the chosen fields before moving to **Quantity**.
5. Remove unnecessary personal or sensitive fields whenever the report does not require them.

## Choose the export quantity

The **Quantity** control limits how many leads are exported from the current result set. Available choices can include:

- **All current results**
- **First 100**
- **First 500**
- **First 1,000**
- **Custom limit**

1. Open the quantity selector.
2. Read the current selection and the result-set total.
3. Choose **All current results** only when the complete result is approved.
4. Choose a preset limit for a smaller review sample.
5. Choose **Custom limit** when you need a specific number and enter the approved value.
6. Confirm that the quantity is within your organization’s export policy.

![Placeholder screenshot of export quantity options](images/placeholder-export-quantity-options.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the quantity menu and options such as **All current results**, **First 100**, **First 500**, **First 1,000**, and **Custom limit**.

## Export the CSV

1. Review the result count, fields, quantity, workspace, and filters one final time.
2. Select **Export CSV**.
3. Wait for PloverCRM to prepare the file.
4. Save or open the CSV only through an approved device and application.
5. Check the header row and a small sample of records.
6. Confirm that the row count and fields match the dialog selection.
7. Store the file securely and remove temporary copies when the retention period ends.
8. Select **Close** when you are finished with the dialog.

## What to verify

After the export, confirm:

- The CSV contains the intended number of leads.
- The headers match **All fields**, **Visible columns**, or **Specific fields** as selected.
- Active filters were respected.
- No unnecessary private fields were included.
- The file is stored only in an approved location.

## Troubleshooting

- If the export count is wrong, close the dialog, review filters, and open **Export** again.
- If **Specific fields** does not show a field, confirm that your role and workspace configuration permit it.
- If the file does not download, check the browser download permission and try once more.
- If the CSV contains unexpected columns, compare it with the selected field option and visible table columns.
- If the export is too large, choose a smaller quantity or export an approved filtered result.
- If export is unavailable, ask an administrator to review your permission and the workspace connection.

> **Security and privacy:** Do not email or publicly upload an unredacted lead export. Protect phone numbers, email addresses, names, tracking data, custom fields, and any other personal information in the CSV.

## Related articles

- [Understand the All Leads Screen](01-understand-the-all-leads-screen.md)
- [Filter Leads by List, Tag, Stage, or Date](03-filter-leads-by-list-tag-stage-or-date.md)
- [Select and Rearrange Lead Columns](04-select-and-rearrange-lead-columns.md)
- [Select Leads and Use Bulk Actions](08-select-leads-and-use-bulk-actions.md)
