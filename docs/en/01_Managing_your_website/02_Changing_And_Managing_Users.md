---
title: Changing and managing users
summary: Managing users access in the CMS administration interface.
---

# Changing and managing users

## In this section:

* Learn how to create users
* Learn how to manage users
* Learn how to change a user's password
* Learn how to delete users

## Before we begin:

* Navigate to the **Security** section in the CMS menu.

## Creating users

Navigate to the tab ***Users*** and click the button ***Add Member***.

![Adding a new user](../_images/users-add-member.png)

In the **New Member** section, you can edit the user's details. The two most important parts of the user's details are the email (which is also used for logging in) and password.

> [!NOTE]
> By default, an email address can only be used once in the system. It is not possible for multiple users to share the same email address.

![User details](../_images/user-details.png)

> [!NOTE]
> Users can be in multiple groups. If you delete a user from a group, they are only removed from that group, not from the system. To fully delete a user from the system, you need to be in the root of Security.
>
> Click the link ***Security*** in the breadcrumbs or click the button ***Back*** which is shown as a left arrow icon.

## Changing a user's password

To change a user's password, navigate to the ***Users*** tab, and select the user you would like to edit.

Click the link ***Change password*** to expand a password field and a confirm password field. Change the password (password entered must match) and confirm the change by clicking the button ***Save***.

![Changing a user's password](../_images/change-password.png)

You also have the option of requiring a user to reset their password next time they log in. You can do this by checking the "" checkbox. This will mean that they can use their current password to log in - but as soon as they do so they must define a _new_ password, which will be required to log in from then-on.

Note that this checkbox will already be checked if the current password has expired.

![Require a user's password to change next login](../_images/change-password-next-login.png)

The user will then need to set a new password next time they log in.

![Setting a new password after it expires](../_images/password-expired.png)

## Managing and deleting users

To edit a user entry click on the item you want to edit from the list. To delete a user click the button ***Delete*** which is shown as a trash icon on either the list view or on the editable view for a user.

![Managing and deleting users](../_images/edit-delete-user.png)
