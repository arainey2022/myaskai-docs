---
description: >-
  Receive email or Slack notifications when new conversation insights are
  created.
---

# 🔔 Conversation insight notifications

**When are new conversation insights created?**

When there are 3 similar conversations, from your customers with your AI agent, they are grouped together into a conversation topic, also known as an insight. This contains a summary of the conversation, highlights key issues and includes a suggestion fix for your team.

#### Can I get alerts when people are speaking about a certain topic?

You can set up conversation topic alerts that to notify you when a topic is raised multiples times within a set time period.

e.g. If you wanted to be alerted if something is discussed 5 times in 1 hour.

To set these alerts go to:&#x20;

**Account Settings > Conversation Topic Alerts** then toggle the "Activate alerts" on and configure the number of new conversations of the same topic being discussed and the timeframe for those conversations and choose how you want to receive the alerts ([Email](conversation-insight-notifications.md#email-notifications) or [Slack](conversation-insight-notifications.md#slack-notifications)).&#x20;

## Email notifications

<figure><img src="../../.gitbook/assets/image (128).png" alt=""><figcaption><p>Example of an email notification for a conversation insight</p></figcaption></figure>

Email notifications are sent to all team members (incl. the admin). Email notifications can be turned on within 'Account settings'. Notifications can only be turned on or off by an admin and cannot be turned off for individual team members.

## Slack notifications

If your team uses Slack, you can receive insight notifications within a specific channel within your Slack workspace. After turning on Slack notifications, please follow the instructions below.

Slack notifications can be turned on within 'Account settings'. Notifications can only be turned on or off by an admin.

### Slack notification setup instructions

{% hint style="warning" %}
_This should be done by your Slack Workspace admin. Some of the steps are mildly technical._
{% endhint %}

1. Decide on a channel you want to receive notifications or create a new channel, e.g. #askai-insights
2. Sign into Slack on the web and create a new 'App': [https://api.slack.com/apps?new\_app=1](https://api.slack.com/apps?new_app=1)
3. Choose 'Create from scratch', name the app 'My AskAI Insights' and select your Workspace
4.  Select 'Incoming webhooks' within the section 'Add features and functionality'<br>

    <div align="left"><figure><img src="../../.gitbook/assets/Screenshot 2024-03-01 at 15.04.40.png" alt="" width="563"><figcaption></figcaption></figure></div>
5.  Activate incoming webhooks with the toggle switch<br>

    <div align="left"><figure><img src="../../.gitbook/assets/image (131).png" alt="" width="563"><figcaption></figcaption></figure></div>
6. Create a webhook by scrolling down and selecting the button 'Add New Webhook to Workspace'.
7.  Select the channel you want to send the insights to and 'Allow' permission for this app with your Workspace.<br>

    <div align="left"><figure><img src="../../.gitbook/assets/image (132).png" alt="" width="563"><figcaption></figcaption></figure></div>
8.  Copy your Slack webhook URL (scroll down).<br>

    <figure><img src="../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>
9. Paste this webhook URL in your My AskAI Dashboard's Slack notifications settings.
10. Try sending a test message by clicking 'send test message to Slack'. If this isn't received, please double check the webhook was pasted correctly. If this is correct, check the instructions above have all been followed correctly. And if you still aren't receiving a Slack notification, please message us.
11. **Bonus**: You can customise the app icon within Slack to give your new insight notifications some personality. Within your Slack app (website), select 'Basic information' from the righthand menu and then scroll down to 'Display information'.\
    \
    You can then upload a logo, like our [My AskAI logo](https://7ac07acbae116a5155080d295197d8d6.cdn.bubble.io/f1709308979339x243661440310076960/Logo.png).



You can always find your Slack app if you need to make changes within '[Your Apps](https://api.slack.com/apps/)' in Slack. If you get stuck, there is an [additional guide from Slack](https://api.slack.com/messaging/webhooks) on how to create an app with webhooks.
