---
title: "Understand Lead Scopes and Entity Permissions"
category: "Team, Workspace, and Permissions"
platform: web
status: Draft
last_verified: ""
---

# Understand Lead Scopes and Entity Permissions

Lead scopes and entity permissions control which records a teammate can access and which actions they can perform on those records. Use them to match access with a person's responsibilities without giving unnecessary workspace-wide control.

![Placeholder screenshot of lead scopes and entity permissions](images/placeholder-lead-scopes-entity-permissions.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of lead scope or entity permission settings after the workflow and privacy review are complete.

## What is a lead scope?

A lead scope defines the set of leads a teammate can access. Depending on the workspace configuration, a scope may be based on an assigned user, team, list, workspace, or another available grouping.

## What is an entity permission?

An entity permission defines what a teammate can do with an available type of workspace data. For example, a role may allow someone to view leads but not edit or delete them. The available entities and actions depend on your PloverCRM account.

## Review access for a teammate

1. Open the team or permissions area in the PloverCRM Web Dashboard.
2. Select the teammate or role you want to review.
3. Check the lead scope assigned to the role or user.
4. Review the entities the role can access.
5. Check each available action, such as view, create, edit, export, or delete.
6. Compare the access with the teammate's responsibilities.
7. Save only when a correction is needed.

## Test the effective access

1. Select an approved test lead within the intended scope.
2. Ask the teammate to open the lead.
3. Confirm that permitted actions are visible.
4. Confirm that restricted actions are unavailable or read-only.
5. Test a lead outside the intended scope only when your organization's privacy policy allows it.
6. Record the result without copying customer information.

Permissions can combine. A teammate may need both a role permission and access to the relevant lead scope before an action appears.

> **Caution:** Widening a lead scope can expose more customer records. Narrowing it can interrupt assignments and follow-up work. Review the impact before saving.

## If a teammate cannot access a lead

- Confirm that the correct workspace is selected.
- Check the teammate's role and lead scope.
- Confirm that the lead belongs to the expected list, team, or assignment.
- Ask the teammate to refresh or sign in again if the permission was recently changed.
- Contact an administrator or PloverCRM Support if the effective access still does not match the configured role.

## Related articles

- [Understand Roles and Permissions](06-understand-roles-and-permissions.md)
- [Understand Read-Only Settings](09-understand-read-only-settings.md)
- [Manage Lists](../11-custom-fields-lists-and-tags/07-manage-lists.md)
