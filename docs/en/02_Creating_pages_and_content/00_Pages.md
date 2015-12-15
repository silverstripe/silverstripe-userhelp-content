title: Pages
summary: How to manage the content structure, page history and batch publishing. 

# Managing your site structure

## In this section:

* Learn the different content types
* Learn how to move pages within the site
* Learn how to hide a webpage
* Learn how to archive a webpage
* Learn how to view an old version of a page, and roll back to that version.
* Learn how to search for a page
* Learn how to publish multiple pages
* Learn how to set content owners and review dates
* Learn how to add "To Do" items.

## Before we begin:

* Make sure you are in the "Pages" section in the navigation menu. 

## Page types

There are many different types of pages in SilverStripe, each with its own functionality and purpose. By now you already know how to create a basic page. It is also possible to change a page from one page type to another.

## Different page types and their functions

### Basic pages

* **Page** - The most basic page type. It contains content, and has no customised functionality or special purpose. Most pages you create on your site will be of this type.
* **Home Page** - The Home Page behaves like any other page, with the exception that it is the home page for your site - what users will see first if they browse directly to the root of your domain.
* **Error Page** - The page displayed when an error is produced by the website. Error pages can be created for individual error types, so for example, a 404 "Page not found" can look different from a 403 "Forbidden" page.
* **Redirector to another page** - This page on the website redirects the user to either another page on the same website, or a page on an external website.
* **Virtual Page** - A virtual page uses the content of another page. This is different from a redirector, as a redirector essentially links one location on the website to another, while a virtual page copies the content of the other page. Editing the page the virtual page is based on will, in turn, edit the copied virtual page.

### Other types of pages

Depending on the code and modules included in your site, your page type list could contain any 
number of other page types. This could include [blog pages](/optional_features/blogs), [forums](/optional_features/forums), [user defined forms](/optional_features/forms), or 
news pages.

### Changing an existing page type

To change a page type, look in the Pages pane for the page you wish to change. 

![Choosing page type](/_images/Choosing-A-Page.png)

Click on it, and head to the "Settings" tab in the editing pane. You can change the page type from the "Page type" drop-down menu. Save your changes by pressing "Save Draft" or "Save & Publish" in the actions menu at the bottom of the editing pane.

![Changing page type](/_images/Changing-Page-Type.png)
 
### Moving pages within the site

To move a page within the site, make sure you are in the "Pages" pane (selected from the navigation on the left side of the screen).

You can move a page by clicking on it in the "page tree", and dragging it to its new position in the website.

![Moving pages](/_images/Moving-Pages.png)

Once a page has been moved the draft site will display the new location. Each page which is moved will need 
to be published in order for it to appear in the new location on the live site.
 
### Hiding pages

To hide a page, look in the Pages pane for the page you wish to hide. Click on it, and head to the "Settings" tab in the editing pane.

You can remove your site from being listed in your site's navigation bar by removing the checkmark next to "Show in menus."

You can remove your site from being listed in search results by removing the checkmark next to "Show in search."

After you have made these changes, hit the "Save & Publish" button in the actions menu at the bottom of the editing pane.

![Hiding pages](/_images/Hiding-Pages.png)
 
### Archiving pages

#### Archiving individual pages

Any page in the CMS can be archived, which removes it from both the staging and live sites, but retains the page in the
internal version history.

To archive a page, look in the Pages panel for the page you wish to remove. Click on it, and 
you will see a "More Actions" option in the actions panel at the bottom.

 * "Unpublish" will remove the page from the live site, but leave it on draft.
 * "Archive" will remove the site both from live and draft simultaneously, but leave the page version history intact.

![Archive a single page](/_images/Archive-Menu.png)

#### Archiving multiple pages

To archive or unpublish multiple pages, you can use the bulk action tool on the
"Pages" pane. This can be accessed either by clicking "Pages" in the main menu
or "Edit Tree" when editing a page.

From the "Actions" drop-down menu at the top of the "Pages" pane, choosing
"Archive" or "Unpublish". Available pages for the select action will have a checkbox
disabled beside them.

Select any number of pages, and then press "Go" to perform the selected action.

![Delete multiple pages](/_images/Archive-Multiple-Pages.png)
 
### Previous versions of pages

#### Viewing previous versions

Click on the page you want to view a previous version of in the "Page" pane's "Page Tree". Click on it, and head to the "History" tab in the editing pane.

![View page version](/_images/view-page-version.jpg)

Click on any of the listed versions to look at the content of the page. If you want to view draft versions of pages as well as published versions, click the "Show unpublished versions" checkbox.

#### Comparing page versions

To compare two versions of the site, click on "Compare mode (select two)" and click on one version of the site, and then another version of the site. Items that have been added to the site in the newer version that were not in the older version will be highlighted in green, while items that were deleted from the older version will be highlighted in red, with a strikethrough through any text that was deleted.

#### Rolling back changes

To revert to a previous version, select the version you with to revert the page back to, and click on "Revert to this version" in the editing pane.

<div class="note" markdown="1">
When a page is rolled back to the previous version, it is only rolled back in the backend CMS as a draft. To show the rolled back page on the public-facing website, it needs to be published by pressing "Save and Publish."
</div>
 
### Searching for pages

To search for a page, enter your search into the "Content" entry form in the page "filter" panel.

The default search mode is by text, and you can type any text to search your pages for that text. Pressing search will show only positive results in the Page Tree on the "Pages" pane.

Search results will remain the only items in the Page Tree until the "Clear" button is pressed.

![Searching pages](/_images/searching-pages.jpg)

You can also earch by different criteria, including:
* "Date" to select modified date
* "Page Type" which is a dropdown of all the page types
* "Pages" which includes the following filters:
  * All pages
  * All pages, including archived
  * Archived pages
  * Changed pages
  * Draft pages
  * Live but removed from draft
  * Modified pages
  * Published pages

<div class="note" markdown="1">
One neat trick is that you can search for pages, and then perform a batch action upon them, such as deleting them or publishing them. For example, by searching for Page Type: "BlogEntry" and then a date range: "(whatever last Thursday was till now)" you can then create a quick batch action to publish all blog posts written since last Thursday.
</div>
 
### Publishing multiple pages

To publish multiple pages, you can follow the same steps as in the archiving multiple pages step.

When viewing the tree, select "Publish" from the batch actions dropdown.
Check all the pages you want to publish, and then click the go button next to the drop-down.