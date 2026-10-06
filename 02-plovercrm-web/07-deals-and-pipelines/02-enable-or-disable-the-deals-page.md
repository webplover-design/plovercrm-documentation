---
title: "Enable or Disable the Experimental Deals Page"
category: "Deals and Pipelines"
platform: web
status: Draft
last_verified: ""
---

# Enable or Disable the Experimental Deals Page

The experimental Deals page is turned on or off from **Settings → Stages**. You must have permission to change workspace settings.

> **Image:** `[Add screenshot here]`

## Turn on the Deals page

1. Open the PloverCRM Web Dashboard.
2. Select **Settings** from the left navigation.
3. Open **Stages**.
4. Locate the **Experimental Deals page** setting.
5. Turn the setting **on**.
6. Return to the main navigation.
7. Select **Deals**.

When the setting is enabled, PloverCRM adds **Deals** to the navigation for users who have the required deal permission. The Deals page displays the available pipeline and groups deals by their current stages.

## Turn off the Deals page

1. Open **Settings**.
2. Select **Stages**.
3. Locate **Experimental Deals page**.
4. Turn the setting **off**.
5. Return to the main navigation.

The Deals page is hidden or shows that the feature is disabled. Turning the page off does **not** delete leads, deals, pipeline stages, or deal values. It only disables access to the experimental Deals workspace.

## What happens to existing data?

Disabling the page does not remove existing deal information. Existing deal stages and values remain associated with their leads and can continue to be used by other CRM features that have access to them.

If you enable the page again later, the existing deal information should be available again, subject to the user's permissions and the current workspace configuration.

## If the setting is missing

If **Experimental Deals page** is not visible under **Settings → Stages**, you may not have permission to change that setting. Ask a workspace administrator to review your access.

## If Deals does not appear after enabling it

Check the following:

- The setting was saved successfully.
- Your role includes permission to read deals.
- A pipeline is configured for the workspace.
- You are viewing the correct workspace.
- The page has been refreshed after the setting changed.

## Related articles

- [Understand Deals and Pipeline Stages](01-understand-deals-and-pipeline-stages.md)
- [Use the Deals Workspace](03-use-the-deals-workspace.md)
- [Troubleshoot Deal Access](04-troubleshoot-deal-access.md)
