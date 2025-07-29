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

### How does human handover work?

Human handover works differently depending on whether you are using:

* One of our native live chat integrations:
  * Learn more about [Intercom](channels/intercom/#how-does-human-handover-work-when-using-the-intercom-messenger-integration) handover
  * Learn more about [Zendesk](channels/zendesk/) (messenger and tickets) handover
  * Learn more about [Freshchat](channels/freshchat.md) handover
  * Learn more about [Freshdesk](channels/freshdesk.md) handover
  * Learn more about [HubSpot](channels/hubspot.md) handover&#x20;
* [Our AI widget](human-handover.md#human-handover-with-the-my-askai-widget)

### Which live chat services do you support for human handover?

We currently support the following live chat services:

* [Intercom](channels/intercom/)
* LiveChat
* Tawk
* [Zendesk](channels/zendesk/) (Messenger and Tickets)
* Crisp
* [HubSpot](channels/hubspot.md)
* Zoho (SalesIQ)
* [Freshchat](channels/freshchat.md) by Freshworks
* [Freshdesk](channels/freshdesk.md)
* Tidio
* Email (also can be used so you can create a ticket in another system)
* Link (e.g. URL to your help docs or a contact form)

(If your live chat provider is missing, contact us via chat).

### What information is passed over with human handover?

The information passed over with human handover is dependent on the live chat widget used as different widgets have different parameters, you can see a full list below:

* Email handover = the email address can be passed into the live chat widget (if [email capture](lead-email-capture.md) is turned on)
* Conversation summary = the user will always be able to generate a summary of their conversation, it is just whether that summary can be automatically passed over to the widget or whether they will have to copy and paste the summary that is the distinction

<table><thead><tr><th width="188">Live chat provider</th><th width="174" data-type="checkbox">Human handover?</th><th width="161" data-type="checkbox">Email handover?</th><th>Conversation summary<select><option value="uWs7AgXNcdFm" label="Automated" color="blue"></option><option value="dT1X6MF4tSw9" label="Copy + Paste" color="blue"></option></select></th></tr></thead><tbody><tr><td>Intercom</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>LiveChat</td><td>true</td><td>true</td><td><span data-option="dT1X6MF4tSw9">Copy + Paste</span></td></tr><tr><td>Tawk</td><td>true</td><td>false</td><td><span data-option="dT1X6MF4tSw9">Copy + Paste</span></td></tr><tr><td>Zendesk (Messenger + Tickets)</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Crisp</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>HubSpot</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Zoho (SalesIQ)</td><td>true</td><td>false</td><td><span data-option="dT1X6MF4tSw9">Copy + Paste</span></td></tr><tr><td>Freshchat</td><td>true</td><td>false</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Freshdesk</td><td>true</td><td>false</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr><tr><td>Tidio</td><td>true</td><td>true</td><td><span data-option="uWs7AgXNcdFm">Automated</span></td></tr></tbody></table>

### Human handover with the My AskAI widget

{% embed url="https://www.loom.com/share/cdefb669fe0541f795d19c32fdaf4f51" %}

<figure><img src="../.gitbook/assets/image (458).png" alt=""><figcaption></figcaption></figure>

### When will it be handed over to a human?

You can decide when users should be able to talk to a person, either:

* All the time - a contact icon will be added to your chat widget's menu that is always visible, like the below and a "Talk to a person" button will be visible at the end of each message:

<figure><img src="../.gitbook/assets/image (210).png" alt="" width="415"><figcaption></figcaption></figure>

* Only after asking a question - the contact icon above the chat widget only becomes visible after the user has asked at least one question to the AI support agent.
* When the user asks to "talk to a person" (or uses similar wording)

In both scenarios, if the AI agent is unable to answer or if a user asked to talk to a person it will immediately give the user the option to talk to a person:

<figure><img src="../.gitbook/assets/image (211).png" alt="" width="374"><figcaption></figcaption></figure>

### How can I test human handover out?

Head over to Chat within your Dashboard and ask a few questions, then click the Contact icon in the widget menu or click the "Talk to a person" button.

### Can I change my human handover chat provider at a later date?

Yes, you can, just go to your Dashboard, then _**AI agent setup > Human handover**_ and click the _"change/remove"_ button beneath the chat icon of your current provider.

### **Custom endings for "I don't know" responses**

You have the option of adding your own custom ending each time the AI agent is unable to answer a question. This can allow you to direct users towards links, the "talk to a person" option, or something else.

To edit your Custom ending, just go to _AI Agent Setup > Human Handover > Advanced Settings._

