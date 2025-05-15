---
description: >-
  Here is a high-level list of all the recent changes we have made to our
  question answering algorithm and set-up.
---

# 👨‍🔬 Algorithm change log

### 12 September 2024

Increase the size of conversational memory 3x to improve responses in longer conversations.

### 31 May 2024

We found the new GPT-4o model to be more obedient so we adjusted our prompts to reflect this conversatism.

### 20 May 2024

We moved all users over to use [the new GPT-4o model](https://openai.com/index/hello-gpt-4o/) exclusively, at no extra cost.

This means all users have access to OpenAI's most powerful model. It also means that, overall, response times should improve as we no longer need to use GPT-4 turbo as a fallback for GPT-3.5.

### 31 January 2024

Migrated from GPT-4 to GPT-4 turbo.&#x20;

We moved to OpenAI's latest, fastest, and most powerful model. The GPT-4 models are currently used as "fallbacks", so if initially, the GPT-3.5 model is unable to answer a query (which is faster), we will re-run the query using the more powerful GPT-4 models.

This also ensures that we are operating on the most up-to-date models when OpenAI deprecates (stops using) their older models in a few months.

You can learn more about the [GPT-4 turbo model here](https://platform.openai.com/docs/models/gpt-4-and-gpt-4-turbo).&#x20;

### 18 January 2024

Reference "relevancy" improvements made.&#x20;

This means that when we identify the most relevant pieces of content to answer a question, we then perform a secondary "re-ranking" of those references or sources to determine the most "relevant" sources or references amongst them to better answer your questions.

### 15 January 2024

Prompt improvements to "follow up" questions, i.e. any question after the 1st question in a conversation.
