title: Creating new pages
summary: Add new pages and descriptions of the default page types.

# Creating new pages

## Creating a new page

1. Navigate to the **Pages** section within the CMS menu.
2. Click the button ***Add new***. You can either create the page:
* **Top Level**—the page will appear in the main navigation bar.
* **Under another page**—this will allow you to select an existing page in the site where you can create a new page type, as a subpage.
For example, if you'd like to create a new page in the "About Us" section of your site, select the "About Us" page from the dropdown field.
3. Choose the desired page type from the selection available. In this example select the most generic content page type, ***Page***.
4. Click the button ***Create***.
5. Your new page will be created, you can now enter some content. Make sure you consider the length of your ***Page name*** for site tree and front-end clarity. Click the button ***Publish*** to make your changes live.

![Adding a page](/_images/adding-a-page.png)

<div class="note" markdown="1"> Different page types will usually have different content fields to fill in, and may also have a slightly different layout when the page is viewed. Depending on the functionality of your site, you may also be able to create "News Article" page types etc.</div>

Don't worry if you create your page in the wrong location. Pages can be moved and re-ordered easily, see [Reordering Pages](reordering_pages/) to learn more.

## Page types

There are many different page types in SilverStripe, each with their own functionality and purpose.

### Different basic page types and their functions

#### Basic pages

* **Page**—The most generic content page type. Page contains HTML content, and has no customised functionality. Most pages you create on your site will be of this type.
* **Error Page**—This page will display an error when produced by the website. Error pages can be created for individual error types, such as, a 404 "Page not found" can look different from a 403 "Forbidden" page.
* **Redirector Page**—This page type redirects the user to either an internal page on your website, or a page on an external website.
* **Virtual Page**—A virtual page displays the content of an existing page on your website. This is different from a redirector page, as a redirector essentially links one location on the website to another, while a virtual page copies the content of another page. Editing the virtual page will, in turn, edit the copied virtual page.

#### Other types of pages

Depending on the code and modules included in your site, your page type list could contain any number of other page types. This could include [blog pages](/optional_features/blogs), [user defined forms](/optional_features/forms), or news pages.

The home page of the site, shown by default when a visitor browses directly to the root of your domain (eg. www.example.com/), is identified within SilverStripe by the URL segment being set to 'home'.

### Changing an existing page type

It is also possible to change from one page type to another. To edit an existing page type, navigate to the site tree and select the page you want to change.

![Choosing page type](/_images/Choosing-A-Page.png)

1. Navigate to the ***Settings*** tab.
2. You can select a new page type from the **Page type** dropdown field.
3. Click the button ***Publish*** to make your changes live.

![Changing page type](/_images/Changing-Page-Type.png)
