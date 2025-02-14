---
title: Workspaces
pageTitle: Workspaces | Plane
description: Workspaces in Plane are where you can access all of your content, including issues, cycles, and modules. Everything is organized within a workspace. To help you understand, you can think of a workspace as similar to a server on Discord or an organization on Slack, where you can bring your entire team together to work.
---

Workspaces in Plane are where you can access all of your content, including issues, cycles, and modules. Everything is organized within a workspace. To help you understand, you can think of a workspace as similar to a server on Discord or an organization on Slack, where you can bring your entire team together to work.

## Creating workspace

If you are a first-time user who has signed up for Plane, you will create a new workspace for your team during the onboarding process.

{% callout type="note" %}
On Plane cloud and self-hosted versions, the workspace URLs (also known as
slugs) must be unique. We allow users to have the same organization names, but
the URLs must still be unique to ensure a better experience.
{% /callout %}

If you are a team member or contributor and are invited to a workspace, you do
not need to have your own workspace. Instead, after accepting the invitation,
you will be redirected directly to the workspace you were invited to.

## Workspace roles

Every user on a workspace has a specific role associated with them, which
determines their permissions and what actions they are allowed to take within
the workspace. This helps to ensure that users only have access to the
resources and functions that they need in order to complete their work.

These roles can be configured when inviting a user to a workspace from the
workspace invite page, or later from the workspace settings page. _Note that
when you invite a user during the onboarding process, they will be assigned
the default role of 'Viewer'_.

**Available roles**

- **Owner** - The owner of the workspace is the supreme administrator and has all permissions set to `true` within the workspace.
- **Administrator** - Workspace administrators have similar privileges to the owner, but they are not able to delete the workspace.
- **Member** - Workspace members are essentially team members within the organization, and they have the ability to read, write, edit, and delete entities inside projects, cycles, and modules within the workspace. It is important to note that workspace members are not able to create new projects, cycles, or modules
- **Guest** - External members of organizations can be invited as guests, which grants them the ability to view all content to which they have been invited. However, they do not have permissions to write, update, or delete entities inside workspace.

{% callout type="note" %}
Users should first join the workspace, in ordered to be invited to public and
secret projects. View [projects](/projects) docs for more.
{% /callout %}

## Inviting user to a workspace

You can easily invite members of your organization with differnt roles onto a workspace.

On cloud, here's how you can invite a user to your workspace,

1. When you are onboarded, you will see a screen that allows you to invite your team members to the workspace. By default, we set the role to `View` only. This is because we perform a bulk operation to get your team up and running.
2. If you've missed step one, you can manage all your members under `/<workspace-name>/settings/members` page.
3. To invite team members, use the Add Member option. When an invitation is sent, the invitee will receive an email to accept the invitation.
4. To update workspace member permissions, use the collapsable menu, next to the member.

{% callout type="note" %}
Self-hosted users should configure an email service in order to send
invitations. Follow [this](/self-hosting/docker-compose) document to learn how to set up
self-hosted instances.
{% /callout %}

## Switching between workspaces

When working with multiple organizations or teams, you can switch between them
using the workspace menu on the left sidebar. Here, you can find all the
workspaces you've created or joined and switch between them anytime, as long
as they are linked to your email. In the future, we plan to allow logging into
multiple workspaces with different emails and improve the overall experience.

## Delete a workspace

Only workspace owners have the ability to delete a workspace, these options can be found under the workspace settings.

{% callout type="note" %}
If a workspace is deleted, all of its content, issues, cycles, and modules
will also be deleted. Currently, Plane does not offer a automatic backup
service on cloud or self-hosted versions, but it is planned on our roadmap.
{% /callout %}

## Workspace plan

- **Cloud**: All-plans, no suggestion, no limits.
- **Self-hosted**: No plans, no suggestion, no limits.
