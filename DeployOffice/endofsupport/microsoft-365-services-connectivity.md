---
title: "Office versions and connectivity to Microsoft 365 services"
ms.author: danbrown
author: DHB-MSFT
manager: dougeby
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
ms.localizationpriority: high
search.appverid: MET150
ms.collection: Ent_O365
ms.custom: Ent_Office_ProPlus
recommendations: true
adobe-target: true
description: "Provides Office admins with information what versions of Office are supported for connecting to Microsoft 365 (and Office 365) services and the implications of using older Office clients."
---

# Office versions and connectivity to Microsoft 365 services

From October 13, 2020 onward, only these versions of Office are supported for connecting to Microsoft 365 (and Office 365) services:

- Microsoft 365 Apps for enterprise *(previously named Office 365 ProPlus)*
- Microsoft 365 Apps for business *(previously named Office 365 Business)*
- Office LTSC 2021, such as Office LTSC Professional Plus 2021
- Office 2019, such as Office Professional Plus 2019
- Office 2016, such as Office Standard 2016

> [!NOTE]
> Office 2019 and Office 2016 will be supported for connecting to Microsoft 365 (and Office 365) services until October 2023.

Examples of Microsoft 365 services include Exchange Online, SharePoint Online, and OneDrive for Business.

For Microsoft 365 Apps, you must be using a supported version. For a list of which versions are currently supported, see [Update history for Microsoft 365 Apps](/officeupdates/update-history-microsoft365-apps-by-date).

> [!IMPORTANT]
> We won’t take any active measures to block other versions of the Office client that are still supported and are up to date, such as Office 2013 with Service Pack 1, from connecting to Microsoft 365 services. But these older clients may encounter performance or reliability issues over time.

## Impact of using older Office clients to connect to Microsoft 365 services

After October 13, 2020, ongoing investments to our cloud services won't take into account older Office clients. Over time, these Office clients may encounter performance or reliability issues. Organizations that use these older clients will almost certainly face an increased security risk and may find themselves out of compliance depending upon specific regional or industry requirements.

Therefore, administrators should update older Office clients to versions of Office supported for connecting to Microsoft 365 services.

## Upgrade resources available to administrators

We recommend that you upgrade older Office clients to a subscription version of the Office client, such as Microsoft 365 Apps for enterprise. The most up-to-date subscription versions of the Office client are always supported connecting to Microsoft 365 services.

We provide various services to help you upgrade to subscription versions of the Office client. The following list provides some examples of resources that are available:

