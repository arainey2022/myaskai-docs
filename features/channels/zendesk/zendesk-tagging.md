---
description: >-
  Automatically tag your tickets and conversations in Zendesk with custom tags
  and sentiment scores.
---

# Zendesk (Tagging)

It can take hours of repetitive work to tag and categorize your support tickets and conversations each month.

But now your AI agent can automatically do this classification and categorization for you, directly in Zendesk, accurately and consistently, so you can focus on understanding what your customers are asking and how they are feeling.

You can find the tagging app in the [Zendesk Marketplace here](https://www.zendesk.co.uk/marketplace/apps/support/1083190/ai-ticket-tagging-by-my-askai/?queryID=5d9bd561d9462ed0f8f61a97e5aebaed).

<figure><img src="../../../.gitbook/assets/tags (1).png" alt=""><figcaption></figcaption></figure>

### How do I set up automated tagging and sentiment scores in Zendesk?

1. To set up your tags in Zendesk, go to **AI Agent Setup > Auto-Tagging** and click **Add custom field or tags.**

<figure><img src="../../../.gitbook/assets/image (3) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

2. Select whether you want to auto-tag a **Custom Field** or a **Tag**

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

3. If you chose a Custom Field and have one setup in Zendesk already, then we will automatically import your Custom Fields to choose from. Select the one you want to auto-tag and we will import all of your tags for that Custom Field and auto generate a description for each tag.\
   \
   If you chose a Custom Field and don't have one setup in Zendesk already or you chose Tag then you will need to add a list of values/tags and descriptions for those values/tags so the AI knows under which circumstances each value/tag should be applied.\


<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4. Once you have reviewed the descriptions for each tag and checked they are correct then you can turn on the auto-tagging.

<figure><img src="../../../.gitbook/assets/image (3) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

5. You will then see your tags auto-applied in Zendesk, additionally the tag `ai-agent-tags-applied` will be applied so you know when it has been used.\
   If you feel any tags have been applied incorrectly, review the description for each tag to ensure it is clear.

<figure><img src="../../../.gitbook/assets/image (9).png" alt="" width="563"><figcaption></figcaption></figure>

### **Ho**w much does it cost to automatically tag and get a sentiment score for each ticket or conversation?

It costs $0.05 for each tag or custom field per ticket, this will be an add-on to your existing subscription and charged at the end of each billing period.&#x20;

For example, if you were to have 3 tags applied to a ticket, this would cost $0.15 for tags on that ticket, if just one custom fields needs populating it will be just $0.05 for that ticket.

### What tagging or categories can I use for my Zendesk tickets and conversations?

You can use your own custom tagging, categories, reason codes or groupings when tagging your Zendesk tickets or conversations.&#x20;

The tagging will be captured in up to 3 Zendesk custom fields you define, for each conversation or ticket, or within the ‘Tags’ field if you don’t use custom fields.

### What reporting do I have for my tags and sentiment?

You can use Zendesk Explore to interrogate and report on your tags and sentiment scores to see which and how they are changing over time.&#x20;

### How many tags can I apply to my Zendesk tickets or conversations?

We would recommend using fewer than 200 tags.

### What if I update my tags in Zendesk?

Your Auto-Tagging isn't automatically kept in sync in Zendesk, so if you add or remove a field or tag in Zendesk, you will have to do the same in My AskAI and vice versa.

<figure><img src="../../../.gitbook/assets/image (4) (1).png" alt="" width="563"><figcaption></figcaption></figure>

### How can I ensure the AI agent only responds to certain types of Zendesk tickets?

If you are using Zendesk Tickets you can use our Ticket tagging product to tell the AI agent which tickets it should respond to.

For example, you might have "reason for contact" field in Zendesk that your agents update today, and there might be 10 category options within that.

If "unsubscribe" was the tag added by our AI agent, and that tag was on your block list, then the AI wouldn't reply to it and it will force a human handover.

To add a tag to your block list, go to **AI Agent Setup > Auto-Tagging**, select the Custom Field or Tag that has the tag you want to block, then find the tag and click **Block AI Replies.**

If a ticket isn't replied to because it was blocked the tag `ai-agent-tag-blocked` will also be added to the ticket.

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Alternatively, you could set up a triage flow for your AI agent, using rules or triggers within Zendesk for where certain tickets should be routed depending on the "reason for contact".

{% hint style="info" %}
You can keep receiving AI note replies, even for blocked AI replies, if you want to see how your AI agent would have responded to the ticket.
{% endhint %}

### Why aren't my tags being applied to pre-existing fields?

If your tags aren't being applied to pre-existing fields it may be because your custom tagging fields don't match.

If you are using a custom field with pre-set values in Zendesk, you must ensure you use the Tag from within Zendesk exactly.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-01-23 at 15.19.26.png" alt="" width="563"><figcaption></figcaption></figure>

### How do I pause or turn off my Zendesk Auto-Tagging?

To turn off or pause your Auto-Tagging, go to **AI Agent Setup > Auto-Tagging** and scroll to **Pause tagging**, then toggle the switch to the 'paused' position.

<figure><img src="../../../.gitbook/assets/image (8).png" alt="" width="563"><figcaption></figcaption></figure>
