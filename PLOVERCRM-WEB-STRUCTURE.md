# PloverCRM Web User Guide

## Proposed documentation structure

**Document status:** Revised structure proposal for approval  
**Product name:** PloverCRM  
**Product area:** PloverCRM Web  
**Audience:** WordPress site owners, workspace managers, teammates, and CRM users  
**Content state:** Structure only; article instructions will be drafted after approval and workflow verification

---

## 1. Purpose

This document defines the customer-facing documentation structure for the PloverCRM Web CRM. It covers the journey from WordPress plugin setup and website connection through everyday lead management, reminders, integrations, automations, workspace administration, and support.

The Web guide remains separate from the PloverCRM Mobile App guide because the products have different setup paths, screens, permissions, and available actions.

Each focused screen or workflow will become a separate Markdown article. Category `README.md` files will explain the category and link to its articles.

**Proposed source location:**

```text
D:\PloverCRM_docs_project\final_file_structure\02-plovercrm-web
```

---

## 2. Documentation rules

### Product naming

Use **PloverCRM** in every folder name, article title, heading, description, and cross-link. Do not use “Clover CRM” or “CloverCRM.”

### Customer-facing scope

Document visible actions and expected results only. Do not expose:

- API routes or request details
- Database tables or internal storage
- Cloudflare, deployment, or export mechanics
- Repository paths or implementation details
- Secret values, credentials, tokens, or customer data

### Article boundaries

Use one Markdown file for one focused task or screen. Split a workflow when it has a different permission requirement, screen, destructive action, or expected outcome.

### Verification labels

The tree below separates features confirmed in the repository from claims that require verification in the running product. Exact labels, screenshots, plan limits, setup instructions, and role boundaries must be checked before article content is written.

### Important product terminology

The current Web implementation uses both a **Lead Detail Drawer** and a **Lead Detail Page**. It does not provide a visible customer-facing table-zoom control. The documentation must not promise table zoom values such as 20%–160% for either Web or Mobile.

---

# 3. Revised Web file tree

