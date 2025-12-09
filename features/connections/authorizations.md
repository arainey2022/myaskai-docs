---
description: >-
  Some Connections require slightly more information than others to set up, here
  is where you can find all details of how to connect your knowledge source.
---

# 🔑 Authorizations

### Google Drive

To authorize your Google Drive connection, you just need to log into your Google Drive account when asked.

<figure><img src="../../.gitbook/assets/image (316).png" alt=""><figcaption></figcaption></figure>

You will see this message after you have selected your account telling you that the app isn't verified, this is because we are waiting on Google to approve our app - to continue, click the "Advanced" button in the bottom left and then "Go to myaskai.com":

<figure><img src="../../.gitbook/assets/image (61).png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="info" %}
If you are using a Google workplace account, you may need your admin to grant access to 3rd party apps to connect.
{% endhint %}

### OneDrive

To authorize your OneDrive connections, you just need to log into your Microsoft account when asked, then click confirm to grant permission.

<figure><img src="../../.gitbook/assets/image (317).png" alt=""><figcaption></figcaption></figure>

#### [​](https://docs.carbon.ai/connectors/onedrive#microsoft-admin-approval-2)Microsoft Admin Approval <a href="#microsoft-admin-approval-2" id="microsoft-admin-approval-2"></a>

To allow My AskAI to access your Microsoft applications (OneDrive and SharePoints), users might need to request admin consent approval.

Here’s a step-by-step guide:

#### [​](https://docs.carbon.ai/connectors/onedrive#prerequisites-2)Prerequisites <a href="#prerequisites-2" id="prerequisites-2"></a>

Before you begin, ensure you have:

* Gone through My AskAI's managed OAuth flow and submitted the admin consent request (see screenshot below):

<figure><img src="../../.gitbook/assets/image (542).png" alt="" width="375"><figcaption></figcaption></figure>

* An administrator role or designated reviewer role to review admin consent requests

#### [​](https://docs.carbon.ai/connectors/onedrive#approve-the-request)Approve the Request <a href="#approve-the-request" id="approve-the-request"></a>

1. Sign in to the Microsoft Entra admin center as at least a Cloud Application Administrator who is a designated reviewer.
2. Navigate to **Identity** > **Applications** > **Enterprise applications**.
3. Under **Activity**, select **Admin consent requests**.
4. Select the **My Pending** tab to view and act on the pending requests.
5. From the list, select the My AskAI application that is being requested.
6. Review the request details:
   * Select **Review permissions and consent** to see what permissions are being requested by My AskAI.
   * Select the **App details** tab to view the application details.
   * Select the **Requested by** tab to see who is requesting access and why.
7. **Approve the request** to grant admin consent to allow My AskAI to access your Microsoft application. All requestors will be notified that their request for access is granted. This allows all users in your tenant to access My AskAI unless otherwise restricted with user assignment.

#### Do You Have the Right Permissions?

If you are unable to consent to the approval request under **My Pending** because the admin consent flow has not been activated, then you will need **Global Administrator** permissions. Once you are a **Global Administrator**, you can set up the admin consent flow or consent directly via My AskAI's managed OAuth flow.

