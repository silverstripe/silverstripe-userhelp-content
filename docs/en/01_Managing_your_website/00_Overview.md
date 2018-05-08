title: Overview
summary: Introducing the SilverStripe CMS administration interface.

<!-- to do bigger refactor piece add images for keys -->

# Overview

The latest SilverStripe CMS administration panel is arranged in four main sections, as shown below:

![SS4 Administration Panel](/_images/basic-overview.png)

## CMS menu

This CMS menu allows you to navigate to the main sections of the SilverStripe CMS. The CMS menu can be collapsed by using the toggle at the bottom left of the screen. The CSM menu lets you manage pages or files and images, run reports or manage security, adjust site settings and even get help. Some modules and optional features add additional sections to the CMS menu. Select the relevant tab to display the associated information in the current window.

The menu you see may change depending on what modules are installed. However, the following tabs are part of a typical SilverStripe installation:

### Pages

This section enables you to access and edit the content of the pages on your website. You can also change the order of pages, remove pages and add new ones. While in this section, the Publishing Bar is available.

### Campaigns

This section allows you to create and group new content together to be released all at once. For example, this might include several pages, images and blocks of content on existing pages that need to be published at the same time across your website for a promotion.

### Files

This section allows you to add or delete files and to synchronise your view with the actual files on the server. You can also organise your files into folders.

### Reports

This section shows reports for your site such as, pages with broken links or pages with no content. What you see in this section will depend on which version of SilverStripe you are running and what modules you have installed.

### Security

The Security section enables you to set up and administer users and user groups as well as control access to various pages. You can also upload these settings in the form of a CSV file.

### Settings

Here is where you can manage some global settings like the site name, themes and user access control.

### Help

Help provides direct access to SilverStripe user help. This is the site you are looking at right now!

## Tree Management

The Tree Management area is found between the page and the CMS menu and displays the Site Tree in a hierarchical format. The page you are working on will be shown on the right, in the Page Management area. Select the page in the tree you want to work on, or add a new page. You can also switch to 'edit' mode with the "Edit Tree" button, enabling you to rearrange your page hierarchy or modify page status. Because pages can be placed 'beneath' one another in the hierarchy, you may need to expand items in the tree to see all of them.

## Page Management

The Page Management area is on the right of the page and shows various data relating to individual pages such as: page name, navigation label (label in the menu), URL and general content. The text and image content of each page is edited through the TinyMCE WYSIWYG (What You See Is What You Get) editor, which behaves in a similar fashion to a word processing application (such as Microsoft Word). More advanced users can also select to edit the page's html directly.

## Publishing Bar

The Publishing bar on the bottom of the page allows you to save, publish (make publicly available), unpublish (return to draft), unpublish and archive (remove from site tree) or add the page to a Campaign.

![SS4 Publishing Options (Save/Publish)](/_images/Publishing-options.png)

## Edit mode toggle

You can review content changes in different ways, including Edit mode, a side-by-side preview in Split mode or as a full screen preview in Preview mode. You can also toggle between preview states ***Draft*** and ***Published***.

![SS4 Edit mode toggle (Split/Preview/Edit modes)](/_images/Preview-Bar.png)

See,
[Previewing content changes](https://userhelp.silverstripe.org/en/3.6/creating_pages_and_content/creating_and_editing_content/previewing_changes/) to learn more.
