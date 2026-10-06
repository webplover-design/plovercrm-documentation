---
title: "Create, Edit, and Delete Roles"
category: "Team, Workspace, and Permissions"
platform: web
status: Draft
last_verified: ""
---

# Create, Edit, and Delete Roles

Create a role for a repeatable access pattern, edit it when responsibilities change, and remove unused roles after checking who depends on them.

![Placeholder screenshot of role creation and editing](images/placeholder-create-edit-delete-roles.png)

> **Screenshot placeholder:** Replace this image with an approved screenshot of the role editor after the workflow and privacy review are complete.

## Before you begin

- Sign in to the PloverCRM Web Dashboard.
- Select the correct workspace.
- Confirm that your account can manage roles.
- Write down the tasks and records the role should access.
- Review existing roles before creating another one.

## Create a role

1. Open the team, workspace, or permissions area.
2. Choose **Roles** or the equivalent access-management option.
3. Choose **Create Role** or **Add Role**.
4. Enter a clear role name and description.
5. Select the permissions required for the role.
6. Set lead or entity scopes when those options are available.
7. Review the permissions from the teammate's point of view.
8. Save the role.
9. Assign it to a test or approved teammate when appropriate.

Use a role name that describes responsibility, such as **Sales Representative** or **Workspace Reviewer**, rather than a person's name.

## Edit a role

1. Open the role list.
2. Select the role you want to change.
3. Review the teammates currently assigned to it.
4. Update the description, permissions, or scope.
5. Check whether the change adds or removes access to leads, exports, settings, or deletion actions.
6. Save the role.
7. Confirm the affected teammates' access after the change.

> **Caution:** Editing a shared role can change access for every teammate assigned to it. Consider creating a new role when only one group needs different permissions.

## Delete a role

1. Open the role list.
2. Locate the unused role.
3. Review the teammates assigned to it and any replacement role they should receive.
4. Reassign those teammates if required.
5. Choose **Delete**, **Remove**, or the equivalent option.
6. Read the confirmation message carefully.
7. Confirm the deletion only when no required user depends on the role.

> **Caution:** Deleting a role may immediately affect assigned teammates and may be difficult to reverse. Do not delete a role just because its name is unclear; rename it or verify its assignments first.

## Troubleshooting

- If the role editor is unavailable, check your administrator permission.
- If a permission has no visible effect, ask the teammate to sign in again and verify the selected workspace.
- If a role cannot be deleted, review its assigned teammates and dependencies.
- If access is broader or narrower than expected, review entity scopes as well as role permissions.

## Related articles

- [Understand Roles and Permissions](06-understand-roles-and-permissions.md)
- [Understand Lead Scopes and Entity Permissions](08-understand-lead-scopes-and-entity-permissions.md)
