---
description: >-
  Connect your AI support agent to your Freshchat workspace and existing
  Freshchat live chat widget (Conversations Widget) on your website.
---

# Freshchat

<figure><img src="../../.gitbook/assets/Freshchat.png" alt=""><figcaption></figcaption></figure>

You can now integrate your AI support agent directly into Freshchat for a seamless AI experience.

{% hint style="success" %}
The Freshchat integration is available on all paid plans, [see pricing](https://myaskai.com/pricing).
{% endhint %}

### What are the benefits of using My AskAI within Freshchat?

There are several reasons why you should use your My AskAI within Freshchat:

* You can add more knowledge to your AI agent in addition to your website and Freshdesk help center by using our [connections](../connections/), live data or [file uploads](../file-uploads.md).
* You don't have to add any code to your site to get your AI agent live, just connect our app and you're ready to go.
* As well as an AI agent, you get all our other features like [Improve,](../improve-+-custom-answers/) [Insights](../insights/), [Email Assistant](../email-assistant.md), [Site Search](../site-search.md), [Private (Internal) mode](../private-internal-mode.md), [Integrations with Slack](./) and more.&#x20;
* While Freshchat has its own AI agent (called "FreddyAI"), it can be more expensive, up to twice the price of My AskAI per conversation (we also think ours is smarter, but we'll let you be the judge!)

### How to use your AI agent within Freshchat

{% embed url="https://youtu.be/m1YPYZcB8Jw?si=m21kOxmab9lumTTH" %}

### How to connect your AI agent to Freshchat

{% hint style="warning" %}
Ensure that you have turned off Freddy before completing these steps.
{% endhint %}

1. Login to your Dashboard and go to _**Channels**_.&#x20;
2. Once enabled you will see "Add to live chat apps" appear, click on the Freshchat icon.

<figure><img src="../../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

3. To connect your Freshchat account enter your API key and Chat URL. To find these in your Freshchat dashboard go to:\
   \
   &#xNAN;_**Admin Settings > Marketplace and Integrations > API Settings > API details for chat > "Your API key" OR "Your chat URL"**_\
   \
   Once you have both of these values, enter them into their respective fields and press the "**Connect your Freshchat account**" button.

<figure><img src="../../.gitbook/assets/image (56) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If you need to create an API key you can do so by [following the instructions here](https://support.freshchat.com/support/solutions/articles/50000000011).
{% endhint %}

4. When connected the button will change to say "**Freshchat account connected**".

<figure><img src="../../.gitbook/assets/image (57) (2).png" alt=""><figcaption></figcaption></figure>

4. You now need to create a new webhook, to do this in your Freshchat dashboard go to:\
   \
   &#xNAN;_**Admin Settings > Marketplace and Integrations > Conversation Webhooks**_\
   \
   Then toggle the webhook from Disabled to **Enabled.**

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 153818.png" alt=""><figcaption></figcaption></figure>

5. Once enabled, copy the webhook address from My AskAI and paste it into Freshchat's webhook field, then enter your email for failure notification alerts and click save.\
   \
   Webhook address: [https://myaskai.com/api/1.1/wf/freshchat-webhook](https://myaskai.com/api/1.1/wf/freshchat-webhook)

<figure><img src="../../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You do not need to do anything with the authentication header key
{% endhint %}

6. To confirm the webhook has been set up correctly, send a test message to your Freshchat widget.

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-13 141002.png" alt=""><figcaption></figcaption></figure>

7. This message will be confirmed as received when you see the _"Webhook successfully setup"_ message appear in your My AskAI setup page.

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-13 141032.png" alt=""><figcaption></figcaption></figure>

7. Your AI agent is now connected to Freshchat and will be [providing "note" responses](freshchat.md#how-to-draft-ai-conversational-replies-to-users-without-sending-them) (not directly to customers).

### How can I use my AI support agent within Freshchat?

There are 3 ways you can use your AI agent within Freshchat:

1. [_As a full conversational AI agent_](freshchat.md#how-to-set-up-an-ai-powered-chatbot-within-intercom-fully-conversational-support)_._
2. [To provide "Note" replies to all messages.](freshchat.md#how-to-draft-ai-conversational-replies-to-users-without-sending-them-in-freshchat)
3. [_As a co-pilot for your human agents to help them improve their efficiency_](chrome-extension.md)_._

### How to set up an AI-powered support agent within Freshchat (Fully conversational support)

1. [Connect your AI agent to Freshchat](freshchat.md#how-to-connect-your-ai-chatbot-to-intercom)
2. Toggle conversational replies "on" by going to your Dashboard then _**Channels > Freshchat**_ clicking the "Reply directly to customers" button.

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-13 144037.png" alt=""><figcaption></figcaption></figure>

3. That's it! Your Freshchat will now automatically respond to user queries using your AI agent's knowledge.

{% hint style="info" %}
New conversations start (and are transferred back to the AI agent) after:

_A conversation is resolved AND the “threading interval” has passed (which can be customised per Topic)_

<img src="../../.gitbook/assets/image (55) (1).png" alt="" data-size="original">
{% endhint %}

### How to draft AI conversational replies to users, without sending them in Freshchat

You can set the agent to automatically create AI note responses for you to use instead of replying directly to the user, to do this:

<figure><img src="../../.gitbook/assets/image (481).png" alt=""><figcaption></figcaption></figure>

1. [Connect your AI support agent to Freshchat](freshchat.md#how-to-connect-your-ai-chatbot-to-intercom)
2. Toggle note replies "on" by going to your Dashboard then _Channels > Freshchat_ clicking the "Reply with 'notes' for admins" toggle.

<figure><img src="../../.gitbook/assets/image (482).png" alt=""><figcaption></figcaption></figure>

3. That's it, now when someone talks with your Freshchat you will see the AI response appear as a note you can use to help with your reply.

### How does human handover work when using the Freshchat integration?

If, at any time, the user wishes to be passed over to a person to continue the conversation, all they need to do is say so, saying "Talk to a person" (or similar words to that effect).

Once the conversation is passed over to the human, the AI will not respond again until the agent hands back control to the AI.

When the AI agent cannot answer a question, it will also prompt the user to type "Talk to a person" to make it obvious they can speak to a person.

As part of the handover, the AI agent will summarize the conversation so the agent can pick up where the user left off so there is no repetition or frustration.

### How can I take control from or give control to the AI agent in Freshchat?

You can give control or take back control from the AI at any time, here's how:

#### To take control of a conversation

Just reply to any open conversation as an admin/agent and the conversation's control will be taken from the AI agent.

### How can I add my agent as part of a triaged chatbot in Freshchat?

1. [Connect your agent to Freshchat](freshchat.md#how-to-connect-your-ai-chatbot-to-intercom)
2. Turn on the toggle switch for Chatbot/Triage settings

<figure><img src="../../.gitbook/assets/image (8) (1).png" alt="" width="540"><figcaption></figcaption></figure>

3. Decide on a trigger phrase to use for your AI chatbot handover button, type it into the field below the toggle switch and include this as the text in a button in your chatbot (example chatbot flow below for "Speak to AI" as the trigger phrase).

{% hint style="danger" %}
This phrase must _**exactly**_ match the pre-defined button you are going to use in your chatbot message.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (52) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (53) (1).png" alt=""><figcaption></figcaption></figure>

4. Ensure you end the AI chatbot with "Make available for assignment".

<figure><img src="../../.gitbook/assets/image (54) (1).png" alt=""><figcaption></figcaption></figure>

5. Your AI agent will now only begin responding after the "Speak to AI" button has been pressed.

### How can I stop the AI agent from replying to specific phrases in Freshchat?

To stop your AI agent from replying to a specific set of phrases in Freshchat, [share with us a list of the phrases you would like to block via email](mailto:team@myaskai.com) and we will update your bot with these.

(Available on Pro accounts and above).

### How do I auto-close a ticket in Freshchat after a set amount of time?

You can auto-close tickets in Freshchat (that have not been transferred to a person) after a certain time period without a response to an AI agent's response by:

1. Going to **Channels > Add to live chat apps** and click on the Freshchat icon
2. In the pop-up, scroll to "Use inactivity auto-close settings" and toggle "Automatically close a conversations" to the On position

<figure><img src="../../.gitbook/assets/image (102).png" alt="" width="474"><figcaption></figcaption></figure>

3. Set the amount of time you want the ticket to close after (by default this is 60 mins)
4. (Optional) You can also set a message to send automatically when the ticket closes notifying the user the ticket will be closed.
5. These changes will go live immediately.

### Will the AI agent use responses to questions the customer has given as part of my chatbot?

Yes, your AI agent will use responses given by customers to chatbot questions as context for its responses.

This is a great way to improve the accuracy of your AI agent's responses and ensure a better user experience.

### Can I stop people speaking to a person on their first message on Freshchat?

You can prevent "instant" human handover on the 1st message in a conversation on Freshchat by navigating to **Channels > Freshchat** and then toggling the "_Ask for more information before handover_" feature.

<figure><img src="../../.gitbook/assets/image (69).png" alt="" width="563"><figcaption></figcaption></figure>

This option is on by default.

When a user tries to handover immediately they will be asked to provide more information first. On any subsequent messages, they can initiate a handover to an agent.

### How can I add my Freshchat AI agent to other services, like WhatsApp, Instagram, Facebook Messenger, or SMS?

You can use the Freshchat integration to use your AI agent directly within:

* WhatsApp
* Instagram DMs
* Facebook Messenger
* SMS

It will retain all the [same features of the Freshchat agent](freshchat.md#how-can-i-use-my-ai-chatbot-within-intercom), including human handover, but within the respective platforms.

### Which Freshchat plan do I need to be on to use My AskAI?

You can use the My AskAI Freshchat integration as long as you are on a Freshchat Pro plan or above.

### How can I pause or temporarily turn off AI replies or notes in Freshchat?

To pause or temporarily pause AI replies or notes in Freshchat go to **Channels > Freshchat** then scroll to the toggle for "Pause AI agent".

<figure><img src="../../.gitbook/assets/image (60) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

When you are ready to turn it back on, just toggle the Pause button once more and it will start responding again.
