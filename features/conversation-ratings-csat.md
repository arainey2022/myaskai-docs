---
description: >-
  You can find out what your customers think of your AI agent by turning on
  Conversation ratings (CSAT), so you can see where you might need to improve
  your agent's responses.
---

# 👍 Conversation ratings (CSAT)

{% hint style="success" %}
Available on paid plans.
{% endhint %}

{% hint style="warning" %}
This CSAT feature is only available in the My AskAI widget, if you are using our [Intercom](channels/intercom/), [Zendesk](channels/zendesk/zendesk-messaging.md) or [HubSpot](channels/hubspot.md) integrations you will have to set up CSAT recording within the respective platforms.
{% endhint %}

<figure><img src="../.gitbook/assets/image (117).png" alt=""><figcaption></figcaption></figure>

### Why should I use conversation ratings?

Conversation ratings are a great way to find out what your customers and visitors think of your AI agent and whether or not it is helping them.

Getting feedback on its responses is also a good way to find out where your AI agent may be [lacking knowledge (missing documentation)](connections/) or where you may need to [correct a response](improve-+-custom-answers.md).

Note that, as with any rating system, responses are usually biased to the negative ends of the spectrum when it comes to customer support, think of it as a feedback mechanism for your support team.

### What is a CSAT score?

CSAT is short for a "Customer Satisfaction" score.

It is calculated by dividing the total number of positive responses by the total number of overall responses.

Satisfaction is often recorded using a 3 or 5-point scale, in our case we use a 5-point emoji scale, like this:

<figure><img src="../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

If the user chooses either the 🙂 or the 😁 emojis then it is recorded as a positive response. 😐 is neutral and 😕 or 😫 are negative responses.

So the overall calculation of your CSAT score will be the number of times the 🙂 or 😁 emojis are selected, divided by the total number of scores collected.

### How do I turn on and use conversation ratings (CSAT)?

To turn on conversation ratings (CSAT), go to _AI agent setup > Human handover > Request customer satisfaction rating (CSAT)_ and toggle the "**Not requesting CSAT rating**" to "**Requesting CSAT** **rating**".&#x20;

Your agent will immediately start collecting responses from customers.

<figure><img src="../.gitbook/assets/image (462).png" alt=""><figcaption></figcaption></figure>

### How does a user rate a conversation?

After each question within a conversation OR at the point of [human handover](human-handover.md) the user will be presented with this " :thumbsup: **That helped**" button:

<figure><img src="../.gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>

Once they click this button they will be shown an emoji picker, they can then select the emoji that best demonstrates their feedback to submit.

<figure><img src="../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure>

The customer may change the emoji/score they have selected until the conversation [Insight](insights/) is generated (60 minutes after the conversation has ended).

{% hint style="info" %}
While you may provide CSAT responses as an admin/team member, these responses are not recorded towards your CSAT scores, only external (public) conversation scores are included.
{% endhint %}

### Where can I see the ratings?

There are a few places you can view the conversation ratings:

* As an overall score in your Insights dashboard

<figure><img src="../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

* If you look at a conversation within a specific topic (you will also see the overall topic CSAT score)

<figure><img src="../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

### What can I do to improve my CSAT score?

To improve your CSAT score there are a few things you can do:

1. Review your neutral and negative CSAT score conversations and topics to determine the context of the issues raised (checking that they are indeed issues you want to resolve or questions you want to answer).
2. Review the responses given by the agent in those conversations to determine what answer was given and whether there were any issues with the responses (incorrect responses or just that the AI didn't know the answer.
3. Decide whether you want to [add additional knowledge](connections/) to train your AI agent or you need a [custom answer](improve-+-custom-answers.md) to improve responses (also [read this on improving responses](../troubleshooting/why-cant-it-answer.md)).
4. If none, of these are applicable, please reach out to our chat and we will try and help.
