---
title: Microsoft 365 Defender streaming event types supported in Event Streaming API
description: Learn which streaming event types (tables) are supported by the streaming API
keywords: raw data export, Streaming API, API, Event hubs, Azure storage, storage account, Hunting, raw data sharing
search.product: eADQiWindows 10XVcnh
search.appverid: met150
ms.service: microsoft-365-security
ms.subservice: m365d
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: 
- m365-security
- tier3
ms.topic: article
---

# Supported Microsoft 365 Defender streaming event types in event streaming API

[!INCLUDE [Microsoft 365 Defender rebranding](../../includes/microsoft-defender.md)]

**Applies to:**
- [Microsoft 365 Defender](https://go.microsoft.com/fwlink/?linkid=2118804)

[!include[Prerelease information](../../includes/prerelease.md)]


The Event Streaming API is constantly being expanded to support more event types. Learn which Hunting tables are generally available, currently in public preview, or not yet supported. 
**New - Email event types/tables are now GA**

## Hunting tables support status in Event Streaming API

The following table only includes the list of the tables supported in the streaming API, and is not inclusive of all AH schema. For a full list of the API see, [Learn the schema tables](advanced-hunting-schema-tables.md#learn-the-schema-tables).

| Table name | Status<br>(Commercial) | GCC | GCC High | DoD |
|----|----|----|----|----|
| **[AlertEvidence](advanced-hunting-alertevidence-table.md)** | GA | GA | GA | GA |
| **[AlertInfo](advanced-hunting-alertinfo-table.md)** | GA | GA | GA | GA |
| **[DeviceEvents](advanced-hunting-deviceevents-table.md)** |GA | GA | GA | GA |
| **[DeviceFileCertificateInfo](advanced-hunting-DeviceFileCertificateInfo-table.md)** |GA | GA | GA | GA |
| **[DeviceFileEvents](advanced-hunting-devicefileevents-table.md)** | GA | GA | GA | GA |
| **[DeviceImageLoadEvents](advanced-hunting-deviceimageloadevents-table.md)** | GA | GA | GA | GA |
| **[DeviceInfo](advanced-hunting-deviceinfo-table.md)** | GA | GA | GA | GA |
| **[DeviceLogonEvents](advanced-hunting-devicelogonevents-table.md)** | GA | GA | GA | GA |
| **[DeviceNetworkEvents](advanced-hunting-devicenetworkevents-table.md)** |GA | GA | GA | GA |
| **[DeviceNetworkInfo](advanced-hunting-devicenetworkinfo-table.md)** | GA | GA | GA | GA |
| **[DeviceProcessEvents](advanced-hunting-deviceprocessevents-table.md)** | GA | GA | GA | GA |
| **[DeviceRegistryEvents](advanced-hunting-deviceregistryevents-table.md)** | GA | GA | GA | GA |
| **[EmailAttachmentInfo](advanced-hunting-emailattachmentinfo-table.md)** | GA |![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
| **[EmailEvents](advanced-hunting-emailevents-table.md)** | GA |![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
| **[EmailPostDeliveryEvents](advanced-hunting-emailpostdeliveryevents-table.md)** | GA |![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
| **[EmailUrlInfo](advanced-hunting-emailurlinfo-table.md)** | GA |![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
| **[IdentityLogonEvents](advanced-hunting-identitylogonevents-table.md)**|GA|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
| **[IdentityQueryEvents](advanced-hunting-identityqueryevents-table.md)**|GA|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
| **[IdentityDirectoryEvents](advanced-hunting-identitydirectoryevents-table.md)**|GA|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
| **[CloudAppEvents](advanced-hunting-cloudappevents-table.md)**|GA|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|![No](../defender-endpoint/images/svg/check-no.svg)|
