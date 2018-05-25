title: Images and documents
summary: Working with files and images.

<!-- to do bigger future refactor piece -->

# Working with files (images and documents)

## Managing files

Files are typically managed within the Files section of the CMS. This section shows a library of files available to use on your website. This includes both images and documents such as PDF files, and can also include javascript files.

Files can be displayed or linked to from multiple places. This means that by updating a file's details, all of the pages which use the file will recieve those updates (both the file and page would need to be published for these changes to be seen on the live site).

You can either upload files within the Files section or directly from pages through the HTML editor. The Files section supports a range of different file types which are typical for use on the web including images, videos, and documents. See [Web content best practices](https://userhelp.silverstripe.org/en/4/creating_pages_and_content/web_content_best_practices/) for additional tips on how to prepare files for use on the web. 

<div class="note" markdown="1">
By default, uploaded files are placed in the "Uploads" directory.

If you place an image in a page, and later move or rename that image the CMS will automatically keep track of those changes, so your webpage will remain unchanged - you don't even have to republish the page.
</div>


## Uploading images to the Files library

Navigate to the **Files** section in the CMS menu. You should see a grid or list of files (and folders containing files) that have already been uploaded to the CMS, otherwise you have a empty files area.

Before you upload your images or files you may wish to create a new folder, or navigate to an existing folder to upload a file into in order to keep your files orderly (More about this in the section [Managing Files](https://userhelp.silverstripe.org/en/4/creating_pages_and_content/working_with_images_and_documents/#managing-files)). You can navigate up and down the folder structure by clicking on folders or clicking the back arrow.

Click the button ***Upload*** button to choose your file(s) from your computer to upload, or alternatively you can drag and drop your file(s) into the main **Files** area.
<!-- (this will automatically start the upload). -->

![Files selection](/docs/en/_images/files-section.png)

![Drag and drop file](/docs/en/_images/files-drag-drop.png)

You should now see the files you uploaded within your chosen folder.

![Uploaded files](/docs/en/_images/files-uploaded.png)

<div class="note" markdown="1">
This same process can be used for filetypes other than images as well, see [Uploading and Linking to Documents](https://userhelp.silverstripe.org/en/4/creating_pages_and_content/creating_and_editing_content/working_with_images_and_documents/) to learn more.
</div>


## Uploading images from a page

<div class="note" markdown="1">
Pages that contain a HTML editor allow you to place files into the content area, some pages don't have a HTML editor area by default and might require a different [Page Type](/en/4/creating_pages_and_content/pages/creating_new_pages/) or for a Content Block to be added.
</div>

1. Navigate to your page within the **Pages** section.
2. In the HTML editor click on the button ***Insert from Files*** which is shown as an image icon.  
3. The Files area will open above the page management section.
4. Navigate to the folder you would like to add your file(s).
5. Either drag files from your computer/device or click the ***Upload*** button to add your file(s). 
6. Select the files you would like to add to your content, they will appear on the right side of your file library so that you can edit its details. 
7. When you have finished editing click the ***Insert*** button. This will place the image in your text where your cursor was in the editing section.

![Inserting uploaded images](/docs/en/_images/Insert-Images.png)

![Images from the CMS](/docs/en/_images/Images-from-cms.png)


## Editing files

Basic functionality and options for files:
* **Alternative text** is shown if the image cannot be loaded or displayed (for example, on text-only web browsers or screen readers)
* The **Title** text field shows additional information about the image when the mouse rolls over the image. See, [Web Content Best Practices](03_Web_Content_Best_Practices) to learn more.
* The **Caption** field can be used to enter text descriptions of an image.
* The **location** of the file within the Files library
* **Alignment** and **text wrapping** properties of the image.
* **Dimensions** of the image to be displayed in the site. 

<!-- Once you have opened the File details section, and you can edit the files details and move the file to a new location by choosing a new parent folder from the folder dropdown. Hit "Save" at the bottom left of the section when you are done editing. -->

![Moving files](/docs/en/_images/Move-file.png)

<!-- Details and Permissions -->

![Inserted image](/docs/en/_images/Inserted-image.png)


## Creating, deleting folders

Folders can be used to organise images and documents, and if a new folder is created, it is added to the view you are currently in. To create a new folder click the ***Add folder*** button (also shown as folder icon). The new folder will appear on the right side of the library and will require a **Folder name** before you save it and it appears in the File library. 

![Add folder](/docs/en/_images/add-folder.png)

Extra care should be taken when deleting a folder as files contained within can be deleted at the same time. There are two ways to delete a folder: 

* Select the folder checkbox field and click the button ***Delete*** shown as a trash icon.
* Select a folder so its details shows in the edit panel (right of the file library), select **Delete** from the file options (accessible through the ellipsis icon).

![Delete folder](/docs/en/_images/delete-folder.png)

![Editing and deleting files](/docs/en/_images/Edit-delete-files.png)


## Searching for images and documents

To search for an image, click the ***Search*** button (shown as a search icon). Type the whole or partial search term to  locate file(s). Click the button ***Advanced*** (or shown as an downward arrow) if you wish to filter by **File type**, **Last changed** or **Limit to current folder and its sub-folders** checkbox field.

![Searching for files](/docs/en/_images/search-files.png)
