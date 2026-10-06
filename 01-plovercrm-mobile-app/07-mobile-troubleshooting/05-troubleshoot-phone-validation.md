---
title: "Troubleshoot Phone Validation"
category: "Mobile Troubleshooting"
categories:
  - "PloverCRM Mobile App"
  - "Mobile Troubleshooting"
tags:
  - "PloverCRM"
  - "mobile app"
  - "Mobile Troubleshooting"
  - "phone validation"
  - "phone numbers"
  - "troubleshooting"
  - "mobile support"
platform: mobile
status: Draft
last_verified: ""
---
# Troubleshoot Phone Validation

Use this guide when PloverCRM rejects a lead phone number or disables a phone-based communication action.

## Enter a valid phone number

1. Open the lead form or lead details edit screen.
2. Tap the **Phone** field.
3. Enter the phone number using digits and common phone punctuation.
4. Remove letters and unsupported symbols.
5. Save the lead.

If the field is invalid, PloverCRM can show **Use only phone digits and common phone punctuation.**

![Placeholder image of the PloverCRM phone validation error](images/placeholder-mobile-phone-validation-troubleshooting.png)

> **Image placeholder:** Replace this image path with the final phone-validation troubleshooting screenshot when it is available.

## Fix an invalid phone number

1. Tap the **Phone** field.
2. Remove letters, unusual symbols, or other unsupported characters.
3. Re-enter the number with digits and common punctuation.
4. Review the field again.
5. Save the lead after the validation message clears.

PloverCRM can normalize a phone number for communication actions. Review the saved value to make sure it represents the intended contact.

## Phone number is required

If PloverCRM shows a required-field message:

1. Enter the lead's phone number if the lead should be reachable by phone.
2. Complete any other required fields.
3. Save the lead again.

If phone information is optional for your workflow, review the other highlighted fields and follow the form instructions.

## Phone action is unavailable

A phone-based action can be unavailable when:

- The lead does not have a usable phone number.
- The number cannot be normalized.
- The action is disabled in **Settings → Lead Details → Manage Lead Actions**.
- The required messaging app is not installed.

Open [Manage Lead Actions](../05-settings-and-preferences/07-manage-lead-actions.md) to review the local action switches.

## Phone number required message

When a phone-based action cannot continue, PloverCRM can show:

> **Phone Number Required**
>
> This lead needs a valid phone number with a country code before this action can be used.

Return to the lead, edit the Phone field, and save a valid number before trying the action again.

## WhatsApp or Telegram is not installed

If the phone number is valid but the required app is unavailable, PloverCRM can show **WhatsApp Not Installed** or **Telegram Not Installed**.

Use **Copy Number** when available to copy the phone number and use it in another app. PloverCRM can show **Phone number copied to clipboard** after the number is copied.

## Template preview cannot send

When using a message template, PloverCRM can show:

> **Missing Information**
>
> Lead phone number is not available.

Close the preview, update the lead's Phone field, and open the template again.

## Troubleshooting

### The number still fails validation

Remove letters and unsupported symbols. Use digits and common phone punctuation, then try again. If the error continues, ask your workspace administrator to confirm the expected phone format.

### Call, SMS, WhatsApp, or Telegram remains disabled

Confirm that the lead has a valid phone number and that the action is enabled in Lead Actions settings. Check whether the required app is installed on your device.

### The saved number looks different

PloverCRM can normalize phone values. Review the saved lead details and correct the number if it does not represent the intended contact.

> **Privacy note:** Do not include real customer phone numbers in screenshots or public support requests. Redact or replace private contact information before sharing an example.

## Related articles

- [Manage Phone Validation](../05-settings-and-preferences/13-manage-phone-validation.md)
- [Manage Lead Actions](../05-settings-and-preferences/07-manage-lead-actions.md)
- [Enter and Validate Lead Information](../04-add-and-manage-leads/02-enter-and-validate-lead-information.md)
- [Use Lead Communication Actions](../04-add-and-manage-leads/06-use-lead-communication-actions.md)
