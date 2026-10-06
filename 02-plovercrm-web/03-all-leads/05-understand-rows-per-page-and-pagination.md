---
title: "Understand Rows per Page and Pagination"
category: "All Leads"
platform: web
status: Draft
last_verified: ""
---

# Understand Rows per Page and Pagination

The bottom of the **All Leads** table controls how many leads appear at once and which page of results you are viewing. In the example shown, the table contains **2,246 leads**, displays **1–20**, and has **113 pages** when **20** rows per page is selected.

![Placeholder screenshot of All Leads rows per page and pagination](images/placeholder-rows-per-page-and-pagination.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the rows-per-page menu and pagination controls. Use fictional lead data or redact names, phone numbers, email addresses, and custom-field values before publishing the final image.

## Before you begin

- Sign in to the **PloverCRM Web Dashboard**.
- Open **All Leads** and confirm the selected workspace.
- Finish any unsaved edit before changing the page size or moving to another page.
- If you plan to use a bulk action, review the selected rows and filters separately before proceeding.

## Read the table footer

At the bottom of the table, PloverCRM shows:

- The visible range, such as **Showing 1–20 of 2246 leads**.
- The **Rows per page** control.
- The current page and total page count, such as **1 of 113**.
- A previous-page arrow.
- Page-number buttons.
- An ellipsis when some page numbers are hidden.
- A next-page arrow.

The total and page count change when you search, filter, refresh, or change the rows-per-page setting.

## Change rows per page

1. Open **All Leads**.
2. Scroll to the bottom of the lead table.
3. Locate **Rows per page**.
4. Select the current value, such as **20**.
5. Choose one of the available values: **10**, **20**, **50**, or **100**.
6. Wait for the table to reload.
7. Check the footer to confirm the new range and total page count.

For example:

- **10** rows per page displays up to 10 leads at once.
- **20** rows per page displays up to 20 leads at once.
- **50** rows per page displays up to 50 leads at once.
- **100** rows per page displays up to 100 leads at once.

A larger page size reduces the number of pages but may make the table slower or harder to scan. Choose the smallest size that supports the task.

![Placeholder screenshot of the rows-per-page options](images/placeholder-rows-per-page-options.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the **10**, **20**, **50**, and **100** options.

## Move between pages

1. Check the current page shown in the footer.
2. Select a page number to open that page directly.
3. Select the right arrow to open the next page.
4. Select the left arrow to return to the previous page.
5. Use the ellipsis to understand that additional page numbers exist between the displayed buttons.
6. Confirm the visible range after each page change.

In the example with 2,246 leads and 20 rows per page, page 1 shows leads 1–20 and page 113 contains the final results. If you change the page size, PloverCRM recalculates the total number of pages.

## Use pagination with filters

1. Apply a filter, such as **Lists**, **Tags**, **Created**, or **Stages**.
2. Review the filtered total in the table footer.
3. Confirm the current page returns to the beginning of the filtered results when the table reloads.
4. Move through the filtered pages using the arrows or page numbers.
5. Check the active filter chips before opening or changing a lead.
6. Select **Clear all** only when you are ready to return to the complete lead view.

Pagination applies to the current result set. It does not remove leads that are outside the current page or filter.

## Use pagination with bulk actions

Before a bulk action, determine whether the action applies to selected rows, the current page, or the full filtered result set.

1. Apply the intended filters before selecting leads.
2. Review the footer total and visible range.
3. Select the required rows or the table selection checkbox.
4. Open **Bulk actions** and read the scope shown by PloverCRM.
5. Do not move to another page until you know whether the selection remains active.
6. Review the selected-count banner and records before confirming.

> **Caution:** A page-size change or page navigation can alter what is visible while a selection is active. Always recheck the selected count and action scope before changing leads in bulk.

## What to verify

After changing the page size or page:

- The footer shows the expected visible range.
- The selected rows per page value is correct.
- The current page and total page count match the current filters.
- The workspace and active filter chips are unchanged.
- No lead was edited, deleted, or selected unintentionally.

## Troubleshooting

- If the page count looks wrong, clear filters and confirm the total lead count.
- If the table does not reload, wait for the request to finish and refresh **All Leads** once.
- If a page number is unavailable, use the previous or next arrow and check whether the result set changed.
- If selected rows disappear after changing pages, recheck the selected-count banner before using a bulk action.
- If the footer is hidden, scroll to the bottom of the table or reduce browser zoom temporarily.

> **Security and privacy:** Pagination can expose customer names, contact details, list membership, stages, and custom-field values. Use the minimum necessary rows per page and redact customer information from screenshots.

## Related articles

- [Understand the All Leads Screen](01-understand-the-all-leads-screen.md)
- [Filter Leads by List, Tag, Stage, or Date](03-filter-leads-by-list-tag-stage-or-date.md)
- [Select Leads and Use Bulk Actions](08-select-leads-and-use-bulk-actions.md)
