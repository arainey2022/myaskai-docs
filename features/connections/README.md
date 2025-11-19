---
description: >-
  In addition to webpages and files, you can connect your cloud-based knowledge
  sources such as Google Drive, Notion, or Confluence (+ more) to train your AI
  agent so it can better answer questions.
---

# ☁️ Connections

{% hint style="success" %}
Available on our Pro plan.
{% endhint %}

To add more knowledge (in addition to adding [website content](../sitesync-adding-and-syncing-your-website-content.md) and [files](../file-uploads.md)) to your AI support agent you can connect your cloud-based knowledge sources.

{% hint style="info" %}
Where possible, you should always try and add knowledge using Connections as you will get much better answer quality as a result.
{% endhint %}

By default, all files or pages uploaded via connections are marked "Public". [You can also make them private](../private-internal-mode.md#connections).&#x20;

When in Public mode, your AI support agent will not answer questions that require Private content.

{% hint style="info" %}
If files or pages connected are marked "Public" in your My AskAI, no links to internal content will be shared as references when displayed publicly (i.e. as a widget on your site), only when used privately.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (446).png" alt=""><figcaption></figcaption></figure>

### How to Add Knowledge to Your AI Support Agent

{% embed url="https://www.youtube.com/watch?v=HdqX28CMJ-g" %}

### Which knowledge sources do you have connections or integrations with?

You can currently connect the following knowledge sources to your AI agent (you can connect multiple sources at once):

* Google Drive
* Notion
* Microsoft OneDrive (Personal and Business)
* Dropbox
* Zendesk Knowledge Base/Help Center (including behind a login)
* Intercom Knowledge Base/Help Center (including behind a login)
* Freshdesk Knowledge Base/Help Center (including behind a login)
* Sharepoint
* Confluence Knowledge Base
* Salesforce
* Shopify pages, products and customer data

More connections are coming soon, please let us know if you have a specific connection you would like to see [by requesting it here](https://feedback.myaskai.com/).

<figure><img src="../../.gitbook/assets/image (82).png" alt="" width="563"><figcaption></figcaption></figure>

### How do I connect a knowledge source?

1. Go to _**Knowledge > Connect knowledge sources.**_
2. Click "**+ Add new connection**".
3. Click on the [knowledge source](./#which-knowledge-sources-do-you-have-connections-or-integrations-with) you would like to integrate with e.g. Google Drive, Intercom etc.
4. You will then be taken to an authorization screen for the relevant integration.
5. Select your account or enter your relevant account details, and grant the necessary permissions, for more help on authorizations, look at instructions for the relevant knowledge source here.&#x20;
6. You will then be shown a page or file picker for your integration.
7. Select the files or pages you wish to connect to your AI support agent.
8. Confirm your selection.
9. These files are now connected to your My AskAI (you can close the file/page picking tab and navigate back to your My AskAI Dashboard to see them being added).

{% hint style="info" %}
If you select to add a folder or a page with subpages then the connection will sync all files within that folder and any folders (and their content) inside that folder. The same applies for "pages", all linked pages or subpages will also be added.
{% endhint %}

{% hint style="warning" %}
If you "Unpublish" or move an article back into "Draft" in Intercom, Zendesk or Freshdesk, you will also need to delete it from your My AskAI account.
{% endhint %}

### How do I delete an individual page or file?&#x20;

To delete a file from your AI support agent:

1. Go to _**Knowledge > Connect knowledge sources > Live connections**_
2. Click "**Manage**"
3. Search for and select the file or pages you want to remove and click the trash can icon :wastebasket: next to the item

<figure><img src="../../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>

Once a file is removed from the knowledge of an agent it is no longer used by the AI to answer questions and that knowledge is removed.

{% hint style="danger" %}
Note, if you are deleting an article from Zendesk, you will also need to delete it in your My AskAI Knowledge section in the dashboard.
{% endhint %}

### How do I remove a connection?

To disconnect a connection you must [delete all content related to that connection](./#how-do-i-delete-an-individual-page-or-file), if you need help doing this, please contact us via chat.

### How often are the connections updated, can I refresh them?

With most connections, each file or page within a connection is checked and updated every 24 hours if files have been modified to ensure content is kept up to date.

See the full table below for content update schedules:

<table><thead><tr><th width="160">Content source</th><th width="145" data-type="checkbox">Added files/folders/pages automatically re-synced?</th><th width="153" data-type="checkbox">New files/folders/pages automatically added and synced?</th><th width="151">Sync frequency</th><th data-type="checkbox">Links visible</th></tr></thead><tbody><tr><td>Websites</td><td>true</td><td>true</td><td>Fortnightly (or on request)</td><td>true</td></tr><tr><td>Google Drive</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>false</td></tr><tr><td>Notion</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>false</td></tr><tr><td>OneDrive</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>false</td></tr><tr><td>SharePoint</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>false</td></tr><tr><td>Intercom</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>true</td></tr><tr><td>Zendesk</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>true</td></tr><tr><td>Freshdesk</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>true</td></tr><tr><td>Dropbox</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>false</td></tr><tr><td>Confluence</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>false</td></tr><tr><td>Salesforce</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>false</td></tr><tr><td>Shopify</td><td>true</td><td>true</td><td>24 hours (if modified)</td><td>true</td></tr></tbody></table>

If you need to update an item intra-day you can find the item in the relevant connection, then click the "Refresh" icon next to it for an instant update.

<figure><img src="../../.gitbook/assets/image (184).png" alt=""><figcaption></figcaption></figure>

### Who sees the files and pages I have uploaded?

[Connection files and pages are public by default](../private-internal-mode.md#connections), this means they are used to answer questions in the public-facing widget, [this is explained in more detail here](../private-internal-mode.md#connections).

The links to those connections will not be shared when the AI answers questions - this is mainly because the pages and documents are not always accessible.&#x20;

### Which file formats can I upload?

You can upload the following file formats:

* pdf&#x20;
* xlsx
* csv\*
* docx
* txt
* md
* rtf
* tsv
* pptx

\*Note that for csv files each row resides on its own line, and each element within the row has the header of its corresponding column added to it as a prefix.

### How many files, pages, or content pieces can I add or connect?

There is a limit of 10,000 files, pages, or content pieces that can be added to an AI support agent.&#x20;

If this is an issue, please get in touch with us via chat.

### What are the file size limitations?

The maximum size of a local file to be uploaded is 10MB (this is a limitation put on us by Google, Microsoft et al and so is not something we can work around unfortunately).&#x20;

### Can I train my AI support agent on historic support tickets?

Yes, you can.

If you don't have a help center and only have historic tickets, we can help you create one, ask to "Talk to a person" and we will help you to set this up.&#x20;

We generally do not recommend training your AI support agent directly on your historic support tickets for a few reasons:

* There is no 'version control' of support tickets - answers that agents gave a year ago about a feature may have changed or no longer be relevant
* They rely on consistent responses from your agents - not all agents will respond in the same way, some will be better, some worse, the AI won't be able to distinguish from them
* 'Managing' the 'knowledge' becomes extremely difficult as you may have thousands or hundreds of thousands of tickets, how do you pick the 'right' ones?

We therefore always recommend that you use a verifiable source of truth to train your AI (like a help center or knowledgebase which has been through a review process and is managed).

This will ensure your AI gives the best quality AI responses.
