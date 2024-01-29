# Power Apps - 2024 Release Wave 1<!-- omit from toc -->

| Feature                                                                                                                                       | Early Access | Public Preview | General Availability | Expected Impact |
|:----------------------------------------------------------------------------------------------------------------------------------------------|:------------:|:--------------:|:--------------------:|:---------------:|
| [Access creation experiences with a modernized create page](#access-creation-experiences-with-a-modernized-create-page)                       |     ---      |    Apr 2024    |         ---          |                 |
| [Visualize and work with complex data using copilot](#visualize-and-work-with-complex-data-using-copilot)                                     |     ---      |    Apr 2024    |         ---          |                 |
| [Use modern screen templates to easily build canvas app screens](#use-modern-screen-templates-to-easily-build-canvas-app-screens)             |   Feb 2024   |      ---       |       Mar 2024       |                 |
| [Define sync settings on mobile devices for model-driven apps](#define-sync-settings-on-mobile-devices-for-model-driven-apps)                 |     ---      |   9 Oct 2023   |       Apr 2024       |                 |
| [Enjoy the new look of model-driven apps](#enjoy-the-new-look-of-model-driven-apps)                                                           |     ---      |      ---       |       Apr 2024       |                 |
| [Model-driven apps in Power Platform environments use monthly channel](#model-driven-apps-in-power-platform-environments-use-monthly-channel) |     ---      |      ---       |       Apr 2024       |                 |
| [Modernize maker experience security settings](#modernize-maker-experience-security-settings)                                                 |     ---      |    Apr 2024    |         ---          |                 |
| [Select columns downloaded on mobile devices](#select-columns-downloaded-on-mobile-devices)                                                   |     ---      |    Jun 2024    |   To be announced    |                 |
| [Share tables and apps as simple as sharing a Word document](#share-tables-and-apps-as-simple-as-sharing-a-word-document)                     |     ---      |    Jun 2024    |         ---          |                 |

# Copilot for Power Apps makers and users

## Access creation experiences with a modernized create page

This feature provides a modern create page designed for experienced makers. The modern create page prioritizes apps but includes paths to create everything you can make in Power Apps UI. Features include:

- Modern, unified design
- Intuitive hierarchy for easy wayfinding
- Prominent entry point for copilot creation 
- Optimized for experienced makers, but beneficial for new makers
- New tile design

### Impact

<!-- Expected impact to your client. -->

## Visualize and work with complex data using copilot

Today, Power Apps has established a WYSIWYG pattern well perceived by its makers for app building. However, when it comes to setting up the data model behind the app for suitable business logic, makers, experienced or not, still have to deal with the plain schema view of their tables and relationships as the only possible option. Now, following the same philosophy we bear for app building experiences, we are introducing a new data modeling experience through a WYSIWYG editor, where makers can create multiple tables with relationships from scratch, external data sources, or conversation with the assistance of copilot. Through the new data model editor, tables and relationships will be visualized in an ERD (entity relationship diagram) view, making it easier than ever to understand how tables and various other data objects work hand in hand. Moreover, with the assistance of copilot, maker productivity will be further boosted as copilot makes it possible to create complex data model consisting of several tables and relationships along with sample data in just a few clicks.

### Impact

<!-- Expected impact to your client. -->

# Building Modern Apps

## Use modern screen templates to easily build canvas app screens

The current canvas app screen templates will be updated with a new set of modernized screen templates. The new set of templates will have screens that are commonly built by makers, and will use modern controls and responsive containers.

### Impact

<!-- Expected impact to your client. -->

## Define sync settings on mobile devices for model-driven apps

Power Apps mobile app users get two new settings in the **Device status** page. These settings, which apply to model-driven apps, let users control the automatic sync intervals and the connection type.

- **WiFi only:** Lets users choose if their automatic sync happens on cellular networks and WiFi connections or only when connected to a WiFi network.
- **Auto sync:** Adjust the sync interval to sync more or less frequently depending on individual needs. Users can also choose not to automatically sync at any interval, if they only want to sync on demand.

### Impact

<!-- Expected impact to your client. -->

## Enjoy the new look of model-driven apps

Model-driven Power Apps now have an updated UI that is on by default. The updated UI provides updated styling including fonts, colors, borders, shadows, and more. The updated look makes model-driven apps easier to use so that users can accomplish their goals quickly and efficiently.

In 2024 release wave 1, the new look becomes the default experience for all model-driven app users. Users can opt out of the experience through the **New look** toggle on the top bar.

### Impact

<!-- Expected impact to your client. -->

## Model-driven apps in Power Platform environments use monthly channel

Model-driven apps running in Power Platform environments with the app release channel value of **Auto** will use monthly channel starting with 2024 release wave 1. This is the next step in gradually shifting from semi-annual channel to monthly channel to provide users with improvements as they become available. Apps in Dynamics 365 enabled environments with the app release channel value of **Auto** will continue to use semi-annual channel until the 2024 release wave 2. Features shipping in monthly channel can be found in [Monthly channel release notes for model-driven apps](https://learn.microsoft.com/en-us/power-platform/released-versions/common-data-service/unified-interface-monthly-releases).

When the model driven app release channel was added it contains values of **Auto**, **Monthly**, and **Semiannual**. The **Auto** value for app release channel provides the behavior if a maker has not made an explicit selection of **Monthly** or **Semiannual**. The value also allows us to gradually migrate usage. Existing apps default to **Auto** and as new apps are created they default to **Monthly**. If an app needs to continue using semi-annual channel, the maker can use the app designer to set the app release channel to **Semi-Annual Channel** before the 2024 release wave 1 to ensure no changes to the release channel behavior.

For more information, go to [Release Channel Overview](https://learn.microsoft.com/en-us/power-apps/maker/model-driven-apps/channel-overview).

### Impact

<!-- Expected impact to your client. -->

## Modernize maker experience security settings

Now, makers can configure security role settings in [Power Apps](https://make.powerapps.com/) using a new security role editor. This feature includes a new panel called **New Role** and lets makers configure column security profiles.

### Impact

<!-- Expected impact to your client. -->

## Select columns downloaded on mobile devices

In the settings of your offline-enabled app in the maker portal, you can customize the offline profile for an optimized data loading experience for your users. For each table, you can select the columns that are required in the app:

- Use the suggested columns computed by the system.
- Manually select the columns.

In the main page for the offline profile, you can see for each table how many columns are selected for download.

### Impact

<!-- Expected impact to your client. -->

## Share tables and apps as simple as sharing a Word document

The new experience will be similar to how you share apps in Microsoft 365. Makers will see a sharing dialog where they can select a list of users as well as what access to share with. Dataverse will then create security roles based on the access configuration and automatically assign to the selected users.

### Impact

<!-- Expected impact to your client. -->