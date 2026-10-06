---
title: "Import Leads from a CSV File"
category: "Data Sources and Imports"
platform: web
status: Draft
last_verified: ""
---

# Import Leads from a CSV File

Import leads from a CSV file when you need to add historical records or move lead data into PloverCRM in bulk. Before starting, review the file, delimiter, header setting, field mapping, duplicate behavior, lists, and tags.

> **Image:** `[Add screenshot here]`

## Prepare the CSV file

- Use a CSV file containing one lead per row.
- Keep the first row available as column headings when your file includes headers.
- Check that required lead information is present and consistently formatted.
- Remove test rows, blank rows, and columns that should not be imported.
- Keep a copy of the original file before making changes.

## Start the import

1. Open **Data Sources** from the main navigation.
2. Open the CSV import option.
3. Choose the CSV file.
4. Review the file preview before continuing.

## Choose the delimiter and header option

PloverCRM must know how the file separates columns. Choose the delimiter used by your file, such as a comma or another separator. If the columns appear combined into one column in the preview, the delimiter is probably incorrect.

Choose the header option that matches the file:

- Select the option indicating that the first row contains headers when the first row contains names such as `Name`, `Email`, or `Phone`.
- Do not treat the first row as headers when the first row contains actual lead data.

After changing the delimiter or header option, review the preview again. Continue only when the columns and sample values appear in the correct places.

## Map incoming fields

1. Match each CSV column to the appropriate PloverCRM field.
2. Map standard fields such as name, email, phone, and other available lead fields.
3. Map custom fields only when the destination field has the correct meaning and data type.
4. Leave unknown or unnecessary columns unmapped instead of guessing.
5. Review required fields and any validation messages.

## Apply lists and tags during import

Use the import options for **Lists** and **Tags** when you want every imported lead to receive the same organization labels.

- Select an existing list to place the imported leads in that list.
- Select one or more existing tags to apply to every imported lead.
- Choose labels that match the purpose of the import, such as a source or campaign.
- Review the selected lists and tags before starting; they may be applied to every row.

Lists and tags organize imported leads but do not replace field mapping. If different rows need different lists or tags, include the relevant columns in the CSV and map them only when the import interface supports that mapping.

## Review duplicate behavior and validation

Review how PloverCRM handles records that may already exist. Check the preview for duplicate warnings, missing required values, invalid email or phone formats, and unmapped columns. Correct the CSV and upload it again when the errors are caused by the file.

## Start and verify the import

1. Review the file name and row count.
2. Review the delimiter and header choice.
3. Review field mappings, lists, tags, and duplicate behavior.
4. Start the import.
5. Wait for the import to finish before starting another import of the same file.
6. Open the leads list and search for a few imported records.
7. Confirm that the expected fields, lists, and tags were applied.

## Troubleshooting

- **Columns are combined:** choose the delimiter used by the CSV file.
- **The first lead is missing:** check whether the first row was incorrectly treated as a header.
- **Values appear under the wrong fields:** correct the field mapping and repeat the preview.
- **Lists or tags are missing:** confirm that they were selected before starting the import.
- **Rows fail validation:** correct the values shown in the validation message and upload the corrected file.
- **The import appears stuck:** wait for its status before submitting the file again.

## Related articles

- [Map Incoming Fields](09-map-incoming-fields.md)
- [Review Failed Leads and Download Error Logs](11-review-failed-leads-and-download-error-logs.md)
- [Configure CRM Routing](07-configure-crm-routing.md)
