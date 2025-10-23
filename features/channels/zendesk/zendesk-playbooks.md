---
description: Here you'll find how to set up specific use cases for your Zendesk AI agent
---

# Zendesk Playbooks

### Only use AI agent for out-of-hours replies in Zendesk Tickets

To set your Zendesk AI agent to only reply to tickets out-of-hours:

1. Create a [schedule](https://support.zendesk.com/hc/en-us/articles/4408842938522-Setting-your-schedule-with-business-hours-and-holidays) in Zendesk for your business hours
2. Edit the My AskAI trigger in Zendesk "Notify My AskAI..."
3. Add a new condition to the list "Meet ALL of the following conditions"
4. New conditions: Ticket within business hours > is > No

<figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

This means that the AI agent will only be notified about tickets outside of business hours.
