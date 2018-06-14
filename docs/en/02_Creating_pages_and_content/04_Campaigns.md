title: Campaigns
summary: Create and group new content together to be released all at once.

# Campaigns overview

The Campaigns section of the CMS is new as of SilverStripe 4.

Campaigns allow for a set of pages on your site to be viewed and published as a collection. Items in a campaign could contain varying types of content including pages, files, data, content blocks, and forms. By default most content types can be added to a campaign but this will depend on how your data structures have been defined.

Campaigns enable:
* individuals or team to have easier visibility of a collection of content they need to work on or maintain
* reviewing a collection of work as draft
* publishing of content simultaniously 

Note: As this section of the CMS is relatively new it will continue to develop, for example, two planned features to be added will be scheduled publishing and permissions/settings of a campaign.


## Creating a new campaigns

1. From the **Campaigns** section, click the button ***Add campaign***
2. Add the details of your campaign:
	1. **Name** Give the campaign an easy to recognise/understand title. For example: Product launch June 2019, Marketing team to do.
	2. **Description** You add additional details to your campaign for easy reference. For example: Go-live date, Team involved, Target audience.
3. Click the ***Create*** button, you will be navigated to the newly created campaign which will initially be empty of content. 

![Adding a new Campaign](/_images/campaigns-section.png)

![New Campaign](/_images/new-campaign.png)

## Editing camapaign details/settings

![Campaign section](/_images/campaign-gridfield.png)

1. To edit the settings of an existing campaign navigate to **Campaigns** in the main CMS menu. 
2. From the list of current campaigns which are presented, for the campaign you want to edit click on the **Settings** action located on the far right of the item.
3. Edit the **Name** and **Description** of your campaign
4. If a campaign details have been changed the call-to-action will be **Save** otherwise it will display as **Saved** (meaning there are no changes which need saving). Click the ***Save*** button, you will notified if the campaign has been successfully updated.  

## Adding items to a campaign

![Adding Page to Campaign](/_images/add-to-campaign.png)

1. To add content to a campaign you need to navigate to the content you want to add.
2. From the ***More options*** dropdown (presented as an ellipsis icon) you should see the action ***Add to campaign***.
3. By clicking on the ***Add to campaign*** action you will be presented with a dialog which will allow you to choose which campaign the content should be added to.
4. From the **Available campaigns** dropdown select a campaign to add your item to, or alternatively select ***Add to a new campaign*** where you will presented with a new field where you can add a new campaign.
5. Click ***Add*** to add your content to the desired campaign, you will be presented with a success message if there were no issues. You can now close the dialog box.

![Campaign modal](/_images/campaign-modal.png)

## Managing items in a campaign

By selecting a campaign you will be taken to a view where you can see the contents of that campaign. These items will be categorised by content type (for example pages and files). 

When an item is selected in the campaign you will see a preview of the item on the right side of the screen if one is available. Items have two actions below the preview area:
 * **Edit**—Takes you to the edatible view outside of campaigns. For example, for a page it will take you to the page within the **Pages** section.
 * **Remove**—This action removes the item from the campaign. This includes any items which are solely tied to the item being removed, for example if a page is removed which contains a file which isn't being used by another item in the campaign both the page and file will be removed at the same time (see linked items below).
 
 ### Content states
 Items will indicate whether the item is already published or has unpublished changes by a badge.
  * **No changes**—Only items that are selected will show this badge, and it indicates that the item is already published and there will be no visible change if the campaign is published.
  * **Draft**—The item does not exist on the live site in any form.
  * **Modified**—The item exists on the live site but there are additional changes which will be visible once the campaign is published.
  * No badge—like **No changes** this indicates that the item is already published and there will be no visible change if the campaign is published.
 
 ### Linked campaign items
 
When a **link** icon appears on selected content in a campaign there are other items in the campaign which are dependant on it. For example, an image might be placed on a page and if the page is removed or published the image will also be removed or published becasue of the relationship they have. Any linked items in the campaign will also show a link icon to represent this relationship.

![Campaign preview](/_images/preview-campaign.png)


