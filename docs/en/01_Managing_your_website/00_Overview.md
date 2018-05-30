title: Overview
summary: Introducing the SilverStripe CMS administration interface.

# Overview

The latest SilverStripe CMS administration panel is arranged in four main areas, as shown below:

![SilverStripe 4 CMS overview](/_images/basic-overview.png)

## CMS menu

This CMS menu allows you to navigate to the main sections of the SilverStripe CMS. The CMS menu can be collapsed by using the toggle at the bottom left of the screen. By default the CMS menu provides you access to your sites pages, files and images, reports, manage security of its members and admins, adjust site settings and get CMS user help.

The menu you see may change depending on what modules are installed. However, the following tabs are part of a typical SilverStripe installation:

### Pages

This section enables you to order, remove, and add pages. When you have a page selected you can edit the content, publish, unpublish or archive a page among many other things.

### Campaigns

This section allows you to create and group new content together to be released all at once. For example, this might include several pages, images and blocks of content that need to be published at the same time across your website for a promotion.

### Files

This section allows you to add or delete files and to synchronise your view with the actual files on the server. You can also organise your files into folders.

### Reports

This section shows reports for your site such as, pages with broken links or pages with no content. What you see in this section will depend on which version of SilverStripe you are running and what modules you have installed.

### Security

The Security section enables you to set up and administer users and user groups as well as control access to various pages or sections. You can also upload these settings in the form of a CSV file.

### Settings

Here is where you can manage some global settings like the site name, themes and user access control.

### Help

Help provides direct access to SilverStripe User Help. This is the site you are looking at right now!

## Areas within the Pages section

### Tree Management

The Tree Management area is found between the CMS menu and page details, and displays as a site tree in a hierarchical format. If a page is selected in the tree its details will be shown in the Page Management area. You can rearrange your page hierarchy. The site tree will indicate if a page is Draft, Modified, or Archived by a page status, if a page is published no status will be shown. Because pages can be placed 'beneath' one another in the hierarchy, you may need to expand items in the tree to see items beneath them.

### Page Management

The Page Management area shows various data relating to individual pages such as: page name, navigation label (label in the website menu), URL and general content. The content of each page is typically edited through a text editor (HTML editor), which behaves in a similar fashion to a word processing application (such as Microsoft Word). Content authors can also select to edit the page's html directly through the editor.

#### Publishing Bar

The Publishing bar on the bottom of the page allows you to save, publish (make publicly available), unpublish (return to draft), unpublish and archive (remove from site tree) or add the page to a Campaign.

![SS4 publishing options](/_images/publishing-options.png)

### View mode toggle and page preview

You can choose view the interface in a few different ways, including Edit Mode, Split Mode (side-by-side edit and preview) or Preview Mode (preview only). Within the preview area you can also toggle between preview states ***Draft*** and ***Published***.

![Edit mode toggle](/_images/Preview-Bar.png)

See,
[Previewing content changes](https://userhelp.silverstripe.org/en/4/creating_pages_and_content/creating_and_editing_content/previewing_changes/) to learn more.
