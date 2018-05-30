title: Web content best practices
summary: Useful tips to improve your content management.

# Web content best practices

## In this section:
* Learn how to make your site search-engine friendly
* Learn how to make your content accessible
* Other web best practices

## Making your content search engine friendly

The majority of your website traffic will come from search engines. To ensure your website is findable, you need to write and mark up your content in a way that allows the search engine to present the most relevant results. In other words, search engine friendly content will get more relevant traffic to your site.

What makes a site search engine friendly?

* Relevant content.
* A site built to meet accessibility standards.

Search engine friendliness and accessibility are very closely related—you can think of Google as just another blind user. SilverStripe CMS automatically does a number of things that make your site search engine friendly and accessible.

As a website editor, you should be aware of creating accessible content such as:
* Post **relevant content**. This may sound obvious, but it's the most important thing you can do as an editor. If your content is relevant to your users, your site will rank higher for the search terms they are using.
* If it's important to you to rank highly for **specific phrases**, it's key to mention these phrases in the first paragraph of relevant pages on the site. The absolute best way to rank number one is to have dedicated pages for these phrases. In the title of these pages would be the phrases you wish to rank for.
* Use CMS tools for to properly **mark up** your content.
* Ensure **correct spelling** across all your content—typos make the site rank lower.
* Ensure there are **no broken links** in your site—again, broken links will make your site rank lower.
* Provide **text alternatives** for media content, such as ALT text for your images, since search engines can't see images, just their descriptions.

### URLs, page names, titles and navigation labels

When you first create a new page, start by entering its name in the **Page name** field on the **Content** tab. SilverStripe CMS automatically populates a number of other fields based on that name. You can leave them as is, or change them individually. It's useful to know where and how the different names are displayed.

![Page name field](/_images/page-names.png)

* **Page name**—generates the main headline (the &lt;h1&gt; tag) for the page's content.
* **URL Segment**—generated based on the page name, using the words and dashes. Human-readable URLs make a page more easily found by search engines. Most of the time, the URL that SilverStripe CMS generates will be fine, but you can manually change it if necessary.
* **Navigation label**—appears in your site's navigation. Sometimes when you have a lengthy page name, it makes sense to create a shortened navigation label.

<div class="note" markdown="1">
Your website developer will have configured your SilverStripe site for either simple or hierarchical URLs.

Simple URLs only use a single level of depth. For example, a page for a staff member might be called "John Smith", and its URL would be www.website.com/john-smith. Simple URLs are short and memorable, however, you are more likely to have multiple pages with the same name.

If a URL is already in use, the CMS will generate URLs with numbers, e.g., /staff-members-1, /staff-members-2, etc.

In this case, it's a good idea to manually change the URLs to something more meaningful, such as /staff-members-berlin, /staff-members-hong-kong.

Hierarchical URLs provide a logical path for a page as it exists in the site's structure. In our example, this might be www.website.com/offices/new-york/staff/john-smith
</div>

### Meta tags

Meta tags also make your web page more findable. The **Meta Description** field should contain a concise and relevant summary of what the page contains. This will show in search engine results, and helps visitors understand the content of the page.

![Meta titles](/_images/meta-title.jpg)

