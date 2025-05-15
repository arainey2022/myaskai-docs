---
description: >-
  How we secure your data at My AskAI. Robust data protection with automatic
  file deletion, bank-grade encryption, and data usage strictly limited to API
  interactions and user-requested support.
---

# 🔐 Security

### How secure is My AskAI? (TLDR)

Yes, to keep your data secure (and cover the main things we get asked about):

* We automatically delete your files after they’ve been added to your AI support agent (uploaded to OpenAI), unless you explicitly tell us not to
* All uploaded content is stored in isolated containers
* All data is encrypted at rest (AES-256) and in transit
* Your data is never used for any reason other than servicing API calls or customer support at your request only
* Your uploaded (embedded) content (vectors) and reference content (text, author, links, etc.) are stored and encrypted on Qdrant, which is run on Google Cloud Platform (GCP) and located in The Dalles, Oregon, USA (us-west1-gcp).&#x20;

For full details of our processors, data retention, technical architecture please refer to our GDPR documentation:

{% content-ref url="../privacy/regulations/gdpr-compliance.md" %}
[gdpr-compliance.md](../privacy/regulations/gdpr-compliance.md)
{% endcontent-ref %}

For additional security:

{% content-ref url="on-premise.md" %}
[on-premise.md](on-premise.md)
{% endcontent-ref %}

{% content-ref url="openai-api-keys.md" %}
[openai-api-keys.md](openai-api-keys.md)
{% endcontent-ref %}
