# PloverCRM User Documentation

## Proposed documentation structure

**Document status:** Structure proposal for approval  
**Product name:** PloverCRM  
**Audience:** PloverCRM customers, WordPress site owners, workspace managers, and CRM users  
**Content state:** Structure only; article instructions will be written after the structure is approved

---

## 1. Purpose

This documentation set will provide a practical, user-first guide for PloverCRM across two product experiences:

1. **PloverCRM Mobile App** — for Android and Apple mobile devices.
2. **PloverCRM Web** — the web CRM connected to a WordPress website through the PloverCRM plugin.

The documentation will explain complete customer workflows rather than internal implementation details. Each focused workflow will have its own Markdown file so it can later be reviewed, updated, and published as an individual help-center article.

The proposed source location is:

```text
D:\PloverCRM_docs_project\final_file_structure
```

---

## 2. Design decisions

### Product naming

Use **PloverCRM** everywhere in folder names, article titles, headings, descriptions, and cross-links. Do not use “Clover CRM” or “CloverCRM.”

### Main categories

The documentation has exactly two top-level product categories:

```text
final_file_structure/
├── 01-plovercrm-mobile-app/
└── 02-plovercrm-web/
```

### Getting Started scope

Plugin and website setup belongs inside **PloverCRM Web → Getting Started**. This reflects the natural onboarding sequence:

1. Download the PloverCRM plugin.
2. Install it on WordPress.
3. Add or import the website.
4. Activate PloverCRM.
5. Complete workspace setup.
6. Open the PloverCRM Web Dashboard and log in.

### Mobile platform scope

The mobile documentation covers both supported mobile platforms:

- Android through Google Play Store
- Apple devices through the App Store

### Article scope

One Markdown file represents one focused user task or screen. A screen overview may link to smaller task articles where the workflow is substantial. This keeps the help center easy to scan without losing detailed instructions.

### Structure versus content

The first phase creates and approves the information architecture. The actual step-by-step content, screenshots, troubleshooting instructions, and product claims will be written only after the relevant workflow is checked against the current PloverCRM interface.

---

# 3. Final proposed file tree

## 01. PloverCRM Mobile App

```text
01-plovercrm-mobile-app/
├── README.md
│
├── 01-getting-started/
│   ├── README.md
│   ├── 01-download-plovercrm.md
│   ├── 02-create-a-plovercrm-account-and-log-in.md
│   └── 03-reset-your-mobile-app-password.md
│
├── 02-navigation-and-dashboard/
│   ├── README.md
│   ├── 01-mobile-app-navigation.md
│   └── 02-dashboard.md
│
├── 03-all-leads/
│   ├── README.md
│   ├── 01-all-leads-screen-overview.md
│   ├── 02-search-for-leads.md
│   ├── 03-filter-leads-with-list-pills.md
│   ├── 04-use-advanced-lead-filters.md
│   ├── 05-customize-lead-columns.md
│   ├── 06-adjust-the-leads-table-zoom.md
│   └── 07-use-bulk-actions.md
│
├── 04-add-and-manage-leads/
│   ├── README.md
│   ├── 01-add-a-new-lead.md
│   ├── 02-enter-and-validate-lead-information.md
│   ├── 03-view-lead-details.md
│   ├── 04-edit-lead-information.md
│   ├── 05-update-the-lead-stage-or-status.md
│   ├── 06-use-lead-communication-actions.md
│   ├── 07-share-a-lead-and-add-it-to-your-phone-book.md
│   ├── 08-understand-additional-lead-information.md
│   ├── 09-review-the-activity-and-timeline-tab.md
│   ├── 10-add-activities-and-notes.md
│   ├── 11-manage-lead-reminders.md
│   ├── 12-find-and-merge-duplicate-leads.md
│   └── 13-delete-a-lead.md
│
├── 05-settings-and-preferences/
│   ├── README.md
│   ├── 01-settings-overview.md
│   ├── 02-manage-your-profile.md
│   ├── 03-change-or-reset-your-password.md
│   ├── 04-manage-workspaces.md
│   ├── 05-manage-business-information.md
│   ├── 06-change-the-app-theme.md
│   ├── 07-manage-lead-actions.md
│   ├── 08-manage-pipeline-stages.md
│   ├── 09-manage-message-templates.md
│   ├── 10-configure-notifications.md
│   ├── 11-customize-notification-alerts.md
│   ├── 12-refresh-workspace-data.md
│   ├── 13-manage-phone-validation.md
│   └── 14-use-help-and-account-support.md
│
├── 06-upcoming-features-and-updates/
│   ├── README.md
│   ├── 01-view-whats-new.md
│   ├── 02-check-for-mobile-app-updates.md
│   └── 03-upcoming-mobile-app-features.md
│
└── 07-mobile-troubleshooting/
    ├── README.md
    ├── 01-troubleshoot-mobile-login.md
    ├── 02-troubleshoot-workspace-connection.md
    ├── 03-troubleshoot-data-refresh.md
    └── 04-troubleshoot-mobile-notifications.md
```

