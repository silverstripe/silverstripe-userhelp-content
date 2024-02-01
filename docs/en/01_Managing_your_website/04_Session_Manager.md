---
title: Session Manager
summary: Allow members to manage and revoke access to multiple login sessions across devices.
---

# What does the session manager module do?

The session manager module allows members to manage (see active and revoke) login sessions across devices used to access the CMS. Each login to a member's account is tracked and can be managed from their profile page.

# How to use it

## Getting started

[Silverstripe CMS Session Manager](https://addons.silverstripe.org/add-ons/silverstripe/session-manager) is installed by default.

## Logging in

When logging in with *_Keep me signed in for 30 days_*" checked, a session will remain active on that device for the full 30 days unless it is terminated prior to that allocated timeframe. Without this option checked, a session will only last for the duration of your browser session.

> [!WARNING]
> You should not use the "Keep me signed in" functionality when working on a device shared with other users (e.g.: internet café computer or a public library workstation).

![Silverstripe CMS log in form](../_images/session-manager-logging-in.png)

## Viewing login sessions

In order to view login sessions once logged in, navigate to your profile by clicking on your name in the left hand CMS menu. Every valid and currently active login session will be listed under ***Login sessions***.

![List of login sessions viewed through the Silverstripe CMS member profile](../_images/session-manager-viewing-login-sessions.png)

There is various data associated with every login session that can be used to identify the device that is logged in.

* Browser
* Operating system
* IP address
* Last active time
* Sign-in time

> [!WARNING]
> A member can only view login sessions for their own profile. No one else will have access to view your sessions.

## Revoking access

To remove access for a session associated with a device, click the **Log out** link next to the session you want to remove. This session will be immediately removed and anyone viewing the CMS using this session will need to log back in.

Administrators can also revoke _all_ active sessions for _all_ users by triggering the `dev/tasks/InvalidateAllSessions` task either in the browser or via the CLI. Note that this will also revoke the session of the user activating the task, so if this is triggered via the browser, that user will need to log back in to perform further actions.

> [!WARNING]
> With exception to the invalidate all sessions task, a member can only revoke access for their _own_ profile. No one else will have access to remove your sessions.
