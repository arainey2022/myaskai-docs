# Chat API

Our Chat API allows a user to have a conversation with your AI agent via a simple API call.&#x20;

The **messages** array should contain the conversation between the user and the AI agent. You can send the entire conversation within the API request.&#x20;

Each message object has a **role** (user or assistant) and **content**.&#x20;

In the example below you can see a short conversation between a user and an AI agent.&#x20;

The message from the user has the **role: user** and all replies from the AskAI have the **role: assistant**.

{% openapi src="../.gitbook/assets/chat.yaml" path="/ask-ai-chat" method="post" expanded="true" %}
[chat.yaml](../.gitbook/assets/chat.yaml)
{% endopenapi %}

{% hint style="warning" %}
If your AI agent doesn't know the answer, the API will also return an additional field to confirm an answer wasn't found as well as 3 suggested questions the user can retry (these have a very high likelihood of being answered correctly):&#x20;



`"unknown_answer": "yes",`

`"suggestedQuestions": ["Example question", ...]`
{% endhint %}

{% hint style="danger" %}
The `query` field has a 750 character limit. If this is exceeded, you will see an error: `{"error":"This question is too long. Please ensure questions are less than 750 characters."}`
{% endhint %}

{% hint style="info" %}
If human handover [guidance](../features/guidance.md) is triggered the API response will include: `"human_handover": true`
{% endhint %}