```text
02-plovercrm-web/
├── README.md
│
├── 01-getting-started/
│   ├── README.md
│   ├── 01-understand-plovercrm-web.md
│   ├── 02-create-or-access-your-plovercrm-account.md
│   ├── 03-download-the-plovercrm-plugin.md
│   ├── 04-complete-guided-workspace-setup.md
│   ├── 05-configure-data-capture-and-pipeline-setup.md
│   └── 06-log-in-to-plovercrm-web.md 
│
├── 02-navigation-and-dashboard/ 1 OR 2 ARTICLES FOR dashboard
│   ├── README.md
│   ├── 01-understand-the-web-app-layout.md
│   ├── 02-use-the-left-navigation-panel.md
│   ├── 03-understand-the-header-controls.md
│   ├── 04-switch-workspaces-or-websites.md
│   ├── 05-understand-dashboard-statistics.md
│   ├── 06-understand-pipeline-stage-summaries.md - ?
│   ├── 07-understand-the-lead-growth-chart.md
│   ├── 08-use-dashboard-reminders-and-lists.md
│   ├── 09-understand-setup-connection-and-license-notices.md
│   └── 10-refresh-workspace-data.md
│
├── 03-all-leads/
│   ├── README.md
│   ├── 01-understand-the-all-leads-screen.md
│   ├── 02-search-for-leads.md
│   ├── 03-filter-leads-by-list-tag-stage-or-date.md
│   ├── 04-select-and-rearrange-lead-columns.md
│   ├── 05-understand-rows-per-page-and-pagination.md
│   ├── 06-refresh-and-load-leads.md
│   ├── 07-export-leads-to-csv.md
│   ├── 08-select-leads-and-use-bulk-actions.md
│   ├── 09-change-stage-assignee-lists-tags-or-custom-fields-in-bulk.md
│   └── 10-delete-leads-in-bulk.md
│
├── 04-add-new-lead/ 5 ARTICLES
│   ├── README.md
│   ├── 01-open-add-new-lead.md
│   ├── 02-add-lists-tags-and-custom-fields.md
│   ├── 03-assign-a-lead-to-a-teammate.md
│   ├── 04-set-the-lead-stage-and-value.md
│   └── 05-save-a-new-lead-and-review-duplicates.md
│
├── 05-lead-details/
│   ├── README.md
│   ├── 01-open-the-lead-detail-drawer-or-page.md
│   ├── 02-navigate-between-leads-in-the-drawer.md
│   ├── 03-use-lead-header-controls.md
│   ├── 04-edit-lead-information.md
│   ├── 05-use-call-sms-email-whatsapp-telegram-and-quick-reply.md
│   ├── 06-share-a-lead-and-download-a-vcard.md
│   ├── 07-add-a-lead-to-your-contacts.md
│   ├── 08-understand-identity-and-assignment.md
│   ├── 09-manage-lists-and-tags-on-a-lead.md
│   ├── 10-review-tracking-signals.md
│   ├── 11-review-ip-information.md
│   ├── 12-understand-pipeline-stage-and-value.md
│   ├── 13-view-custom-fields-and-lead-metadata.md
│   ├── 14-find-and-merge-duplicate-leads.md
│   └── 15-delete-a-lead.md
│
├── 06-activities-and-reminders/
│   ├── README.md
│   ├── 01-review-the-lead-activity-timeline.md
│   ├── 02-filter-activity-history.md
│   ├── 03-add-a-manual-activity-or-note.md
│   ├── 04-edit-or-delete-an-activity.md
│   ├── 05-create-a-lead-reminder.md
│   ├── 06-review-reminder-statuses.md
│   ├── 07-complete-or-snooze-a-reminder.md
│   ├── 08-delete-a-reminder.md
│   ├── 09-use-the-global-reminders-page.md
│   └── 10-configure-browser-reminder-notifications.md
│
├── 07-deals-and-pipelines/
│   ├── README.md
│   ├── 01-understand-deals-and-the-experimental-deals-page.md
│   ├── 02-enable-or-disable-the-deals-page.md
│   ├── 03-review-deal-stage-and-value-on-a-lead.md
│   ├── 04-use-the-deals-workspace.md
│   └── 05-troubleshoot-deal-access.md
│
├── 08-data-sources-and-imports/
│   ├── README.md
│   ├── 01-understand-the-data-sources-hub.md
│   ├── 02-review-data-source-logs.md
│   ├── 03-connect-a-form-data-source.md
│   ├── 04-connect-google-ads-lead-forms.md
│   ├── 05-connect-meta-lead-ads-forms.md
│   ├── 06-create-and-manage-webhooks.md
│   ├── 07-configure-crm-routing.md
│   ├── 08-import-leads-from-a-csv-file.md
│   ├── 09-choose-csv-delimiter-and-header-options.md
│   ├── 10-map-incoming-fields.md
│   ├── 11-apply-lists-and-tags-during-import.md
│   ├── 12-review-import-history-and-progress.md
│   ├── 13-resume-a-historical-import.md
│   ├── 14-review-failed-leads-and-download-error-logs.md
│   ├── 15-connect-and-manage-google-ads.md
│   └── 16-repair-or-disconnect-a-data-source.md
│
├── 09-automations/
│   ├── README.md
│   ├── 01-understand-automations.md
│   ├── 02-view-automation-logs.md
│   ├── 03-browse-flow-templates.md
│   ├── 04-create-an-automation-from-a-template.md
│   ├── 05-create-an-automation-from-scratch.md
│   ├── 06-configure-automation-basics.md
│   ├── 07-configure-automation-triggers.md
│   ├── 08-configure-automation-actions.md
│   ├── 09-configure-internal-email-actions.md
│   ├── 10-use-google-ads-conversion-actions.md
│   ├── 11-use-meta-capi-actions.md
│   ├── 12-preview-automation-email-content.md
│   ├── 13-manage-automation-status-and-queue.md
│   ├── 14-connect-google-ads-for-automations.md
│   └── 15-manage-meta-capi-connections.md
│
├── 10-settings-and-preferences/
│   ├── README.md
│   ├── 01-understand-the-settings-overview.md
│   ├── 02-manage-your-profile.md
│   ├── 03-change-or-reset-your-password.md
│   ├── 04-manage-display-and-appearance.md
│   ├── 05-configure-lead-table-columns.md
│   ├── 06-configure-lead-actions-and-activity-logging.md
│   ├── 07-configure-browser-notifications.md
│   ├── 08-customize-new-lead-and-reminder-alerts.md
│   ├── 09-manage-business-information.md
│   ├── 10-configure-email-reply-settings.md
│   ├── 11-manage-pipeline-stages.md
│   ├── 12-manage-message-templates.md
│   ├── 13-refresh-workspace-data.md
│   ├── 14-review-system-health.md
│   └── 15-review-settings-feature-logs-and-support.md
│
├── 11-custom-fields-lists-and-tags/
│   ├── README.md
│   ├── 01-understand-custom-fields.md
│   ├── 02-create-a-custom-field.md
│   ├── 03-edit-and-reorder-custom-fields.md
│   ├── 04-group-custom-fields.md
│   ├── 05-delete-a-custom-field.md
│   ├── 06-review-system-managed-fields.md
│   ├── 07-manage-lists.md
│   └── 08-manage-tags.md
│
├── 12-team-workspace-and-permissions/
│   ├── README.md
│   ├── 01-manage-saved-browser-workspaces.md
│   ├── 02-understand-workspace-connection-status.md
│   ├── 03-understand-wordpress-hosted-workspace-behavior.md
│   ├── 04-invite-and-manage-teammates.md
│   ├── 05-manage-teammate-sign-in-details.md
│   ├── 06-understand-roles-and-permissions.md
│   ├── 07-create-edit-and-delete-roles.md
│   ├── 08-understand-lead-scopes-and-entity-permissions.md
│   └── 09-understand-read-only-settings.md
│
├── 13-help-updates-and-account-support/
│   ├── README.md
│   ├── 01-use-the-help-center.md
│   ├── 02-contact-support.md
│   ├── 03-view-whats-new.md
│   ├── 04-request-a-feature.md
│   ├── 05-understand-the-advocate-program.md
│   ├── 06-use-the-wordpress-host-launcher.md
│   └── 07-understand-license-and-plan-notices.md
│
└── 14-web-troubleshooting/
    ├── README.md
    ├── 01-troubleshoot-login-and-account-access.md
    ├── 02-troubleshoot-plugin-installation.md
    ├── 03-troubleshoot-plugin-connection-and-activation.md
    ├── 04-troubleshoot-workspace-connection.md
    ├── 05-troubleshoot-lead-loading-search-and-refresh.md
    ├── 06-troubleshoot-csv-imports-and-failed-leads.md
    ├── 07-troubleshoot-data-source-connections.md
    ├── 08-troubleshoot-automations-and-queues.md
    ├── 09-troubleshoot-browser-notifications.md
    ├── 10-troubleshoot-permission-and-read-only-access.md
    └── 11-frequently-asked-questions.md
```

