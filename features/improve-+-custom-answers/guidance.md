---
description: >-
  Our guidance feature will help you set up your AI agent to respond exactly how
  you want it to, tone, scenarios and when you want it to handover to your team.
---

# 🎯 Guidance

### What is guidance?

Guidance is a way to instruct and control your AI agent's responses so that they can more closely align with your brand's communication style, support policies and business processes.

This all results in higher quality responses, better brand identification and consistency and faster resolutions for your users or customers.

You can use guidance to ensure your AI agent uses the right terminology, does the right thing and escalates issues to your human agents at the right time.

You'll always be able to see what guidance was used by your AI agent and you can change it at any time.

{% hint style="info" %}
Guidance is currently only available for the following channels: \
\
Intercom (chat and email), Zendesk (messaging and tickets/emails) and My AskAI's own widget. \
\
More channels coming soon.
{% endhint %}

### What are the types of guidance and when should I use them?

There are 3 types of guidance you can add to your AI agent:

#### Communication style

This guidance controls the phrases, vocabulary/terminology and writing style of your AI responses to ensure that your AI agent responds like your best agents.

All of the communication style guidance added will be used in every response by your AI agent.

You should use this for instructions like:

> _Use inclusive terms such as “folks” or “everyone” and avoid gender-specific pronouns when uncertain._

> _Spell out acronyms on first use, then use the acronym only (e.g., “Natural Language Processing (NLP)”)._

> _Use one or two emojis in your responses to create a friendly and engaging tone._

#### Context & clarification

This guidance should be used to define follow-up questions that should be asked by the AI agent in certain scenarios in order to gather more information to better answer questions.

Only one piece of the context & clarification guidance will be used in each response by your AI agent.

You should use this for instructions like:

> _If a user is unsure how to reset their API key, verify whether they want to regenerate the existing key or create an additional one._

> _If a user asks how to export their data, first clarify whether they need a CSV file or a full JSON export._

> _When a user reports a bug, first ask for the following information before continuing troubleshooting: 1) what device are you using? 2) URL where the bug is occurring; 3) when was the bug first noticed._&#x20;

#### Handover & escalation

This guidance should be used so your AI agent knows when a specific topic of conversation should be handed over to one of your human agents for resolution.

Only one piece of the handover guidance will be used in each response by your AI agent.

You should use this for instructions like:

> _If a user requests a custom contract, MSA, or NDA, always hand the conversation over to a human agent._

> _If a subscriber submits a GDPR “right to be forgotten” request, always hand the conversation over to a human agent._

> _If a user requests a return of a product, always hand the conversation over to a human agent._

### How do I add or enable guidance?

To add or enable guidance for your AI agent:

1. Login to your Dashboard.
2. Go to Improve > Guidance.
3. Select the [type of guidance](guidance.md#what-are-the-types-of-guidance-and-when-should-i-use-them) you want to add and click the "+ New" button.
4. Enter your guidance and edit the title to make it easier for you to find later.
5. Click "Save".
6. Your guidance will be applied instantly, to test it out, ask a question in the adjacent chat window and see how it responds.

### How do I write the best guidance?

When writing your guidance, there are several things you should consider to get the best results and the most obedient AI:

#### Outcome-oriented&#x20;

Work backwards from what you want the AI to achieve to come up with your instruction. For example:

:x: _Before (vague and ineffective):_

> _“Make sure the AI customer support agent understands our different product types before answering.”_

:white\_check\_mark: _After (clear and structured):_

> _“If a customer asks about the ‘search’ feature, first ask which product they are using before responding. Then, provide product-specific instructions based on their answer.”_> \
> _By structuring guidance with clear steps and conditions, it can be applied consistently and correctly._

#### Use simple and precise language

Ambiguous or overly complex instructions can lead to inconsistent responses. Write as if you’re training a new support agent—be direct, specific, and easy to understand.

:x: _Before (unclear and open to interpretation):_

> _“Be professional but also friendly, keeping responses engaging.”_

:white\_check\_mark: _After (defined and actionable):_

> _“Use a professional yet approachable tone. Keep responses concise, avoid jargon, and use reassuring language when addressing customer frustrations (e.g., ‘I understand how that can be frustrating. Here’s how we can resolve it’).”_

#### Provide context and concrete examples

Instructions perform best when they can be understood as to when and how to apply guidance. Use words like “if,” “when,” and “then” to define conditions, and include clear examples.

:x: _Before (lacks context):_

> _“When customers ask about pricing, make sure you answer correctly.”_

:white\_check\_mark: _After (context-driven and detailed):_

> _“If a customer asks about pricing, first check if they mention a specific plan. If they don’t, ask which plan they’re interested in before providing details. Always refer to prices as ‘starting at \[lowest tier price]’ unless the customer specifies a plan.”_

#### Create separate, focused guidance

Each piece of instruction should address a single objective. If one instruction tries to convey more than one objective, it should be split into separate instructions. Avoid mixing multiple instructions, as this can make it harder to apply them correctly.

:x: _Before (too broad and unfocused):_

> _“Use a fomal tone, clarify questions before answering, and escalate returns issues to an agent.”_

:white\_check\_mark: _After (one clear purpose per entry):_

> _Communication guidance: “Maintain a fun, friendly tone by using positive language and avoiding jargon.”_

> _Context & clarification guidance: “If a customer asks about pricing but does not specify a plan, ask for their ticket volume before proceeding.”_>

> _Handover & escalation guidance: “If a customer mentions ‘return’ or ‘cancellation,’ immediately escalate the conversation to a human agent.”_

#### Speak directly to the AI agent in your guidance

When writing instructions, avoid referring to the AI customer support agent in the third person or commenting on how it should modify its responses. Instead, write as if you are speaking directly to it, telling it exactly what to do.

:x: _Before (third-person and indirect)_

> _“If the AI answer tells the customer to uninstall and reinstall the app, then rewrite the answer to remove that information, as reinstalling is not a valid troubleshooting step.”_

:white\_check\_mark: _After (direct and actionable)_

> _“Never tell the customer to uninstall and reinstall the app. Reinstalling is never a valid troubleshooting step, and the AI customer support agent should never communicate this to the customer.”_

#### Provide examples

When writing instructions, it is valuable to demonstrate correct and sometimes incorrect behaviours as part of the instruction using examples.

:x: _Before (tells AI customer support agent how to respond without an example):_

> "If a customer is frustrated, acknowledge their feelings and use calming language to show you care."

:white\_check\_mark: _After (helps AI customer support agent understand how it should and should not respond):_

> _"If a customer is frustrated, acknowledge their feelings and use calming language to show you care. For example:_\
> _"I understand this is frustrating, and I'm sorry for the trouble. Let's work through this together to find a solution."_\
> _"I know this isn't ideal, and I'm sorry for the inconvenience. I'm here to help and will get this sorted as quickly as possible.""_

#### Correct formatting

Always ensure proper grammar is used, including proper sentence grammar and punctuation, including full stops at the end of each instruction.



### How to optimize your guidance

When writing guidance there are a number of things you need to consider ([see here](guidance.md#how-do-i-write-the-best-guidance)).&#x20;

However, to make this easy for you we have added in an "Optimize" feature which you can click to rewrite your guidance in an optimal way that will be most effective for the AI agent.&#x20;

We highly recommend you use this feature to get the best results from your AI agent!&#x20;

### How can I test my guidance?

### What should guidance not be used for?

### How do I know if guidance has been used on a response?

### Is it possible to create multi-step guidance?

### How do I update my guidance?

### How do I delete guidance?

