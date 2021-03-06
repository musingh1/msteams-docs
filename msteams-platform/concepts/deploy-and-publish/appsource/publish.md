---
title: Microsoft Teams app approval process guidance
description: Describes the approval process for getting your app published to the Microsoft Teams app store
keywords: teams publish store office publishing AppSource
---
# Submit your app to AppSource

Publish your app on AppSource to make it available to your end users in the Teams app catalog and on the web. At a high level, the process for submitting your app to AppSource is:

1. Develop your app following our [design guidelines](~/concepts/design/understand-use-cases.md). Tabs should follow our [tab design guidelines](~/tabs/design/tabs.md) and your bot should follow the [bot design guidelines](~/bots/design/bots.md).
2. [Register as a developer](#register-as-a-developer) with Microsoft.
3. Prepare your app for submission: Make sure your app passes the [Submission checklist](~/concepts/deploy-and-publish/appsource/prepare/overview.md)
4. Go through our [Tips and most frequently failed cases](~/concepts/deploy-and-publish/appsource/prepare/frequently-failed-cases.md) for a quicker approval process.
5. Submit your package to App Source through [Partner Center](/office/dev/store/use-partner-center-to-submit-to-appsource) and monitor your Partner Center dashboard to track approval.
6. Post submission: Check our guidance for [Maintaining and supporting your published app](~/concepts/deploy-and-publish/appsource/post-publish/overview.md).

## Register as a developer

You must register as **both** Microsoft app developer and developer in seller dashboard in order to publish your app.

* [Register as a Microsoft app developer](#register-as-a-microsoft-app-developer).
* [Register as a developer in the Seller Dashboard](#register-in-the-seller-dashboard-to-submit-to-appsource).

### Register as a Microsoft app developer

If you have already registered in the Microsoft Store ecosystem, either by distributing a Universal Windows App (UWA) via the Windows Store or an Office or SharePoint add-in via AppSource, you should use this account to distribute your Microsoft Teams app. Otherwise, you must first [Register as an app developer](https://developer.microsoft.com/store/register) to create your publisher identity in the Microsoft Store ecosystem. Account registration allows you to secure your company identity and triggers validation checks by the Microsoft Store team to ensure you are who you say you are.

Account management in the Microsoft Store ecosystem relies on a [Microsoft account](https://account.microsoft.com/account). This identity will be the main administrator/owner of your AppSource experience. For more information, please review [Opening a developer account](/windows/uwp/publish/opening-a-developer-account) and the [Developer program FAQ](https://developer.microsoft.com/store/register/faq).

* Create a Microsoft account specifically for your developer/AppSource account. Keep this account and password confidential, and share it only with your release team.
* If you've developed with a trial developer Office 365 account, do not use this account for your AppSource identity. Create a separate Microsoft account instead.

### Register in the Seller Dashboard to submit to AppSource

A second approval process happens after you create your developer account: You need to create your identity in the [AppSource Seller Dashboard](https://sellerdashboard.microsoft.com/Application/Summary). Although the content here should be similar to the details of your developer account, this extra step ensures that AppSource has all the required information and that your identity in that storefront accurately reflects your business.

If you already submitted other product types to AppSource, this additional registration may not be necessary.

To start the process, choose the **Continue** button under **Office**.

![AppSource Seller Dashboard entry point](~/assets/images/submission/sellerdashboardofficeentry.png)

By developing and submitting a Microsoft Teams app that contains a bot, you are subject to the Bot Developer Framework [Terms of Use](https://aka.ms/bf-terms), [Privacy Policy](https://aka.ms/bf-privacy), and [Code of Conduct](https://aka.ms/bf-conduct). If your app contains Office 365 Connector functionality, separate terms may also apply as part of your Connector Registration on the [Connectors Developer Dashboard](https://aka.ms/connectorsdashboard).
