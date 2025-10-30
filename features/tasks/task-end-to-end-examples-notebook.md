---
description: >-
  Full examples of some tasks, so you can see what they look like once added to
  your AI Agent.
---

# 🗒️ Task End to End Examples (Notebook)

This guide walks you through **creating your first Task** in AskAI — whether your task uses **tools (APIs)** or runs without them. Tasks let your AI Agent handle structured, repeatable actions like updating customer details, resetting passwords, or collecting feedback.

Need some inspiration on what Task to create first?

{% content-ref url="task-use-cases.md" %}
[task-use-cases.md](task-use-cases.md)
{% endcontent-ref %}

***

### ⚙️ Step 1: Give Your Task a Name and Purpose

#### **Name**

Give your task a short, action-oriented title that describes what it does.\
**Examples:** `Update Contact Details`, `Reset Password`, `Schedule Appointment`

#### **Description**

Explain briefly what the task helps users do.

**Example:**

```
Assist users with updating contact details on their account.
```

This description helps your team recognize the task later.

***

### 💬 Step 2: Add Example Triggers

#### **Example questions to trigger this task**

Provide 2–3 sample user messages that should start this task.\
These help the AI agent recognize when to use it.

**Example:**

```
Can I update my contact details to x@c.com  
Please contact me on jim@email.com  
Use this alex@gmail.com and +73474385930
```

#### **Negative examples (optional)**

List examples of messages that **shouldn’t** trigger this task.

**Example:**

```
Can I update my subscription?  
Can I add a team member to my account?
```

These examples improve accuracy and reduce false positives.

***

### 🔁 Step 3: Write Example End-to-End Flows

Show how a full conversation should go. Write at least one **normal flow** that clearly demonstrates how the AI should respond.

**Example:**

```
**Normal flow: email and phone**
- Customer: Update my details to alex@gmail.com and +73474385930
- Agent: Sure thing. To confirm, you want your new booking contact details to be alex@gmail.com and +73474385930?
- Customer: Yes
- Agent: Okay, that’s been updated for you. Please let me know if I can help with anything else.
```

Include variations where the user might only provide one piece of information (email or phone) or need to confirm details.

***

### 🤔 Step 4: Add Handover or Escalation Rules

Sometimes users may get stuck or need human help.\
Use this section to explain **when the AI should hand over to a human agent**.

**Example:**

```
Handover if the user is repeatedly struggling to update their contact details.
```

***

### 🧪 Step 5: Add Instruction Steps

Instruction steps are the **step-by-step recipe** your AI Agent follows to complete the task.\
Each step should include clear instructions in plain English.

#### Common examples:

**Step 1 – Get Contact Details**

```
Unless already provided, request the customer’s email and/or phone number they want used on their booking.
- If they already provided this, skip this step.
```

**Step 2 – Confirm Details**

```
Repeat the details back to the user before proceeding.
- If invalid or unclear (e.g., typo), ask them to confirm again.
- Allow them to edit their details if needed.
```

**Step 3 – Perform the Update**

If your task **uses tools (APIs)**, include the tool reference here:

```
Update the booking with the new email and phone.
- Tool: {{update_contact_details}}
- Only proceed after confirmation in Step 2.
```

**Step 4 – Confirm Completion**

```
Tell the customer the update was successful (or failed) and check if they need any more help.
```

If your task **does not use tools**, you could replace this final confirmation step with a handover for an a human agent to complete the final step.

```
Let the user know their request will be completed by the team.
- Then call {{handover}} to escalate.
```

***

### 🛠 Step 6: Add Available Tools (Optional)

Tools (API access for AI agents) are available for accounts with 5,000+ conversations per month. You can learn more about tools below.

{% content-ref url="../ai-actions-tools.md" %}
[ai-actions-tools.md](../ai-actions-tools.md)
{% endcontent-ref %}

If your task needs to use an API, you'll need to add this as a Tool first. This can then be reference in a task step.

**Example:**

```
Update the booking with the new email and phone.
- Tool: {{update_contact_details}}
- Only proceed after confirmation in Step 2.
```

***

### ✨ Step 7: Guidance for Tone and Style

Use the **Guidance** box to define your Agent’s tone for this task. Tasks don't any existing Guidance you have for your AI agent. Tasks have their own Guidance that's more focused on the task at hand.

**Example:**

```
Be polite but very brief — the user wants to complete the task quickly.
```

This ensures consistency across all responses.

***

### :test\_tube: Step 8: Save & Test

1. Click **Save changes** but do not set live until you've tested it
2. Once saved, close the task and test your task in the chat widget

***

### 🚀 Step : Activate

1. Before setti
2. Once it’s ready, toggle **Set task live**.
3. Click **Save changes**.

Your first AI task is now live! 🎉

***

### ✅ Quick Tasks Checklist

| Step               | What to Do                    | Applies To       |
| ------------------ | ----------------------------- | ---------------- |
| Name & Description | Clearly describe task purpose | All tasks        |
| Example Triggers   | Add real user phrases         | All tasks        |
| End-to-End Flows   | Show sample conversations     | All tasks        |
| Handover Rules     | Define when to escalate       | All tasks        |
| Instruction Steps  | Define step-by-step actions   | All tasks        |
| Tool References    | Add API or automation tools   | Tool-based tasks |
| Guidance           | Set tone and personality      | All tasks        |
| Test               | Test in your Dashboard        | All tasks        |
| Set Live           | Activate the task for users   | All tasks        |

***

#### 🔑 Tip

Start with a simple task (like “Update Contact Details”) before building more advanced ones. Once comfortable, you can chain multiple tasks or integrate APIs for full automation.
