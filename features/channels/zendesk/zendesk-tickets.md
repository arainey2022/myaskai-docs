---
description: >-
  Connect your AI customer service agent to your Zendesk account and existing
  Zendesk Tickets, to get AI responses to your support tickets
---

# Zendesk (Tickets)

You can now integrate your AI agent directly into Zendesk Tickets for a seamless AI support experience.

The Zendesk Ticket integration is available on all paid My AskAI plans, [see our pricing](https://myaskai.com/pricing).

### What are the benefits of using My AskAI within Zendesk Tickets?

There are several reasons why you should use your My AskAI within Zendesk Tickets:&#x20;

* You get access to an intelligent AI agent, directly within Zendesk Tickets that can automatically and instantly answer user or visitor queries, using your company knowledgebase.
* Your AI agent can respond either [directly](zendesk-tickets.md#direct-replies) to users, generate [Internal notes](zendesk-tickets.md#internal-notes) for you, or [generate AI responses on demand](zendesk-tickets.md#how-can-i-use-my-zendesk-ticket-ai-agent-to-reply-to-follow-up-tickets).
* You can add more knowledge to your AI agent in addition to your website and Zendesk help center by using our [connections](../../connections/) or [file uploads](../../file-uploads.md).
* You don't have to add any code to your site and you don't need a developer, [just connect your Zendesk account and you're ready to go](zendesk-tickets.md#how-to-connect-your-ai-chatbot-to-zendesk-messaging).
* AI answers provided with "References" to the sources used to answer the question.
* You can add your AI agent to [Zendesk's Messenger](zendesk-messaging.md) too.
* As well as an AI agent, you get all our other features like [Insights](../../insights/), [Private (Internal) mode](../../private-internal-mode.md), [Integrations with Slack](../) and more.&#x20;

### How to connect your AI agent to Zendesk Tickets

{% hint style="danger" %}
You must be an Admin in your Zendesk account to connect your AI agent to Zendesk
{% endhint %}

{% hint style="info" %}
Your AI agent can use one of your existing Zendesk ticket agent seats or you can create a new one, specifically for it.&#x20;
{% endhint %}

{% embed url="https://youtu.be/lnxOWzyiEKw" %}

1. Login to your Dashboard and go to _**Channels**_.&#x20;
2. In "Add to your existing support tools", click on the Zendesk icon.
3. Select 'Zendesk Tickets'
4. Enter your Zendesk sub-domain (you can find instructions on how to find your sub-domain [here](https://support.zendesk.com/hc/en-us/articles/4409381383578-Where-can-I-find-my-Zendesk-subdomain)) and click 'Connect your Zendesk account'.
5. Allow access to your Zendesk account

<figure><img src="../../../.gitbook/assets/image (524).png" alt="" width="375"><figcaption></figcaption></figure>

7. You'll then be shown a "Connecting to Zendesk" screen, which will take a few seconds, once connected you will be redirected back to My AskAI.
8. Once back at My AskAI, you can Configure how you want your AI agent to reply, by default it will create [Internal Note](zendesk-tickets.md#internal-notes) responses, but you can also enable [Direct replies](zendesk-tickets.md#direct-replies).&#x20;
9. You can now choose whether you want your AI agent to only reply to the 1st message in a ticket or to all messages in a ticket by selecting the relevant option.
10. You will now be generating AI replies to your tickets, test it out by emailing your Zendesk inbox. [You can also set it to reply to other channels (like web forms).](zendesk-tickets.md#what-will-my-zendesk-ticket-ai-agent-respond-to)

<figure><img src="../../../.gitbook/assets/image (530).png" alt="" width="563"><figcaption></figcaption></figure>

### What will my Zendesk Ticket AI agent respond to?

By default your Zendesk Ticket AI agent will respond to Email tickets that are "New" or "Open" (identified by a webhook trigger).

{% hint style="warning" %}
By default your AI agent won’t reply to tickets that are created by an agent. If you need to change this, please contact by asking to "Talk to a person".
{% endhint %}

If you want the Zendesk Ticket AI agent to respond to other channels, for example, a web form, then you will need to add a new trigger by either:

* Duplicating the "Trigger" in Zendesk (if you want a web form in addition to your email tickets)
* Editing the "Trigger" in Zendesk (if you only want it to respond to another channel, not email tickets)

{% hint style="warning" %}
Only change or update the Channel DO NOT edit any other trigger settings.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Untitled (34).png" alt="" width="563"><figcaption></figcaption></figure>

### How do I know what the Zendesk Ticket AI agent has replied to and what has been handed to a human agent?

When a ticket is replied to by your AI agent in Zendesk Tickets a tag `ai-agent-replied` is added to the ticket.

{% hint style="info" %}
If the ticket has been replied to in notes mode the tag will be `ai-agent-replied-note` instead.
{% endhint %}

When a ticket is replied to by a customer (if they need more help for instance) then the tag `human-handover-requested` is added to the ticket.&#x20;

This can be used to run a Trigger or Automation to re-assign a ticket to human agents.

<figure><img src="../../../.gitbook/assets/Untitled (36).png" alt="" width="304"><figcaption></figcaption></figure>

### Can I change the name and image of my Zendesk Ticket agent?&#x20;

You can customize the appearance of your AI agent by naming it and giving it a logo. This name and logo will appear within your Zendesk Ticket workspace and on replies to customers.

{% hint style="info" %}
You will need an Extra Zendesk agent seat available in your account in order for us to change/create this. &#x20;
{% endhint %}

### How can I use my AI support agent within Zendesk Tickets?

Once you've connected the My AskAI agent within your Zendesk Admin Centre, it will automatically start responding to user's questions with Internal Notes within the Zendesk Ticket responder by default.&#x20;

#### Internal Notes

For the first question of each ticket an Internal Note will be generated by the AI, you can then use this information to assist you in the composition of your response.

With each question, the links used to answer the question will be provided.

<figure><img src="../../../.gitbook/assets/image (529).png" alt="" width="563"><figcaption></figcaption></figure>

#### Direct Replies

Alternatively, you can have your Zendesk Tickets AI agent respond directly to customers by toggling to "Reply directly to customers" within your Zendesk Ticket setup settings in My AskAI.

By default, all messages of the ticket will be replied to, however you can change this by selecting "Reply to 1st message only".

<figure><img src="../../../.gitbook/assets/image (531).png" alt="" width="563"><figcaption></figcaption></figure>

Here it is in action:

{% embed url="https://youtu.be/gPhN5wP-ZtY" %}

{% hint style="warning" %}
If you’re using your AI agent to directly reply to users in Zendesk Tickets, we recommend you disable automatic email replies (for ticket creation acknowledgement), otherwise users will receive multiple emails.&#x20;

This can be done by deactivating the below Trigger.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Untitled (35).png" alt="" width="563"><figcaption></figcaption></figure>

### How does human escalation work when using the Zendesk Ticket integration?

When using in either [Direct reply](zendesk-tickets.md#direct-replies) or [Internal Note](zendesk-tickets.md#internal-notes) reply mode, by default your Zendesk Ticket AI agent will respond to all Ticket message sent to you. You can change this however by selecting "Reply to 1st message only".&#x20;

If you select "Reply to 1st message only" any further questions or responses will be handed over to you, as the agent, to address.

If however, you have selected for the AI to "Reply to all messages" then you can choose when you want the AI to hand over the conversation to your human agents, either select:

* "Cannot answer" - when it can't answer a question, instead of saying as such, it will automatically pass over to a person AND it will also escalate if a user requests to speak to a person.
* "Escalation request"- it will only escalate if the customer explicitly requests to speak to a human agent&#x20;

If you only have set your AI agent respond to the first Ticket message you can also continue using our AI agent responses for follow-up questions with our [AI drafting tool](../chrome-extension.md).&#x20;

### How can I control which Zendesk tickets the Zendesk AI agent replies to?

There are 3 ways you can control which tickets your AI agent can reply to:

1. Use the ["Block AI replies"](zendesk-tagging.md#how-can-i-ensure-the-ai-agent-only-responds-to-certain-types-of-tickets) feature as part of our AI tagging feature in Zendesk.&#x20;
2. Use "Handover & escalation" [Guidance](../../improve/guidance.md#handover-and-escalation).
3. Use Zendesk Triggers, this will give you the most control if you want to choose certain user groups the AI agent will reply to, or filter out certain subject lines.

### How can I filter my AI replies by using Zendesk Triggers?

1. Create a new ticket status: AI Agent

<figure><img src="../../../.gitbook/assets/image (69) (1).png" alt="" width="563"><figcaption></figcaption></figure>

2. Create a new trigger to assign AI agent-handled tickets to AI Agent status\
   \
   Trigger name: Assign AI Agent Ticket\
   \
   Tag values: `ai-agent-replied` & `human-handover-requested`

<figure><img src="../../../.gitbook/assets/image (70) (1).png" alt="" width="563"><figcaption></figcaption></figure>

3. Create a new trigger to assign escalation tickets back to Open status\
   \
   Trigger name: Assign AI Handover Ticket\
   \
   Tag value: `human-handover-requested`

<figure><img src="../../../.gitbook/assets/image (71) (1).png" alt="" width="563"><figcaption></figcaption></figure>

4. Create a new view for agents to see AI Agent assigned tickets\
   \
   These triggers (or order of triggers) may need to be adjusted to match your organisation's workflows and avoid any conflicts.

<figure><img src="../../../.gitbook/assets/image (72) (1).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (73) (2).png" alt="" width="563"><figcaption></figcaption></figure>

### Can I stop people speaking to a person on their first message on Zendesk Tickets?

You can prevent "instant" human escalation on the 1st message in a conversation on Zendesk Tickets by navigating to **Channels > Zendesk > Zendesk Tickets** and then toggling the "_Prevent immediate escalation_" feature.

This option is on by default.

When a user tries to escalate immediately they will be asked to provide more information first. On any subsequent messages, they can initiate an escalation to an agent.

### I have multiple brands, users or email accounts in Zendesk, can I have the AI agent only respond to one of them (or specific ones)?

Yes, you can set your AI agent up so it only responds to specific emails or brands in Zendesk.

By default your AI agent will reply to all inbound emails and chats.

But if you want it to reply to only certain email addresses or brands e.g. support@company.com and not vip-support@company.com  then you can edit the Trigger conditions and add the brands or email accounts you want it to reply to (e.g. support@company.com).&#x20;

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

This will ensure it only replies to these brand and accounts.

### How do I remove my Zendesk Ticket AI agent?

1. Login to your Dashboard and go to _Channels_.&#x20;
2. Go to the "Add to helpdesk" section and click on the Zendesk icon.
3. Select 'Zendesk Tickets'
4. Expand the "Connect" header and click "Disconnect" then confirm your deletion.

### Can I train it on my Zendesk Macros?

Yes, when you connect your Zendesk account to My AskAI, you can also import your Zendesk Macros as [Custom Answers](../../improve/#custom-answers) (where you can edit and manage them).

To do this, go to the **Knowledge** section of your **Dashboard** and click **"Import Macros"**.

### Can I delay my Zendesk email replies to make them seem more 'human'?

Yes, you can delay your Zendesk email replies to make them seem more human.

{% hint style="info" %}
Setting the delay will only be for the first reply in the chain.
{% endhint %}

Go to **Channels > Zendesk > Zendesk Tickets > First reply delay** and specify the number of minutes you want the AI agent to wait before sending the reply.

When the time period is up the response will then be sent.

### How do I change the Zendesk Tickets profile icon?

To change the Zendesk Tickets profile icon:

1. Go into your Dashboard
2. Click Channels > Zendesk > Zendesk Tickets
3. Scroll to where the icon section is
4. Click and update with your new icon

### How can I stop the AI agent replying in Zendesk Tickets?

To stop the AI agent replying in Zendesk tickets, just reply to the ticket yourself and the AI agent will automatically stop replying.

### How can I pause or temporarily turn off AI replies or notes in Zendesk Tickets?

To pause or temporarily pause AI replies or notes in Zendesk Tickets go to **Channels > Zendesk > Zendesk Tickets** then scroll to the toggle for "Pause AI agent".

When you are ready to turn it back on, just toggle the Pause button once more and it will start responding again.
