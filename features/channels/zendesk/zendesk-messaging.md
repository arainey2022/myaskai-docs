---
description: >-
  Connect your AI support agent to your Zendesk account and existing Zendesk
  Messaging, live chat widget on your website.
---

# Zendesk (Messaging)

<figure><img src="../../../.gitbook/assets/Frame 10.png" alt=""><figcaption></figcaption></figure>

You can now integrate your AI agent directly into Zendesk Messaging for a seamless AI experience.

{% hint style="success" %}
The Zendesk Messaging integration is available on all paid My AskAI plans, [see our pricing](https://myaskai.com/pricing).\
\
All Zendesk Messaging bot integrations require you to have Sunshine Conversations access (on the Zendesk Suite Professional plan or above) and usage purchased or included in your Zendesk plan.&#x20;

If you would like to learn more about purchasing Sunshine Conversations, please speak directly with Zendesk who will be happy to help.
{% endhint %}

### What are the benefits of using My AskAI within Zendesk Messaging?

There are several reasons why you should use your My AskAI within Zendesk Messaging:&#x20;

* While Zendesk has its own AI agent (called "Zendesk AI"), it is expensive, around 5-10x the price of My AskAI per conversation (we also think ours is smarter, but we'll let you be the judge!)
* You get access to an intelligent AI agent, directly within Zendesk Messaging that can automatically and instantly answer user or visitor queries, using your company knowledgebase.
* You can add more knowledge to your AI agent in addition to your website and Zendesk help center by using our [connections](../../connections/) or [file uploads](../../file-uploads.md).
* You don't have to add any code to your site to get your AI agent live, [just connect our app and you're ready to go](zendesk-messaging.md#how-to-connect-your-ai-chatbot-to-zendesk-messaging).
* Every AI answer is provided with reference links to the sources used to answer the question.
* You can add your AI agent to Zendesk's other messaging channels e.g. WhatsApp, Facebook Messenger, and many more
* As well as an AI agent, you get all our other features like [Improve](../../improve-+-custom-answers.md), [Insights](../../insights/), [Email Assistant](../../email-assistant.md), [Site Search](../../site-search.md), [Private (Internal) mode](../../private-internal-mode.md), [Integrations with Slack](../) and more.&#x20;

See how Customer.io are using My AskAI within Zendesk to reduce their ticket volume by 47%:

{% embed url="https://myaskai.com/blog/customerio-myaskai-case-study" %}

### How to connect your AI agent to Zendesk Messaging

{% embed url="https://www.youtube.com/watch?v=UpFd5arkVj0" %}
How to add My AskAI to your Zendesk Mesaging widget
{% endembed %}

1. Login to your Dashboard and go to _Channels_.&#x20;
2. Once enabled you will see "Live Chat apps" appear, click on the Zendesk icon.

<figure><img src="../../../.gitbook/assets/image (450).png" alt=""><figcaption></figcaption></figure>

3. Click to connect your Zendesk account:

<figure><img src="../../../.gitbook/assets/2 09.44.07.png" alt="" width="563"><figcaption></figcaption></figure>

4. If you have multiple Zendesk accounts, you will need to input your Zendesk subdomain, which you can find by looking at the URL of your Admin Center or Agent Dashboard e.g. (the text in <mark style="color:blue;">**blue**</mark> is the subdomain):\
   \
   &#x20;       _https://<mark style="color:blue;">**teammyaskai**</mark>.zendesk.com_\

5. Enter your subdomain and click "Sign in"

<figure><img src="../../../.gitbook/assets/image (367).png" alt="" width="453"><figcaption></figcaption></figure>

6. Allow access to your Zendesk account

<figure><img src="../../../.gitbook/assets/zd.png" alt="" width="464"><figcaption></figcaption></figure>

7. You'll then be shown a "Connecting to Zendesk" screen, which will take a few seconds, once connected you will be redirected back to My AskAI.
8. Once back at My AskAI, you will be shown instructions to help you "Configure your Zendesk account"
9. Go to your Zendesk Admin Center, click _**Channels > Bots > Manage Bots**_ then select '**Connect**' beside the My AskAI bot and '**Connect**' again on the pop-up.

<figure><img src="../../../.gitbook/assets/image (372).png" alt="" width="500"><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (370).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (373).png" alt="" width="444"><figcaption></figcaption></figure>

10. After tickets have been 'Solved' they need to be moved to 'Closed', so that the AI assistant can take control of the conversation again. There are two ways you can do this.
    1.  Go to _**Objects and rules > Automations**_, and find the existing automation called "Close ticket 4 days". Edit the "Hours since status..." field to 1 (recommended, but you can choose your own value). This means after tickets are solved, they will be closed within an hour and control returned to the AI assistant.\


        <figure><img src="../../../.gitbook/assets/image (402).png" alt="" width="563"><figcaption></figcaption></figure>
    2. If you want to immediately pass back control to the AI assistant when a ticket has been solved, then you will need to set up a 'Trigger'. To do this, go to _**Objects and rules > Triggers > Create trigger.**_\
       \
       Create the following trigger:\
       \
       **Trigger name**: Auto-Close Solved Ticket\
       **Description**: Close a ticket that has been marked as solved\
       **Category**: Ticket Status (you may have to + Add Category if this is not already available)\
       **Conditions**: Meet ALL of the following conditions: _Ticket > Status category_ | _IS_ | _Solved_\
       **Actions:** _Ticket Status > category_ | _Closed_

<figure><img src="../../../.gitbook/assets/image (374).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (375).png" alt="" width="563"><figcaption></figcaption></figure>

12. Go back to My AskAI and click the "_I've completed these steps_" button.
13. Customize the appearance of your AI agent by naming it and giving it a logo. This name and logo will appear within the Zendesk Messaging widget when your AI assistant is replying.

<figure><img src="../../../.gitbook/assets/4.png" alt="" width="563"><figcaption></figcaption></figure>

14. You're all done! Ask questions to your new AI agent within your Zendesk Messaging widget and see how it responds.

### How can I use my AI agent within Zendesk Messaging?

Once you've connected the My AskAI agent within your Zendesk Admin Centre, it will automatically start responding to user's questions within the Zendesk Messaging chat widget.&#x20;

With each question, it will provide the reference link used to answer the question.

<figure><img src="../../../.gitbook/assets/image (95).png" alt="" width="298"><figcaption></figcaption></figure>

### How does human handover work when using the Zendesk Messaging integration?

If, at any time, the user wishes to be passed over to a person to continue the conversation, all they need to do is say so, saying "Talk to a person" (or similar words to that effect) or just press the "Talk to someone" button at the end of the most recent message.

Once the conversation is passed over to the human, the AI will not respond again until the agent hands back control to the AI or the ticket is closed.

As part of the handover, the AI agent will summarize the conversation so the agent can pick up where the user left off so there is no repetition or frustration.

### How can I stop the AI agent from replying to specific phrases in Zendesk Messaging?

To stop your AI agent from replying to a specific set of phrases, share with us a list of the phrases you would like to block via chat and we will update your bot with these.

(Available on Pro accounts and above).

### Can I stop people speaking to a person on their first message on Zendesk Messaging?

You can prevent "instant" human handover on the 1st message in a conversation on Zendesk Messaging by navigating to **Channels > Zendesk** and then toggling the "_Ask for more information before handover_" feature.

<figure><img src="../../../.gitbook/assets/image (69).png" alt="" width="563"><figcaption></figcaption></figure>

This option is on by default.

When a user tries to handover immediately they will be asked to provide more information first. On any subsequent messages, they can initiate a handover to an agent.

### How do I remove my Zendesk Messaging AI agent?

1. Go to your Zendesk Admin Center, click _**Channels > Bots > Manage Bots**_ and look for 'My AskAI' (at the bottom)

<figure><img src="../../../.gitbook/assets/image (372).png" alt="" width="500"><figcaption></figcaption></figure>



2. Click the 3 dots next to the 'Connect' button, then select 'Uninstall':

<figure><img src="../../../.gitbook/assets/image (382).png" alt="" width="482"><figcaption></figcaption></figure>

3. On the pop-up, click to confirm the Uninstall:

<figure><img src="../../../.gitbook/assets/image (383).png" alt="" width="442"><figcaption></figcaption></figure>

4. Your My AskAI bot will now disappear from your 'Channels' view and you will have fully removed and disconnected your AI agent.

### Do conversations with the AI agent create new tickets in Zendesk Messaging?

A ticket is only created in the Zendesk inbox from a Zendesk Messaging conversation with the AI agent if the conversation is transferred to a person, i.e. when the user types "Talk to a person" (or similar) or uses the "Speak to someone" quick reply.

If they never choose one of these options, you will not see a ticket created.

This is how all Zendesk Messaging app integrations work.

### How can I add my AI agent to other channels that Zendesk Messaging offers? E.g. WhatsApp, Instagram, Facebook Messenger

Your AI agent will work with any additional messaging channels you connect​ it to within Zendesk Messaging. The messaging channels available are:

* WhatsApp
* Instagram DMs
* Facebook Messenger
* Android
* iOS
* Unity
* LINE
* Slack
* WeChat
* Twitter/X DMs

It will retain all the same features of the AI agent, including human handover, but within the respective platforms.

Refer to [Zendesk's instructions on how to get each channel set-up with your AI agent](https://support.zendesk.com/hc/en-us/sections/4405298883482-Third-party-and-social-messaging-channels).

### How can I capture an email in Zendesk Messaging?

If you are using the Zendesk integration we recommend you use Zendesk authentication to authenticate a user and pass their email into the Zendesk widget (this will then appear in My AskAI’s insight data as well).&#x20;

### How do I edit the Starter questions in the Zendesk Messaging widget?

To edit the starter questions in the Zendesk Messaging widget go to the **Dashboard**, then **AI Agent Setup > Customization > Starter Questions** - from here you can add or remove the Starter questions and they will be updated in your Zendesk Messaging widget.

### How can I pause or temporarily turn off AI replies or notes in Zendesk Messaging?

To pause or temporarily pause AI replies or notes in Zendesk Messaging go to **Channels > Zendesk Messaging** then scroll to the toggle for "Pause AI agent".

<figure><img src="../../../.gitbook/assets/image (60) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

When you are ready to turn it back on, just toggle the Pause button once more and it will start responding again.
