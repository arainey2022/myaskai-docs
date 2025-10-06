---
description: >-
  Make the most of your AI agent by allowing it to execute SOPs or processes on
  your behalf, taking repetitive tasks like refunds, address changes and more
  away from your human agents.
---

# 👷 Tasks

{% embed url="https://youtu.be/yJPErtsa1kg" %}

### What are tasks?

Tasks enable you to bring together personalized [user data](../user-data-api/), interactions with your back end databases and product via [actions and tools](../ai-actions-tools.md), [customized guidance](../improve/guidance.md) and your AI's knowledge to step a user or customer through a process that requires business logic.

In simple terms what that means is, instead of users having to click through a multistep flow (old world of chatbots), they can talk to the AI that refers to an SOP or process that will ask the right questions at the right time and not be as rigid as something flow-based.

As a simple example, you could have a refund task where you need your AI agent to:

* Check which order the user wants a refund for
* Ask for a reason for the refund,&#x20;
* Checking back to your policies whether that it is reasonable
* Confirm the refund with the customer&#x20;
* Issue the refund from your payments platform

All performed automatically by your My AskAI agent in your existing help desk.

And all of this can be created easily with natural language instructions to your AI agent instead of adding decision trees.

### When should I use tasks?

Tasks are an incredibly powerful feature of your AI agent, but they do involve more setup than most other features, so should generally only be used for:

* The highest impact tasks your human agents currently have to complete - think: which 1-2 tasks or workflows, which, if automated, would reduce your ticket volume by the largest amount?

{% hint style="info" %}
Tip: Review your [Insights](../insights/) and sort by the lowest resolution topics to identify high impact areas for tasks
{% endhint %}

* Processes that require multi-turn interactions with customers&#x20;
* Complex, multi-step, business-logic-based flows&#x20;

### What is the difference between tasks, actions/tools, knowledge or guidance?

Tasks are the most powerful, but also the most complex form of AI functionality available for your AI agent.

Tasks will usually utilize [tools](../ai-actions-tools.md) you have already set up i.e. one task may use 1 or more tools in order to complete. The task is the overall process or procedure, the tools are what actually _does_ the action.

[Guidance](../improve/guidance.md) should be used for controlling how the AI responds in simple scenarios or if there is [a single follow up question](../improve/guidance.md#context-and-clarification) or an [immediate handover required](../improve/guidance.md#handover-and-escalation).&#x20;

The majority of your AI's ability and performance will still be derived from the [Knowledge](../connections/) you have given to your AI agent. It will perform best by looking up processes and troubleshooting steps from here. Tasks should only be used when you need the AI to "do" something off the back of this.

### What will I need to set up tasks?

As tasks are a more complex features setting them up will require a few things:

1. **APIs:** While a task doesn't necessarily always require use of a [tool](../ai-actions-tools.md) (API), the majority will. So it is best to start by identifying which (or creating) APIs in your owns systems you want the task to interact with and how you want them to interact.
2. **Internal alignment:** Most tasks will touch multiple teams, in terms of set-up and ongoing maintenance, this could include your engineering team, customer service or success team, product and operations teams. Ensure everyone is on the same page.

* **Testing and improving**: Tasks will require monitoring and improvements over time, especially as you identify edge-cases, so set up a process to test initially and review their performance over time, along with a feedback and improvement loop.

### How do I use tasks?

To set up tasks, contact us by asking to "Talk to a person" and we will help you get your Tasks set up.

{% hint style="info" %}
Tasks are currently only available to customers with 5,000 tickets/mo or more and Enterprise customers.
{% endhint %}

### How much do tasks cost?

Tasks are priced at $0.10 per conversation or ticket, but you are only charged if the task has been used, so, if only 5% of your tickets require the task to be executed, then you'll only pay the $0.10 for those 5% of tickets.

### How do I use a handover within a Task?

To instruct a handover within a Taskm use the phrase `{{handover}}` to reference the handover should be made e.g. “If they are refunding because of a safety issue then `{{handover}}`”
