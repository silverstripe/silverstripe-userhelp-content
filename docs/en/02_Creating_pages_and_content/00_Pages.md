title: Pages
summary: How to manage the content structure, page history and batch publishing. 

# Managing your site structure

## In this section:

* Learn the different content types
* Learn how to move pages within the site
* Learn how to hide a webpage
* Learn how to delete a webpage
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

* **Blog Holders and Blog Entries** - [See the "Blogs" section](/optional_features/blogs)
* **Forum Holders and Forum Entries** - [See the Forums section](/optional_features/forums)
* **User Defined Forms** - [See the Forms section](/optional_features/forms)

### Changing an existing page type

To change a page type, look in the Pages pane for the page you wish to change. 

![Choosing page type](/_images/choosing-page.jpg)

Click on it, and head to the "Settings" tab in the editing pane. You can change the page type from the "Page type" drop-down menu. Save your changes by pressing "Save Draft" or "Save & Publish" in the actions menu at the bottom of the editing pane.

![Changing page type](/_images/change-page-type.jpg)
 
### Moving pages within the site

To move a page within the site, make sure you are in the "Pages" pane (selected from the navigation on the left side of the screen).

Make sure that "Drag'n'drop" is selected from the Display menu, then you can move a page by clicking on it in the "page tree", and dragging it to its new position in the website.

![Moving pages](/_images/moving-pages.jpg)
 
### Hiding pages

To hide a page, look in the Pages pane for the page you wish to hide. Click on it, and head to the "Settings" tab in the editing pane.

You can remove your site from being listed in your site's navigation bar by removing the checkmark next to "Show in menus."

You can remove your site from being listed in search results by removing the checkmark next to "Show in search."

After you have made these changes, hit the "Save & Publish" button in the actions menu at the bottom of the editing pane.

![Hiding pages](/_images/hiding-pages.jpg)
 
### Deleting pages

#### Deleting individual pages

To delete a page, look in the Pages pane for the page you wish to delete. Click on it, and head to the "Content" tab in the editing pane. You will see in the actions menu at the bottom of the editing pane, two buttons, "Unpublish" and "Delete from Draft".

The "Unpublish" button will remove the current webpage from the public-facing front end of your site. However, the content will remain as a draft, and no data will be lost - the page will remain in the CMS.

The "Delete Draft" button will remove the current webpage from the back-end CMS, but if you have previously published it, it will not be removed from the public-facing front-end of your site.

To completely delete a webpage, click on "Unpublish" first, then click on "Delete Draft".

![Delete a single page](/_images/delete-single-page.jpg)

#### Deleting multiple pages

To delete multiple pages, click "Multi-selection" on the top-right of the "Pages" pane. Each page in the page tree in the "Pages" pane should now have a checkbox next to it. Check all the pages you want to delete. (And perhaps more importantly, make sure NOT to check those pages you do not want to delete.)

From the "Actions" drop-down menu at the top of the "Pages" pane, choosing "Delete from Published Site" will remove the page from the public-facing portion of the website, but retain a copy of those pages in the backend CMS.

Choosing "Delete from draft site" will remove the page from the backend CMS, but the page will remain on the public-facing portion of the website.

Once you have chosen the intended action click the go button next to the drop-down.

To completely delete multiple pages, you must do both. The order of deletions in "Batch Actions" does not matter, though it's generally a good idea to delete from the published site first, then delete from the draft site.

![Delete multiple pages](/_images/delete-multiple-pages.jpg)
 
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
### Notes:

When a page is rolled back to the previous version, it is only rolled back in the backend CMS as a draft. To show the rolled back page on the public-facing website, it needs to be published by pressing "Save and Publish."
</div>
 
### Searching for pages

To search for a page, enter your search into the "Content" entry form in the page "filter" panel.

The default search mode is by text, and you can type any text to search your pages for that text. Pressing search will show only positive results in the Page Tree on the "Pages" pane.

Search results will remain the only items in the Page Tree until the "Clear" button is pressed.

![Searching pages](/_images/searching-pages.jpg)

You can also earch by different criteria, including "Date", "Pages" (All pages, Changed pages, and All pages including deleted) and "Page Type".

<div class="note" markdown="1">
### Notes:

One neat trick is that you can search for pages, and then perform a batch action upon them, such as deleting them or publishing them. For example, by searching for Page Type: "BlogEntry" and then a date range: "(whatever last Thursday was till now)" you can then create a quick batch action to publish all blog posts written since last Thursday.
</div>
 
### Publishing multiple pages

To publish multiple pages, click "Multi-selection" on the top-right of the "Pages" pane. Each page in the page tree in the "Pages" pane should now have a checkbox next to it. Check all the pages you want to publish.

From the "Actions" drop-down menu at the top of the "Pages" pane, choose "Publish" and then click the go button next to the drop-down.