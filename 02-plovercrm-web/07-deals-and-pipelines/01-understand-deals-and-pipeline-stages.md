---
title: "Understand Deals and Pipeline Stages"
category: "Deals and Pipelines"
platform: web
status: Draft
last_verified: ""
---

# Understand Deals and Pipeline Stages

A **deal** is a sales opportunity associated with a lead. A deal can have a title, monetary value, currency, pipeline, and pipeline stage.

A **pipeline stage** shows where the lead or deal currently sits in your sales process. For example, a workspace might use stages such as **New**, **Contacted**, **Qualified**, **Proposal**, **Won**, or **Lost**.

A stage and a deal are not the same thing. Changing a stage from **New** to **Contacted** updates the position of the existing lead or deal. It does not create a new deal.

> **Image:** `[Add screenshot here]`

## Understand deal values

The **Value** field is the monetary amount associated with the sales opportunity. A lead may show `$0` when no value has been entered. The currency and formatting depend on the workspace configuration.

Changing the stage and changing the value are separate actions:

- A stage change moves the lead or deal through the sales process.
- A value change updates the expected monetary amount.
- Neither action automatically creates another deal.

## Understand the experimental Deals page

PloverCRM includes an experimental **Deals** page that presents deals by pipeline stage. The page can show:

- The active pipeline.
- The total number of deals.
- Deal groups organized by stage.
- The current stage of each deal.
- Deal values and related lead information when available.

The page is experimental, so it may be disabled by default and may change in a future version.

## How deals and stages relate

A deal belongs to a pipeline and normally has a stage within that pipeline. When a deal changes from **New** to **Contacted**, it remains the same deal but appears under a different stage. The deal value remains unchanged unless you edit it separately.

A lead can also have a default deal created for it. This is why a lead may show pipeline information even when you have not manually created a separate sales opportunity.

## Access and availability

The Deals page is available only when:

1. The experimental Deals setting is enabled.
2. A pipeline is available for the workspace.
3. Your role includes permission to read deals.

If any of these conditions is missing, the Deals page may not appear or may show an access message.

## Related articles

- [Enable or Disable the Experimental Deals Page](02-enable-or-disable-the-deals-page.md)
- [Use the Deals Workspace](03-use-the-deals-workspace.md)
