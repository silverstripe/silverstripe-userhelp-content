title: Images and documents
summary: Uploading and working with files and images.

<!-- to do bigger future refactor piece -->

# Working with images and documents

You can either upload an image from the ***Files*** section or the HTML editor.

## Uploading images to the CMS from the Files section

Navigate to the **Files** section in CMS menu.

 <!-- (Be sure to save any page you are working on in the editing page to a draft before doing so, otherwise you may lose any changes you have made since the last save). -->

You should see a list of all of the files (and folders containing files) that have been uploaded to the CMS.

Before you upload your images/files, create a new folder. See the section below, [Managing Files](https://userhelp.silverstripe.org/en/4/creating_pages_and_content/working_with_images_and_documents/#managing-files)).

To upload a file or image into the folder, click the button ***Upload***.
<!-- This will take you to the upload files section. -->

Click the button ***Upload*** to choose your first file to upload or drag and drop your files into the CMS.
<!-- (this will automatically start the upload). -->

![Files selection](/docs/en/_images/files-section.png)

![Drag and drop file](/docs/en/_images/files-drag-drop.png)

<!-- Repeat this process for every file you wish to upload or you can select multiple images/files to upload by holding "control" (Windows) or "command" (Mac) on the keyboard while clicking your chosen images/files. -->

Once the images have finished uploading, click the button ***Back*** which is shown as a left arrow to navigate to the parent folder or the link ***Files*** in the breadcrumbs. You should now see the files you uploaded within your chosen folder. <!-- you an also push that up arrow to do -->

![Uploaded files](/docs/en/_images/files-uploaded.png)

<div class="note" markdown="1">
This same process can be used for filetypes other than images as well, see [Uploading and Linking to Documents](https://userhelp.silverstripe.org/en/4/creating_pages_and_content/creating_and_editing_content/working_with_images_and_documents/) to learn more.
</div>


## Uploading images from the HTML editor

<!-- Once you have uploaded an image, you can insert it into any page. -->

Navigate to the **Pages** section in CMS menu and click on the button ***Insert Images*** which is shown as a file icon in the HTML editor.

![Inserting uploaded images](/docs/en/_images/Insert-Images.png)

The **Files** modal will open over the page management section.
Click the button ***Upload***


<!-- and you should see a list of files. If you do not see the image you want, it may be in another folder. You can choose which folder you would like to view by clicking on the ***Folder*** dropdown field above the list of files. Additionally, you can use the provided search box to search by the image's filename. -->

![Images from the CMS](/docs/en/_images/Images-from-cms.png)

When you locate the image you want, select the image and click the button **Open**. You can now edit the details of the image by selecting the uploaded image thumbnail.
* Alternative text—shown if the image cannot be displayed (for example, on text-only web browsers, or screen readers)
* Title text—shows additional information about the image when the mouse rolls over the image. See, [Web Content Best Practices](03_Web_Content_Best_Practices) to learn more.
* Caption
* Alignment and text wrapping properties of the image
* Dimensions of the image to be displayed in the site

<!-- Details and Permissions -->

When you are done entering this information, click the button ***Insert file***. This will place the image in your text where your cursor was in the editing section.

![Inserted image](/docs/en/_images/Inserted-image.png)

## Managing files

To manage your uploaded files, navigate to the **Files** section in the CMS menu. The main CMS section will now show a list of the directories that hold files in your website. This includes both images and documents such as PDF files, and can also include javascript files.

## Creating, deleting folders

To create a new folder to store images and documents click the button ***Add folder*** shown as a folder icon. The newly created folder will be placed in the folder path you are currently located in.

![Add folder](/docs/en/_images/add-folder.png)

To delete a folder, select the checkbox field and click the button ***Delete*** shown as a trash icon.
This will expand a browser dialog box saying *Do you really want to delete this folder and all contained files?*. Select yes to delete the folder.

![Delete folder](/docs/en/_images/delete-folder.png)

## Searching for images and documents

To search for an image, click the button ***Search*** which is shown as a search icon. Type the whole or partial filename to locate the file. Click the button ***Advanced*** which is shown as a down arrow to filter the **File type**, **Last changed** or **Limit to current folder and its sub-folders** checkbox field.

![Searching for files](/docs/en/_images/search-files.png)

<!-- ## Moving and renaming files -->

<!-- To edit the details of a file such as the file name or location, select the file thumbnail.

 This will bring up the file details section. -->

<!-- Locate the file you want to edit, (you may need to use the search function if there are a large number of images in the folder). To edit the location or details of a file, click the edit icon in the actions column to the right of the file listing. This will bring up the file details section. If you wish to delete a file, simply click the delete icon in the actions column to the right of the file listing. -->

![Editing and deleting files](/docs/en/_images/Edit-delete-files.png)

Once you have opened the File details section, and you can edit the files details and move the file to a new location by choosing a new parent folder from the folder dropdown. Hit "Save" at the bottom left of the section when you are done editing.

![Moving files](/docs/en/_images/Move-file.png)

You can also delete the file from here too. To do this click the delete button which is located next to save at the bottom of the section.

<div class="note" markdown="1">
By default, uploaded files are placed in the "Uploads" directory.

If you place an image in a webpage, and later move or rename that image in "Files & Images," SilverStripe CMS will automatically keep track of those changes, so your webpage will remain unchanged - you don't even have to republish the page.
</div>
