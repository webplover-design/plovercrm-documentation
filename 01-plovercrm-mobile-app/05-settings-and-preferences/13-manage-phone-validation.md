---
title: "Manage Phone Validation"
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
  - "phone validation"
  - "phone numbers"
platform: mobile
status: Draft
last_verified: ""
---
# Manage Phone Validation

Enter lead phone numbers in a format that PloverCRM can validate and use for calling, SMS, WhatsApp, and other phone actions.

## Enter a valid phone number

When you add or edit a lead:

1. Open the lead form.
2. Enter the phone number in the **Phone** field.
3. Use phone digits and common phone punctuation.
4. Review any validation message.
5. Save the lead after the field is valid.

![Placeholder image of phone-number validation in PloverCRM Mobile](images/placeholder-mobile-phone-validation.png)

> **Image placeholder:** Replace this image path with the final phone-validation screenshot when it is available.

## Accepted input

Use phone digits and common phone punctuation. Avoid entering letters or unsupported symbols in the Phone field.

PloverCRM can normalize a number for communication actions, but you should still review the value before saving it.

## Fix a phone validation error

If PloverCRM shows **Use only phone digits and common phone punctuation**:

1. Tap the **Phone** field.
2. Remove letters or unsupported symbols.
3. Re-enter the number using digits and common punctuation.
4. Save the lead again.

If a phone number is required by the form, PloverCRM can also show a required-field message.

## Check communication actions

After saving a valid phone number, open the lead details screen and review the available actions. Call, SMS, WhatsApp, or Telegram can still be unavailable when the related action is disabled in Settings, the required app is not installed, or the lead does not have usable contact information.

## Troubleshooting

### The phone number is rejected

Remove letters and unusual symbols, then enter the number again with digits and common phone punctuation.

### The phone action is unavailable

Confirm that the phone field contains a valid value and that the action is enabled under [Manage Lead Actions](07-manage-lead-actions.md).

### The saved number looks different

PloverCRM can normalize phone values for use by communication actions. Review the lead details and correct the number if it does not represent the intended contact.

## Related articles

- [Enter and Validate Lead Information](../04-add-and-manage-leads/02-enter-and-validate-lead-information.md)
- [Manage Lead Actions](07-manage-lead-actions.md)
- [Use Lead Communication Actions](../04-add-and-manage-leads/06-use-lead-communication-actions.md)
