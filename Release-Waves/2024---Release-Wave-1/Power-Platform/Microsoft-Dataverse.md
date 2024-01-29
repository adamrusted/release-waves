# Microsoft Dataverse - 2024 Release Wave 1

| Feature                                                                                                                               | Early Access | Public Preview | General Availability | Expected Impact |
|:--------------------------------------------------------------------------------------------------------------------------------------|:------------:|:--------------:|:--------------------:|:---------------:|
| [Associate activities with multiple related records](#associate-activities-with-multiple-related-records)                             |     ---      |   4 Dec 2023   |       Apr 2024       |                 |
| [Enable Power Platform connector plug-ins in Microsoft 365 Chat](#enable-power-platform-connector-plug-ins-in-microsoft-365-chat)     |     ---      |    Apr 2024    |         ---          |                 |
| [Share system views with security role](#share-system-views-with-security-role)                                                       |     ---      |    Mar 2024    |       Jun 2024       |                 |
| [Maintain security role privileges for better ALM solution import](#maintain-security-role-privileges-for-better-alm-solution-import) |     ---      |    Jan 2024    |       Apr 2024       |                 |
| [Share apps and data access modernization](#share-apps-and-data-access-modernization)                                                 |     ---      |    Feb 2024    |       Apr 2024       |                 |
| [Prevent data exfiltration with user level controls](#prevent-data-exfiltration-with-user-level-controls)                             |     ---      |    Jun 2024    |       Sep 2024       |                 |
| [Process app data more efficiently with delegation](#process-app-data-more-efficiently-with-delegation)                               |     ---      |    Mar 2024    |       Apr 2024       |                 |
| [Scan files and attachments for viruses and malware](#scan-files-and-attachments-for-viruses-and-malware)                             |     ---      |    Jun 2024    |       Aug 2024       |                 |

# Microsoft 365 collaboration

## Associate activities with multiple related records

Users will be able to associate an activity record with additional related party records (parties). This means a user can perform actions like associating an email or meeting to additional related parties, such as an email or meeting related to additional cases or opportunities.

### Impact

<!-- Expected impact to your client. -->

# Empower users with copilot and your enterprise data

## Enable Power Platform connector plug-ins in Microsoft 365 Chat

Plug-ins can enhance the copilot experience in Microsoft Copilot by leveraging business data across different systems. With this feature, customers can leverage many standard plug-ins from Power Platform in Microsoft Copilot (Microsoft 365 Chat). Using Microsoft Copilot Studio, customers can also enable their own custom plug-ins.

For more information, go to [Create and configure copilot plugins](https://learn.microsoft.com/en-us/microsoft-copilot-studio/copilot-plugins-overview).

### Impact

<!-- Expected impact to your client. -->

# Enterprise data activation

## Share system views with security role

Currently, when users are on a table form, such as an account form, a list of system views is automatically displayed to allow the user to choose from. Often times this list of views is overwhelming and long and most of them aren't relevant to users. Makers and admins don't have the ability to select the ones that are applicable to their target users by security role.

With this feature, the admin can select the appropriate system views for their respective users by security role. Users with the selected security roles will only see the system views that were shared with their security role.

### Impact

<!-- Expected impact to your client. -->

## Maintain security role privileges for better ALM solution import

Currently, when the system predefines customizable security roles, custom security roles, and privileges that are shipped in upgraded managed partner solutions, all updates to security roles and privileges done by the Power Platform admin in their environment are overwritten.

With this feature, the system predefined customizable security roles, custom security roles, and privileges will be merged with the updates to the security roles and privileges done by the Power Platform admin in an environment instead of overwriting the preexisting updates.

### Impact

<!-- Expected impact to your client. -->

## Share apps and data access modernization

Currently, when makers share their apps, they often miss the required step to create the appropriate security roles for their app. The security role creation step is not part of the app making process and is done outside of the maker experience on the Power Platform admin center. The security role creation also requires elevated admin privileges that makers might not have.

With this feature, makers can easily share their app and table access with their users. Makers don't need to leave Power Apps to create the required security role for their apps. They can share their app and specify what permission level to provide for the tables in their app as part of the app sharing experience.

### Impact

<!-- Expected impact to your client. -->

## Prevent data exfiltration with user level controls

By default when this feature is activated, only approved first party solution apps can run in an environment, such as Dynamics 365 Sales or Dynamics 365 Customer Service. The local environment admin sets what apps can run by their authorized users in an environment. Unauthorized apps are blocked when the user tries to access the environment. To help administration with selecting which apps to approve for their environment, an audit mode run can be enabled. This is where all app accesses are audited, and the admin can download this audit log for review.

Conditional access on which users can run what authorized apps can be set by the administrator. The administrator can allow list an app for selected security role(s). Only users who have the selected security roles can run the app in the environment.

### Impact

<!-- Expected impact to your client. -->

# Build your low-code, hyperscale backend in Dataverse

## Process app data more efficiently with delegation

The delegation issue in canvas apps is a problem that occurs when you use certain functions or operators in a formula that can’t be delegated to the data source. Delegation means that Power Apps sends the processing of data to the data source, rather than moving the data to the app for processing locally. This way, you can work with large data sets (more than 500 records) efficiently and avoid wrong results.

If the data source has more rows than the delegation limit (500 rows by default, though you can increase the limit to 2,000) you might not be able to pull in all the data you want in the way you want without extra work. You'll normally see a small yellow warning symbol in your app when editing to let you know that something you're doing will hit the delegation limit and so you might not get the results you expect. The goal of this feature is to address this gap in the Dataverse platform.

### Impact

<!-- Expected impact to your client. -->

# Data ingestion in Microsoft Dataverse

## Scan files and attachments for viruses and malware

Customers are handling more than 520 million files and uploading them into Dataverse daily. We have detected that some of these files are infected.

With this feature, Power Platform admins can set their environments up for scanning their users' file uploads. When infected file uploads are detected, the infected files are quarantined to prevent users from accidentally downloading them. Admins have the ability to check the infected files and decide whether to report them to Microsoft or to delete them.

### Impact

<!-- Expected impact to your client. -->