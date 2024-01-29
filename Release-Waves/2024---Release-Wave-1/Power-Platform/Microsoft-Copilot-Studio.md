# Microsoft Copilot Studio - 2024 Release Wave 1

| Feature                                                                                                                                                                       | Early Access | Public Preview | General Availability | Expected Impact |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------:|:--------------:|:--------------------:|:---------------:|
| [Deploy copilots to WhatsApp, Azure Communication Services Chat and SMS channels](#deploy-copilots-to-whatsapp-azure-communication-services-chat-and-sms-channels)            |     ---      |    May 2024    |         ---          |                 |
| [Use customer managed encryption keys to protect your data](#use-customer-managed-encryption-keys-to-protect-your-data)                                                       |     ---      |    Sep 2024    |         ---          |                 |
| [Import and export topics across copilots and environments](#import-and-export-topics-across-copilots-and-environments)                                                       |     ---      |    May 2024    |         ---          |                 |
| [Use generative actions](#use-generative-actions)                                                                                                                             |     ---      |      ---       |       Apr 2024       |                 |
| [Use generative AI insights and other analytics enhancements to improve your copilots](#use-generative-ai-insights-and-other-analytics-enhancements-to-improve-your-copilots) |     ---      |    May 2024    |         ---          |                 |
| [Use IVR with Omnichannel for Customer Service](#use-ivr-with-omnichannel-for-customer-service)                                                                               |     ---      |      ---       |       Apr 2024       |                 |

# Copilot configuration

## Deploy copilots to WhatsApp, Azure Communication Services Chat and SMS channels

Microsoft Copilot Studio enables makers to connect to their consumer and enterprise audiences on a variety of channels. In conjunction with the Azure Communication Services, Copilot Studio is introducing support for WhatsApp, SMS through Communication Services, and Communication Services Chat, a multipoint chat service.

Customers can provision an Azure Communication Services resource, and then bring it to Microsoft Copilot Studio where they can connect their copilot to these new channels.

### Impact

[[Expected impact to your client.]]

## Use customer managed encryption keys to protect your data

Microsoft Copilot Studio now enables you to user your own encryption keys (hosted in Microsoft Azure Key Vault) to govern how Copilot Studio encrypts your copilot content; ensuring you have control over how your data is stored at rest.

Key capabilities include:

- Hosting with Azure Key Vault to manage your keys, lifetimes, and rotation periods
- Encryption of all of your content, including copilot topics, settings and configurations, and conversation transcript data
- Revocation of access, if necessary

### Impact

[[Expected impact to your client.]]

# Core authoring

## Import and export topics across copilots and environments

Microsoft Copilot Studio is a capable authoring environment for makers of all sorts to create sophisticated conversational assistants using generative AI and more traditionally authored topics. As organizations create and deploy more copilots, being able to reuse common building blocks, such as topics, across copilots and, for SIs/ISVs, across instances is a necessity.

Copilot Studio enables customers to export and import topics across copilots and across environments to facilitate this reuse of content and accelerate the multi-copilot authoring environment.

### Impact

[[Expected impact to your client.]]

# Copilot and AI innovation

## Use generative actions

Generative actions allow you to replace the traditional natural language-based approach for topic triggering (using the trigger phrases you've defined in each topic). Instead, your copilot uses GPT to select one or more topics or plugin actions to respond to a user's query.

All topics and plug-in actions have an associated description, which is the primary piece of information used when selecting which item should be selected. When enabled, generative actions is responsible for orchestrating the conversations users have with your copilot, which can help provide users with a more natural and fluid conversation.

For more information, go to [Use Generative Actions in Microsoft Copilot Studio (preview)](https://learn.microsoft.com/en-us/microsoft-copilot-studio/advanced-generative-actions).

### Impact

[[Expected impact to your client.]]

## Use generative AI insights and other analytics enhancements to improve your copilots

Copilot admins and makers can see new and improved analytics directly in the Microsoft Copilot Studio app, and they can instantly take actions to address low customer satisfaction (CSAT) and improve the deflection rate.

### Impact

[[Expected impact to your client.]]

# Speech and IVR

## Use IVR with Omnichannel for Customer Service

Microsoft Copilot Studio incorporates native voice authoring capabilities when used with the Voice channel in Dynamics Omnichannel for Customer Service integrations.

These capabilities include:

- Dual-tone multi-frequency (DTMF) input, including single and multi-digit processing so users can use their phone keypad to interact with the bot
- Silence detection for prompts, including retries and reprompts, and configurable actions on no response
- Barge-in control for determining whether the bot can be interrupted or not
- [SSML](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-synthesis-markup) support so you can configure how the bot sounds on a per-message basis, including playing audio files to the user in place of text-to-speech
- Long running operation latency message
- Enhanced speech recognition based on bot content

### Impact

[[Expected impact to your client.]]