### Mobile feature coverage

| User-provided feature | Planned article location |
| --- | --- |
| Download from Google Play Store or App Store | `01-getting-started/01-download-plovercrm.md` |
| Create an account and log in | `01-getting-started/02-create-a-plovercrm-account-and-log-in.md` |
| Password reset | `01-getting-started/03-reset-your-mobile-app-password.md` and `05-settings-and-preferences/03-change-or-reset-your-password.md` |
| Mobile app navigation, login guidance, and workspace navigation | `02-navigation-and-dashboard/01-mobile-app-navigation.md` |
| Dashboard overview, statistics, stages, growth chart, reminders, and lists | `02-navigation-and-dashboard/02-dashboard.md` |
| All Leads screen and lead table | `03-all-leads/01-all-leads-screen-overview.md` |
| Search, search results, and query scope | `03-all-leads/02-search-for-leads.md` |
| List filter pills | `03-all-leads/03-filter-leads-with-list-pills.md` |
| Advanced lead filters | `03-all-leads/04-use-advanced-lead-filters.md` |
| Select and rearrange columns | `03-all-leads/05-customize-lead-columns.md` |
| Table zoom | `03-all-leads/06-adjust-the-leads-table-zoom.md` |
| Bulk actions | `03-all-leads/07-use-bulk-actions.md` |
| Add New lead | `04-add-and-manage-leads/01-add-a-new-lead.md` |
| Lead information validation | `04-add-and-manage-leads/02-enter-and-validate-lead-information.md` |
| Lead details screen | `04-add-and-manage-leads/03-view-lead-details.md` |
| Edit lead information | `04-add-and-manage-leads/04-edit-lead-information.md` |
| Lead stage, status, and value | `04-add-and-manage-leads/05-update-the-lead-stage-or-status.md` |
| Lead communication actions | `04-add-and-manage-leads/06-use-lead-communication-actions.md` |
| Share lead and add to phone book | `04-add-and-manage-leads/07-share-a-lead-and-add-it-to-your-phone-book.md` |
| Additional lead information | `04-add-and-manage-leads/08-understand-additional-lead-information.md` |
| Activity and Timeline | `04-add-and-manage-leads/09-review-the-activity-and-timeline-tab.md` |
| Add activities and notes | `04-add-and-manage-leads/10-add-activities-and-notes.md` |
| Lead reminders | `04-add-and-manage-leads/11-manage-lead-reminders.md` |
| Duplicate lead review and merge | `04-add-and-manage-leads/12-find-and-merge-duplicate-leads.md` |
| Delete a lead | `04-add-and-manage-leads/13-delete-a-lead.md` |
| Profile | `05-settings-and-preferences/02-manage-your-profile.md` |
| Manage workspaces | `05-settings-and-preferences/04-manage-workspaces.md` |
| Business information | `05-settings-and-preferences/05-manage-business-information.md` |
| Theme | `05-settings-and-preferences/06-change-the-app-theme.md` |
| Lead actions and communication channels | `05-settings-and-preferences/07-manage-lead-actions.md` |
| Manage stages | `05-settings-and-preferences/08-manage-pipeline-stages.md` |
| Message templates | `05-settings-and-preferences/09-manage-message-templates.md` |
| Sales tips and product updates | `05-settings-and-preferences/10-configure-notifications.md` |
| Activity notifications | `05-settings-and-preferences/10-configure-notifications.md` |
| Daily summary | `05-settings-and-preferences/10-configure-notifications.md` |
| Notification alert customization | `05-settings-and-preferences/11-customize-notification-alerts.md` |
| Data Sync | `05-settings-and-preferences/12-refresh-workspace-data.md` |
| Help and Updates | `05-settings-and-preferences/14-use-help-and-account-support.md` |
| What's New, support, feature requests, updates | `06-upcoming-features-and-updates/` |
| Lead header dropdown | `04-add-and-manage-leads/06-share-a-lead-and-add-it-to-your-phone-book.md` |
| Lead status and value | `04-add-and-manage-leads/04-update-the-lead-stage-or-status.md` |
| Reply, Call, SMS, Email, WhatsApp, Telegram | `04-add-and-manage-leads/05-use-lead-communication-actions.md` |
| Assigned To, Submitted At, Lists, Tags, Source | `04-add-and-manage-leads/07-understand-additional-lead-information.md` |
| Activity and Timeline | `04-add-and-manage-leads/08-review-the-activity-and-timeline-tab.md` |
| Lead reminders | `04-add-and-manage-leads/11-manage-lead-reminders.md` |

