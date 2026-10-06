---
title: "Manage Lead Actions"
category: "Settings and Preferences"
categories:
  - "PloverCRM Mobile App"
  - "Settings and Preferences"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Settings and Preferences"
  - "settings"
  - "preferences"
platform: mobile
status: Draft
last_verified: ""
---
# Manage Lead Actions

Choose which communication actions appear on lead details and decide how PloverCRM records activity after an action.

## Open Lead Actions

1. Open PloverCRM.
2. Tap **Settings**.
3. Under **App preferences**, tap **Lead Details**.
4. Tap **Manage Lead Actions**.

![Placeholder image of the PloverCRM Lead Actions settings](images/placeholder-mobile-lead-actions-settings.png)

> **Image placeholder:** Replace this image path with the final Lead Actions screenshot when it is available.

## Show or hide communication actions

Under **Visible Actions**, use the switches for:

- **Quick Response** — Access message templates.
- **Call** — Make phone calls.
- **SMS** — Send text messages.
- **Email** — Send emails.
- **WhatsApp** — Send WhatsApp messages.
- **Telegram** — Send Telegram messages.

Turn an action on to show it in the lead actions menu. Turn it off to hide it from the menu on this mobile device.

The action can still be unavailable for a particular lead when the lead does not have the required phone number or email address, or when the related app is not available.

## Choose activity logging behavior

Under **Activity Logging**, choose how PloverCRM handles activity after a communication action:

- **Quick Prompt** — Show a brief prompt with an **Add Activity** button.
- **Confirm with Modal** — Open the activity form after the action starts.
- **Create Automatically** — Save an activity automatically after the action completes.
- **Disabled** — Do not prompt or create activities.

The activity logging preference is saved to your CRM profile and can apply across web and mobile.

## Save and apply changes

Visible action switches apply to the mobile device. Activity logging choices can show **Activity logging preference saved** after they are saved.

Disabled actions do not appear in the lead actions menu when you view lead details.

## Troubleshooting

### An action is missing from Lead Details

Open **Settings → Lead Details → Manage Lead Actions** and turn on the action. The action may still require a lead phone number, email address, or an installed messaging app.

### An action is unavailable for a lead

Review the lead's contact information and the app requirements for that action. PloverCRM can offer **Copy Number** when a phone action cannot be used.

### Activity logging did not occur

Review the selected activity mode. **Disabled** prevents prompts and automatic activity creation. Other modes may require you to complete the activity form.

## Related articles

- [Settings Overview](01-settings-overview.md)
- [Manage Pipeline Stages](08-manage-pipeline-stages.md)
- [Manage Message Templates](09-manage-message-templates.md)
- [Use Lead Communication Actions](../04-add-and-manage-leads/06-use-lead-communication-actions.md)
