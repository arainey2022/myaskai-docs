# 🔍 Inspect & Logs

### How can I review previous conversations/tickets and understand why the AI agent answered how it did?

One of our most powerful features of our 'Improve' studio is the **Inspect & Logs** view.

From this view, you can search for any ticket or conversation, by date, Ticket ID, email and/or keyword, then click into it to see the conversation/ticket history.

If you are an Intercom or Zendesk user, you can also click the Ticket ID link in the conversation/ticket view and it will take you to that ticket in your Intercom ro Zendesk account.

From the conversation/ticket history you can see:

* The knowledge sources used to answer any question
* The interpretation of the question as the AI understood it
* A button to "Inspect answer"

Clicking the "Inspect answer" button will let you ask questions to understand why the AI answered in the way that it did, for example:

* "Why did it say x?"
* "Why did it handover the ticket?"
* "Where did it find x information?"

After you have typed your question, clicking "Ask question" will then show you the explanation for the answer, including any sources, user data or guidance that the AI agent used to answer.

If this wasn't a satisfactory answer for you, you will also be shown options to "Fix" the answer by either:

* Creating a [Custom Answer](inspect-and-logs.md#custom-answers)
* Adding [Guidance](guidance.md)
* Adding [User Data](../user-data-api/)
* Adding a [Task](../tasks/) or [Tool](../ai-actions-tools.md) call

### How can I quickly find and correct a ticket or conversation?

When a conversation is handed over to a human agent a note will be generated giving you tips on how to improve the response for next time, it will offer options of:

* [Inspecting ](inspect-and-logs.md#how-can-i-see-what-content-or-knowledge-is-used-most-often-in-conversations)the conversation to see what knowledge was used
* Adding [guidance](guidance.md) to control reply tone/style & how scenarios are handled
* Creating [custom answers](inspect-and-logs.md#custom-answers) to fill knowledge gaps (draft with AI)
* Connecting your internal systems for [live customer data](../../api-documentation/user-data-api.md)
* Drafting AI replies with our [copilot extension](../channels/chrome-extension.md)

### How do I turn off the "Admin notes" that I see on each handover?

You can turn off the "Admin notes" by going to **Account Settings > Other settings > Disable admin note tips.**