---

# 4. Web feature-to-article mapping

| Confirmed or requested feature | Planned article location |
| --- | --- |
| Account access and sign-up | `01-getting-started/02-create-or-access-your-plovercrm-account.md` |
| Download, WordPress installation, website addition, and plugin activation | `01-getting-started/03-download-the-plovercrm-plugin.md` |
| Guided workspace setup | `01-getting-started/04-complete-guided-workspace-setup.md` |
| Data capture and pipeline setup | `01-getting-started/05-configure-data-capture-and-pipeline-setup.md` |
| PloverCRM Web Dashboard login | `01-getting-started/06-log-in-to-plovercrm-web.md` |
| Left navigation panel | `02-navigation-and-dashboard/02-use-the-left-navigation-panel.md` |
| Header controls, search, sync, notifications, and theme | `02-navigation-and-dashboard/03-understand-the-header-controls.md` |
| Workspace or website switching | `02-navigation-and-dashboard/04-switch-workspaces-or-websites.md` |
| Dashboard statistics and stages | `02-navigation-and-dashboard/05-understand-dashboard-statistics.md` and `06-understand-pipeline-stage-summaries.md` |
| Lead Growth Chart and date ranges | `02-navigation-and-dashboard/07-understand-the-lead-growth-chart.md` |
| Dashboard reminders and lists | `02-navigation-and-dashboard/08-use-dashboard-reminders-and-lists.md` |
| Setup, connection, license, and mobile-app notices | `02-navigation-and-dashboard/09-understand-setup-connection-and-license-notices.md` |
| Lead table overview | `03-all-leads/01-understand-the-all-leads-screen.md` |
| Search by lead fields | `03-all-leads/02-search-for-leads.md` |
| Lists, tags, stages, and created/updated date filters | `03-all-leads/03-filter-leads-by-list-tag-stage-or-date.md` |
| Column selection and ordering | `03-all-leads/04-select-and-rearrange-lead-columns.md` |
| Rows per page and pagination | `03-all-leads/05-understand-rows-per-page-and-pagination.md` |
| Refresh and loading leads | `03-all-leads/06-refresh-and-load-leads.md` |
| CSV export fields, result limits, and download | `03-all-leads/07-export-leads-to-csv.md` |
| Bulk selection and “all leads matching this filter” | `03-all-leads/08-select-leads-and-use-bulk-actions.md` |
| Bulk stage, assignee, list, tag, and custom-field updates | `03-all-leads/09-change-stage-assignee-lists-tags-or-custom-fields-in-bulk.md` |
| Bulk deletion | `03-all-leads/10-delete-leads-in-bulk.md` |
| Add New Lead | `04-add-new-lead/01-open-add-new-lead.md`, `02-add-lists-tags-and-custom-fields.md`, `03-assign-a-lead-to-a-teammate.md`, `04-set-the-lead-stage-and-value.md`, and `05-save-a-new-lead-and-review-duplicates.md` |
| Lead Detail Drawer and Lead Detail Page | `05-lead-details/01-open-the-lead-detail-drawer-or-page.md` |
| Previous/next lead navigation in the drawer | `05-lead-details/02-navigate-between-leads-in-the-drawer.md` |
| Close, stage selector, header menu, edit, delete, share, vCard, and full-page controls | `05-lead-details/03-use-lead-header-controls.md` |
| Call, SMS, Email, WhatsApp, Telegram, and Quick Reply | `05-lead-details/05-use-call-sms-email-whatsapp-telegram-and-quick-reply.md` |
| Tracking signals | `05-lead-details/10-review-tracking-signals.md` |
| IP information | `05-lead-details/11-review-ip-information.md` |
| Lead stage and value | `05-lead-details/12-understand-pipeline-stage-and-value.md` |
| Possible duplicates and irreversible merge | `05-lead-details/14-find-and-merge-duplicate-leads.md` |
| Lead deletion | `05-lead-details/15-delete-a-lead.md` |
| Activity timeline and activity filters | `06-activities-and-reminders/01-review-the-lead-activity-timeline.md` and `02-filter-activity-history.md` |
| Manual activity and note entry | `06-activities-and-reminders/03-add-a-manual-activity-or-note.md` |
| Reminder creation and status management | `06-activities-and-reminders/05-create-a-lead-reminder.md` through `08-delete-a-reminder.md` |
| Global reminders page | `06-activities-and-reminders/09-use-the-global-reminders-page.md` |
| Deals page and experimental availability | `07-deals-and-pipelines/01-understand-deals-and-the-experimental-deals-page.md` |
| Deal stage and value on a lead | `07-deals-and-pipelines/03-review-deal-stage-and-value-on-a-lead.md` |
| Data Sources hub and logs | `08-data-sources-and-imports/01-understand-the-data-sources-hub.md` and `02-review-data-source-logs.md` |
| Forms as an embedded source workflow | `08-data-sources-and-imports/03-connect-a-form-data-source.md` |
| Google Ads and Meta Lead Ads forms | `08-data-sources-and-imports/04-connect-google-ads-lead-forms.md` and `05-connect-meta-lead-ads-forms.md` |
| Webhooks and mapping suggestions | `08-data-sources-and-imports/06-create-and-manage-webhooks.md` |
| CSV import, delimiter/header options, mapping, lists/tags, progress, history, and recovery | `08-data-sources-and-imports/08-import-leads-from-a-csv-file.md` through `14-review-failed-leads-and-download-error-logs.md` |
| Automation list and logs | `09-automations/01-understand-automations.md` and `02-view-automation-logs.md` |
| Flow Templates | `09-automations/03-browse-flow-templates.md` and `04-create-an-automation-from-a-template.md` |
| Basic, Trigger, and Action builder | `09-automations/05-create-an-automation-from-scratch.md` through `11-use-meta-capi-actions.md` |
| Google Ads and Meta CAPI Connections | `09-automations/14-connect-google-ads-for-automations.md` and `15-manage-meta-capi-connections.md` |
| Settings overview | `10-settings-and-preferences/01-understand-the-settings-overview.md` |
| Profile and password | `10-settings-and-preferences/02-manage-your-profile.md` and `03-change-or-reset-your-password.md` |
| Display: Lead Table and Appearance | `10-settings-and-preferences/04-manage-display-and-appearance.md` and `05-configure-lead-table-columns.md` |
| Lead actions and activity logging | `10-settings-and-preferences/06-configure-lead-actions-and-activity-logging.md` |
| Browser alerts and shared alert templates | `10-settings-and-preferences/07-configure-browser-notifications.md` and `08-customize-new-lead-and-reminder-alerts.md` |
| Business details and reply-to email | `10-settings-and-preferences/09-manage-business-information.md` and `10-configure-email-reply-settings.md` |
| Stages and message templates | `10-settings-and-preferences/11-manage-pipeline-stages.md` and `12-manage-message-templates.md` |
| System Health | `10-settings-and-preferences/14-review-system-health.md` |
| Custom fields and system-managed fields | `11-custom-fields-lists-and-tags/` |
| Lists and Tags | `11-custom-fields-lists-and-tags/07-manage-lists.md` and `08-manage-tags.md` |
| Saved browser workspaces | `12-team-workspace-and-permissions/01-manage-saved-browser-workspaces.md` |
| Teammates and roles | `12-team-workspace-and-permissions/04-invite-and-manage-teammates.md` through `08-understand-lead-scopes-and-entity-permissions.md` |
| Help Center, support, What's New, and feature requests | `13-help-updates-and-account-support/` |
| Login, plugin, connection, import, automation, notification, and permission recovery | `14-web-troubleshooting/` |

