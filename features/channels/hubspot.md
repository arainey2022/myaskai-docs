---
description: >-
  Connect your AI support agent to your HubSpot account and existing HubSpot
  live chat widget on your website.
---

# HubSpot

<figure><img src="../../.gitbook/assets/Frame 11.png" alt=""><figcaption></figcaption></figure>

You can now integrate your AI support agent directly into HubSpot for a seamless AI experience.

{% hint style="success" %}
The HubSpot integration is available on all paid plans, [see pricing](https://myaskai.com/pricing).
{% endhint %}

### What are the benefits of using My AskAI within HubSpot?

There are several reasons why you should use your My AskAI within HubSpot:

* While HubSpot has its own AI agent (called "Breeze or BreezeAI"), it is basic in its functionality (we also think ours is smarter, but we'll let you be the judge!)
* You can add more knowledge to your AI agent in addition to your website and HubSpot help center by using our [connections](../connections/), live data or [file uploads](../file-uploads.md).
* You don't have to add any code to your site to get your agent live, just connect our app and you're ready to go.
* Every AI answer is provided with "References" to the sources used to answer the question.
* As well as an AI agent, you get all our other features like [Improve](../improve/), [Insights](../insights/), [Email Assistant](../email-assistant.md), [Site Search](../site-search.md), [Private (Internal) mode](../private-internal-mode.md), [Integrations with Slack](./) and more.&#x20;

### How to use your AI agent within HubSpot

{% embed url="https://youtu.be/i4MkELHiCqE" %}

### How to connect your AI agent to HubSpot

{% hint style="warning" %}
You must be a **Super Admin** to install an app in a HubSpot account, however the AI agent app doesn't get Super Admin rights.

The only scopes or permissions the app obtains are:

conversations.read

conversations.write
{% endhint %}

1. Login to your Dashboard and go to _Channels_.&#x20;
2. Once enabled you will see "Live Chat apps" appear, click on the HubSpot icon.

<figure><img src="../../.gitbook/assets/image (453).png" alt=""><figcaption></figcaption></figure>

3. Then click the "Connect your HubSpot account" button.

{% hint style="info" %}
Messages from your AI agent will be sent from the account/user that is used to login to HubSpot and connect with My AskAI. e.g. AI responses will appear to come from an agent.\


You can create a separate account for this if you’d like to customise the name or image of the AI agent.
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-04-18 at 10.13.10.png" alt=""><figcaption></figcaption></figure>

4. If you're not logged into HubSpot, this will open an authorizations/permissions screen. Click "Sign in to your HubSpot account".
5. Select your HubSpot account and click "Choose Account", you'll then be asked to confirm the connection and be redirected back to My AskAI.

<figure><img src="../../.gitbook/assets/Screenshot 2024-04-18 at 10.16.07.png" alt="" width="563"><figcaption></figcaption></figure>

6. Your My AskAI is now connected to HubSpot and will be [providing "note" responses](hubspot.md#how-to-enable-draft-ai-support-replies-for-agent-within-hubspot), that only agents can see. You can [set the AI agent to reply directly to customers](hubspot.md#how-to-set-up-and-activate-the-fully-automated-ai-support-agent).

### How can I use my AI support agent within HubSpot?

There are 2 ways you can use your AI support agent within HubSpot:

1. [_Fully automated AI support agent_](hubspot.md#how-to-set-up-and-activate-the-fully-automated-ai-support-agent)
2. Default: [_Agent tool to automatically draft responses as notes (ready to send or edit)_](hubspot.md#how-to-enable-draft-ai-support-replies-for-agent-within-hubspot)

#### How to set up and activate the fully automated AI support agent

1. [Connect your AI support agent to HubSpot](hubspot.md#how-to-connect-your-ai-chatbot-to-hubspot)
2. Toggle conversational replies "on" by going to your Dashboard then _Channels > HubSpot_ clicking the "Reply directly to customers" toggle.

<figure><img src="../../.gitbook/assets/image (392).png" alt=""><figcaption></figcaption></figure>

3.  _(Highly Recommended - but optional)_ - Disable your “Knowledge base search” within any “Chatflows”\


    <figure><img src="../../.gitbook/assets/image (400).png" alt=""><figcaption></figcaption></figure>
4.  _(Recommended - but optional)_ - Change your chat to show as "available 24/7" and don't show "Typical reply time", you can get to this from: _Conversations (drop down) > Inbox > Inbox Settings > Channels: Chat > ‘Edit’_\


    <figure><img src="../../.gitbook/assets/image (401).png" alt=""><figcaption></figcaption></figure>
5. That's it! Your Hubspot live chat will now automatically respond to user queries using your AI agent's knowledge.

<figure><img src="../../.gitbook/assets/image (393).png" alt="" width="434"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (111).png" alt="" width="375"><figcaption></figcaption></figure>

#### How to enable draft AI support replies for agent within HubSpot

You can set the AI agent to automatically create AI note responses for your agents to use instead of replying directly to the user.

<figure><img src="../../.gitbook/assets/image (395).png" alt="" width="451"><figcaption></figcaption></figure>

1. [Connect your AI support agent to Hubspot](hubspot.md#how-to-connect-your-ai-chatbot-to-hubspot)
2. Toggle note replies "on" by going to your Dashboard then _Channels > Hubspot_ clicking the "Reply with 'notes' for admins" toggle.

<figure><img src="../../.gitbook/assets/image (394).png" alt=""><figcaption></figcaption></figure>

3. That's it, now when someone talks with your HubSpot you will see the AI response appear as a note you can use to help with your reply.

### How can I stop draft notes from being generated for a conversation in HubSpot?

To stop draft notes from being generated for a conversation, just add a comment to the conversation with:

_`Stop writing AI notes`_

{% hint style="warning" %}
This must be written as a 'Comment' and not a 'Reply', otherwise the customer will see this.
{% endhint %}

You can create this as a Snippet in HubSpot

<figure><img src="../../.gitbook/assets/image (399).png" alt="" width="375"><figcaption></figcaption></figure>

### How does human handover work when using the HubSpot integration?

If, at any time, the user wishes to be passed over to a person to continue the conversation, all they need to do is say so, saying "Talk to a person" (or similar words to that effect).

Once the conversation is passed over to the human, the AI will not respond again until the agent hands back control to the AI or the ticket is closed.

When the AI agent cannot answer a question, it will also prompt the user to type "Talk to a person" to make it obvious they can speak to a person.

As part of the handover, the chatbot will summarize the conversation so the agent can pick up where the user left off so there is no repetition or frustration.

In the HubSpot inbox you will be shown this note at the point of handover, saying that the User requested to speak to a person:

<figure><img src="../../.gitbook/assets/image (10) (1).png" alt="" width="563"><figcaption></figcaption></figure>

### How can I take control from the AI support agent in HubSpot?

You can give control or take back control from the AI at any time, here's how:

#### To take control of a conversation

To stop the AI responding to a conversation in HubSpot, just add a note to the conversation with:

_`"Stop AI replies"`_

The AI will then stop responding.

### How can I add my support agent as part of a triaged chatflow in HubSpot?

1. [Connect your support agent to HubSpot](hubspot.md#how-to-connect-your-ai-chatbot-to-hubspot)
2. Turn on the toggle switch for chatflow/Triage settings

<figure><img src="../../.gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>

3. Decide on a trigger phrase to use for your AI chatflow handover button, type it into the field below the toggle switch and include this as the text in a button in your chatflow (example chatflow for "Chat with AI assistant" as the trigger phrase)

{% hint style="danger" %}
This phrase must exactly match the pre-defined button you are going to use in your chatflow message.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (3).png" alt="" width="563"><figcaption></figcaption></figure>

4. After creating the chatflow button in HubSpot, add a "Reply" action with a message such as "What is your question?" (can be anything).

<figure><img src="../../.gitbook/assets/image (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

5. "Disable open responses" in your initial welcome message chatflow.
6. Your AI assistant will now only begin responding after the AI chat button has been pressed.

### How can I stop the AI agent from replying to a specific phrase in HubSpot?

To stop your AI agent from replying to a specific set of phrases, share with us a list of the phrases you would like to block via chat and we will update your bot with these.

(Available on Pro accounts and above).

### Will the AI agent reply to messages in other HubSpot channels e.g. Facebook, WhatsApp or via email?

By default your AI agent in HubSpot will reply to messages sent to all channels in your HubSpot.

However, you can also select for it to only reply to specific channels, this could be:

* Live Chat
* Facebook Messenger
* Email
* WhatsApp
* SMS or&#x20;
* Customer Portal Thread

To update the channels your AI agent responds to, go to _**Dashboard > Channels > HubSpot**_ and then select your active channels under "**Activate & configure your AI agent".**

<figure><img src="../../.gitbook/assets/image (9) (1).png" alt="" width="563"><figcaption></figcaption></figure>

### How can I pause or temporarily turn off AI replies or notes in HubSpot?

To pause or temporarily pause AI replies or notes in HubSpot go to **Channels > HubSpot** then scroll to the toggle for "Pause AI agent".

<figure><img src="../../.gitbook/assets/image (60) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

When you are ready to turn it back on, just toggle the Pause button once more and it will start responding again.

### Can I turn off the "Just thinking..." or "Just having a think..." messages in HubSpot?

Yes you can turn off the "Just thinking" or "Just having a think" messages.

Just go to **Channels > HubSpot > Other Settings** and toggle the "Hide the "just thinking" message to off.
