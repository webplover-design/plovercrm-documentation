---
title: "Find and Merge Duplicate Leads"
category: "Add and Manage Leads"
categories:
  - "PloverCRM Mobile App"
  - "Add and Manage Leads"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Add and Manage Leads"
  - "leads"
  - "lead management"
  - "duplicate leads"
  - "data quality"
platform: mobile
status: Draft
last_verified: ""
---
# Find and Merge Duplicate Leads

Review possible duplicate leads and combine them when you are authorized to do so. Merging removes one of the two lead records, so review every choice carefully.

## Review a possible duplicate

1. Open the lead's **Lead Details** screen.
2. Review the **Possible duplicate** notice when it appears.
3. Tap **Review**.
4. Wait for the duplicate lead details to load.

![Placeholder image of the PloverCRM duplicate lead review](images/placeholder-mobile-duplicate-lead-review.png)

> **Image placeholder:** Replace this image path with the final duplicate-review screenshot when it is available.

PloverCRM opens **Merge duplicate leads?** and identifies one record as **This lead (will be kept)** and the other as **Duplicate lead**.

## Choose which details to keep

1. Compare the two lead records.
2. For each field shown, select the value that should be kept.
3. Use the swap control if the other lead should be kept instead.
4. Review the count of details selected from the duplicate lead.
5. Tap **Merge selected details** only after reviewing the selections.

If there are no fields requiring a choice, PloverCRM can show **No details need your review.**

## Confirm the destructive action

Merging is permanent. PloverCRM warns:

> **The other lead will be removed after merging. This action cannot be undone.**

Do not merge records unless you have confirmed that they belong to the same person or organization and that the selected details are correct.

## What happens next

PloverCRM combines the selected details into the lead being kept and removes the other lead. Related records that can be preserved are moved to the resulting lead. PloverCRM then opens the resulting lead details.

## Troubleshooting

### The duplicate review is unavailable

Your role may not have permission to merge leads, or no possible duplicate may currently be available. Ask a workspace administrator to confirm your access.

### The duplicate lead cannot be loaded

Tap **Try again** in the merge review. If the lead changed while you were reviewing it, close the review and open it again from the current lead details screen.

### The merge fails

Review the error shown by PloverCRM. Do not retry repeatedly if the lead information has changed; reload both records and review the choices again.

## Related articles

- [View Lead Details](03-view-lead-details.md)
- [Understand Additional Lead Information](08-understand-additional-lead-information.md)
- [Delete a Lead](13-delete-a-lead.md)