- [Microsoft FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/office-365?rtc=1), for migration and deployment assistance from Microsoft experts.
- [App Assure](https://www.microsoft.com/fasttrack/microsoft-365/app-assure?rtc=1), for assistance from Microsoft with application compatibility issues.
- [Deployment guide for Microsoft 365 Apps](../deployment-guide-microsoft-365-apps.md), for technical documentation.
- [Product lifecycle dashboard](/mem/configmgr/core/clients/manage/asset-intelligence/product-lifecycle-dashboard) and [upgrade readiness dashboard](/mem/configmgr/sum/deploy-use/office-365-dashboard#bkmk_o365_readiness), for users of Microsoft Endpoint Configuration Manager (current branch).
- [Readiness Toolkit for Office add-ins and VBA](../readiness-toolkit-application-compatibility-microsoft-365-apps.md), to help identify potential issues with add-ins and VBA macros used in your organization.

## Other changes related to connectivity to Microsoft 365 services

### Retirement of TLS 1.0 and 1.1

After October 15, 2020, you must be using at least TLS 1.2 to connect to Microsoft 365 services. For more information, see [Disabling TLS 1.0 and 1.1 for Microsoft 365](/microsoft-365/compliance/tls-1.0-and-1.1-deprecation-for-office-365) and [Preparing for TLS 1.2 in Office 365 and Office 365 GCC](/microsoft-365/compliance/prepare-tls-1.2-in-office-365).

### Basic authentication with Exchange Online

There are some changes planned related to the use of Basic Authentication with Exchange Online. For more information, see [Basic Authentication Deprecation in Exchange Online – May 2022 Update](https://techcommunity.microsoft.com/t5/exchange-team-blog/basic-authentication-deprecation-in-exchange-online-may-2022/ba-p/3301866).

### Retirement of Skype for Business Online

Skype for Business Online was retired on July 31, 2021. For more information, see [Skype for Business Online retirement](/microsoftteams/skype-for-business-online-retirement).

### Minimum version requirements for Outlook for Windows

> [!NOTE]
> - The information in this section was communicated in the following Message center post in the Microsoft 365 admin center.
>   - Message ID: MC229143
>   - Message title: Update to Microsoft 365 and Outlook for Windows connectivity
>   - Publish date: December 9, 2020.
>
> - For more information, see the [New minimum Outlook for Windows version requirements for Microsoft 365](https://techcommunity.microsoft.com/t5/microsoft-365-blog/new-minimum-outlook-for-windows-version-requirements-for/ba-p/2684142) blog post on the Microsoft Tech Community.
>
> - This information only applies to Outlook for Windows. It doesn't apply to Outlook on other operating systems, such as macOS, iOS, or Android.

Starting on November 1, 2021, the following versions are the minimum versions of Outlook for Windows you need to be using to be able to connect to Microsoft 365 services, such as Exchange Online.

- Version 1706 of Microsoft 365 Apps
- Version 16.0.4600.1000 of Office 2016 (with the November 2017 Update, [KB 4051890](https://support.microsoft.com/topic/e61d9ede-8ba3-aa75-9887-15fb20f847c7))
- Version 15.0.4971.1000 of Office 2013 (Service Pack 1 with the October 2017 Update, [KB 4043461](https://support.microsoft.com/help/4043461))

All versions of Outlook 2019 should be able to connect to Microsoft 365 services, but only the most current version is supported.

Even though newer versions of Outlook 2013 might be able to connect to Microsoft 365 services, it's not supported and you may encounter performance or reliability issues.

Versions of Outlook that are newer than those versions listed, but aren't the most current (supported) versions, may experience connectivity issues. To find what is the most current (supported) version, see the following articles:
- [Update history for Microsoft 365 Apps (listed by date)](/officeupdates/update-history-microsoft365-apps-by-date)
- [Update history for Office 2016 C2R and Office 2019](/officeupdates/update-history-office-2019)
- [Latest updates for versions of Outlook that use Windows Installer (MSI)](/officeupdates/outlook-updates-msi)

## Additional information about connectivity to Microsoft 365 services  

- Versions of Office LTSC 2021 will be supported for connecting to Microsoft 365 (and Office 365) services until October 2026.
- Connecting to Microsoft 365 services using Office 2016 for Mac isn’t supported. That’s because Office 2016 for Mac reached its end of support on October 13, 2020.
- The following versions of Project are supported for connecting to Microsoft 365 (and Office 365) services:
  - Project Online Desktop Client
  - Project Professional 2021 and Project Standard 2021
  - Project Professional 2019 and Project Standard 2019 *(until October 2023)*
  - Project Professional 2016 and Project Standard 2016 *(until October 2023)*
- The following versions of Visio are supported for connecting to Microsoft 365 (and Office 365) services:
  - Visio desktop app that comes with a Visio Plan 2 subscription
  - Visio LTSC Professional 2021 and Visio LTSC Standard 2021
  - Visio Professional 2019 and Visio Standard 2019 *(until October 2023)*
  - Visio Professional 2016 and Visio Standard 2016 *(until October 2023)*
- This information about connecting to Microsoft 365 services doesn't apply to InfoPath 2013 or SharePoint Designer 2013.
- For end of support dates for different versions of Office on various versions of Windows, see the [Office configuration support matrix](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE2OqRI).
- To discuss or learn more about end of support for Office versions, visit [Microsoft Office End of Support on the Microsoft Tech Community](https://techcommunity.microsoft.com/t5/microsoft-office-end-of-support/ct-p/OfficeEOS).
