---
title: "Troubleshoot Deal Access"
category: "Deals and Pipelines"
platform: web
status: Draft
last_verified: ""
---

# Troubleshoot Deal Access

Use these checks when the Deals page is missing, disabled, empty, or unavailable.

> **Image:** `[Add screenshot here]`

## The Deals page is not visible

1. Open **Settings → Stages**.
2. Check whether **Experimental Deals page** is enabled.
3. If it is disabled, ask a user with settings access to enable it.
4. Refresh the application and check the main navigation again.

## The page says that Deals is experimental

This message means the experimental setting is off. Enable **Experimental Deals page** in **Settings → Stages** before using the Deals board.

## The page says that Deals are unavailable

Your role may not include permission to read deals. Ask a workspace administrator to review your role and deal permissions.

## Deals does not appear after activation

Check that:

- The experimental setting was saved.
- Your role includes deal access.
- A pipeline exists in the workspace.
- You have refreshed the page after changing the setting.
- The navigation is not filtered by another account or workspace condition.

## The Deals page is empty

An empty page can mean that the workspace has no deals, the selected pipeline has no deal records, or your role limits the records you can view. Confirm that leads have deal information and review the configured pipeline stages.

## A stage does not update

Confirm that:

- You selected a stage from the active pipeline.
- Your role allows deal updates.
- The save action completed successfully.
- You refreshed the Deals page after saving.

Changing a stage updates the position of the existing deal. It does not create a new deal.

## A deal value does not update

Check that the value uses the number format accepted by PloverCRM and that you have permission to update deals. Stage and value are separate fields, so changing one does not automatically change the other.

## When contacting support

Include the page name, the non-sensitive message shown, the approximate time, and the action that failed. Do not include passwords, tokens, private URLs, or customer data.

## Related articles

- [Understand Deals and Pipeline Stages](01-understand-deals-and-pipeline-stages.md)
- [Enable or Disable the Experimental Deals Page](02-enable-or-disable-the-deals-page.md)
- [Use the Deals Workspace](03-use-the-deals-workspace.md)
