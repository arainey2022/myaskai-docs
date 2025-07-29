---
description: Use the Query API to create an integratation with your AI agent.
---

# Query API

With our API you can build your own internal tools or workflows and harness the power of your AI agent wherever you want, however you want.

The API is powerful, but very simple. You input a question and get an answer back, along with the references/content used in the answer.

See full details of the API below. [Alternatively, you can use our pre-built integrations with Slack, Microsoft Teams or Zapier](../features/channels/).

{% openapi src="../.gitbook/assets/query (2).yaml" path="/ask-ai-query" method="post" %}
[query (2).yaml](<../.gitbook/assets/query (2).yaml>)
{% endopenapi %}

{% hint style="info" %}
If your AskAI doesn't know the answer, the API will return a field to confirm an answer wasn't found:`"unknown_answer": "yes"`
{% endhint %}

{% hint style="info" %}
The `query` field has a 750 character limit. If this is exceeded, you will see an error: `{"error":"This question is too long. Please ensure questions are less than 750 characters."}`
{% endhint %}

{% hint style="info" %}
If human handover [guidance](../features/improve/guidance.md) is triggered the API response will include: `"human_handover": true`
{% endhint %}
