title: Archiving and restoring content
summary: Sending content to the Archive and restoring content from the Archive to your website.

# Archive

<div class="note" markdown="1">The Campaigns section of the CMS is new as of SilverStripe 4 and therefore will continue to develop with functionality.</div>

All content which can be archived is stored within the CMS Archive. By default this includes pages, files, and content blocks. Depending on the way your CMS has been configured the Archive might extend to contain additional content types.

When archiving an item, the CMS will first automatically unpublished the item if published, before sending it to the archive. The Archive stores the item along with its entire history so that it can be restored at a later date. If an item is restored then it will be returned to the relevant section of the CMS it came from in a draft state.

**Note:** Some types of content can’t be sent to the **Archive**, or the functionality has been removed. If a **Delete** action is present instead of the **Archive** action, typically the content will be removed from the CMS without a way of retrieving the information via the CMS interface, although the content will typically still be stored in the database.

## Archiving content (Pages, Files, Content blocks etc.)

1. Navigate to the item you wish to archive within its section of the CMS (for example, navigate to the page you wish to archive within the Pages section of the CMS).
2. Click the **More options** button, typically located in the action toolbar e.g. to the right side of the Save and Publish buttons.
3. Select the **Archive** option. You will receive a confirmation notification if the the item has successfully been archived.

Location of the **Archive** action for pages:

![Archiving a page](../_images/archive-page.png)

Location of the **Archive** action for files:

<div class="note" markdown="1">Archiving for files is turned off by default.</div>

![Archiving in the files section](../_images/archive-file.png)

Location of the **Archive** action for tabled content:

![Archiving a gridfield item](../_images/gridfield-archive.png)

## Retrieving content

**Option 1: Undo archiving**
Upon archiving an item, a success message will appear at the top of the view, with **Undo** link. Clicking the **Undo** link would instantly restore the item into its original location

**Restore from Archive**

1. Navigate to **Archive** section.
2. Select a content type.
3. Click the **More options** button.
4. Select the Restore to draft option. Alternatively, the **Restore to draft** button is also available after clicking into an item.

![Restoring an archived page](../_images/archive-restore.png)

![Restoring an archived item](../_images/restore-page.png)
