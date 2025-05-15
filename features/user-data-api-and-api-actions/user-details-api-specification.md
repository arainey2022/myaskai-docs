---
description: >-
  How to set up your AI agent to use user data ingested via API to improve its
  responses.
---

# 👤 User details API specification

{% hint style="info" %}
If you have a Shopify store, you can use our [no-code Shopify connector](../shopify.md)
{% endhint %}

#### **Overview**

This API, provided by your company, allows us to retrieve user information based on a provided identifier. The endpoint will accept a POST request and will return relevant user data.

#### **Endpoint**

* **Example URL:** `https://api.client.com/user-data`
* **Method:** `POST`

#### **Headers**

* **Authorization** (required): The request must include an `Authorization` header with an API key provided to My AskAI.
* **Content-Type** (required): The request should accept only: `application/json`
* No other headers are required.

#### **Request Body**

The request will come from My AskAI with every new support ticket or support conversation.

The request body will be in JSON format and will include only the following field:

```json
{
	"identifier": "alex@alex.com"
}
```

* `identifier`: (String) The unique email of the user whose data is being requested. This must be available to My AskAI from an authenticated or valid source e.g. extracted from a Zendesk ticket or authenticated Intercom conversation

#### **Response**

The API must respond with a JSON object containing the requested user information:

```json
{
	"user_info": "Name: Alex Johnson\nEmail: alex@alex.com\nSubscription: Premium Subscription (Monthly)\nSubscription Start Date: January 15, 2024\nNext Renewal Date: October 15, 2024\n\nRecent Orders:\n1. Order #12345\n   - Date: September 1, 2024\n   - Items: Running Shoes\n   - Status: Delivered\n\n2. Order #12346\n   - Date: September 10, 2024\n   - Items: Fitness Tracker\n   - Status: In Transit\n\n3. Order #12347\n   - Date: September 25, 2024\n   - Items: Wireless Earbuds\n   - Status: Processing",
	"identifier": "alex@alex.com"
}
```

* `user_info`: (String) Information related to the user.
  * _Tip: Provide all relevant info that might be needed to support a request or question about their account. Try to avoid providing unnecessary information. Provide information in a concise format._
* `identifier`: (String) The same identifier provided in the request.
* Here is an example of detailed "user\_info" (unstringified) with hierarchical information:

````
Name: John Doe  
Email: john.doe@example.com  
Phone: 01234 567890  
Address: 123 Fake Street, Faketown, Fakeshire, FK1 1ZZ, United Kingdom


##### Orders:

   1. Order #CROWDOX-3504716:
    - Product Generation: Eco/Pro (Gen 2)
    - Status: Your Order Portal is locked, and we have started manufacturing your order.
    - Total Amount: 449 GBP
    - Shipping: 25 GBP
    - Paid: 424 GBP
    - Created At: 2020-08-06 10:40:21
    - Fulfillment Group: PB9
    - Estimated Dispatch Date: 2020-08-13 10:40:21 - 2020-08-20 10:40:21
    - Items: Universal Magnetic Disc (1),  (1), Thumb Throttle (1), 2A Charger (1), UK Plug (1)
    - Refund Eligibility:: Important: Refund Entitlement Response (for all refund questions for this order CROWDOX-3504716): 
      ```
      You are entitled to a refund for order CROWDOX-3504716. Please reply with 'Talk to a person' to be connected with our team.
      ``` (this answer must be used verbatim)
    - Order Cancellation Eligibility:: Important: Cancellation Entitlement Response (for all cancellation questions for this order CROWDOX-3504716)
      ```
      You are entitled to cancel your order CROWDOX-3504716 and get a refund. Please reply with 'Talk to a person' to be connected with our team.
      ``` (this answer must be used verbatim)

###### Dispatches:

     1. Dispatch #CROWDOX-3504716:
      - Reference: CROWDOX-3504716
      - Status: Fulfilled (Assumed Delivered)
      - Courier: Collection Collect from Vdepot Warehouse
      - Tracking Number: 
      - Address: N/A

     2. Dispatch #ZD254796-W-JR:
      - Reference: ZD254796-W-JR
      - Status: Fulfilled (Assumed Delivered)
      - Courier: Royal Mail 24 Small Packet
      - Tracking Number: 3709659540011B0B09ACF
      - Address: John Doe, 123 Fake Street, Faketown, Fakeshire, FK1 1ZZ, United Kingdom
````

#### **Performance Requirements**

* The API must respond within 10 seconds.
* The API must be capable of responding for each new support conversation or ticket.

#### **Error Handling**

* **401 Unauthorized**: If the `Authorization` header is missing or invalid.
* **400 Bad Request**: If the request body does not contain the required `identifier` field or is improperly formatted.
* **404 Not Found:** If the user data is not found from the identifier
* **500 Internal Server Error**: For any other unexpected errors.
* If the API fails, the AI agent will continue support the user, but without any additional user data

#### **Standards & Conventions**

* All requests must be in JSON format
* All responses are in JSON format
