title: Forums
summary: Setting up and running forums on your website.

# Forums

## In this section:

* Learn how to manage forums.
* Register a new username
* Learn how to create new topics, (a.k.a. threads)
* Learn how to create, edit, and publish posts.
* Learn how to administrate topics.
* Learn how to administrate forum users.

## Before we begin
Make sure that your SilverStripe installation has the Forum module installed.

Make sure you are in the "Pages" section on the navigation tabs in the Content Management System backend (CMS) and you are on your "Forums" Forum Holder page. If you do not have a forum holder page, you can create one by clicking on the top level of your website in the CMS, or the page you would like the forum to be a subpage of, hitting the "Add New" button on the top of the pane. Choose "Forum Holder" from the list, and then press the "Create" button.

## Managing forums

### Creating a new forum

Click on the new "Forums" Forum Holder page. Now click the "Add new" button at the top of the "site tree" side-pane. Go ahead and select "Forum" from the list and then hit the "Create" button.

![Add new forum](/_images/new-forum.jpg)

You will notice that a new forum page has been created, with the name of "New Forum".

![New forum created](/_images/created-new-forum.jpg)

Once you have created the new forum page it should automatically open up the editing pane.

If you head back to the pages pane you will also notice it has a yellow "losenge" saying "Draft" next to "New Forum". "Draft" pages are new and have never been published.

![Draft forum](/_images/draft-forum.jpg)

<div class="note" markdown="1">
### Notes:

Don't worry if you create your forum in the "wrong" place. Pages can be moved and re-ordered easily, and we will cover that under "[Managing Your Site](/managing_your_website)".
</div>

### Naming and editing your forum

In the Editing Pane, to edit your forum, you want to click on the "Content" tab if it it not already selected, and then the "Main Content" subtab.

Here you will be presented with three forms. The first is for the "Page Name" - this will define what the forum will be known as in the CMS, but it will also be used to form the "default" navigation label and URL for the page, though both can be changed manually.

Below it, you will find the Navigation Label. This will define what the forum will show up as when listed in forum page on the public-facing front page of your site. If you fill in the Page Name first, it will automatically put the page name in the navigation label field. It is usually, but not always, a good idea to leave it the same. If you wish to change the navigation label but not the page name, you can do so here.

Finally, there is the Content box. In the content box, you can write a description of the forum's contents. This is optional but helps to eliminate ambiguity.

### Enabling, creating, and using categories

If you have many forums on your site, you may want to organise them by category. For example, if your website was about farming, and had a separate forums for each product, you may want to group them into categories, such as: Fruits, Veggies, Meat & Dairy, and Livestock.

![Adding categories](/_images/add-category.jpg)

To enable categories, click on the forum holder "Forums" in the left hand "PageTree" Pane. (The forum holder is the root page of all your forums.) In the Editing Pane, click on the "Content" tab, then "Settings". Check the box next to "Show forums in categories," and hit save.

![Enable categories](/_images/show-forum-category.jpg)

To create categories, click on any of your site's forums in the Contents pane, and click on the "Category" tab on the editing pane. Click on Add Forum Category. This will bring up a pop-up menu where you can add a category title and set a priority for the category. Categories with a higher priority (100 is high, 1 is low) will be listed before lower priority categories. Hit Save. You may enter multiple categories at this time, by typing in additional category names and hitting Save after each one. When you are finished adding categories, close the window.

![Create categories](/_images/add-forum-category-fields.jpg)

To sort forums into different categories, click on each forum you wish to sort in the Contents pane, and go to the "Category" tab in the Editing Pane on each one. Select the category you wish each forum to be in, in turn, and hit Save in the bottom right corner of the Editing pane.

![Sorting Forums into categories](/_images/category-list.jpg)

### Creating New Topics (a.k.a. Threads)

To create a new topic, head to the front-end of the live website. Either log-in under your username, or, if you do not have one, register a new username.
Registering a new username

Head to the public-facing website (the "frontend") and browse to the forum. Click on the "Register" link. You will be brought to a page where you can enter in your personal details. You may enter in your personal information in the fields.

Your nickname and any field you mark with a checkbox will be shown in your public profile on the forum. If you do not want a field to show up in your publicly accessible profile, make sure that the checkmark next to these fields are unchecked.

If you have an avatar (a small personal photograph or illustration which helps people visually identify you,) you may also upload it at this time, by either dragging and dropping an image into the "Drop Files" area or pressing the "From Files" button and choosing a .JPG, .GIF, or .PNG file from your hard drive.

### Signing in with a username

To sign in with your username, head to the public-facing website (the "frontend") and browse to the forum. Click on the "Login" link. Enter your user "nickname" and the password you chose during registration.

<div class="note" markdown="1">
### Notes:

If you have forgotten your password, click on "Forgot Password," and follow the steps to reset or recover your password.
</div>

### Starting a new topic

To start a new topic, head to the public-facing website, and browse to the forum. Sign in, and click on the forum you would like to add the new topic to. Click on "Start a new topic," and enter in the title of the topic, as well as the content of the first post in the topic, and hit the "Post" button. The change should show up immediately.
Editing a previously published post (as the post author)

Once you have made a post, you may edit or delete a post you have authored, by browsing to that post in the forum and hitting the "Edit" or "Delete" links respectively.

## Administrating topics

### Editing or deleting a previously published post (as an administrator)

If you have administrative access, you may edit or delete any post made by any poster, by browsing to that point and hitting the "Edit" or "Delete" links respectively.

### Making threads sticky

To make a thread "sticky," that is, to make sure it always appears at the top of the topic listings for the forum, click the checkbox next to "Is this a sticky thread?" and hit Save.

To make a sticky thread global - that is, to make sure it always appears at the top of every topic listing on every forum on your site, click the checkbox next to "Is this a Global Sticky" as well, and hit Save.
Locking threads as read only

To prevent people from making changes to a topic, (also known as "locking" a topic), click the checkbox next to "Is this a Read only Thread?" and hit Save.

### Changing thread forums

To move a topic from one forum to another, browse to the topic in question, and choose the forum you wish to move the thread to under the "Change Thread Forum" drop-down box, and hit Save.

## Administrating users

To administrate users, make sure you are in the CMS "backend" for administration, and press the "Security" navigation tab. This should give you a list of all the users that have registered on the forum or website.

![Administrating forum users](/_images/forum-users.png)

### Deleting user accounts

To delete a user account, click on the red "X" icon next to the username for the account. This will remove the account from the forum and website, and the user will not be able to log in using that name again.

### Assigning moderation responsibilities to users

To assign moderation responsibilities, click on the "edit" icon next to the username for the account. This will bring up the profile of the user.

![Edit forum user](/_images/edit-forum-user.jpg)

Click on the "Forum" tab in the user profile, and change the "User Rating" drop-down menu to "Moderator." Hit Save.

![User rating](/_images/edit-user-forum-tab.jpg)

Click on the "Moderated Forums" tab in the user profile, and place a checkmark next to any forums the user will be given moderation access to. Hit Save.

![Moderated forums](/_images/moderated-forums.jpg)

After you are done, click the "security" link in the breadcrumbs at the top of the screen and it will take you back to the list of users.

<div class="note" markdown="1">
### Notes:

While this limited information will suffice for forum administration, administrating users across your SilverStripe site is a much broader topic which will be covered in more under "Changing and Managing Users" in the "For Website Administrators" section.
</div>
