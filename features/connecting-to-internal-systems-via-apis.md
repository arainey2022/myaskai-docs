---
description: >-
  Like your human agents, you'll want to give you AI agent access to your
  internal systems to look up user's details or take actions like issuing a
  refund.
---

# 🏢 Connecting to Internal Systems via APIs

We provide a number of ways you can give your AI agent access to your internal systems, the primary uses cases for this are:

* Accessing live customer data e.g. recent orders for a given customer's email address
* Accessing specific information about something e.g. all details about a specific Order ID
* Taking action e.g. refunding an order

We connect to your internal systems securely via APIs you give your AI agent access to. See the below options to decide what's best for your use case.

#### Before Getting Started

Before you begin considering connecting your internal systems/data with your AI agent, you will very likely need a developer to help with this step. You will be providing APIs (in most cases new ones) to your AI agent.

#### 1) Get User Information (using verified customers email address)

When a customer is verified, by either emailing you from a known email address or the user is logged in on your system (and you've authenticated them with Zendesk, Intercom, etc.) then your AI agent can view the user's verified email address.

The AI agent will call a user data API you provide and your API will return information about the user.

The is perfect for returning information about a user, their recent orders, their account, subscription, current plan, etc.

{% content-ref url="user-data-api/" %}
[user-data-api](user-data-api/)
{% endcontent-ref %}

#### 2) Get Specific Information About Something e.g. Order

Whether a customer is verified or not, you may want to allow them to ask about the status of a particular order. In this case, for example, you would provide your AI agent with an API that can accept a zip/post code and an order ID and return the latest information about that order.

The AI agent will call the API you provide and answer the user's question with the content returned from your API.

This is perfect for allow un-verified users to ask about their account/orders or if you want to allow users to ask more about a specific piece of content in your system e.g. order, project, team, etc.

If your API (tool) is just fetching some information about something, it doesn't need to be part of a task (see more below).

{% content-ref url="ai-actions-tools.md" %}
[ai-actions-tools.md](ai-actions-tools.md)
{% endcontent-ref %}

#### 3) Tasks: Take Action e.g. Collect & Save User Data or Cancelling an Order

This is a more advanced case where you have a multi-step workflow usually done by your human agents. This might involve collecting some information from a user for booking a demo and then creating the meeting invite. Or it might involved checking recent orders, seeing if an order can be cancelled and then cancelling it.

With a task, the AI agent will follow each step you define and some of these steps may involve API calls as well. So you can consider a task as a set of instructions that wrap together tools (APIs) that you have given your AI agent access to.

{% content-ref url="tasks/" %}
[tasks](tasks/)
{% endcontent-ref %}
