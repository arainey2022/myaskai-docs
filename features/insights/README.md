---
description: >-
  Your AI support agent will analyse all conversations customers and visitors
  have with it to identify common topics, issue, bugs and feedback so you can
  use the data to build better products for users.
---

# 💡 Insights

What good is having hundreds or thousands of customer or user conversations if you can't quickly see what they are saying?

We wanted to make it easy to get deep insights into what your users are asking your AI agent, without you having to read through all the transcripts, manually tag things and generally do a lot of "busy work".

<figure><img src="../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### How to Use Your AI Support Agent's Insights

{% embed url="https://youtu.be/SjMDPjvvSrw?si=nMWCuAFtaMHZTFgt" %}

Here's how our Insights work:

### Conversations

A conversation is a chat that a user has had with an AI agent within a session, or 2.5 messages if you are using one of our integrations (i.e. with [Intercom](../channels/intercom/), [Zendesk](../channels/zendesk/zendesk-messaging.md) or [HubSpot](../channels/hubspot/)). Sessions are re-set after 1 hour. 1 conversation or chat can include multiple messages.

You can review and re-read conversations at any time by clicking on a topic and selecting the conversation you want to review.

A conversation is between a visitor and the AI support agent, there is not an allowance per visitor, only at your overall account level.

In the dashboard you will see a number of "Public conversations", these are conversations held with users and are the number of different conversation "[topics](./#topics)" that the conversations have been broken into.

{% hint style="info" %}
Any conversations held from the Dashboard or via the Slack or Teams integrations will not contribute to the Insights as they are classed as "Internal" or "Private" conversations.
{% endhint %}

In the bottom left of the Dashboard, you will see "Conversation credits", these may not match your "Public conversations" or tickets/conversations in your messaging platform for a few reasons:

* The Insights dashboard does not capture "[Internal/Private](../private-internal-mode.md)" conversations held
* Conversations via our [Integrations](../channels/) follow our API pricing, meaning that each question sent by a user counts as 0.4 "conversation credits", or, to put it another way, every 5 questions counts as 2 conversation credits.&#x20;

{% hint style="info" %}
We do not charge any conversation credits for "Quick replies" i.e. responses to messages like "Thanks", "Got it", "Sure" or telling a user about accepted question types.
{% endhint %}

### Topics

After each conversation has concluded with an AI agent we use AI to analyze it and break it down into "topics".

Topics are summaries of each issue identified or raised within the conversation, one conversation could contain multiple topics or just a single topic.

Each topic is given a title and description that summarises that topic, along with several tags that can help you quickly get up to speed.

You can dive into each topic by clicking the title, this will open up the detailed Insights page from which you can see all the associated conversations, and also a link to share the topic with a team member.

**Insight notifications**

When a topic reaches 3 conversations, a notification (email or Slack) is sent to the admin and all team members to notify them.&#x20;

[Learn more about setting up insight notifications](conversation-insight-notifications.md).

#### Top topic

Your Top topic is the topic that has the most conversations related to it.

#### Topic visibility

All topics are shown until a topic reaches 3 conversations, at which point only topics with more than 3 conversations will be displayed.&#x20;

You can view all topics with any number of conversations by clicking _"view all"_ at the top of the Topics table.

#### Categories

Each topic will also be categorized into either a:

* Question
* Bug
* Feedback

This is so you can quickly find and filter on topics of interest to you, questions may require documentation, bugs may require passing to an IT team and feedback to a product team.

### Status

When a topic is created it is automatically designated the status "Open", you can see this by clicking on the title of each topic in the Dashboard.

If you click on the Open status you can change the status to either "Mark as done :white\_check\_mark:" or "Mute & Hide :no\_bell:", here's what they each mean:

* _Mark as done_ :white\_check\_mark: = Mark as done to permanently close this insight/issue. For new similar conversations, a new insight/issue will be created. Anything marked as "Done" will disappear from your Dashboard. To re-open, you can select _"View all"_ on the topic list, find the closed topic, then change the status.
* _Mute & Hide_ :no\_bell: _=_ Mute and hide this insight/issue from your dashboard. New similar conversations will continue to be added to this insight/issue. Anything "Muted" will disappear from your Dashboard. To unmute you can select _"View all"_ on the topic list, find the closed topic, then change the status.

### AI resolved

This is a flag showing whether the user requested to "Talk to a person" from the conversation. If they didn't then the conversation is marked as being "Resolved by AI".&#x20;

The AI resolved % is then calculated as the number of conversations resolved by AI / total number of conversations.

If you have our [Email assistant](../email-assistant.md) enabled, then you will see separate AI-resolved rates for your AI agent and your email assistant.

