title: Roles & permissions
summary: Managing CMS access and permissions using groups and roles.

# Managing roles and permissions

## In this section:

* Understand roles and security groups
* Learn how to set up a role
* Learn how to edit a role
* Learn how to create a security group
* Learn how to assign a role to a security group or members
Learn how to restrict access by IP address

## Before we begin:

* Make sure you are in the "Security" section on the navigation tabs.

## Explaining security groups and roles

Instead of assigning individual permissions to access, create, edit, or delete content per user, you can use Security Groups and Roles to organise what accounts have which permissions.  

Roles are collections of permissions.  For example, you might create an editor role to give a group read/write access to all content, or a "contributor" role who has the right to add content to the CMS but not to publish it, or a "spectator" role which gives a person a right to view the backend of the CMS, but not any ability to edit it.

Security groups are collections of users, and whatever permissions they have apply to a subset of pages. So, for example, the marketing team could have access to the parts of the website dealing with marketing, and the development team could have access to the parts of the website dealing with development.

One of the ways that the two can be used together is to assign similar roles to different groups.  You only need to define an "editor" role once, but by applying the "editor" role to different groups with different access to different pages, so if you assigned the "editor" role to both the marketing team and development team security groups, the marketing team would be able to edit the marketing pages, and the development team would be able to edit the development pages, but they would not be able to edit each other's pages.

As a general rule of thumb, Roles define what can be done, and Security Groups define who can do it, and where.

## Using roles

The most typical user roles are:

* Author (someone who can create and edit content, but not publish)
* Publisher (someone who can also publish)
* Administrator (someone who has full rights for the management of the site, including the ability to create users and roles)

These roles may be all you ever need, however, the CMS allows you to create as many different roles as are appropriate for your organisation.

## Setting up roles

To set up roles, click on the "Roles" tab in the "Security" Pane.

![The roles pane](/_images/roles-pane.jpg)

Click on "Add Role." A pop-up dialog should prompt you for information ont the role, including the title of the role.  Select the appropriate permissions from the Permissions checklist. Hover over a permission to see more information about it as a tooltip.

![Creating roles](/_images/creating-roles.jpg)

Click on the "Create" button to save the changes. Click the "Security" link in the breadcrumbs at the top of the "New Role" pane, to go back to the main "Security" pane. 

<div class="note" markdown="1"> 
### Notes:

A role can have any number of permissions.

For example, an author typically has "Access to Site Content," (they can access the "Site Content" section in the CMS; the part where all content is managed), "Access to Files & Images," (they can browse the "Files and Images section in the CMS, organise assets in folders, upload new assets, etc.), and "Change site structure," (They can change the location for a page in the site tree and so manage the site structure and navigation.)
</div>
 
## Editing roles

To see details about or edit an existing role, click on the "Edit" icon to the right of the role's name.  

## Using groups

Each CMS user for your website belongs to one or more groups. For example, you may have a group who can only access the News section of your website, and another group who can only access the Events section of your website. The users in each group would be the people who manage the content for the respective section.

To view the "Groups" pane, click on the "Groups" tab in the "Security" section.

![The groups pane](/_images/groups-pane.jpg)

Unlike roles, there are no basic groups that typically apply to all sites. Instead, the groups you set up depend on your organisation, and who is involved in updating your website. We recommend you think about who manages which areas or sections of your website, and then create groups based on those areas of responsibility.

## Creating a new security group

To create a new Security Group, click the "Add Group" button in the top of the "Groups" pane. Put the name of the group in the "Group Name" field in the "Members" tab in the "New Group" Pane.  Create the group by pressing the "Create" button in the bottom-left hand corner of the "New Group" pane.

<div class="note" markdown="1"> 
### Notes:

We recommend you set up a top-level group for your entire site, as well as for each section that is managed by specific people.
</div>
 

You can nest groups, and create sub-groups which may represent different roles The parent group acts as a place to organise different subgroups.  In this case, it's probably best not to add members directly to the parent group. 

## Adding members to groups

Once you have created a group, you can then add members to the group. First, find the security group you want to add members to in the "Groups" Pane. Click on it, then click on the "Members" tab in the "Group Editing" Pane.

Starting to type in the first name, last name, or e-mail address in the "Find members by..." field will give you a drop-down choice of autocomplete names. If you see the name you are looking for, click on it, and click "Link Existing" to the right of the fields.

![Adding members to a group](/_images/adding-member-to-group.jpg)

If you wish to add a new member instead of choosing from an already established member, you can click the "Add Members" button to the left of the "Find members by..." dropdown.

<div class="note" markdown="1"> 
### Notes:

Users can be in multiple groups.  If you delete a user from a group, they are only removed from that group, not from the system.  To fully delete a user, you need to be in the root of Security.  You can reach the security group root by clicking on "Security" link in the breadcrumbs at the top of the Security Pane.
</div>

## Editing and deleting groups

To edit a group, click the group name in the Groups list. This opens the group details. You can change the group name, and add, edit or delete members. Note that a single user can belong to more than one group.

To delete a group, click the Delete icon to the right of the group entry. Note that deleting a group does not delete its members.

## Assigning roles to security group members

You can assign roles to security group members by clicking on the "Roles" tab in the editing pane, and selecting the appropriate roles for your group.

Save the changes by pressing "Save" in the bottom-left hand corner of the "Roles" pane. 

## Assigning permissions to security group members

It is suggested that, where possible, permissions are assigned to roles, and roles are assigned to security group members.  However, it is possible to assign permissions to security group members, by clicking on the Permissions tab in the "Groups" pane.  The Permissions tab allows you to apply additional permissions to a group.