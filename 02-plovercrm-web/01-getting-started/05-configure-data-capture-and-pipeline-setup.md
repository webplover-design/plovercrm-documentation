---
title: "Configure Data Capture and Pipeline Setup"
category: "Getting Started"
platform: web
status: Draft
last_verified: ""
---

# Configure Data Capture and Pipeline Setup

Review how PloverCRM receives leads and how your team moves those leads through the pipeline after the initial workspace setup.

![Placeholder screenshot of PloverCRM data capture and pipeline setup](images/placeholder-data-capture-pipeline-setup.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of PloverCRM data capture or pipeline settings after the workflow and privacy review are complete.

## Before you start

- Complete [guided workspace setup](04-complete-guided-workspace-setup.md).
- Have workspace configuration permission.
- Know which website forms or other lead sources your team will use.
- Agree on the pipeline stages, lists, tags, and assignment rules your team needs.

## Review data capture

1. Open the connected workspace in PloverCRM.
2. Open **Data Sources** or the data-capture area shown in your workspace.
3. Review the enabled lead sources.
4. For each source, confirm the destination workspace and any available field mapping.
5. Confirm that incoming leads receive the intended list, tags, stage, or assignment.
6. Save changes before leaving the source settings.

![Placeholder screenshot of the PloverCRM data sources screen](images/placeholder-data-sources-screen.png)

> **Screenshot placeholder:** Replace this image with an approved data-sources screenshot after the workflow and privacy review are complete.

Available data sources and labels depend on your workspace. If a source is not shown, ask a workspace administrator whether it is available for your plan and connection.

## Review pipeline stages

1. Open **Settings**.
2. Open the pipeline or stages settings.
3. Review the existing stages in the order your team uses them.
4. Add, rename, reorder, or disable stages according to your team's process.
5. Save the changes.
6. Confirm that the stages appear in the lead and dashboard views.

Use clear stage names that describe the next step for the lead. Before changing or removing a stage, check whether existing leads use it and agree on the effect with your workspace team.

> **Caution:** Changing pipeline stages can affect how existing leads are organized. Review the impact before removing or renaming a stage.

## Test the setup

1. Use an approved test source or test form.
2. Submit a test lead without real customer information.
3. Wait for the lead to arrive in PloverCRM.
4. Open the lead and confirm the source, list, tags, stage, and assignment.
5. Correct the source or pipeline settings if the result is not what you expected.
6. Remove the test lead when your team's process requires it.

## What happens next

When the setup is correct, new leads are available in the selected workspace and follow the configured pipeline process. You can open PloverCRM from the connected website's dashboard or [log in to the PloverCRM Web Dashboard](06-log-in-to-plovercrm-web.md).

## Troubleshooting

- If no lead arrives, confirm that the plugin is active and the source is connected.
- If a lead arrives in the wrong workspace, check the selected workspace and source destination.
- If fields or tags are missing, review the source mapping and default values.
- If a stage is unavailable, review the workspace stage settings and your permissions.
- For connection issues, see [Troubleshoot Plugin Connection and Activation](../14-web-troubleshooting/03-troubleshoot-plugin-connection-and-activation.md).
