# Business Central - 2024 Release Wave 1

> ![NOTE]
> This page is not yet completed. Please do not share with clients yet!

| Feature                                                                                                                                                             | Early Access | Public Preview | General Availability |             Expected Impact              |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :----------: | :------------: | :------------------: | :--------------------------------------: |
| [Achieve sustainable compliance with Business Central](#achieve-sustainable-compliance-with-business-central)                                                       |     ---      |    Apr 2024    |       May 2024       | <!-- Expected impact to your client. --> |
| [Automate country of origin listed for item tracking code in Intrastat reporting](#automate-country-of-origin-listed-for-item-tracking-code-in-intrastat-reporting) |     ---      |    May 2024    |       Jun 2024       | <!-- Expected impact to your client. --> |
| [See VAT date in posting previews](#see-vat-date-in-posting-previews)                                                                                               |     ---      |    May 2024    |       Jun 2024       | <!-- Expected impact to your client. --> |
| [Improved update release processes](#improved-update-release-processes)                                                                                             |     ---      |      ---       |       Mar 2024       | <!-- Expected impact to your client. --> |
| [Use linked environment in Dataverse integration](#use-linked-environment-in-dataverse-integration)                                                                 |     ---      |    Mar 2024    |       Apr 2024       | <!-- Expected impact to your client. --> |
| [Allow customers to consent to Microsoft Support accessing their data](#allow-customers-to-consent-to-microsoft-support-accessing-their-data)                       |     ---      |      ---       |       May 2024       | <!-- Expected impact to your client. --> |
| [Audit Business Central operations in Microsoft Purview](#audit-business-central-operations-in-microsoft-purview)                                                   |     ---      |      ---       |       May 2024       | <!-- Expected impact to your client. --> |
| [Encrypt data at-rest with customer-managed encryption key](#encrypt-data-at-rest-with-customer-managed-encryption-key)                                             |     ---      |      ---       |       May 2024       | <!-- Expected impact to your client. --> |
| [Link Business Central environments to Power Platform environments](#link-business-central-environments-to-power-platform-environments)                             |     ---      |      ---       |       May 2024       | <!-- Expected impact to your client. --> |
| [Archive Projects](#archive-projects)                                                                                                                               |     ---      |    Mar 2024    |       Apr 2024       | <!-- Expected impact to your client. --> |
| [Connect Business Central with Shopify B2B](#connect-business-central-with-shopify-b2b)                                                                             |     ---      |    Mar 2024    |       Apr 2024       | <!-- Expected impact to your client. --> |
| [Define a service invoice posting policy for various users](#define-a-service-invoice-posting-policy-for-various-users)                                             |     ---      |    Mar 2024    |       Apr 2024       | <!-- Expected impact to your client. --> |
| [Define default location for project or project phase](#define-default-location-for-project-or-project-phase)                                                       |     ---      |    Mar 2024    |       Apr 2024       | <!-- Expected impact to your client. --> |
| [Get more productive while entering time sheets](#get-more-productive-while-entering-time-sheets)                                                                   |     ---      |    Mar 2024    |       Apr 2024       |                                          |

# Legislation

## Achieve sustainable compliance with Business Central

This feature enables you to collect and report on your sustainability activities. The solution is the foundation that will be used for compliance with the European Union's Corporate Sustainability Reporting Directive (CSRD) and other ESG standards.

### Feature Details

We're introducing a groundbreaking feature focused on sustainability reporting. This new, easily extendable functionality lets you record and report on a wide spectrum of sustainability information, encompassing both qualitative and quantitative aspects, and forward-looking and retrospective data. You can also leverage the feature to actively reduce emissions, making it a valuable tool for small and midsized organizations seeking to comprehensively report on sustainability initiatives.

This feature ensures compliance with the European Union's CSRD, which requires companies to report on the sustainability of their activities. The CSRD introduces a heightened requirement for reporting, impacting approximately 50,000 companies in the European Union—more than four times the number covered by the previous Non-Financial Reporting Directive (NFRD), which the CSRD supersedes. However, the solution will be built to ensure that ESG compliance aligns with other standards.

You can use **Sustainability Journals** and **Recurring Sustainability Journals** to record data, based on the **Chart of Emission Accounts**. You can use different emission groups, subgroups, and formulas to make the collection of emissions as easy as possible. This feature also has **Sustainability Entries** where data is recorded and used for reporting. It's important to understand that Business Central supports other emissions besides carbon footprint.

You can benefit from streamlined business processes and enhanced productivity, irrespective of your current stage in the sustainability journey. The initial release lays the foundation for future expansion and automation, promising ongoing advancements in the functionality.

### Impact

<!-- Expected Impact to your client. -->

## Automate country of origin listed for item tracking code in Intrastat reporting

This feature enables users to include the country of origin in item tracking. This enhancement is poised to increase productivity by automatically inheriting the country of origin for items in sales documents from corresponding purchases, eliminating the need for manual intervention. This information will later be used in Intrastat reporting.

### Feature Details

Intrastat currently uses **Country of Origin** from the **Item Card**. However, it's common that users are buying the same item from different countries. The new Intrastat solution in Dynamics 365 Business Central improves the usage of country of origin by allowing users to set up a **Country of Origin** on an **Item Tracking Code**. With this new approach, the **Country of Origin** for **Items** in sales documents automatically inherits values from corresponding purchase documents based on the **Item Tracking Code** setup, such as lot number or serial number. This eliminates the need for manual intervention and potential mistakes. With this information, **Intrastat** reporting will be faster and more accurate.

### Impact

<!-- Expected Impact to your client. -->

## See VAT date in posting previews

This feature provides better overviews, compliant accounting and reporting, and increased productivity related to VAT details.

### Feature Details

With this feature, you can view the **VAT Date** when you post previews in documents and journals. When a document is posted, the **VAT Date** field is visible in **VAT entries** and in **G/L entries**. Now, you can see the **VAT Date** before you post, when you run the **Posting Preview** action. This feature is a continuation of the VAT improvements based on user and partner feedback.

### Impact

<!-- Expected Impact to your client. -->

# Governance and administration

## Improved update release processes

Improved update release processes ensure that updates run as close to the start of the update window as possible and that updates are made available globally more gradually.

### Feature Details

During 2023 release wave 2, we're improving our update release processes. Customers who don’t manually schedule their environment updates can expect updates to start quickly after the start of the environment update window. To deploy updates more gradually to environments that don't manually reschedule the update to a different date, update availability and default scheduling will vary per region.

### Impact

<!-- Expected Impact to your client. -->

## Use linked environment in Dataverse integration

Businesses want to keep their data safe and secure within their privacy boundary, and especially when their business management application integrates with other apps. By linking Business Central and Dataverse environments, you’ll not only achieve those considerations, but also give your administrators an easier way to create and maintain your integrations with other Dynamics 365 apps.

### Feature Details

In the Business Central admin center, you can link your Business Central environment to your Dataverse environment. Business Central can use the information from the link to make it easier, and more secure, to integrate with other Dynamics 365 apps, such as Sales and Field Service. For example, the linked Dataverse environment URL is available by default on the Dataverse Connection Setup page and when you run the Dataverse Integration assisted setup guide. Administrators can connect to the linked environment with confidence, less friction, and a streamlined workflow.

### Impact

<!-- Expected Impact to your client. -->

## Allow customers to consent to Microsoft Support accessing their data

Customers can fulfill their data privacy requirements and get support from Microsoft in a way that ensures their explicit consent.

### Feature Details

In the Power Platform admin center, administrators can create lockbox policies that apply to Power Platform and Dynamics 365 environments so that our customers can review and approve or reject access requests from Microsoft engineers in response to a customer-initiated support ticket, or a problem identified by Microsoft. With 2024 release wave 1, lockbox policies in the Power Platform admin center now apply to Business Central environments as well.

Customers can choose to enable lockbox on their Microsoft Entra tenant to:

- Increase security and privacy of their data in the cloud.
- Have more visibility and control over who accesses their data and for which purposes.
- Comply with regulatory or organizational requirements for data access governance.

### Impact

<!-- Expected Impact to your client. -->

## Audit Business Central operations in Microsoft Purview

This feature provides administrators with a unified and comprehensive view of their organization's operations so they can better monitor and audit events across multiple Microsoft services.

### Feature Details

In 2024 release wave 1, auditable events occurring in Dynamics 365 Business Central environments are emitted to Microsoft Purview, allowing administrators to monitor and audit events across Business Central and other Microsoft services in a single place.

### Impact

<!-- Expected Impact to your client. -->

## Encrypt data at-rest with customer-managed encryption key

This capability will allow customers to meet their data and privacy policy according to the standard privacy guidelines.

### Feature Details

With Dynamics 365 Business Central 2024 release wave 1, customers will gain the ability to encrypt their environment database using their own encryption key. This feature, also known as customer-managed key (CMK), provides enhanced data protection and compliance for your business data. With CMK, you can use your own Azure Key Vault key to protect and control access to the key that encrypts your environment database. This gives you more flexibility and control over your encryption keys, such as the ability to rotate, revoke, or restore them.

This feature will be administered in the Power Platform admin center, and will require the Business Central environment to be linked to a Power Platform environment. Enabling CMK on a Power Platform environment linked to a Business Central environment will apply the same CMK policy on the Power Platform and Business Central environments.

### Impact

<!-- Expected Impact to your client. -->

## Link Business Central environments to Power Platform environments

Link your Business Central to a Power Platform environment from the admin center to provide a default target environment for integrations and apply Power Platform environment settings to your Business Central environment. This simplifies the integration process and reduces the need to specify the target environment for each integration.

### Feature Details

Business Central integrates with many different Power Platform and Dynamics 365 products in various ways. In 2024 release wave 1, Business Central administrators are able to link a Business Central environment to a Power Platform environment from the Business Central admin center. This capability provides the following benefits:

- The Business Central environment will inherit settings that are enabled on the linked Power Platform environment in the Power Platform admin center, such as customer-managed encryption keys.
- The linked Power Platform environment will provide a default target environment for any integrations set up between Business Central and other Dynamics 365 and Power Platform products, such as Dynamics 365 Sales and Power Automate.

Business Central environments can only be linked to Power Platform environments that are in the same Azure geography and are of the same type (production or sandbox). Linking environments isn't a permanent operation, meaning it's possible to unlink and relink environments. Environment lifecycle operations, such as updating or deleting an environment, on each of the linked environments is administered separately.

### Impact

<!-- Expected Impact to your client. -->

# Application

## Archive Projects

Projects often change and evolve during their lifecycle. The archiving capability gives you control over your project data through audit trails and version control.

### Feature Details

Archiving capabilities for projects are similar to the functionality you might already be familiar with from the sales and purchase areas. You can set up projects to archive automatically, so that you don't need to think about it. With automatic archiving, Business Central creates a new version of the archived document when people do the following:

- Change the status of a document, or delete it.
- Print, download, or send a document by email.
- Post an invoice.

You're in full control of archiving. The following table describes the options you can choose when you set up automatic archiving on the **Project Setup** page.


| Option       | Description                                                                                                              |
| :----------- | :----------------------------------------------------------------------------------------------------------------------- |
| **Never**    | Don't archive projects automatically. You can manually archive projects by using the Archive Document action, if needed. |
| **Question** | Be prompted to choose whether to archive a project when one of the events mentioned earlier occurs.                      |
| **Always**   | Silently archive the project automatically when one of the events mentioned earlier occurs.                              |

You can reuse earlier versions of archived projects, if needed. For archived projects where the original still exists and isn't posted, you can use the **Restore** action to overwrite the current project with an archived version.

To keep database size under control, archived projects are added to a list of Retention policy tables.

The following are known limitations:

- The **Statistics** page isn't available on the **Archived Project Card** page.
- Dimensions aren't stored in the archive and can't be restored. When you restore a project, Business Central will use the default dimensions.

### Impact

<!-- Expected Impact to your client. -->

## Assemble to project

Assemble to project helps you improve inventory management by assembling to order only when it's required, and enable other ways to customize projects.

### Feature Details

When you enter an assemble-to-order item on a project planning line, an assembly order is automatically created. The assembly order is based on the project planning line, and its lines are based on the item’s assembly BOM. The quantity of components on the assembly BOM is multiplied by the order quantity. The **Assemble-to-Order Lines** page shows details about the linked assembly order lines. The details can help you customize the assembly item. As in sales, you can't directly post linked assembly orders. The created assembly order is reserved for the project, and Business Central synchronizes item tracking between project planning lines and assembly orders. The feature integrates with warehouse management features to make assembly and shipping easier, and ensure that the workflow from project assembly to delivery runs smoothly.

Assemble to project supports the following warehouse configurations:

- **No warehouse handling:** Use a project journal to post full or partial usage. The output and consumption of components post automatically for the assembly order.
- **Inventory pick:** Use an inventory pick to post full or partial usage. The output and consumption of components post automatically for the assembly order.
- **Warehouse pick:** Create and register warehouse picks for components, and then use a project journal to post usage. Business Central verifies whether the consumed assembly components were picked. The output and consumption of components post automatically for the assemble order.

You can also use the **Explode BOM** action in the **Project Planning Lines** to convert the product into a set of components.

The following are known limitations:

- The **Quantity to Assemble to Order** field isn't available for closed projects.
- For warehouse pick scenarios, the **Quantity to Assemble to Order** can be either zero or equal to the quantity. You can't mix assemble to order and assemble to stock on a project planning line. You must create separate project planning lines.
- Assemble to order does not affect billable parts of a project. An assembly is included on sales invoices, but not its components. You can't edit the **Quantity to Assemble to Order** field for Billable lines (not Budget+Billable).
- Order planning and the planning worksheet aren't affected because the job is the input for planning. The planning engine considers the assembly as demand.
- You can't enter a negative quantity in the **Quantity to Assemble to Order** field.
- You can't undo an assembly.

### Impact

<!-- Expected Impact to your client. -->

## Connect Business Central with Shopify B2B

Connecting Shopify B2B and Business Central improves visibility into pricing, customers and their order histories, order status, billing, and payments. Better visibility means faster response to customer inquiries, timely returns and refunds, and more accurate order processing.

### Feature Details

The Shopify Connector now supports the latest features of Shopify's B2B platform, such as companies, prices, payment options and more. These features allow you to manage multiple buyers and groups, offer different pricing and discounts, and streamline your B2B operations. You can easily synchronize your Shopify B2B data with Business Central and automate your workflows. This helps save time, reduce errors, and increase customer satisfaction.

#### Adapt faster
Connecting Business Central with Shopify helps merchants around the world to implement more agile online business processes, while keeping their people focused on selling. With connected data across your online stores and business operations, you can rapidly respond to consumer demands to adjust product pricing and merchandising. With support for multitier pricing structures and multiple currencies, companies, and entities, Business Central easily supports multiple Shopify store scenarios.

#### Work smarter
Eliminating manual processes improves accuracy and lets people focus on taking care of customers. Connecting Shopify and Business Central improves visibility into stock, pricing, existing customers and their order histories, order status, billing, and payments. Better visibility means faster response to customer inquiries, timely returns and refunds, and more accurate order processing.

#### Perform better
Enhanced operational efficiency not only saves you time and reduces costs, it can also translate into better results and faster decision-making. You'll have the confidence to expand your online presence while minimizing overhead with automatic synchronization between systems for price changes, product updates, and customers. At the end of accounting periods, Business Central will help with the financial reporting and tax reporting required by local legislation.

##### Details
To make sure that both the D2C and B2B flows are supported, the current customer synchronization flow focuses on D2C scenarios and a new flow is available for B2B customers.

#### Customer Sync D2C
**Export Customers To Shopify** is removed. The Connector won't export all existing Business Central customers automatically. Instead, on the **Shopify Customer** page, use the **Add Customers to Shopify** action. On the request page, specify the Shopify Shop and filters if you want to export a subset of customers. The Connector checks whether a customer with the same phone number or email address already exists in Shopify. If it finds a match, it maps it to a customer in Business Central. If it doesn't find a match, it creates a new customer.

You can also open the **Shopify Customer**s page by using the **Customers** action on the **Shopify Shop** card.

#### Company B2B
There are several new actions in the **Shop Card** page:

- Related > Companies
- Reset Companies Sync action

The B2B fields work in a similar way as their counterparts for the Customer D2C synchronization:

- **Can Update Shopify Companies**
- **Default Permission on Contact** that is assigned to the contact linked to the company. Possible options are: No permission, Ordering only, Location admin
- **Company import type**
- **Can Shopify Update Companies**
- **Auto Create Unknown Companies**
- **Auto Create Catalog**: If for exported company you want to create a catalog automatically. You can assign a catalog manually from a list of Shopify catalogs

There's a new entity representing Company, for which we added the following objects:

- Company Table
- Company List
- Company Card
- Main Contact Factbox
- Company Location Table

New actions allow you to add or synchronize a company to Shopify.

The **Add Company to Shopify** action and report do the following:

- Create a customer and company in Shopify
- Add a customer as the main contact
- Add location ‘Main’ (this is subject to change)
- Add a catalog, depending on your settings

The **Sync Company** action and report which, depending on the synchronization direction, either updates the company in Shopify or imports a company to Business Central. In the latter case, the Connector does the following:

- Retrieves the company, main contact, and location and map Company/Customer, updated (if allowed) or create (if allowed).

For catalogs, we've added the following:

- Catalog Table
- Catalog List
- Price synchronization settings for each catalog. These settings are similar to the price settings in the Shopify Shop card FastTab.
- Hyperlink to Shopify Admin to review and manage products included in the catalog.

You can import catalogs from Shopify, assign them to companies, set price calculation settings, and trigger a price update for catalogs.

#### Orders
Imported orders use the D2C customer or, if available, the B2B company information to look for a mapping of bill-to and sell-to customers.

### Impact

<!-- Expected Impact to your client. -->

## Define a service invoice posting policy for various users

Companies often have unique processes for invoices and shipments. For example, processes can vary from one person posting everything on a service order to multiple employees, each working with their own pages. A setting on the **User Setup** page lets you specify how each user can process service invoices.

### Feature Details

You can use posting policies to restrict users from posting service invoices, or require them to post invoices together with the related service shipment. To specify a posting policy, on the User Setup page, choose one of the following options in the Service Invoice Posting Policy field:

- **Allowed** (Default): Keep the current behavior, where you can choose the posting option, such as **Ship**, **Invoice**, and **Ship and Invoice**.
- **Prohibited**: Prevent people from posting invoices. Business Central shows a confirmation dialog that provides only the **Ship** option.
- **Mandatory**: Let people post invoices along with service shipments. Business Central shows a confirmation dialog with the **Ship and Invoice** option.

The setting affects the following documents:

- Service orders
- Warehouse shipments
- Service invoices
- Service credit memos

The following table describes the effects on different documents.

| Document            | Option 1: Allow<br />Displays a series of options      | Option 2: Prohibited<br />Confirmation dialog	Option | 3: Mandatory<br />Confirmation dialog         |
| ------------------- | ------------------------------------------------------ | ---------------------------------------------------- | --------------------------------------------- |
| Service Order       | <li>Ship</li><li>Invoice</li><li>Ship and Invoice</li> | Do you want to post the shipment?                    | Do you want to post the shipment and invoice? |
| Warehouse Shipment  | <li>Ship</li><li>Ship and Invoice</li>                 | Do you want to post the shipment?                    | Do you want to post the shipment and invoice? |
| Service invoice     | No options                                             | Do you want to post the invoice?                     | Do you want to post the invoice?              |
| Service credit memo | No options                                             | Do you want to post the credit memo?                 | Do you want to post the credit memo?          |

#### Note

When you post service invoices and credit memos, you don't have any posting options. The documents always post the physical and financial transactions together. You can't partially post invoices and credit memos.

### Impact

<!-- Expected Impact to your client. -->

## Define default location for project or project phase

Reduce the time you spend on data entry and focus more on core tasks by specifying a default location and bin for projects on the Project Card page. When you create project tasks, project planning lines, and project journal lines for the project, the default location and bin are automatically assigned. Stay flexible with the ability to change the location code and bin on tasks and lines if needed.

### Feature Details

Specify a default **Location Code** and **Bin Code** on the **Project** and **Project Task Lines Subform** pages. Similar to production order processes, these default values simplify data entry on project tasks, project planning lines, and project journal lines.

#### Project Card page
The Location Code and Bin Code are available on the Posting Tab. If you define a To-Project Bin Code on the location, the bin code is populated when you select the location code. If your warehouse flow requires warehouse picks, you can also define other bins from which to consume items.

These fields are the defaults when you create project tasks. Changes won't be made to existing project tasks.

#### Project tasks
The Location Code and Bin Code don't display by default, but you can add them through personalization. These fields are the defaults when you create project planning lines and project journal lines. Changes won't be made to existing lines.

#### Project planning lines
The Location Code is based on the value selected on the job planning line when you select an item. If a bin code isn't defined for the project task, the bin from the default bin content is selected. You can change both values manually.

#### Project journal lines
The Location Code is based on the value selected on the job journal line when you select an item. If a bin code isn't defined for the project task, the bin from default bin content is selected. You can change both values manually.

#### Purchase lines
This change doesn't affect purchase documents.

### Impact

<!-- Expected Impact to your client. -->

## Get more productive while entering time sheets

Copying time sheets from previous periods can save you time and effort by reducing the need to manually enter data. The process improves productivity and efficiency by allowing you to quickly and easily create time sheets based on data you already have. Additionally, copying time sheets can help to ensure that your data is consistent and accurate by reducing the risk of data entry errors.

### Feature Details

We've made it faster and more efficient to fill out time sheets. You can use the **Copy From** action on the **Time Sheet** page to copy information from lines on previous time sheets. You can also copy information from the previous row on your time sheet. For example, when you're filling out a time sheet where you've worked on the same job, you might want to copy the job or job task numbers.

### Impact

<!-- Expected Impact to your client. -->