<figure><img src="../../.gitbook/assets/Untitled (28).png" alt="" width="375"><figcaption></figcaption></figure>

### CSAT rating

If you have the [CSAT rating](./#csat-rating) feature turned on then in your Dashboard you will see your overall CSAT rating across conversations in that period.

<figure><img src="../../.gitbook/assets/image (104).png" alt="" width="224"><figcaption></figcaption></figure>

### AI CSAT

We’ve trained a specialized AI model to give every single conversation and ticket a CSAT score.

This means you get an AI CSAT score for 100% of conversations (instead of the usual 2-10%) to give you a much more accurate representation of your AI agent’s performance.

You can view your AI CSAT score in the Dashboard and for each individual topic and conversation by clicking on the respective conversation.

<figure><img src="../../.gitbook/assets/image (55).png" alt="" width="273"><figcaption></figcaption></figure>

You can also see the rationale for the CSAT score by clicking on an individual conversation.

<figure><img src="../../.gitbook/assets/image (56).png" alt="" width="563"><figcaption></figcaption></figure>

### Date

The date refers to the date the 1st conversation was held on a topic.

### Time saved

The time saved is calculated by estimating the time saved per conversation, multiplied by the number of conversations (which were resolved by AI).

You can edit the time saved per conversation by going to your Account Settings, by default it is set to 5 minutes.&#x20;

### Resolution times

Each conversation is timed from the time of the 1st question asked to the time of the last question or the point of human handover.

This time is denoted as the "resolution time" and can be found for each individual conversation.

<figure><img src="../../.gitbook/assets/image (105).png" alt="" width="563"><figcaption></figcaption></figure>

The median resolution time across all conversations can also be found on the main dashboard.

<figure><img src="../../.gitbook/assets/image (107).png" alt="" width="230"><figcaption></figcaption></figure>

### Historic data

At any time you can see the historic Insights data for your AI agent by using the period dropdown to see data from the last day, week, month, quarter, half year and year.

This will allow you to see how many conversations your AI agent has had over different periods, how your AI resolution rate is changing over time and how much time you are saving each day, week or month.

Note, that this data is for the last period from the date you have selected, you cannot currently choose to see data between specific historic dates unless you use the Insights Export feature.&#x20;

<figure><img src="../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

### Export Insights, Conversations, Message History and Questions

{% hint style="info" %}
Insight, Conversation and Question Exports are only available on Pro plans and above.
{% endhint %}

To export conversational Insights, Conversation, Message History or Question data to Excel or Google Sheets, you can click the export button in the top right of the Dashboard.

{% hint style="info" %}
For best results, import the Exported data to Google Sheets, as Excel has a tendency to not be able to parse/read special characters.
{% endhint %}

This will allow you to choose to export Insight topics, Conversation, Message History or Questions between the two dates you choose into a CSV file that you can use for further analysis.

<figure><img src="../../.gitbook/assets/image (54).png" alt="" width="563"><figcaption></figcaption></figure>

Currently for each topic you will be able to see:

* [Category](./#categories)&#x20;
* [CSAT rating](../conversation-ratings-csat.md) &#x20;
* CSAT satisfied&#x20;
* Description&#x20;
* Human handover: TRUE means the conversation was passed to a live agent&#x20;
* [Lead email](../lead-email-capture.md)&#x20;
* Original conversation&#x20;
* Parent conversation topic&#x20;
* Parent topic&#x20;
* Total conversation topics count&#x20;
* Resolution time&#x20;
* Resolved&#x20;
* Source: Where the conversation with the user was held (e.g. Intercom, Dashboard, Slack)&#x20;
* Status&#x20;
* Title&#x20;
* Creation&#x20;
* Date&#x20;
* Unique ID

### Filtering and sorting

By default your Open Topics are sorted by number of conversations, and show for all categories. However, you can filter on the Category (Question, Bug, Feedback), or sort from high to low on:

* Number of conversations
* % AI resolved
* Days open

<figure><img src="../../.gitbook/assets/image (298).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The maximum export period for questions is 30 days. Should you need longer than this, contact support and ask to speak to a person.
{% endhint %}

### Charts

In both your main Dashboard page and your individual topics' Insights pages, you will see charts so you can track activity over time.

On the Dashboard, you can see: AI resolution rates/AI CSAT and Conversation volumes over time, switching between them using the toggle switch in the bottom right hand side of the chart.

<figure><img src="../../.gitbook/assets/image (3) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

On the detailed Insights page you will see a chart showing how often that particular topic has been raised over time, helping you identify peaks and troughs in activity.

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

All data is calculated nightly, so you will see conversations summarised from the previous day only.