---

## 02. PloverCRM Web

```text
02-plovercrm-web/
├── README.md
│
├── 01-getting-started/
│   ├── README.md
│   ├── 01-what-is-plovercrm.md
│   ├── 02-download-the-plovercrm-plugin.md
│   ├── 03-install-the-plovercrm-plugin-on-wordpress.md
│   ├── 04-add-or-import-your-website.md
│   ├── 05-activate-plovercrm-on-your-website.md
│   ├── 06-complete-your-first-workspace-setup.md
│   ├── 07-open-the-plovercrm-web-app.md
│   └── 08-log-in-to-plovercrm-web.md
│
├── 02-dashboard/
│   ├── README.md
│   ├── 01-dashboard-screen-overview.md
│   ├── 02-switch-workspaces-or-websites.md
│   ├── 03-understand-lead-statistics-and-stages.md
│   ├── 04-understand-the-lead-growth-chart.md
│   ├── 05-use-the-dashboard-reminder-section.md
│   ├── 06-use-the-dashboard-list-section.md
│   └── 07-customize-dashboard-display-settings.md
│
├── 03-all-leads/
│   ├── README.md
│   ├── 01-all-leads-screen-overview.md
│   ├── 02-search-for-leads.md
│   ├── 03-select-and-rearrange-lead-columns.md
│   ├── 04-adjust-the-leads-table-zoom.md
│   └── 05-understand-the-all-leads-table.md
│
├── 04-add-new-lead/
│   ├── README.md
│   ├── 01-add-a-new-lead.md
│   ├── 02-complete-lead-fields.md
│   └── 03-save-a-new-lead.md
│
├── 05-lead-details/
│   ├── README.md
│   ├── 01-lead-details-screen-overview.md
│   ├── 02-use-the-lead-header-menu.md
│   ├── 03-update-the-lead-stage-or-status.md
│   ├── 04-use-lead-communication-actions.md
│   ├── 05-understand-additional-lead-information.md
│   ├── 06-review-the-activity-and-timeline.md
│   └── 07-manage-lead-reminders.md
│
├── 06-settings/
│   ├── README.md
│   ├── 01-settings-screen-overview.md
│   ├── 02-manage-your-profile.md
│   ├── 03-manage-workspace-settings.md
│   ├── 04-manage-business-information.md
│   ├── 05-change-the-web-app-theme.md
│   ├── 06-manage-lead-actions.md
│   ├── 07-manage-pipeline-stages.md
│   ├── 08-manage-message-templates.md
│   ├── 09-configure-notification-settings.md
│   ├── 10-refresh-workspace-data.md
│   └── 11-use-help-and-updates.md
│
├── 07-custom-fields/
│   ├── README.md
│   ├── 01-custom-fields-screen-overview.md
│   ├── 02-create-a-custom-field.md
│   ├── 03-edit-a-custom-field.md
│   ├── 04-delete-a-custom-field.md
│   └── 05-organize-custom-fields-into-groups.md
│
├── 08-team-and-workspace-access/
│   ├── README.md
│   ├── 01-manage-workspaces.md
│   ├── 02-invite-and-manage-teammates.md
│   ├── 03-understand-roles-and-permissions.md
│   └── 04-manage-lists-and-tags.md
│
├── 09-data-sources-and-automations/
│   ├── README.md
│   ├── 01-understand-data-sources.md
│   ├── 02-connect-a-data-source.md
│   ├── 03-map-incoming-lead-data.md
│   ├── 04-import-historical-leads.md
│   ├── 05-create-and-manage-automations.md
│   └── 06-troubleshoot-data-synchronization.md
│
├── 10-reminders-and-daily-work/
│   ├── README.md
│   ├── 01-manage-reminders.md
│   ├── 02-review-lead-activity.md
│   ├── 03-add-lead-activities-and-notes.md
│   └── 04-use-message-templates.md
│
└── 11-web-troubleshooting/
    ├── README.md
    ├── 01-troubleshoot-login-and-access.md
    ├── 02-troubleshoot-plugin-installation-and-activation.md
    ├── 03-troubleshoot-workspace-connection.md
    ├── 04-troubleshoot-data-synchronization.md
    └── 05-frequently-asked-questions.md
```

### Web feature coverage

