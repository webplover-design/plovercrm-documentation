---
title: "Understand and Manage Read-Only Access"
category: "Team, Workspace, and Permissions"
platform: web
status: Draft
last_verified: ""
---

# Understand and Manage Read-Only Access

Read-only access lets a teammate view permitted workspace information without changing it. It is useful when someone needs to review leads, activities, reminders, deals, reports, or other available CRM information but should not create, edit, delete, assign, or configure those records.

Read-only access is different from having no access. A read-only user may still see only the workspaces, lead records, and entities allowed by their role and lead scope. Read-only access does not automatically grant access to every record or Settings page.

> **Image:** `[Add screenshot here]`

## What read-only access controls

A read-only restriction may prevent a user from performing actions such as:

- Creating a new lead or other record.
- Editing lead details, custom fields, stages, assignments, or notes.
- Deleting or archiving records.
- Adding or removing activities, reminders, lists, or tags.
- Sending messages or triggering customer-facing actions.
- Changing pipeline stages or deal information.
- Editing automations, data sources, templates, or workspace settings.
- Managing teammates, roles, or permissions.

The exact restrictions depend on the role, entity permissions, lead scope, and features enabled in the workspace. A user may be read-only for one entity while having a different level of access to another.

## Read-only access versus lead scope

These settings answer different questions:

- **Lead scope:** Which records can the user see?
- **Entity permission:** Which types of records or features can the user access?
- **Read-only access:** What can the user do with the records or features they can see?

For example, a user may have access to leads assigned to their team but be unable to edit those leads. Another user may have read-only access to all workspace leads. Confirm all three settings when troubleshooting access.

## Give a teammate read-only access

Only an administrator or user with permission to manage roles and teammates should change access.

1. Open the PloverCRM Web Dashboard.
2. Confirm that the intended workspace is selected.
3. Open **Settings** and go to **Team**, **Teammates**, **Roles**, or the access-management area shown in your account.
4. Locate the teammate who needs restricted access.
5. Review the teammate’s current role, workspace access, lead scope, and entity permissions.
6. Select **Edit**, **Change Role**, or the matching action.
7. Choose an existing read-only role, or apply the read-only permissions available for the required entities.
8. Confirm which workspaces, lead records, and CRM areas the teammate should be able to view.
9. Save the change.
10. Reopen the teammate’s access details and confirm that the read-only setting is shown.

Use the narrowest access that supports the person’s work. Do not grant workspace-wide visibility when the teammate only needs to review a specific team or assigned group of leads.

## Create a read-only role

If no suitable role exists, an administrator may be able to create one.

1. Open **Settings** and select **Roles** or the permissions-management area.
2. Select **Create Role** or the matching action.
3. Enter a clear name, such as **Sales Reviewer** or **Read-Only Support**.
4. Add a description that explains what the role can view and what it cannot change.
5. Enable view or read permissions for the required entities.
6. Leave create, edit, delete, send, and administrative permissions disabled unless a specific exception is required.
7. Configure the appropriate lead scope.
8. Review access to settings, reports, exports, integrations, and customer communications separately.
9. Save the role.
10. Assign it to an approved test user or teammate.
11. Test the role before assigning it broadly.

Do not assume that disabling edit permission also disables exports, downloads, message sending, or access to sensitive fields. Review each available permission explicitly.

## Verify read-only access

Test the resulting access with an approved account that has the same role and scope.

1. Sign in as the test user, or ask the teammate to verify access without sharing credentials.
2. Open the intended workspace.
3. Confirm that the expected leads and entities are visible.
4. Open a lead and review its details, activities, reminders, deals, and available related information.
5. Confirm that edit, delete, create, assign, send, and configuration controls are hidden or disabled where expected.
6. Attempt only safe, non-destructive checks; do not submit a real message or change a production record merely to test a permission.
7. Confirm that records outside the intended lead scope are not visible.
8. Return to the administrator access screen and correct any unexpected permission.

A hidden button is useful evidence, but the complete role and permission configuration is the authoritative source. If the application displays a disabled control, read its explanation before contacting support.

## Change or remove read-only access

1. Open the teammate or role access settings.
2. Confirm the correct teammate, role, and workspace.
3. Review the proposed change and its effect on visible records and actions.
4. Select the new role or update the relevant permissions.
5. Save the change.
6. Ask the teammate to sign out and back in if PloverCRM requires a new session before permissions refresh.
7. Verify the new access using an approved test workflow.

When removing access entirely, review assigned leads, reminders, activities, deals, and automations first. Reassign work according to your team’s process before deactivating the account or removing the workspace access.

## Common read-only scenarios

### A user can see a lead but cannot edit it

This is normally expected for read-only access. Check whether the role intentionally disables editing. If the user needs to update only one field or perform one action, consider a narrower custom permission rather than granting full edit access.

### A user cannot see a lead

Read-only access does not override lead scope. Check the selected workspace, team or assignment scope, entity access, and whether the lead is restricted by another rule.

### A user can view records but can still send messages

Review message, email, automation, and external-action permissions separately. View-only access to a lead does not necessarily prevent every communication feature unless those actions are disabled in the role.

### A user still sees old controls after a permission change

Ask the user to refresh the page or sign out and back in. Confirm that the change was saved and that the user is in the intended workspace. Do not change additional permissions until the current change has been verified.

### A user cannot access the role or permission settings

Role management is normally restricted to administrators. Ask an authorized administrator to review the account rather than sharing credentials or attempting to bypass the restriction.

## Read-only access checklist

Before assigning read-only access, confirm:

- The teammate can view only the intended workspace and lead scope.
- Required entities are visible.
- Create, edit, delete, assignment, send, and administrative actions are restricted as intended.
- Sensitive fields and exports have been reviewed separately.
- Existing work assigned to the teammate has been reviewed.
- The teammate understands what they can view and which actions require another user.
- A safe test confirmed the final behavior.

> **Security and privacy:** Never share passwords, one-time codes, API keys, tokens, or identifiable customer data while testing permissions. Use separate accounts or approved test users; never test by sharing an administrator’s login.

## Related articles

- [Manage Roles and Permissions](04-manage-roles-and-permissions.md)
- [Manage Lead Scopes, Entity Permissions, and Read-Only Access](05-manage-lead-scopes-entity-permissions-and-read-only-access.md)
- [Invite and Manage Teammates](03-invite-and-manage-teammates.md)
