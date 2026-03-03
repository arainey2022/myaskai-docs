---
description: >-
  Collect any data on customers and user at the point of escalation - emails,
  phone numbers, bug details and more.
---

# 📧 Escalation data collection (emails)

### What is escalation/handover data collection?

Escalation/handover data collection is set up as a [Task](tasks/) and means that if and when a customer or user has their chat/conversation or ticket [escalated/handed over to a human member](human-escalation.md) of your team it will collect details from them while doing so.

This means you can ensure you collect details that will help you to resolve the ticket faster when you get to it.

It could be an email address, a name, a phone number, bug details, whatever you need.

And best of all, it doesn't show a form to the user, it asks them naturally, in conversation, just like a person would.

### How do I set up escalation/handover data collection?

To set up an escalation/handover data collection task, just [create a task](tasks/) as you usually would

1. Give it a descriptive name and description, e.g.:\
   \
   **Name**: Pre-Escalation User Info Collection\
   \
   **Description:** Collect the customer's email and phone number before passing them on or ending the interaction.
2. Turn the toggle on for "Run task on every escalation / handover (live chat only)\
   \
   ![](<../.gitbook/assets/image (549).png>)<br>
3. Describe the steps you want the AI agent to go through and the data you want it to collect and what format it will be in.

### Does it happen on every escalation/handover?

If you have created an escalation data collection task and enabled it, then it will run on every handover/escalation.

### Does it work for any helpdesk?

The escalation/handover data collection task works on all helpdesk integrations.

### What happens with the data once it has been collected?

Once the data is collected by the AI agent, it will reside in the conversation or ticket history but will only be added to any meta data or other fields if you create an integration to allow this, e.g. an [API tool](ai-actions-tools.md) that posts the collected data somewhere.

One exception is with [Zendesk Messaging](channels/zendesk/zendesk-messaging.md) where there is a native escalation data collection integration already which you can enable by clicking "Use both verified and unverified emails" in the Zendesk Messaging settings in Zendesk (accessible via the Admin panel and going to **Messaging > Messaging Settings**).

<figure><img src="../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure>