| User-provided feature | Planned article location |
| --- | --- |
| Plugin download | `01-getting-started/02-download-the-plovercrm-plugin.md` |
| Website import/addition | `01-getting-started/04-add-or-import-your-website.md` |
| Plugin activation | `01-getting-started/05-activate-plovercrm-on-your-website.md` |
| Web login | `01-getting-started/08-log-in-to-plovercrm-web.md` |
| Dashboard screen | `02-dashboard/01-dashboard-screen-overview.md` |
| Workspace/website switcher | `02-dashboard/02-switch-workspaces-or-websites.md` |
| Stats and stages | `02-dashboard/03-understand-lead-statistics-and-stages.md` |
| Lead Growth Chart | `02-dashboard/04-understand-the-lead-growth-chart.md` |
| Reminder section | `02-dashboard/05-use-the-dashboard-reminder-section.md` |
| List section | `02-dashboard/06-use-the-dashboard-list-section.md` |
| All Leads screen | `03-all-leads/01-all-leads-screen-overview.md` |
| Select and rearrange columns | `03-all-leads/03-select-and-rearrange-lead-columns.md` |
| Table zoom from 20% through 160% | `03-all-leads/06-adjust-the-leads-table-zoom.md` |
| Search bar | `03-all-leads/02-search-for-leads.md` |
| All Leads grid/table | `03-all-leads/05-understand-the-all-leads-table.md` |
| Add New screen/tab | `04-add-new-lead/` |
| Save a new lead | `04-add-new-lead/03-save-a-new-lead.md` |
| Settings screen | `06-settings/01-settings-screen-overview.md` |
| Profile | `06-settings/02-manage-your-profile.md` |
| Workspace | `06-settings/03-manage-workspace-settings.md` |
| Business information | `06-settings/04-manage-business-information.md` |
| Theme | `06-settings/05-change-the-web-app-theme.md` |
| Lead actions | `06-settings/06-manage-lead-actions.md` |
| Manage stages | `06-settings/07-manage-pipeline-stages.md` |
| Message templates | `06-settings/08-manage-message-templates.md` |
| Notifications | `06-settings/09-configure-notification-settings.md` |
| Data Sync | `06-settings/10-refresh-workspace-data.md` |
| Help and Updates | `06-settings/11-use-help-and-updates.md` |
| Custom Fields screen | `07-custom-fields/01-custom-fields-screen-overview.md` |
| Create, edit, delete custom fields | `07-custom-fields/02-create-a-custom-field.md`, `03-edit-a-custom-field.md`, and `04-delete-a-custom-field.md` |
| Custom field groups | `07-custom-fields/05-organize-custom-fields-into-groups.md` |
| Lead details and communication | `05-lead-details/` |
| Team and permissions | `08-team-and-workspace-access/` |
| Data sources and automations | `09-data-sources-and-automations/` |
| Reminders and activity history | `10-reminders-and-daily-work/` |

---

# 4. Article-writing standard

Each article will be written as a customer-facing task guide using only the sections that help the reader:

```markdown
---
title: ""
category: ""
platform: [mobile or web]
status: Planned
last_verified: ""
---

# Article title

Short explanation of what the reader will accomplish.

## Before you start

Required account, website, workspace, role, or permission.

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

### Writing rules

- Use **PloverCRM** consistently.
- Use the exact labels visible in the current interface.
- Explain prerequisites before the steps.
- Keep each article focused on one screen or task.
- Separate Android and Apple instructions when their steps differ.
- Explain role or permission requirements where relevant.
- Use screenshots only after the workflow has been verified.
- Remove customer names, private lead information, credentials, and other sensitive data from screenshots.
- Do not include source-code paths, API details, database information, deployment instructions, or internal implementation details in public user documentation.
- Link related mobile and web articles where the same task exists on both platforms.

---

# 5. Feature audit and additions

The spoken feature list is fully covered in the proposed tree. The following additional areas were included because they are present in the current project sources or are necessary for a complete user journey:

- Mobile account creation and password recovery
- Mobile workspace connection and switching
- Mobile lead search, column preferences, and table behavior
- Lead detail header actions, activity history, and reminders
- Mobile help, support, feature requests, and update checks
- WordPress plugin installation and first workspace setup
- Web lead detail workflows
- Web custom field creation, editing, deletion, and grouping
- Teammates, roles, permissions, and workspace access
- Data sources, field mapping, historical imports, and automations
- Reminders, activities, and notes
- Troubleshooting articles for login, activation, connection, synchronization, and notifications

These additions do not change the two main categories. They ensure that the documentation supports both the initial setup path and the common daily CRM workflows.

---

# 6. Approval requested

Please approve or request changes to:

1. The two top-level categories.
2. The subcategory names and order.
3. The division of the Web Getting Started category, including plugin and website setup.
4. The separate articles for Dashboard, All Leads, Add New Lead, Settings, Lead Details, and Custom Fields.
5. The inclusion of Android and Apple download instructions.
6. The additional supporting articles listed in the feature audit.

After approval, the next phase will create the Markdown folders and article scaffolds, then draft and verify the actual article content one feature at a time.
