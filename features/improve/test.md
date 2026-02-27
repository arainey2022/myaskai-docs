---
description: >-
  We know putting an AI agent live with your customers can feel scary, so we
  want to give you the tools to boost your confidence. Test lets you see how
  your AI agent will perform on your questions.
---

# ☑️ Test

Our batch Test feature takes a sample of your historic support tickets and previous questions asked (if you have integrated [Zendesk](../channels/zendesk/) or [Intercom](../channels/intercom/)) and/or lets you add in your own test question set and shows you how your AI agent will respond to those questions, so you can see quickly how it will perform on day 1.

You can find the batch testing feature in your Dashboard under **Improve > Test**.

{% hint style="info" %}
Historic tickets for batch testing are only imported at onboarding, you can't import them subsequent to this. We will however use your human replies to tickets on an ongoing basis to generate proposed custom answers to fill knowledge gaps. &#x20;
{% endhint %}

### How do I add test questions to my AI agent to evaluate its performance?

There are 2 ways you can add test questions to your AI agent to evaluate its performance:

1. If you have your [Zendesk](../channels/zendesk/) or [Intercom](../channels/intercom/) connected then when you are on the batch Test page you will see an option to "Create from previous Intercom/Zendesk conversations". \
   \
   Clicking this button will import a sample of up to 50 historic conversations or tickets to use as your test question set.
2. You can manually add test questions by typing your test question in the text entry field and then clicking the "+ Test Question" button.&#x20;

Once you have added your test question set you will then be able to click into each question and see how your AI agent would have responded.

### How can I evaluate, score, and QA my test questions?

You can evaluate, score and QA your test question set by clicking into any question. From there you can score the agent on:

* Whether you’d send the response to a customer
* Provide an overall score for the response
* Give notes on what can be improved
* Add any additional comments

You can then track these as you make updates to your agent.

<figure><img src="../../.gitbook/assets/image (1).png" alt="" width="563"><figcaption></figcaption></figure>

### How do I improve my AI agent responses once I have tested them?

Once you have tested your AI agent's responses, if you want to change or improve them you can add more [Knowledge](../connections/), [Guidance](guidance.md) or a [Custom Answer](custom-answers.md).

If you click into the question and scroll to the bottom of the response you'll see options to do all of these or you can go directly to them in the Dashboard menu.

### What do the "AI Resolved" and "Answered" columns mean in Test?

When you see AI Resolved in Test it shows whether the conversation would have been automatically handed over to a person or not.

You can change whether this happens automatically by applying [Handover & Escalation Guidance](guidance.md#handover-and-escalation).

When you see Answered in Test it shows whether the AI agent had sufficient knowledge added to it to answer the question.

You can add more knowledge to improve this via [Connections](../connections/) or [Custom Answers](custom-answers.md).

### How do I retest my question in Test once I have updated Guidance or added more knowledge?

If you have just updated guidance or knowledge and want to retest for a single, particular question, then you can select that question in Test, then click "Refresh" and a response will be regenerated.

If however you have made larger changes and what to see how that impacts all responses then click the "Refresh all" button on the main Test view.

### How do I change or delete a question from my Test question set?

To edit a question from your Test question set, select the question you want to Edit then click the Edit button from the side menu and make the update.&#x20;

The answer will then be automatically re-generated for that question.

To delete a question from your Test question set, select the question you want to Delete then click the Delete button from the side menu.&#x20;

### How do I delete all of the Test questions and start again?

To delete all of the Test questions and start again with a new Test question set, click the "Delete All" button on the main Test question set page, then follow the instructions to [add new Test questions](test.md#how-do-i-add-test-questions-to-my-ai-agent-to-evaluate-its-performance).

### How can I export or share the Test question responses with my team?

To export or share the Test question responses with your team, click the "Export / Share Tests" button in the top right of the Test view to download a CSV file with all the questions and responses.
