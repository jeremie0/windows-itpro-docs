---
title: Microsoft Defender ATP preview features
description: Learn how to access Microsoft Defender Advanced Threat Protection preview features.
keywords: preview, preview experience, Microsoft Defender Advanced Threat Protection, features, updates
search.product: eADQiWindows 10XVcnh
search.appverid: met150
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: M365-security-compliance 
ms.topic: conceptual
---

# Microsoft Defender ATP preview features

**Applies to:**
- [Microsoft Defender Advanced Threat Protection (Microsoft Defender ATP)](https://go.microsoft.com/fwlink/p/?linkid=2069559)

The Microsoft Defender ATP service is constantly being updated to include new feature enhancements and capabilities.

>Want to experience Microsoft Defender ATP? [Sign up for a free trial.](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?ocid=docs-wdatp-preview-abovefoldlink) 

Learn about new features in the Microsoft Defender ATP preview release and be among the first to try upcoming features by turning on the preview experience.

For more information on new capabilities that are generally available, see [What's new in Microsoft Defender ATP](whats-new-in-microsoft-defender-atp.md).

## Turn on preview features
You'll have access to upcoming features which you can provide feedback on to help improve the overall experience before features are generally available.

Turn on the preview experience setting to be among the first to try upcoming features.

1. In the navigation pane, select **Settings** > **Advanced features** > **Preview features**.

2. Toggle the setting between **On** and **Off** and select **Save preferences**.

## Preview features
The following features are included in the preview release:

- [Threat & Vulnerability Management Report inaccuracy](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/tvm-security-recommendation#report-inaccuracy) <BR> You can report a false positive when you see any vague, inaccurate, incomplete, or already remediated [security recommendation](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/tvm-security-recommendation#report-inaccuracy), [software inventory](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/tvm-software-inventory#report-inaccuracy), and [discovered vulnerabilities](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/tvm-weaknesses#report-inaccuracy).  
 
- [Threat & Vulnerability Management Advanced Hunting Schemas](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/advanced-hunting-registryevents-table) <BR> You can now use the Threat & Vulnerability Management tables in the Advanced hunting schema to query about software inventory, vulnerability knowledgebase, security configuration assessment, and security configuration knowledgebase. 
 
 - [Threat & Vulnerability Management role-based access controls](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/user-roles#create-roles-and-assign-the-role-to-an-azure-active-directory-group) <BR> You can now use the new permissions to allow maximum flexibility to create SecOps-oriented roles, Threat & Vulnerability Management-oriented roles, or hybrid roles so only authorized users are accessing specific data to do their task. You can also achieve even further granularity by specifying whether a Threat & Vulnerability Management role can only view vulnerability-related data, or can create and manage remediation and exceptions.

- [Threat & Vulnerability Management granular exploit details](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/tvm-weaknesses) <BR> You can now see a comprehensive set of details on the vulnerabilities found in your machine to give you informed decision on your next steps. The threat insights icon now shows more granular details, such as if the exploit is a part of an exploit kit, connected to specific advanced persistent campaigns or activity groups for which, Threat Analytics report links are provided that you can read, has associated zero-day exploitation news, disclosures, or related security advisories.

- [Machine health and compliance report](machine-reports.md)  The machine health and compliance report provides high-level information about the devices in your organization.

- [Information protection](information-protection-in-windows-overview.md)<BR>
Information protection is an integral part of Microsoft 365 Enterprise suite, providing intelligent protection to keep sensitive data secure while enabling productivity in the workplace. Microsoft Defender ATP is seamlessly integrated in Microsoft Threat Protection to provide a complete and comprehensive data loss prevention (DLP) solution for Windows devices.

    >[!NOTE]
    >Partially available from Windows 10, version 1809.

- [Integration with Microsoft Cloud App Security](microsoft-cloud-app-security-integration.md) <BR> Microsoft Cloud App Security leverages Microsoft Defender ATP endpoint signals to allow direct visibility into cloud application usage including the use of unsupported cloud services (shadow IT) from all Microsoft Defender ATP monitored machines.

    >[!NOTE]
    >Available from Windows 10, version 1809 or later.

- [Onboard Windows Server 2019](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/configure-server-endpoints#windows-server-version-1803-and-windows-server-2019) <BR> Microsoft Defender ATP now adds support for Windows Server 2019. You'll be able to onboard Windows Server 2019 in the same method available for Windows 10 client machines.

- [Power BI reports using Microsoft Defender ATP data](powerbi-reports.md) <br>
Microsoft Defender ATP makes it easy to create a Power BI dashboard by providing an option straight from the portal.

>Want to experience Microsoft Defender ATP? [Sign up for a free trial.](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?ocid=docs-wdatp-preview-belowfoldlink)  