---

# 5. Repository-based audit

The revised structure incorporates the current Web repository audit and the supplied product walkthrough.

## Confirmed in the current Web repository

### Navigation and dashboard

- Dashboard statistics
- Pipeline stage summaries
- Lead growth chart
- Upcoming reminders
- Dashboard list filtering
- Setup guidance and connection states
- License-related notices
- Mobile-app setup prompt
- Left navigation for Dashboard, Leads, Deals, Reminders, Automations, Data Sources, and Settings
- Conditional navigation for Automations, Data Sources, Deals, and Advocate Program
- What's New, Request a Feature, Support Portal, and Log out controls

### All Leads

- Refresh leads
- Export leads
- Add Lead
- Column chooser with search and saved columns
- Search with field scoping
- Lists, Tags, Stages, Created, and Updated filters
- Date presets: Today, Yesterday, Last 7 days, Last 30 days, and This month
- Rows per page and page navigation
- Bulk selection, including all leads matching the active filter
- Bulk stage, assignee, list, tag, and custom-field actions
- Bulk deletion
- Empty, loading, and error states

### Add New Lead and Lead Details

- Add New Lead dialog with validation
- Assignment, lists, tags, and lead fields
- Duplicate warning after a lead is created
- Lead Detail Drawer with close and previous/next controls
- Full Lead Detail Page
- Identity Info, Assignee, Pipeline, Reminders, Lists & Tags, Tracking Signals, and Metadata cards
- Call, SMS, Email, WhatsApp, Telegram, and Quick Reply actions
- Edit, Delete, Share, V-card, and Open Lead Page controls
- Activity and Reminders entry points
- Possible duplicate review and field-level merge selection
- Tracking Details and IP Information views
- Lead stage and value editing in lead detail

