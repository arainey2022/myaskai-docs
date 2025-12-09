---
description: >-
  In addition to the visitor or customer facing mode of your AI agent, you can
  also have "Private" mode, that you can use for your team, trained on material
  that isn't public.
---

# 🔓 Private (Internal) mode

Your AI agent in the dashboard has 2 modes depending on how you want to use it:

* **Private + Public content** On: In this mode your AI agent will be able to answer questions from all available information uploaded to your AI agent as knowledge. It is also the mode used by your AI agent when using our Copilot Chrome Extension.
* **Private content** Of&#x66;**:** In this mode, your AI agent will only use knowledge and content designated as public to answer questions, this will replicate how your AI agent will reply directly to customers in tickets or chats.

{% hint style="info" %}
Note that toggling between these modes for the widget in the dashboard will not impact your content visibility or its use by the AI agent for end customers/users. \
\
If you want to make specific content available to the AI agent for end customers/users you will need to [update its visiblity](private-internal-mode.md#setting-visibility-on-files-and-connections).
{% endhint %}

### How to use your AI agent internally (Public v Private mode)

{% embed url="https://youtu.be/jMK6gYAaBZ0" %}

### Accessing public or public + private modes

There are a few ways you can access each mode:

#### **Chat**

When you log in to your Dashboard, on the Knowledge, Customization or Human Handover views you will see and be able to test your AI agent.

In the bottom left corner, you will see a toggle switch, which will allow you to change between "Public only" or "Public + Private" modes.

[Here is how you can invite another team member.](team-access.md)

#### Slack, Teams, Zapier, API

When using any of our integrations with [Slack](channels/slack.md), [Microsoft Teams](channels/microsoft-teams.md), [Zapier](channels/zapier.md) or the [API](/broken/pages/dNdFSSoUyqRI4TkfZFuY), responses will be given using the Public + Private mode, so your team can access answers on your complete knowledge base.

### Setting visibility on files and connections

{% hint style="info" %}
If you are asking a question on content you have uploaded but are not getting a response, the most common reason is that you have the content marked as private but you are asking questions in public mode.\
\
To fix this, either mark the content as public, or toggle the widget to public + private mode.
{% endhint %}

Each type of content added to your AI agent's knowledge base can be specified as "Public" or "Public + Private", except for the content added from your public site, which is always classed "Public".&#x20;

#### File uploads

By default, [files uploaded](private-internal-mode.md#file-uploads) to your AI agent are public.&#x20;

You can change this for each file:

1. Go to _**Knowledge > Content > Upload files**_
2. Click "**Manage**"
3. Click on the toggle switch next to the file you want to amend the privacy of

#### Connections

By default, files uploaded or pages added via connections to your AI chatbot are public.&#x20;

You can change this to Private either for all files at once:

1. Go to _**Knowledge > Content > Connect knowledge sources >**_**&#x20;Connected knowledge sources**
2. Click "**Manage**"
3. Click on "**Change visibility**"
4. Click "**Set x content to private/public"**
5. Each connected file or page will then be classified in your chosen setting, this may take a few minutes depending on the number of files or pages you have connected.

Or by specifying on an individual connected file or page:

1. Go to _**Knowledge > Content > Connect knowledge sources >**_**&#x20;Connected knowledge sources**
2. Click "**Manage**"
3. Click on the toggle switch next to the file you want to amend the privacy of
