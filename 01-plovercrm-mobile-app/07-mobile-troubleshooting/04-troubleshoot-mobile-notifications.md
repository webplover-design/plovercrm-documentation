---
title: "Troubleshoot Mobile Notifications"
category: "Mobile Troubleshooting"
categories:
  - "PloverCRM Mobile App"
  - "Mobile Troubleshooting"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Mobile Troubleshooting"
  - "notifications"
  - "alerts"
  - "troubleshooting"
  - "mobile support"
platform: mobile
status: Draft
last_verified: ""
---
# Troubleshoot Mobile Notifications

Use this guide when PloverCRM Mobile notifications do not appear, have no sound, or cannot be refreshed.

## Check device notification permission

1. Open your device settings.
2. Find PloverCRM in the app list.
3. Allow notifications.
4. Return to PloverCRM.
5. Open **Settings → Notifications**.

When notification permission is missing, PloverCRM can show **Please allow notifications on this phone first.**

![Placeholder image of the PloverCRM mobile notification troubleshooting screen](images/placeholder-mobile-notifications-troubleshooting.png)

> **Image placeholder:** Replace this image path with the final notification troubleshooting screenshot when it is available.

## Check notification modes

In **Settings → Notifications**, review each notification type:

- **Normal** — Show the notification with sound.
- **Silent** — Show the notification without sound.
- **Off** — Do not show the notification.

Set the relevant notification type to **Normal** or **Silent** when you want notifications to appear.

## Check each notification type

Review these settings separately:

- **Activity Notifications** — Real-time lead activity alerts for the current workspace and phone.
- **Daily Summary** — One daily overview at the selected time.
- **Reminder Notifications** — Alerts for reminders in the current workspace.
- **Sales Tips & Product Updates** — Product information that follows the app across connected workspaces.

Daily Summary can be scheduled for **09:00**, **12:00**, or **18:00** in your current time zone.

## Refresh notifications

1. Open **Settings → Notifications**.
2. Turn on **Activity Notifications**.
3. Scroll to **Alert Messages**.
4. Tap **Refresh Notifications**.
5. Wait for the refresh to finish.

PloverCRM can show **Notifications are ready again** after a successful refresh.

The refresh control may be disabled until Activity Notifications are enabled.

## Understand notification status

Activity notifications can show one of these statuses:

- **Ready** — Notification registration is available.
- **Service unavailable** — The mobile push service is not available at the moment.
- **Unavailable** — Notification registration is not available for the current setup.

PloverCRM can also show **This workspace does not support mobile push yet** when push notifications are not supported for the selected workspace.

## Review alert messages

If notifications appear with unexpected text:

1. Open **Settings → Notifications**.
2. Open **New Lead Alerts** or **Reminder Alerts** under **Alert Messages**.
3. Review the shared alert title and message.
4. Ask a teammate with notification-template permission to update them when the settings are read-only.

## Common problems

### Activity notifications are not appearing

Allow device notifications, set Activity Notifications to **Normal** or **Silent**, and tap **Refresh Notifications**.

### Notifications appear without sound

Check both PloverCRM's notification mode and the device's sound or Focus settings. **Silent** intentionally suppresses notification sound.

### Reminder notifications are missing

Confirm that Reminder Notifications are not **Off**. Then check that the reminder is pending and belongs to the selected workspace.

### Daily Summary is missing

Confirm that Daily Summary is enabled, review the selected delivery time, and check device notification permission.

### The mobile push relay is unavailable

PloverCRM can show **Mobile push relay is unavailable right now**. Try refreshing notifications later. Contact your site administrator if the problem continues.

## Related articles

- [Configure Notifications](../05-settings-and-preferences/10-configure-notifications.md)
- [Customize Notification Alerts](../05-settings-and-preferences/11-customize-notification-alerts.md)
- [Manage Workspaces](../05-settings-and-preferences/04-manage-workspaces.md)
- [Use Help and Account Support](../05-settings-and-preferences/14-use-help-and-account-support.md)