### Activities and Reminders

- Activity timeline
- Manual activity creation
- Activity filters for type, origin, action, and integration
- Activity update and delete actions
- Lead reminders with Add Reminder, Complete, Snooze, Delete, and View all actions
- Pending, Overdue, and Completed reminder statuses
- Global reminders page with Pending, Overdue, Completed, and All views
- Reminder pagination and lead drill-down

### Data Sources and Automations

- Data Sources hub
- Forms as embedded data-capture workflows, not a standalone Forms route
- Google Ads account and lead-form connection flows
- Meta Lead Ads form binding, repair, refresh, and disconnect flows
- Webhook integrations and mapping suggestions
- CRM routing
- CSV import with delimiter and header options
- Import history, progress polling, resumable historical import sessions, and shared field mapping
- Automation list, detail drawer, status toggle, queue details, delete flow, and View Logs
- Flow Templates browser
- Three-step automation builder: Basic, Trigger, and Action
- Source, list, and tag trigger filters
- Internal Email, Google Ads conversion, and Meta CAPI actions
- Email preview
- Google Ads and Meta CAPI Connections pages
- Feature logs exposed through View Logs controls and modals, not a standalone route

### Settings and access

- Categorized Settings overview
- Workspace summary, plan, teammate seats, connection status, and last refresh
- Refresh Workspace Data
- Guided setup restart for permitted users
- Profile display name, avatar, role, email, username, and password reset
- Display settings split between Lead Table and Appearance
- Local/browser theme, lead-action visibility, and browser alert preferences
- Workspace-level alert templates for New Lead Alerts and Reminder Alerts
- Business details and a separate reply-to email setting
- Pipeline stage management
- Message Templates
- Custom fields with create, edit, reorder, group, delete, and system-managed field views
- Lists and Tags direct settings route
- Teammates and sign-in details
- Roles, lead scopes, permission matrices, and entity permissions
- Saved browser workspaces, hidden in WordPress-hosted mode
- System Health currently exposing email-verification health to super-admins
- Help Center and Contact Support on the Settings overview
- Feature-log cards when permitted

