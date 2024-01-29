# Governance and administration - 2024 Release Wave 1

| Feature                                                                                                                 | Early Access | Public Preview | General Availability | Expected Impact |
|:------------------------------------------------------------------------------------------------------------------------|:------------:|:--------------:|:--------------------:|:---------------:|
| [Enhance SAS calls to include IP restrictions ](#enhance-sas-calls-to-include-ip-restrictions)                          |     ---      |    Apr 2024    |       Jun 2024       |                 |
| [Use managed identities for Dataverse plug-ins](#use-managed-identities-for-dataverse-plug-ins)                         |     ---      |    Apr 2024    |         ---          |                 |
| [Enhance network security with connectors](#enhance-network-security-with-connectors)                                   |     ---      |    May 2024    |         ---          |                 |
| [Get insights into currency and storage consumption](#get-insights-into-currency-and-storage-consumption)               |     ---      |    Mar 2024    |       May 2024       |                 |
| [Limit access to Dataverse TDS endpoints with IP firewall](#limit-access-to-dataverse-tds-endpoints-with-ip-firewall)   |     ---      |    Apr 2024    |         ---          |                 |
| [Use management connector in Power Automate and Logic Apps](#use-management-connector-in-power-automate-and-logic-apps) |     ---      |  30 Nov 2023   |       Apr 2024       |                 |
| [Use Power Platform Advisor to get recommendations](#use-power-platform-advisor-to-get-recommendations)                 |     ---      |  20 Nov 2023   |       Apr 2024       |                 |
| [Stop cookie replay attacks](#stop-cookie-replay-attacks)                                                               |     ---      |    Jul 2024    |         ---          |                 |
| [Take advantage of a modern user interface](#take-advantage-of-a-modern-user-interface)                                 |     ---      |    Apr 2024    |         ---          |                 |
| [Use a modern UI to manage security roles](#use-a-modern-ui-to-manage-security-roles)                                   |     ---      |    Feb 2024    |       Apr 2024       |                 |
| [Use a modern UI when using Access Team templates](#use-a-modern-ui-when-using-access-team-templates)                   |     ---      |    Jan 2024    |       May 2024       |                 |

# Power Platform data policies and governance controls

## Enhance SAS calls to include IP restrictions

Customers can configure the IP restrictions for SAS calls within our low-code products. These options include:

- **IP Binding Only** - Restrict SAS keys to the requester’s IP.
- **IP Firewall Only** - Restrict using SAS keys to only work within an admin-specified range.
- **IP Binding and Firewall** - Restrict using SAS keys to work within an admin-specified range and only to the requestor's IP.
- **IP Binding or Firewall** - Allow SAS keys to be used within an admin-specified range. If the request comes from outside the range, IP Binding is applied.

Today, this feature specifically applies to:

- Power Apps
- Power Automate
- Microsoft Dataverse

Due to routing and additional calls that must be made to enhance security, customers with advanced apps, flows, and large data sets may see a slight effect on performance when this feature is enabled.

In addition to these calls gaining IP restrictions, the ability to log creation and usage events and monitor this activity is actively being developed. These logs are off, by default, due to the significant amount of traffic generated, but they can be activated in the Power Platform admin center. Once activated, logs are visible in Purview.

For more information, go to [SAS IP Binding](https://learn.microsoft.com/en-us/power-platform/admin/security/data-storage#sas-ip-binding).

Customers interested in testing the private preview should reach out to their account team to contact the program manager.

### Impact

[[Expected impact to your client.]]

## Use managed identities for Dataverse plug-ins

With the support of Power Platform managed identities in Dataverse for third-party and ISV plug-ins, you can use managed identities to access Azure resources without the need of usernames or passwords. For example, suppose you want to connect to Azure Key Vault without using a username and password to retrieve secrets to connect to an external web service from your third-party or ISV plug-ins. You can leverage Power Platform managed identities from your third-party or ISV plug-ins to directly connect to Azure Key Vault to retrieve the secrets securely and access the external web service.

### Impact

[[Expected impact to your client.]]

## Enhance network security with connectors

You can use private, outbound connectivity from Power Platform to securely access services and manipulate and protect data from your apps. You can connect privately from Power Apps, Power Automate, and Dynamics 365 apps.

You can connect to:

- Azure SQL, SQL Server, or Azure Synapse Analytics without exposing the traffic to the internet and protect your data from data exfiltration and other external threats.
- Azure file storage or blob storage without exposing the files to the internet and protect your data from data breaches and other incidents.
- Azure Key Vault without exposing the secrets to the internet and protect your data from data leaks and other risks.
- Your own services, authenticated by Microsoft Entra, without exposing them to the internet and protect your data from external attacks and data leaks.

You can also authenticate your services within your private network with Microsoft Entra and leverage your existing investment in Microsoft Entra that ensures only authorized users can access them from your Power Platform apps over private network. Therefore, you can enhance the security of your data integration with external data sources within your secured network from your Power Platform or Dynamics 365 apps.

For more information, go to [What is subnet delegation?](https://learn.microsoft.com/en-us/azure/virtual-network/subnet-delegation-overview). Subnet delegation helps you mitigate data exfiltration risks both from insider and external threats and provides security compliance by enforcing traffic to travel through virtual, private networks. It also helps you gain more control of data from subnet-delegated, Power Platform services.

### Impact

[[Expected impact to your client.]]

# Power Platform analytics

## Get insights into currency and storage consumption

Customers lack visibility into their currency consumption status, pre-purchased capacity, and consumption.

- Visibility to license consumption is crucial for having any license enforcement.
- Improved visibility to license usage facilitates resolutions for unintentionally, under-licensed customers.
- License enforcement encourages customers to acquire the necessary capacity and ensure license compliance.

We're providing improved capacity usage visibility through the Power Platform admin center, which displays allocation, usage, and license compliance status for different currencies available for customers. This feature empowers administrators and helps them comprehend the utilization of storage, including Dataverse, finance and operations storage, and currencies.

### Impact

[[Expected impact to your client.]]

# Managed Environments for Power Platform

## Limit access to Dataverse TDS endpoints with IP firewall

By using the IP firewall feature, you can apply access controls when needed to help keep your organization secure and stay out of your users' way when not needed. IP firewall analyzes and enforces the IP address of each request in real time. For example, suppose the IP firewall is turned on in a Dataverse environment, and IP ranges are set with the IP address of the office location. When a user decides to access the resources from another location, such as a coffee shop, Dataverse denies access to resources in real time.

Today, IP-based firewalls for [Microsoft Dataverse APIs](https://learn.microsoft.com/en-us/power-platform-release-plan/2021wave1/data-platform/dataverse-api) don't exist, but in 2024 release wave 1, administrators can configure the IP ranges for their businesses in the Power Platform admin center where Dataverse APIs can be accessed.

### Impact

[[Expected impact to your client.]]

## Use management connector in Power Automate and Logic Apps

As the [Power Platform API](https://learn.microsoft.com/en-us/rest/api/power-platform/) matures in feature capabilities across the platform, the need for the related tooling to be auto-generated and always up to date grows. This new version of the management connector for administrators will work and be available in Power Automate and Azure Logic Apps. This gives extra flexibility for those customers who use ARM templates and manage their tenant automation capabilities in Azure to stay in Azure. For those who don't want the additional complexity of Azure, they can stay within Power Automate and Power Platform.

### Impact

[[Expected impact to your client.]]

## Use Power Platform Advisor to get recommendations

Power Platform Advisor provides proactive recommendations for admins and makers to govern assets across Managed Environments. The recommendations allow admins to effectively govern Power Platform across security, performance, and compliance all in one place. Admins can take inline actions to address the recommendations without having to navigate various screens and surfaces within the platform.

### Impact

[[Expected impact to your client.]]

## Stop cookie replay attacks

You can stop cookie replay attacks by binding the IP address of the computer with a cookie to block unauthorized access to Dataverse. You can apply this control, when needed, to help keep your organization secure. Cookie replay attacks can be exploited if the device is compromised or a man-in-the-middle attack happens, and the browser’s valid cookie is copied by a malicious user. This valid cookie can only be replayed until it [expires](https://learn.microsoft.com/en-us/power-platform/admin/user-session-management).

For example, a user copies a valid browser cookie from one computer, using publicly available tools, and tries to replay the same cookie from a different computer using any publicly available tool. The cookie IP binding feature evaluates the IP address of the cookie origin in real time and prompts the user with a message if the IP address of the cookie origin is different than the IP address of the request being made.

Today, cookie binding with an IP address doesn't exist, but in 2024 release wave 1, administrators can use cookie IP binding in finance and operations environments to block cookie replay attacks.

### Impact

[[Expected impact to your client.]]

# Power Platform user management experiences

## Take advantage of a modern user interface

Admins can take advantage of the modern UI to complete the following tasks:

- Access Team templates
- Manage security fields for sharing user records
- Delete users
- Configure column-level security and hide sensitive data
- Redirect all traffic from legacy UI to modern UI

### Impact

[[Expected impact to your client.]]

## Use a modern UI to manage security roles

A modern, intuitive UI experience within the Power Platform admin center replaces the legacy, web client UI for managing security roles for environment makers. They can perform all security role management operations in the Power Platform admin center.

### Impact

[[Expected impact to your client.]]

## Use a modern UI when using Access Team templates

The legacy, web client UI for managing Access Team templates is being updated to provide a modern, intuitive experience for admins in the Power Platform admin center. Admins can perform all management tasks for Access Team templates in the updated UI quickly and efficiently.

### Impact

[[Expected impact to your client.]]