---
title: "Understand Setup, Connection, and License Notices"
category: "Navigation and Dashboard"
platform: web
status: Draft
last_verified: ""
---

# Understand Setup, Connection, and License Notices

PloverCRM can show notices in two places: in the **PloverCRM Web Dashboard** and in the PloverCRM plugin area inside the **WordPress dashboard**. These notices may tell you that setup is incomplete, the website connection needs attention, your account is connected, your license or plan has changed, or an optional plugin action is available.

Read the complete notice before dismissing it or changing settings. The account-connection screen shown in the WordPress dashboard is especially important because its actions can affect the website’s connection to PloverCRM.

![Placeholder screenshot of PloverCRM setup connection and license notices](images/placeholder-understand-setup-connection-and-license-notices.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot showing the PloverCRM account-connection screen and related notices. Redact website addresses, account identifiers, credentials, tokens, customer information, and other sensitive values before publishing the final image.

## Before you begin

- Know whether you are working in the **PloverCRM Web Dashboard** or the **WordPress dashboard**.
- Select the intended workspace or connected website before reviewing a notice.
- Confirm that your account has permission to view the notice and complete its action.
- If the notice concerns licensing, billing, or a website-wide plugin change, coordinate with the account owner or WordPress administrator.
- Do not click an activation, disconnect, installation, or purchase link until you understand its effect.

## Know where the notice appears

### PloverCRM Web Dashboard

The PloverCRM Web Dashboard can show workspace setup, connection, permission, update, or plan notices near the dashboard, workspace selector, or header. These notices describe what is needed for the currently selected workspace.

Use the Web Dashboard to review CRM data, workspace status, leads, activities, reminders, and dashboard information. A Web Dashboard notice does not mean that the WordPress administration area has been opened.

### WordPress dashboard

The PloverCRM plugin can show account and license information inside the WordPress dashboard. To open it:

1. Sign in to the WordPress dashboard for the connected website.
2. Open the **PloverCRM** menu.
3. Select **License**, **Account Connection**, or the equivalent item displayed by the plugin.
4. Confirm the website before reviewing or changing the connection.

The page title may read **Account Connection**. Treat this as a WordPress plugin administration screen, not as a page inside the PloverCRM Web Dashboard.

## Understand the Account Connection screen

The account-connection screen can include the following areas:

- **Account Connected:** Confirms that the WordPress plugin is linked to a PloverCRM account.
- **Plan:** Shows the plan associated with the connected account. The plan name may be a custom plan.
- **Subscription Status:** Shows whether the subscription is active or has another status.
- **Activated:** Shows when the account connection was activated.
- **Current Period:** Shows the current license or subscription period when the account provides that information.
- **Refresh Account Details:** Requests the latest account, plan, and subscription information.
- **Disconnect Account:** Removes the account connection from this website after confirmation.
- **Manage Account:** Opens the account-management destination supplied by PloverCRM.

The values displayed on this page belong to the connected account and website. They are not necessarily the same as the currently selected workspace view in another browser tab.

## Review an account-connected status

1. Open the PloverCRM account-connection page in the WordPress dashboard.
2. Confirm that the page shows the intended website and that the **Account Connected** status is present.
3. Review the **Plan** and **Subscription Status** values.
4. Check the **Activated** date and **Current Period** when you need to confirm account timing.
5. Compare the displayed status with the account information approved by your organization.
6. Open the PloverCRM Web Dashboard in a separate tab when you need to confirm the related workspace connection.
7. Verify that the workspace and website shown in the Web Dashboard correspond to this WordPress site.

A connected account status confirms the account link; it does not by itself confirm that every lead, data source, automation, or optional feature is configured correctly.

## Refresh account details

Use **Refresh Account Details** when the plan, subscription status, activation information, or current period looks out of date.

1. Confirm that the correct website is open in the WordPress dashboard.
2. Review the values currently displayed on the Account Connection page.
3. Select **Refresh Account Details** once.
4. Wait for the request to finish and for the status message or page values to update.
5. Compare the refreshed plan and subscription details with the expected account information.
6. Return to the PloverCRM Web Dashboard and check the workspace connection status if the notice came from there.

Do not repeatedly refresh while the request is processing. If the values remain unchanged, record the non-sensitive status message and contact the account owner or PloverCRM Support through an approved channel.

## Understand optional plugin recommendations

The WordPress dashboard may display a recommendation from another installed plugin, such as a notice asking you to install additional plugins. These recommendations are separate from the PloverCRM account connection.

1. Read the name of the plugin making the recommendation.
2. Review the recommended plugin names and the reason given.
3. Ask the website administrator whether the recommendation is approved.
4. Select **Begin installing plugins** only when the installation is authorized.
5. Select **Dismiss this notice** when your organization does not want to act on the recommendation.
6. Return to the PloverCRM account-connection area after the notice is handled.

Do not treat a third-party plugin recommendation as proof that the PloverCRM connection is broken. Installing a plugin can change the WordPress website, so follow your organization’s plugin review process.

## Understand activation notices

The plugin may display a green or highlighted notice saying that one step remains to activate a feature or restriction. For example, a notice may contain a link such as **Complete “Controlled COD Restriction” Activation Now**.

1. Read the feature name in the activation notice.
2. Confirm that the feature is intended for this website and account.
3. Review the linked activation page before submitting anything.
4. Ask the website or account administrator to approve the activation when it affects checkout, order handling, access, or another site-wide behavior.
5. Complete the activation only after reviewing the final confirmation.
6. Return to the Account Connection page and confirm whether the notice changed or cleared.
7. Test the affected website workflow with approved test data when required.

> **Caution:** An activation notice may change website behavior beyond the PloverCRM Web Dashboard. Do not activate a feature merely to remove the notice.

## Manage or disconnect the account

### Manage the account

Select **Manage Account** only when you need to review account-level details in the destination provided by PloverCRM. Confirm the destination before entering account information and use the approved account owner or administrator workflow.

### Disconnect the account

1. Confirm that the correct WordPress website is open.
2. Review which workspace and PloverCRM features depend on this connection.
3. Coordinate with the account owner and website administrator.
4. Select **Disconnect Account** only when the connection should end for this website.
5. Read the confirmation dialog carefully.
6. Confirm the disconnection only after understanding the effect on the Web Dashboard, lead capture, data sources, and plugin features.
7. Return to the PloverCRM Web Dashboard and check the workspace connection status.

> **Caution:** Disconnecting the account can stop or interrupt website-to-PloverCRM communication. It may affect lead capture, connected data sources, and access to workspace information. Do not use it as a troubleshooting shortcut.

## What to verify

After reviewing or acting on a notice, confirm:

- You know whether the action occurred in the WordPress dashboard or the PloverCRM Web Dashboard.
- The website and workspace are the intended destinations.
- The account, plan, subscription, and connection status show the expected values.
- Any activation or plugin installation was approved and tested.
- A notice changed only after the related requirement was completed.
- No account disconnection, purchase, plugin installation, or site-wide activation happened unintentionally.

## Troubleshooting

- If **Account Connected** is not shown, confirm the website, plugin activation, account authorization, and workspace connection status.
- If plan or subscription values are stale, use **Refresh Account Details** once and wait for the result.
- If **Manage Account** opens an unexpected destination, close it without entering information and contact the account owner through an approved channel.
- If a connection notice remains after the account is connected, check the PloverCRM plugin status and the Web Dashboard workspace status separately.
- If an activation link is unavailable, ask a WordPress administrator to review plugin permissions and the account plan.
- If the account was disconnected accidentally, stop changing settings and contact the account owner or PloverCRM Support before reconnecting it.

> **Security and privacy:** Never share passwords, one-time codes, API keys, connection tokens, private website URLs, billing details, or customer information in screenshots or support requests. Redact the Account Connection page before publishing it, especially the account destination, website address, plan details, and any activation links.

## Related articles

- [Understand the PloverCRM Web Dashboard Layout](01-understand-the-web-app-layout.md)
- [Use Navigation and Header Controls](02-use-navigation-and-header-controls.md)
- [Switch Workspaces or Websites](03-switch-workspaces-or-websites.md)
- [Understand Workspace Connection Status](../12-team-workspace-and-permissions/02-understand-workspace-connection-status.md)
- [Understand WordPress-Hosted Workspace Behavior](../12-team-workspace-and-permissions/03-understand-wordpress-hosted-workspace-behavior.md)
- [Troubleshoot Plugin Connection and Activation](../14-web-troubleshooting/03-troubleshoot-plugin-connection-and-activation.md)
