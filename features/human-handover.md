---
description: >-
  Human handover ensures customers can still talk to you when they need to. Best
  of all, we integrate with your existing live chat tools, so you won't have to
  learn to use a new one.
---

# 🤝 Human handover

Some customers and questions will still need a person to answer them, here's how you can ensure your customers are answered by one with your AI support agent.

### What is human handover?

Your AI agent is the 1st line of defence for customer queries, but sometimes customers may want or need to talk to a human.&#x20;

Human handover allows the customer or visitor to switch between talking with the AI and talking to a member of your support team.

Before any handover occurs, we use AI to summarize the conversation they have had so far, so the visitor doesn't have to repeat themselves and the support agent can instantly get up to speed with their issue, reducing resolution times.

{% hint style="info" %}
The user-generated handover summaries that are shown on a human handover summarizing the conversation so far cannot be turned off.&#x20;
{% endhint %}

### How does human handover work?

Human handover works slightly differently depending on which of our native chat integrations you are using:

* Learn more about [Intercom](channels/intercom/#how-does-human-handover-work-when-using-the-intercom-messenger-integration) handover
* Learn more about [Zendesk](channels/zendesk/) (messaging and tickets) handover
* Learn more about [Freshchat](channels/freshchat.md) handover
* Learn more about [Freshdesk](channels/freshdesk/) handover
* Learn more about [HubSpot](channels/hubspot/) handover&#x20;
* Learn more about [Gorgias](channels/gorgias.md#how-does-human-handover-work-when-using-the-gorgias-integration-for-email-tickets) handover

### Which live chat services do you support for human handover?

We currently support the following live chat services:

* [Intercom](channels/intercom/)
* [Zendesk](channels/zendesk/) (Messenger and Tickets)
* [HubSpot](channels/hubspot/)
* [Freshchat](channels/freshchat.md) by Freshworks
* [Freshdesk](channels/freshdesk/)
* [Gorgias](channels/gorgias.md)
* Link (e.g. URL to your help docs or a contact/ticketing form).

### What information is passed over with human handover?

The information passed over with human handover is dependent on the live chat widget used as different widgets have different parameters, you can see a full list below:

* Email handover = the email address can be passed into the live chat widget (if [email capture](lead-email-capture.md) is turned on)
* Conversation summary = the user will always be able to generate a summary of their conversation, it is just whether that summary can be automatically passed over to the widget or whether they will have to copy and paste the summary that is the distinction

<table><thead><tr><th width="188">Live chat provider</th><th width="174" data-type="checkbox">Human handover?</th><th width="161" data-type="checkbox">Email handover?</th><th>Conversation summary<select><option value="uWs7AgXNcdFm" label="Automated" color="blue"></option><option value="dT1X6MF4tSw9" label="Copy + Paste" color="blue"></option></select></th></tr></thead><tbody><tr><td>Intercom</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Zendesk (Messaging + Tickets)</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>HubSpot</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Freshchat</td><td>true</td><td>false</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Freshdesk</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Gorgias</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr></tbody></table>

### When will it be handed over to a human?

Our goal isn't to prevent customers and users from speaking to a person when they need to, just to help them in the most efficient way possible.

Therefore we have a number of ways they can still speak to a person if they need:

1. They can directly ask to "Speak to a person" - our AI agents auto-recognise the intent of the user asking to speak to a human in a variety of different ways and will handover the conversation or ticket.
2. They may be frustrated - if our AI agent hasn't been able to answer and senses the user is getting annoyed it will proactively hand the conversation or ticket over.&#x20;
3. When the AI can't answer a question (because it doesn't have the available information), it will offer for the user or customer to handover the conversation or ticket, either by instructing them to type "Talk to a person" or by showing a button for them to click to initiate the handover. If you are using one of our ticketing integrations you can also define auto-handover if the AI can't answer so the user or customer will never see an "I don't know" response.
4. You can define qualitative rules or scenarios for the AI to look out for to handover the conversation, using [guidance](improve/guidance.md#handover-and-escalation), e.g. "If the user contacts us about a safety issue, handover to a person"
5. If you are using one of our tagging integrations e.g. [Zendesk](channels/zendesk/zendesk-tagging.md) or [Intercom](channels/intercom/intercom-tagging.md), you can specify topics that you don't want your AI to answer on, and you want an instant handover to occur.

### How can I test human handover out?

Head over to Chat within your Dashboard and ask a few questions, ask something it won't be able to answer and it will show a "Talk to a person" button or ask to "Talk to a person" and you should see the handover initiated.

### Can I change my human handover chat provider at a later date?

Yes, you can, just go to your Dashboard, then _**Channels**_ and choose the provider you want to change to.

