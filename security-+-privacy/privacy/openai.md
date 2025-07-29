---
description: How does My AskAI work with OpenAI?
---

# OpenAI

### Does OpenAI use my conversations to train its model?

No. OpenAI no longer uses other people’s data for their training for use via the API (and hasn’t since 1 March 2023).&#x20;

You can learn more about their data retention policy here: [https://openai.com/policies/api-data-usage-policies](https://openai.com/policies/api-data-usage-policies).

### Do I need to add an OpenAI key

No, unless you are on an [Enterprise plan and choose to use your own key](broken-reference).

### Can OpenAI access documents?

No. OpenAI doesn’t store any of your content.&#x20;

Your content is processed by them, to convert the text into searchable numbers (vectors), but it isn’t actually stored by them.&#x20;

All content storage is with [Qdrant](https://qdrant.tech/).
