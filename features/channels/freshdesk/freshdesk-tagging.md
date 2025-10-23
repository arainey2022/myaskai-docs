---
description: >-
  Automatically tag your tickets and emails in Freshdesk with custom tags and
  sentiment scores.
---

# Freshdesk (Tagging)

It can take hours of repetitive work to tag and categorize your support tickets and emails each month.

But now your AI agent can automatically do this classification and categorization for you, directly in Freshdesk, accurately and consistently, so you can focus on understanding what your customers are asking and how they are feeling.

### How do I set up automated tagging and sentiment scores in Freshdesk?

{% hint style="warning" %}
You can only set up Tagging for Freshchat **OR** Freshdesk, **not both**
{% endhint %}

1. To set up your tags in Freshdesk, go to **AI Agent Setup > Auto-Tagging** and click **Import tag or custom field.**

<figure><img src="../../../.gitbook/assets/image (488).png" alt="" width="563"><figcaption></figcaption></figure>

2. Select your tag or custom field from the dropdown list of options (imported from Freshdesk) and click "Import tag/custom field"

<figure><img src="../../../.gitbook/assets/image (491).png" alt="" width="563"><figcaption></figcaption></figure>

3. Once you have reviewed the descriptions for each tag or custom field and checked they are correct then you can turn on the auto-tagging.
4. You will then see your tags auto-applied in Freshdesk, additionally the tag `ai-agent-tags-applied` will be applied so you know when it has been used.\
   If you feel any tags have been applied incorrectly, review the description for each tag to ensure it is clear.

<figure><img src="../../../.gitbook/assets/image (492).png" alt="" width="563"><figcaption></figcaption></figure>

### **Ho**w much does it cost to automatically tag and get a sentiment score for each ticket or email?

It costs $0.05 for each tag or custom field per ticket, this will be an add-on to your existing subscription and charged at the end of each billing period.&#x20;

For example, if you were to have 3 tags/custom fields applied to a ticket, this would cost $0.15 for that ticket, if just one tag/custom field needs populating it will be just $0.05 for that ticket.

### What tagging or categories can I use for my Freshdesk emails and tickets?

You can use your own custom tagging, categories, reason codes or groupings when tagging your Freshdesk emails or tickets.&#x20;

The tagging will be captured in up to 3 Freshdesk custom fields or tags you define, for each email or ticket, or within the ‘Tags’ field if you don’t use custom fields.

### How can I ensure the AI agent only responds to certain types of Freshdesk tickets?

If you are using Freshdesk Tickets you can use our Ticket tagging product to tell the AI agent which tickets it should respond to.

For example, you might have "reason for contact" custom field in Freshdesk that your agents update today, and there might be 10 category options within that.

If "unsubscribe" was the tag added by our AI agent, and that tag was on your block list, then the AI wouldn't reply to it and it will force a human handover.

To add a tag to your block list, go to **AI Agent Setup > Auto-Tagging**, select the Custom Field or Tag that has the tag you want to block, then find the tag and click **Block AI Replies.**

If a ticket isn't replied to because it was blocked the tag `ai-agent-tag-blocked` will also be added to the ticket.

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Alternatively, you could set up a triage flow for your AI agent, using rules or automations within Freshdesk for where certain tickets should be routed depending on the "reason for contact".

### What reporting do I have for my tags and sentiment?

You can use Freshdesk's reporting to interrogate and report on your tags and sentiment scores to see which and how they are changing over time.&#x20;

### How many options can I apply for each tag or custom field to my Freshdesk emails or tickets?

We would recommend using fewer than 200 options for your tags or custom fields.

### What if I update my custom fields or tags in Freshdesk?

Your Auto-Tagging isn't automatically kept in sync in Freshdesk, so if you add or remove a field or tag in Freshdesk, you will have to do the same in My AskAI and vice versa (make sure the value name matches exactly).

Alternatively, you can just remove and re-add the tag or custom field in My AskAI for it to re-sync, although be aware that descriptions will be re-written (in case you have changed many of them).

<figure><img src="../../../.gitbook/assets/image (493).png" alt="" width="563"><figcaption></figcaption></figure>

### Why aren't my tags or custom fields being applied to tickets or emails?

If your tags aren't being applied to pre-existing fields it may be because your fields don't match.

If you are using a custom field with pre-set values in Freshdesk, you must ensure you use the custom field or tag name from within Freshdesk exactly.

### How do I pause or turn off my Freshdesk Auto-Tagging?

To turn off or pause your Auto-Tagging, go to **AI Agent Setup > Auto-Tagging** and scroll to **Pause tagging**, then toggle the switch to the 'paused' position.

<figure><img src="../../../.gitbook/assets/image (8).png" alt="" width="563"><figcaption></figcaption></figure>