![](https://imagedelivery.net/_sHUUMiZokZ59YDFOZEZTw/d45b40bc-423a-4f77-3dc5-f93f2633fa00/public)

### Dropbox

To authorize your Dropbox connection, you just need to log into your Dropbox account when asked.

<figure><img src="../../.gitbook/assets/image (543).png" alt=""><figcaption></figcaption></figure>

### Intercom

{% hint style="warning" %}
Your Intercom help center must be published and turned on to use this feature
{% endhint %}

To authorize your Intercom connection, you just need to log in and authorize your Intercom account when asked.

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

### Zendesk

To authorize your Zendesk connection, you just need to provide the Zendesk sub-domain of the account you want to connect when asked, then log in with your Zendesk account details to approve.

<figure><img src="../../.gitbook/assets/image (323).png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

### Freshdesk

{% hint style="warning" %}
If you are unable to connect to Freshdesk, first check whether you have Admin permissions on your Freshdesk account as it will be needed to connect to your knowledgebase.

The role type you need to connect i&#x73;**`Account Administrator`**
{% endhint %}

To authorize your Freshdesk connection, you just need to provide the Freshdesk domain and API key you want to connect to when asked.

{% hint style="info" %}
When adding your Freshdesk domain, ensure it is your original Freshdesk domain e.g. yourdomain.freshdesk.com, not any custom domains you may now use.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (328).png" alt="" width="360"><figcaption></figcaption></figure>

To find your API key:

1. Log in to your Freshdesk Support Portal
2. Click on your profile picture on the top right corner of your portal

<figure><img src="../../.gitbook/assets/image (329).png" alt=""><figcaption></figcaption></figure>

3. Go to Profile settings Page

<figure><img src="../../.gitbook/assets/image (330).png" alt=""><figcaption></figcaption></figure>

4. Your API key will be available below the change password section to your right.

<figure><img src="../../.gitbook/assets/image (331).png" alt=""><figcaption></figcaption></figure>

For more information, please refer to [this solution article](https://docs.carbon.ai/connectors/'https://support.freshdesk.com/en/support/solutions/articles/215517') from Freshdesk.

### Notion

To authorize your Notion connection, you just need to log in and authorize your Notion account when asked and grant permission.

<figure><img src="../../.gitbook/assets/image (544).png" alt="" width="563"><figcaption></figcaption></figure>

### SharePoint

To authorize your SharePoint connection enter your SharePoint `tenant` and `site name`.&#x20;

For example, if the SharePoint site URL is: `https://mikemmyaskai.sharepoint.com/sites/myaskai-dev`

`mikemyaskai` is the tenant and `myaskai-dev` is the site name.

<figure><img src="../../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>

Log into your Microsoft SharePoint account.

<figure><img src="https://i.ibb.co/86FPknL/Screen-Shot-2023-08-31-at-4-41-48-PM.png" alt=""><figcaption></figcaption></figure>

Click the “Confirm” button to grant us permission to access your SharePoint.

<figure><img src="https://i.ibb.co/x6L7knS/Screen-Shot-2023-10-24-at-11-45-27-AM.png" alt=""><figcaption></figcaption></figure>

Once clicking “Confirm”, you will be taken through a flow to grant permissions.

<figure><img src="../../.gitbook/assets/image (548).png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
You may get a message like the below, if you are using a workplace Sharepoint, if so you will need to get your company admin to grant access to 3rd party apps in order to connect, you can [read more on user consent and permissions here](https://learn.microsoft.com/en-us/microsoft-365/admin/misc/user-consent?view=o365-worldwide).
{% endhint %}

{% hint style="info" %}
Note, the app approval request will be for My AskAI.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (547).png" alt="" width="375"><figcaption></figcaption></figure>

#### Approving the SharePoint admin request

1. Sign in to the Microsoft Entra admin center as at least a Cloud Application Administrator who is a designated reviewer.
2. Navigate to **Identity** > **Applications** > **Enterprise applications**.
3. Under **Activity**, select **Admin consent requests**.
4. Select the **My Pending** tab to view and act on the pending requests.
5. From the list, select the Carbon application that is being requested.
6. Review the request details:
   * Select **Review permissions and consent** to see what permissions are being requested by Carbon.
   * Select the **App details** tab to view the application details.
   * Select the **Requested by** tab to see who is requesting access and why.
7. **Approve the request** to grant admin consent to allow My AskAI to access your Microsoft application. All requestors will be notified that their request for access is granted. This allows all users in your tenant to access My AskAI unless otherwise restricted with user assignment.

{% hint style="info" %}
If you are unable to consent to the approval request under **My Pending** because the admin consent flow has not been activated, then you will need **Global Administrator** permissions. Once you are a **Global Administrator**, you can set up the admin consent flow or consent directly via Carbon’s managed OAuth flow.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (484).png" alt=""><figcaption></figcaption></figure>

### Confluence

To authorize your Confluence connection, you just need to provide the Confluence sub-domain of the workspace you want to connect to when asked, then log in with your Confluence account details to approve.

When you connect Confluence, the content that will be synced will be the same content that the user profile (used to authenticate with Confluence) has access to (i.e. all available content, you can't choose specific content to add).&#x20;

If you want to choose specific content to add from Confluence you can create a separate, specific account on Confluence that has access to certain 'spaces' to make sure that only certain content is synced.

For example, if the Confluence workspace URL is `https://myaskai.confluence.com`, then`myaskai` will be the subdomain.

<figure><img src="../../.gitbook/assets/image (326).png" alt="" width="301"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (546).png" alt=""><figcaption></figcaption></figure>

### Salesforce

{% hint style="info" %}
All `Published` articles under a single Salesforce knowledgebase will be synced. Any Draft article won’t be synced.
{% endhint %}

To authorize your Salesforce connection, you just need to provide the Salesforce domain of the account you want to connect to when asked, then log in with your Salesforce account details to approve.

For example, if the Salesforce account URL is `https://myaskai.my.salesforce.com`, then`myaskai` will be the domain.

<figure><img src="../../.gitbook/assets/image (364).png" alt="" width="242"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (546).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (545).png" alt=""><figcaption></figcaption></figure>
