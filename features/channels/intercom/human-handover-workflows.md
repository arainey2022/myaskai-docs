# Human Handover Workflows

### How can I run a workflow after a human handover in Intercom?

To run a workflow after a human handover in Intercom:

1. Create a new workflow by going to ‘**+ New workflow**’ > ‘**Start from scratch**’ > ‘**Customer sends any message**’

<figure><img src="../../../.gitbook/assets/image (39) (2).png" alt="" width="563"><figcaption></figcaption></figure>

2. Set the  Trigger rule to ‘**Leads and Users**’ and any relevant channels for your business

<figure><img src="../../../.gitbook/assets/image (40) (1).png" alt="" width="563"><figcaption></figcaption></figure>

3. Create two paths:

**Path 1: Wait and Check**

1. Set a **Wait** action for 1 minute
2. Create a **Branches** action with the following conditions:
   1. IF: Conversation tag is `AI human handover`&#x20;
   2. AND conversation state = "_is not closed_"
   3. AND (Optional) Team assigned is not your human agent's team&#x20;
   4. ELSE: End the workflow

<figure><img src="../../../.gitbook/assets/image (41) (1).png" alt="" width="496"><figcaption></figcaption></figure>

**Path 2: Assign to Team**

Assign the conversation to your human team

4. Finally, set the new workflow live and your handover will automatically take place.
