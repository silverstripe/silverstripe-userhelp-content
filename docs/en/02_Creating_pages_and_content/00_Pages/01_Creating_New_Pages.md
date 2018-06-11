title: Creating new pages
summary: Add a new pages and descriptions of the deafult page types.

# Creating new pages

## Quick Reminder

 1. Go to the ![pages-tab-single](/_images/pages-tab-single.png) tab
 2. Click on the page you wish to edit
 3. Make your required changes
 4. Click ![save publish](/_images/save-publish.png) to make your changes live

## Creating a new page

 1. From the ![pages-tab-single](/_images/pages-tab-single.png) tab, click on the add new page button button.
 2.First choose **where** you'd like to create the page:
	a. **Top Level**: The page shall appear in the main navigation bar, make sure there is enough room!
	b. **Under another page**: Shall allow you to select an existing page on the site where you'd like to create the new page, as a subpage. For example, if you'd like to create a new page in the About Us section of your site, select the About Us page from the dropdown.
 3. Choose the **type** of page you'd like to create. Normally you just wish to create a standard content page, so just select ![page generic selected](/_images/page-generic-selected.png)
 <div class="note" markdown="1"> Different page types will usually have different content fields for you to fill in, and may also have a slightly different layout when the page is viewed. Depending on the functionality of your site, you may also be able to create News Article pages etc.</div>
 4. Click on ![create button](/_images/create-button.png)
 5. Your new page shall be created, you can now enter it's content, and click on ![save publish](/_images/save-publish.png) to make it live. Don't forget to give it a Page name!

<div class="note" markdown="1">
Don't worry if you create your page in the "wrong" place.  Pages can be moved and re-ordered easily, and we cover that under "[Pages](creating_pages_and_content/pages/reordering_pages/) section."
</div>

## Page types

There are many different types of pages in SilverStripe, each with its own functionality and purpose. By now you already know how to create a basic page. It is also possible to change a page from one page type to another.

### Different page types and their functions

#### Basic pages

* **Page** - The most basic page type. It contains content, and has no customised functionality or special purpose. Most pages you create on your site will be of this type.
* **Home Page** - The Home Page behaves like any other page, with the exception that it is the home page for your site - what users will see first if they browse directly to the root of your domain.
* **Error Page** - The page displayed when an error is produced by the website. Error pages can be created for individual error types, so for example, a 404 "Page not found" can look different from a 403 "Forbidden" page.
* **Redirector to another page** - This page on the website redirects the user to either another page on the same website, or a page on an external website.
* **Virtual Page** - A virtual page uses the content of another page. This is different from a redirector, as a redirector essentially links one location on the website to another, while a virtual page copies the content of the other page. Editing the page the virtual page is based on will, in turn, edit the copied virtual page.

#### Other types of pages

Depending on the code and modules included in your site, your page type list could contain any number of other page types. This could include [blog pages](/optional_features/blogs), [forums](/optional_features/forums), [user defined forms](/optional_features/forms), or
news pages.

### Changing an existing page type

To change a page type, look in the Pages pane for the page you wish to change.

![Choosing page type](/_images/Choosing-A-Page.png)

Click on it, and head to the "Settings" tab in the editing pane. You can change the page type from the "Page type" drop-down menu. Save your changes by pressing "Save Draft" or "Save & Publish" in the actions menu at the bottom of the editing pane.

![Changing page type](/_images/Changing-Page-Type.png)