<div class="note" markdown="1">
The meta fields for title and keywords have been removed in v3.1. Keywords have been removed due to an official Google press release which confirmed that [Google doesn't use the keywords tag anymore](http://googlewebmastercentral.blogspot.co.nz/2009/09/google-does-not-use-keywords-meta-tag.html).

It is best to avoid repetition of keywords and phrases in the description. Google sees this as 'keyword stuffing', which is looked at as search engine spam.
</div>

### Clean HTML

SilverStripe CMS generates clean HTML code when you type your content into the CMS. However, often you already have content in another format, such as Microsoft Word, which you need to simply transfer into the CMS.

Avoid cutting and pasting directly from a word processor with the standard cut and paste functions. Always "Paste from Word" if using Microsoft Word, or "Paste as Text" if using another word processor. Word processors tend to do poor jobs of creating web markup code and often insert extraneous code which make your site less search-engine friendly and accessible.

## Making your content accessible

### Why does accessibility matter?

An accessible website means that it can be viewed by the widest audience possible. Accessibility not only refers to people with physical disabilities (such as blind users), but also people with cognitive, learning or motor skills disabilities, and people who access your site with mobile devices or old, outdated technology. Lastly, as mentioned previously, search engines can be considered disabled users in the sense that they can't see your design or images or interact with your site.

Accessibility is important for a number of reasons:
* **Ethical**—being inclusive is the right thing to do and has a positive impact on how your audience perceives you or your organisation.
* **Business**—sites that can be used by everyone have a larger audience. They are more findable and therefore generate more traffic/business. Accessible sites are also easier to maintain, resulting in fewer ongoing costs.
* **Legal**—many governments require websites to comply with certain standards. Details depend on your country, however, typically the guidelines are based on the Web Content Accessibility Guidelines developed by the World Wide Web Consortium (W3C.)

### What can content editors do?

Accessibility is not something you implement once and then have it. There is an infinite number of types of disability, platforms, devices, configurations, so you have to choose to what level you want to comply.

The more you know about your users, the better. Web stats, such as Google Analytics, can help you find out about your users' most frequently used browsers and operating systems. User research can help to learn more about how users with disabilities interact with the site. Automated tools can help and are a useful first step as they look for all the obvious issues and generate a list of problems. However, it still requires a person to assess and interpret the results and make decisions about items flagged by the automated tools. For example, you can use an automated tool to check whether all your images have alternative text, but you as the editor of your site need to determine if the text in the alt attribute is descriptive and appropriate.

The following paragraphs describe some of the quick wins—things you can do easily to greatly increase the accessibility of your site.

#### Alternative text (ALT tag) for images

When embedding images in the HTML editor, always provide alternative text that can serve as a placeholder in case the image itself cannot be displayed. Alternative text is often referred to as the "ALT tag". Alternative text is important for those who cannot see the image, such as vision impaired users, people with text-only browsers, or search engine, and it should be meaningful and describe what the image shows.

In addition, you may also want to add **Title text** for your image. Title text is for additional information about your image, such as the name of the photographer, or the date when it was taken. The title text appears as a tooltip when the user hovers over the image.

![Alternative text for images](/_images/alt-image-text.png)

#### Headings and lists

Mark up your headings by selecting the right heading style from the Format dropdown. Using headings properly gives your content hierarchy and, for example, allows users with screen readers to skip ahead to the next heading. Note that Heading 1 will be the title of your page, and all lower-level headings should be nested properly (e.g., Heading 3 should be within a Heading 2 section, etc.)

If your content uses lists, select either bullets (unordered list) or numbers (ordered list)—don't use dashes or asterisks to mark up lists.

#### Links

When you insert a link, make sure your link text (the part of your content that's clickable) is meaningful and relates to the page you're linking to. Don't use "click here" or "read more" as they don't tell the user where your link is going. Think about what would make sense for someone who has the link text read out to them by a screen reader.

#### Alternative formats for media

If your site uses other media, such as Flash, audio or video content, document attachments or animations, make sure this content is accessible to users who can't see or hear it, or who don't have the software to view it. How exactly you do this will depend on the kind of content and how critical it is to your site and your users. Typical alternatives would be transcripts, summaries (for example, of PDF documents), captions (for videos), or text-only versions.

#### Tables and charts

If your site uses graphs to convey information, also provide text-based summaries that describe the information displayed in the graphs.

For tables, make sure you mark them up so that screen readers can interpret them correctly (for example, mark header rows/columns as such.) It's also a good idea to provide a text-based summary of the information contained in the table.

## Other best practices

### Image dimensions

When you embed images in your content, always specify width and height. This allows the browser to start rendering the page before downloading the actual image, which speeds up page loading. SilverStripe CMS pre-populates the image dimensions automatically, so you do not need to edit them unless you would like to change the dimensions.

### Custom error pages

Sometimes your users will get a **Page not Found** error because they clicked on an outdated link or misspelled the URL of the page they were looking for. The **Page not Found** error is also known as a "404 error".

It's a good idea to create a custom 404 page for your site. On this page, you can refer your users to key pages on your site, encourage them to use search or a sitemap, and give them information on how to contact you about problems with the website.

To create a custom error page, select ***Add new*** in the **Pages** section and choose **Error Page** from the page types listed. In the **Content** tab, from the **Error code** field select "404 - not found" and add your error message. Note that you can also create custom pages for other errors. "Page not found" is the most common error type that your users will encounter.

![Error page](/_images/error-page.jpg)

To learn more about best practices see Web Aim's [Introduction to Web Accessibility](http://webaim.org/intro/) guide.
