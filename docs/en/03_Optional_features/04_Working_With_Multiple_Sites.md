title: Working with multiple sites
summary: Setting up and editing multiple websites using SilverStripe

# Working with multiple sites

## In this section:

* Understand subsites
* Learn how to create a subsite
* Learn how to create and use subsite templates
* Learn how to edit existing subsites
* Enable/Disable public access to subsites
* Delete subsites
* Create a virtual page on a subsite

## Before we begin:

* Make sure you have the SilverStripe Subsites module installed.
* Make sure you are in the "Subsites" section on the Navigation Tabs. 
* Make sure you have full administrative rights on your site.

## Understanding subsites

The SilverStripe Subsites module allows you to manage multiple related sites through a single CMS interface. Because all sites run on a single installation of SilverStripe, they can share users, content and assets. They can all use the same templates, or each use different ones.

To edit a particular subsite, choose the subsite from the dropdown menu in the left-hand menu.

![Subsites menu](/_images/subsites-menu.jpg)

## Creating subsites

In the Subsites section of the CMS, click on "Add Subsite". This will bring up the Subsite configuration tab in the Editing Pane.

![Add subsite](/_images/add-subsite.jpg)

In the Configuration tab, you can edit the name of the subsite, add a domain for the subsite, set a language for the site, enable or disable public access for the subsite, and choose the theme for the website.

![Configure subsite](/_images/configure-subsite.jpg)


## Using subsite templates

If you wish to create several subsites based on the same general site structure, you can create a subsite template.  

You can set up a collection of pages, files, and images and save it as a template. Then, when you click "Add new from template", you can choose the template you've created from the dropdown menu under "Copy Structure From."

To create a new template, click on the "Subsite Template" tab then "Add subsite template". Make sure you add a name that will make it easy to see that it's a template. Press the "Create" button at the bottom of the screen.

![Add subsite template](/_images/add-subsite-template.jpg)

You can edit the template, like any other subsite, by selecting the template in the subsite dropdown menu in the left menu.  By editing it, you create a template structure which can be copied to newly created subsites using the "Copy Structure From" dropdown menu when configuring a new subsite.

Select the new template from the dropdown in the left-hand nav. Create the pages and add the files and images you'd like to become part of the template.

When you create a new subsite, you can now choose to Copy structure from your template. All your pages, files and images will be copied over to your new subsite.

You can, at this point, choose a site from which to copy pages and files if you wish, by choosing a template in the "Copy Structure From" drop-down menu. See "Using Subsite Templates" for more information. 

![Copy structure](/_images/copy-structure.jpg)

To add your subsite, click the "Create" button at the bottom of the screen.

## Editing existing subsites

To edit an existing subsite, you must first find it using the subsites "Filter".  Pressing the "Apply Filter" button in the left-hand "Filter" panel while all fields are blank will return a list of all subsites.  If there are many subsites, and you know the site's name in the CMS or the site's domain name, you can search specifically for that site.  

![Filter on existing subsite](/_images/subsites-filter.jpg)

In either case, once you see the name of your subsite in the search results, click on the subsite's name to bring up the configuration tab.

![Subsite configuration tab](/_images/subsite-configtab.jpg)

## Enable/disable public access to subsites

To enable or disable public access to the subsite, find the subsite in search (see Editing Existing Subsites) and head to the subsite's configuration tab.  To enable or disable public access check (or uncheck, respectively) the box next to "Enable public access" and press the "Save" button at the bottom of the screen. 

## Change the theme of the subsite

To change the theme of a subsite, find the subsite in search (see Editing Existing Subsites) and head to the subsite's configuration tab.  To change the theme, select the theme from the drop-down menu labeled "Theme" and press the "Save" button at the bottom of the screen. 

## Deleting a subsite

To delete a subsite, find the subsite in search (see Editing Existing Subsites) and press the red "X" button next to the subsite's name.

## Creating a virtual page for a subsite

You can pull in content from a page that resides on another subsite by creating a page of the type "Subsites Virtual Page".

Pick the subsite from which you want to pull the content, then select the page. As with regular virtual pages, your Subsites Virtual Page will display the content from the original page, and get updated automatically if the original content changes.

<div class="note" markdown="1">
### Notes:

To limit access to subsites to specific security roles or groups, please see the "Managing Roles and Permissions" page of this user help document.
</div>