## Confirmed corrections to the previous structure

1. Removed the table-zoom article. No visible customer-facing table-zoom control was found in the Web Leads UI, and the supplied audit confirms it is unavailable in Web and Mobile.
2. Renamed the lead-detail concept from a generic pop-up to Lead Detail Drawer / Lead Detail Page.
3. Added separate articles for export, pagination, bulk actions, field-scoped search, advanced filters, and column selection.
4. Added separate Tracking Signals and IP Information articles.
5. Moved deal stage and value emphasis into Lead Details while retaining a cautious Deals category for the experimental Deals page.
6. Added explicit duplicate-warning and irreversible merge coverage.
7. Added CSV delimiter/header selection, resumable imports, progress, history, and failed-lead error-log downloads.
8. Split Data Sources from Automations and documented Flow Templates and Connections separately.
9. Split Display into Lead Table and Appearance.
10. Split Business Information from email reply settings.
11. Added Lists & Tags as a first-class documentation area.
12. Added WordPress-hosted workspace behavior and browser-local setting distinctions.
13. Limited System Health wording to the currently observed email-verification surface.
14. Added read-only and permission-related articles throughout the structure.

## Needs verification in the running product before article drafting

1. Exact public account creation, sign-in, free-trial, plan, and site-quota wording.
2. Exact plugin download, website-addition, connection, and activation sequence described in the supplied walkthrough.
3. Exact dashboard growth-chart range controls and table presentation.
4. Exact visible row-limit values and export limits in the deployed build.
5. Which lead communication actions are enabled for each workspace and browser.
6. Whether the Deals workspace supports creating and updating deals in the current customer build, or only lead-level stage/value editing.
7. Exact Google Ads and Meta Ads plan requirements, OAuth prompts, and connection recovery steps.
8. Exact forms available during onboarding and data-source setup; there is no standalone Forms page in the repository.
9. Exact CSV failure-log format and whether failed rows are downloadable in every import mode.
10. Browser notification permission behavior and supported browsers.
11. Which users can view or manage each settings area, bulk action, import, automation, merge, and deletion workflow.
12. Whether Lists & Tags should appear in the normal Settings navigation or remain a direct/admin route.
13. Whether System Health remains email-verification-only in the shipped build.
14. Whether the disabled Provide Feedback control becomes available in the shipped build.
15. Exact WordPress-hosted versus standalone Web differences.

