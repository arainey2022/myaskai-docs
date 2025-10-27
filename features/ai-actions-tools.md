---
description: >-
  Having your AI support agent answer questions based on knowledge and user data
  is all well and good, but what about if you want it to start doing things for
  you, on your behalf, to truly automate?
---

# 🛠️ AI Actions (Tools)

### What are tools?

Tools are how your AI support agent can interact with your systems and backend in a more autonomous way.

For each ticket, your AI agent will decide whether or not it needs to use a tool you give it access to, so it will only use the tool when it deems it necessary.&#x20;

### What can tools be used for?

Tools can be used for pretty much any action you would use an API for today.&#x20;

Examples include:

* Looking up data that isn't necessarily user-specific, such as property or product lookups
* Automating cancellations
* Automating refunds
* Automating background checks
* Automating customer data updates, e.g. address updates

Your AI agent will understand the ticket it is answering and decide when it needs to take action using one of these tools.

### How do tools differ from the User Data API?

The [User Data API](../api-documentation/user-data-api.md) is to be used when you need to retrieve information or data about a specific user and can only be used where you have a verified user (email support ticket or authenticated live chat user).

### How do I set up tools?

Each tool will map to an API and needs the following details:

* **POST API endpoint:** e.g. `https://api.company.com/orders`
* **Authentication headers:** e.g. `Authorization: Bearer <token>`
* **JSON request body:** include the fields your tool needs, such as `"email"` and `"order_id"`
* **Other headers (optional)**
*   **JSON response body:** include all the information you want your AI agent to access, e.g.

    ```
    {
      "orders": [...]
    }
    ```

There is no other specific API format expected by your AI agent, apart from the above. This makes it fairly flexible to integrate existing APIs or modify existing APIs for exposing to your AI agent.

To get your tools set up, open the live chat in your Dashboard and ask to “Talk to a person.”

### How much do tools cost?

Tool calls cost $0.02 per reply that used a tool/API call, you will only pay for responses where tool calls are made.
