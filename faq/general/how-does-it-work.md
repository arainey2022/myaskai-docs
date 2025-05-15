---
description: >-
  The nitty-gritty of how My AskAI actually works behind the scenes to answer
  your questions with AI (in case you are interested).
---

# 🤔 How does it work?

When you share a website with us we extract all of the text from it (keeping none of the original structure)

We then break that text up into _chunks_ of text, each of which are then _vectorized_ - this means that they are converted into a set of numbers or _dimensions_ ([1,536 to be precise](https://platform.openai.com/docs/guides/embeddings/second-generation-models)) that, when considered together, in their entirety represent the semantic meaning of the text.

We then do the same vectorizing process with the question you ask (to understand the semantic meaning of your question)&#x20;

We then perform a search to try to find the 6 closest (semantically relevant) chunks of text to the question you have asked (which, hopefully, indicates that the question and chunks of text are similar or related).

Once we have the question and chunks of text we put them into a completion prompt in the GPT-4o model (like you would use in ChatGPT) and ask it to answer your question using those pieces of text, its answer is what you see displayed to you.

Simple, eh?
