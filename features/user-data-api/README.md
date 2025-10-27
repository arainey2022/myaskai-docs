---
description: Looking to connect your AI agent to your back-end databases? Now you can
---

# 👤 User Data API

### Can I give my AI agent data on users?

Initially, your AI agent will be limited to answering questions based on the static knowledge you have provided to it.

However, you can give your AI agent additional background and context to answer user queries by connecting your back-end or user databases via API.

As a result, your AI agent will be able to understand who it is talking to and answer specific questions about their account e.g.&#x20;

* Where is my order?&#x20;
* When can I expect delivery?
* Do you have x in stock?

To set this up, we will provide you with a simple API schema that you will pass information about the user the AI is currently talking to.

Or, if you have a **Shopify store**, you can connect it using our [Shopify connector](../shopify.md).

To set this up, follow the instructions [here](user-data-api-setup.md).

### Is there a risk of user information being shared across users when using your User data API?&#x20;

No, there is no risk of user information being shared across users.

Because of the way our architecture is set up (using silos) there is no risk of "cross-talk" whereby a user asks a question and gets an answer from another user's data.

### Can I let my AI agent automatically take actions via API?

Yes, your AI agent can take API actions automatically, it will do this using a slightly different process, you can read more about it here: [AI Actions (Tools)](../ai-actions-tools.md).

If you are looking for your AI agent to automatically do things like:

* Refund orders
* Let users change their address
* Amend orders

All via API, to get this set up, contact our team via live chat by typing "Talk to a person".

### Which integrations can I use the User Data API with?

You can use the User Data API with the following integrations:

* **Zendesk Tickets** & **Zendesk Messaging**
* **Intercom**
* **Gorgias Tickets** (not Gorgias Live Chat)
* **HubSpot Email** & **HubSpot Live Chat**
* **Freshdesk** & **Freshchat**

The User Data API can only be used when there’s a **verified user** — for example, an email support ticket or an authenticated live chat user. Each live chat provider has its own way of authenticating logged-in users.

### Why can't I see "Connect live user data"?

If you can't see an option to "Connect live user data" in your Dashboard, it is likely because you are not using one of our supported integrations for live user data.

[Check your integration is supported](./#which-integrations-can-i-use-the-user-data-api-with) before contacting our live chat support as only some integrations are currently supported.

### How much does the User Data API cost?

There is no cost for using the User Data API, it's usage is included in all plans.