## Technical topics intentionally excluded

These belong in internal engineering documentation, not the public user guide:

- Next.js routes and static-export implementation
- API client modes and endpoint contracts
- Query caching internals
- Permission-engine implementation
- Feature-flag implementation
- Database and WordPress REST internals
- Deployment, hosting, and infrastructure operations
- Internal repository decomposition or shared type organization

---

# 6. Article-writing standard

After approval, each article should use the following customer-facing format where applicable:

```markdown
---
title: ""
category: ""
platform: web
status: Planned
last_verified: ""
---

# Article title

Short explanation of what the reader will accomplish.

## Before you start

Required account, website, workspace, role, browser, or permission.

## Steps

1. ...
2. ...

## What happens next

Explain the expected result.

## Troubleshooting

Include only verified, user-actionable solutions.

## Related articles

- Link to the next logical task.
```

### Web article rules

- Use the exact labels visible in the current PloverCRM Web interface.
- Explain WordPress and workspace prerequisites before setup steps.
- Separate WordPress-hosted and standalone Web instructions when their screens differ.
- State when a workflow requires an administrator, workspace manager, super-admin, or specific permission.
- Explain local/browser settings separately from workspace-level settings.
- Add warnings before lead deletion, bulk deletion, and duplicate merging.
- State that duplicate merging removes the other lead and cannot be undone when confirmed by the product.
- Do not document table zoom as an available Web or Mobile feature.
- Add screenshots only after the current workflow has been verified.
- Redact credentials, tokens, customer names, email addresses, phone numbers, IP addresses, and private lead information from screenshots.
- Link corresponding PloverCRM Mobile articles where the same workflow exists on both platforms.

---

# 7. Approval checklist

Please approve or request changes to:

1. The separate `02-plovercrm-web` product category.
2. The Web Getting Started sequence, including plugin and website setup.
3. The Navigation and Dashboard, All Leads, Add New Lead, Lead Details, Activities and Reminders, and Deals categories.
4. The separate Data Sources and Imports and Automations categories.
5. The Settings, Custom Fields, Lists & Tags, Team, Workspace, and Permissions categories.
6. The Help, Updates, Support, and Troubleshooting categories.
7. The removal of table zoom from the confirmed feature list.
8. The Lead Detail Drawer / Lead Detail Page split.
9. The separate Tracking Signals, IP Information, CSV failure logs, duplicate merge, export, and bulk-action articles.
10. The permission, read-only, local/browser, and WordPress-hosted behavior notes.
11. The items marked Needs verification before article drafting.
12. The division between customer-facing documentation and internal technical documentation.

After approval, create the category `README.md` files and article scaffolds. Draft detailed instructions only after each workflow has been verified in the current PloverCRM Web interface.
