# Customer Service - 2024 Release Wave 1<!-- omit from toc -->

| Feature                                                                                                                       | Early Access | Public Preview | General Availability | Expected Impact |
|:------------------------------------------------------------------------------------------------------------------------------|:------------:|:--------------:|:--------------------:|:---------------:|
| [Add up to 200 route-to-queue rules in a workstream](#add-up-to-200-route-to-queue-rules-in-a-workstream)                     |     ---      |      ---       |       Apr 2024       |                 |
| [Prioritize existing conversations in asynchronous channels](#prioritize-existing-conversations-in-asynchronous-channels)     |     ---      |      ---       |       Apr 2024       |                 |
| [Update queue memberships for agents in real time](#update-queue-memberships-for-agents-in-real-time)                         |     ---      |      ---       |       Apr 2024       |                 |
| [Check configuration health in admin center](#check-configuration-health-in-admin-center)                                     |     ---      |      ---       |       Apr 2024       |                 |
| [Create multiple cases from email sent to multiple boxes](#create-multiple-cases-from-email-sent-to-multiple-boxes)           |     ---      |      ---       |       Apr 2024       |                 |
| [Explore enhancements to outbound dialing](#explore-enhancements-to-outbound-dialing)                                         |   Feb 2024   |      ---       |       Apr 2024       |                 |
| [Get FedRAMP certified for new features](#get-fedramp-certified-for-new-features)                                             |   Feb 2024   |      ---       |       Apr 2024       |                 |
| [Mask sensitive data and prevent unauthorized access](#mask-sensitive-data-and-prevent-unauthorized-access)                   |     ---      |    Apr 2024    |       Sep 2024       |                 |
| [Rate call quality and provide feedback on improvements](#rate-call-quality-and-provide-feedback-on-improvements)             |   Feb 2024   |      ---       |       Apr 2024       |                 |
| [See enhancements in call transfers to external numbers](#see-enhancements-in-call-transfers-to-external-numbers)             |     ---      |      ---       |       Apr 2024       |                 |
| [Support voice channel in Government Community Cloud Moderate](#support-voice-channel-in-government-community-cloud-moderate) |     ---      |    Apr 2024    |       Apr 2024       |                 |
| [Test call, microphone, speakers before and during calls](#test-call-microphone-speakers-before-and-during-calls)             |   Feb 2024   |      ---       |       Apr 2024       |                 |
| [Transfer calls to Teams users through VOIP](#transfer-calls-to-teams-users-through-voip)                                     |     ---      |      ---       |       Apr 2024       |                 |
| [Use skills to find agents for consult, transfer scenarios](#use-skills-to-find-agents-for-consult-transfer-scenarios)        |   Feb 2024   |      ---       |       Apr 2024       |                 |
| [Improve productivity by converting voicemail to case](#improve-productivity-by-converting-voicemail-to-case)                 |     ---      |      ---       |       Apr 2024       |                 |
| [Use enhanced attachment experience while composing email](#use-enhanced-attachment-experience-while-composing-email)         |   Feb 2024   |      ---       |       Apr 2024       |                 |
| [Forecast case volumes daily and at 15-minute intervals](#forecast-case-volumes-daily-and-at-15-minute-intervals)             |     ---      |  28 Apr 2023   |       Jul 2024       |                 |
| [Get automatic prompts from Copilot](#get-automatic-prompts-from-copilot)                                                     |     ---      |    Apr 2024    |   To be announced    |                 |
| [Get relevant results with filters for Copilot](#get-relevant-results-with-filters-for-copilot)                               |     ---      |    Apr 2024    |   To be announced    |                 |
| [Validate Copilot responses faster with more transparency](#validate-copilot-responses-faster-with-more-transparency)         |     ---      |    Apr 2024    |   To be announced    |                 |

# Unified Routing

## Add up to 200 route-to-queue rules in a workstream

Administrators can now add up to 200 route-to-queue rules in a workstream, allowing for more specific routing conditions. This ensures work items are directed to the most suitable queue, enhancing efficiency in complex customer service environments.

### Impact

<!-- Expected impact to your client. -->

## Prioritize existing conversations in asynchronous channels

The first-in-first-out prioritization for live channels is based on the conversation start time. However, conversations that come from asynchronous messaging channels like persistent chat, Facebook, WhatsApp, and SMS can be paused or kept in the waiting state allowing the customer to respond on their own schedule while preserving the conversation continuity. This enhancement will prioritize conversations in asynchronous channels by the latest interaction time. This means that for new conversations, the conversation start time is considered to be the interaction time while the resume time will be considered the interaction time for conversations that are revived from the waiting state. This will be applicable to the default first-in-first-out prioritization in the out-of-box assignment strategies, which are highest capacity.

### Impact

<!-- Expected impact to your client. -->

## Update queue memberships for agents in real time

Administrators who manage these updates won't have to wait for 15 minutes for an agent's queue membership update to reflect in the system. With the real-time queue membership update, agents can take work in their new queues as soon as they are added to them. When you remove agents from queues, they won't receive work from the removed queues, thus reducing the wait time due to reroutes.

### Impact

<!-- Expected impact to your client. -->

# Administrator experiences

## Check configuration health in admin center

Released in the last wave, the contact center health check allows administrators to run a comprehensive check on their configurations and identify any issues or gaps. In this release, we're adding more checks for channels, bots, service level agreements, and automatic record creation. These checks help administrators optimize their contact center performance and increase customer satisfaction.

### Impact

<!-- Expected impact to your client. -->

## Create multiple cases from email sent to multiple boxes

Here are the key capabilities of this feature:

- Email sent to multiple queue-enabled mailboxes (irrespective of To, Cc, Bcc) gets converted into multiple cases (one case corresponding to each queue enabled mailbox).
- Email gets associated to each case and is shown on the case timeline.
- Agents belonging to any of the queues (to which the email was sent to) can respond to the customer independently from any case using the case timeline.
- Any reply from the customer to the original email gets associated to the case created in response to the original email, instead of creating a new case.
- If a customer replies to the original email while adding a new queue-enabled mailbox, a case gets created for the new mailbox and the replied email gets associated with the new case in addition to the existing cases.

### Impact

<!-- Expected impact to your client. -->

# Omnichannel

## Explore enhancements to outbound dialing

The enhanced outbound dialing experience enables you to:

- Place a call by searching for a customer contact or account right from the outbound dialer.
- Open the conversation record or customer record right from the call history.

### Impact

<!-- Expected impact to your client. -->

## Get FedRAMP certified for new features

Microsoft are submitting FedRAMP certifications for the internal and external components that are added in the end-to-end omnichannel stack in Dynamics 365 Customer Service. The FedRAMP compliance will allow customers in government community clouds to use the newly integrated features. This will be FedRAMP High certification on GCC Moderate.

### Impact

<!-- Expected impact to your client. -->

## Mask sensitive data and prevent unauthorized access

This feature provides the following configuration capabilities to prevent unauthorized access and create a secure environment for agents and supervisors to address customer needs.

- **Administrative control:** Administrators can define rules for handling sensitive data items and establish masking rules. These rules can be applied for data storage, during IVR sessions, and agent sessions.
- **Service-wide application:** The established masking rules will be applied to transcription and call recording services.
- **Audit trails:** Auditing features to track changes to sensitive data rules and access to Dataverse entities that host sensitive data.

### Impact

<!-- Expected impact to your client. -->

## Rate call quality and provide feedback on improvements

The end of call rating will enable you to:

- Leave a star rating at the end of a configurable percentage of calls, where 5 is considered excellent, 4 is good, 3 is okay, 2 is poor, and 1 is bad.
- For ratings of 4 and below, you can share what could have been better.
- Admins can choose to configure this rating to show up after every 1 call to 100 calls.
- Admins can also choose to run this survey for a specific time bound period.

### Impact

<!-- Expected impact to your client. -->

## See enhancements in call transfers to external numbers

In this release, the following enhancements will be available for call transfers to external numbers:

- Transfers will always be done in one step. Agents will be dropped from the call immediately.
- Transfers will have the option to be bridged or blind. Bridged is in the product now, and blind means recording and transcription will automatically stop.
- Agents can specify a call forwarding number for their direct inward dialing assigned numbers.

### Impact

<!-- Expected impact to your client. -->

## Support voice channel in Government Community Cloud Moderate

In this release, the voice channel in Omnichannel for Customer Service will be available for GCC customers. With this support, customers in government clouds will now have access to all features that are a part of the voice channel.

View the complete set of the voice feature capabilities [here](https://learn.microsoft.com/en-us/dynamics365/customer-service/administer/voice-channel).

### Impact

<!-- Expected impact to your client. -->

## Test call, microphone, speakers before and during calls

With this feature, agents can:

- Test the microphone and speaker anytime - before calls, during calls, and after calls.
- Place a test call to ensure that the microphone and speaker are working and to familiarize themselves with the in-call experience.

### Impact

<!-- Expected impact to your client. -->

## Transfer calls to Teams users through VOIP

Consult and transfer calls to any Teams user in your organization, regardless of whether they have a phone number assigned to them.

- Use your Teams investments in your contact center.
- Use the Voice over Internet Protocol (VOIP) to contact Teams subject matter experts in your organization.
- Teams users are no longer required to have a phone number.

### Impact

<!-- Expected impact to your client. -->

## Use skills to find agents for consult, transfer scenarios

During a conversation, when agents need to consult with other agents, they can now specify skills, such as language, product knowledge, and proficiency to find suitable agents with the right expertise using the skills-based search. The system then recommends agents who match the requirement. Agents will see the agent's name, presence, and level of match to choose for a consult. Subsequently, after the consultation there is the option to warm transfer to the agent they have consulted with.

The UI for the skills-based consult and transfer are enhanced to be modern and user-friendly whilst different than the normal consult and transfer control for distinction.

### Impact

<!-- Expected impact to your client. -->

## Improve productivity by converting voicemail to case

The convert to case option will be available in the voicemail ribbon to convert a voicemail to a case, allowing agents to do this operation in one click.

### Impact

<!-- Expected impact to your client. -->

# Agent experiences

## Use enhanced attachment experience while composing email

The key enhancements to the attachment experience are as follows:

- Add attachments by dragging and dropping them to the email.
- Copy attachments from one or more emails to and paste it another email.
- Bulk download and deletion of attachments.
- Attachment size displayed in the appropriate units.
- Toggle between the tile and grid views.
- Export attachments details to Excel.
- Reminder to add attachments if agents miss attaching files but have mentioned it in their email.
- Add attachments before saving an email.

### Impact

<!-- Expected impact to your client. -->

## Forecast case volumes daily and at 15-minute intervals

Case volume forecasting was released with the following set of capabilities:

- Forecast case volumes daily.
- Visualize forecasted volumes daily, weekly, and monthly basis, for up to six months.
- Slice forecasted volumes by channel and queue.
- Automatically detect seasonality from historical traffic to help customer service managers accurately predict case volumes during special, seasonal events.

Now, customer service managers can also forecast case volumes at 15-minute intervals from historical data.

### Impact

<!-- Expected impact to your client. -->

# Copilot and AI innovation

## Get automatic prompts from Copilot

Copilot in Dynamics 365 Customer Service can help customer service agents in a variety of ways. It's not always obvious to agents what Copilot might be able to do for them next. Automatic prompts give contextual suggestions to agents on what they can do next. This makes it easier for customer service agents to quickly ask questions and get help.

### Impact

<!-- Expected impact to your client. -->

## Get relevant results with filters for Copilot

Filtering results based on knowledge for the appropriate business lines or customer information ensures that Copilot generates relevant and precise responses. This saves agents time and improves customer satisfaction.

### Impact

<!-- Expected impact to your client. -->

## Validate Copilot responses faster with more transparency

Copilot in Dynamics 365 Customer Service has been upgraded to provide enhanced transparency in its responses, including better citations of its sources. With this increased transparency, customer service representatives can easily understand how Copilot generated its responses and validate its accuracy, reducing the time taken to verify the replies. This, in turn, enables representatives to decrease handle times and enhance customer satisfaction.

### Impact

<!-- Expected impact to your client. -->