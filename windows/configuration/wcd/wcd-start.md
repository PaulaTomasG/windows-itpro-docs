---
title: Start (Windows 10)
description: This section describes the Start settings that you can configure in provisioning packages for Windows 10 using Windows Configuration Designer.
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
author: greg-lindsay
ms.localizationpriority: medium
ms.author: greglin
ms.topic: article
ms.date: 09/06/2017
ms.reviewer: 
manager: dansimp
---

# Start (Windows Configuration Designer reference)

Use Start settings to apply a customized Start screen to devices.

## Applies to

| Setting   | Windows client | Surface Hub | HoloLens | IoT Core |
| --- | :---: | :---: | :---: | :---: | 
| StartLayout | ✔️  | |  |  |

>[!IMPORTANT]
>The StartLayout setting is available in the advanced provisioning for Windows 10, but shouldn't be used. For Windows client, use [Policies > StartLayout](wcd-policies.md#start).

## StartLayout

Use StartLayout to select the `LayoutModification.xml` file that applies a customized Start screen to a mobile device.

