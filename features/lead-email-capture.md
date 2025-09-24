---
description: >-
  Lead or email capture is a feature that allows your AI agent to capture the
  email addresses of anyone who uses it so you can follow up with them at a
  later date.
---

# 📩 Lead (Email) Capture

{% hint style="info" %}
The lead capture is available when using the My AskAI widget, if you are using one of our channels ([Intercom](channels/intercom/), [Zendesk](channels/zendesk/zendesk-messaging.md) or [HubSpot](channels/hubspot/)), you will use their respective lead capture features to collect email addresses.&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/image (332).png" alt=""><figcaption></figcaption></figure>

### What is lead or email capture?

Lead capture is an optional feature you can turn on for your AI agent that will force users to input an email address to have a conversation with your AI agent, you can use it to capture leads for your business or to prevent abuse of your agent.

Users will only be asked for their email once, it will be saved for future conversations.

### &#x20;How do I turn lead capture on or off?

To turn lead capture on or off, go to your _**Dashboard > AI agent setup > Lead capture**_ then toggle the "Email capture" switch on or off.

<figure><img src="../.gitbook/assets/image (444).png" alt=""><figcaption></figcaption></figure>

### Where can I see the leads the AI agent has collected?

There are 3 main ways you can see the leads your AI agent has collected, each method will provide you with the email address of the lead, a title of the topic they were talking about along with a summary of the conversation the lead had with your AI agent:

#### Export/Download all your leads as a CSV file

Go to _**Dashboard > AI agent setup > Lead capture > Export leads**_ and press the "Download all leads" button.

<figure><img src="../.gitbook/assets/image (445).png" alt=""><figcaption></figcaption></figure>

#### View your leads with their conversations in the Insights view

In your Insights view, with Lead capture turned on, you will see a new statistic showing you the number of leads captured in the last 30 days.

In addition to this if you click on any topic you will then see leads assigned to conversations where they have been collected, and, if you click into a conversation to view the details you will see the lead associated with that conversation too.

<figure><img src="../.gitbook/assets/image (467).png" alt=""><figcaption></figcaption></figure>

#### Receive new leads via a webhook

If you have set up a webhook, then you will receive a notification 60 minutes after your AI agent has collected a lead, the lead details will be sent wherever you have set the destination of the webhook.

### How do I create a webhook for lead capture?

To create a webhook for lead capture go to _**Dashboard > AI agent setup > Lead capture > Webhook settings**_ and then click the toggle to make your webhook "active".

Once activated you will need to set a destination for your webhook, for example, Zapier (if you want to create an email trigger for each lead captured).

Here is a tutorial showing you how to create your webhook and send leads to your email (or CRM) via Zapier:

{% embed url="https://youtu.be/mbc8iASV-Ek?si=DLOPlybvxdgv4NdE" %}

You can test that the webhook is set up correctly by pressing the "Test webhook" button, this will send an example dummy notification to your webhook's destination so you can see what the request will look like.

<figure><img src="../.gitbook/assets/image (468).png" alt=""><figcaption></figcaption></figure>

### How do I turn off lead capture for logged-in users?

By default, lead capture will be on for all users of your AI agent.&#x20;

You can however set a flag within the embed script tag to turn off lead capture for logged-in customers or users on certain pages you don't want to require email collection.

You will just need to add the flag **data-hide-lead-capture="true"** to your script on pages you want to turn lead capture off.

<figure><img src="../.gitbook/assets/image (338).png" alt=""><figcaption></figcaption></figure>
