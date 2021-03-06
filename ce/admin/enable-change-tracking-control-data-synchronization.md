---
title: "Enable change tracking to control data synchronization for Dynamics 365 for Customer Engagement apps | MicrosoftDocs"
ms.custom: 
ms.date: 09/30/2017
ms.reviewer: 
ms.service: crm-online
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
applies_to: 
  - Dynamics 365 for Customer Engagement  (online)
  - Dynamics 365 for Customer Engagement  Version 9.x
ms.assetid: 3fa9c316-9dc9-4b28-9abf-43a3fce5b01d
caps.latest.revision: 5
author: jimholtz
ms.author: jimholtz
manager: brycho
search.audienceType: 
  - admin
search.app: 
  - D365CE
  - Powerplatform
---
# Enable change tracking to control data synchronization

[!INCLUDE[cc-applies-to-update-9-0-0](../includes/cc_applies_to_update_9_0_0.md)]<br/>[!INCLUDE[cc_applies_to_on-prem-9_0_0](../includes/cc_applies_to_on-prem-9_0_0.md)]

Large [!INCLUDE[pn_microsoftcrm](../includes/pn-dynamics-crm.md)] apps organizations that synchronize their data with external data sources can now enable entities for change tracking. You can export or retrieve a selected set of [!INCLUDE [pn-crm-shortest](../includes/pn-crm-shortest.md)] apps data, and then keep the external data warehouse in sync.  
  
 By selecting, or deselecting, change tracking for specific entities you can reduce the load on your server resources and save processing time when extracting [!INCLUDE [pn-crm-shortest](../includes/pn-crm-shortest.md)] apps data and synchronizing it to an external store. You can enable change tracking for both system and custom entities.  
  
1. [!INCLUDE[proc_customization_customize_system](../includes/proc-customization-customize-system.md)]  
  
2. Select an entity, and under **Data Services**, select the **Change Tracking** check box.  
  
   ![Select Change Tracking for an entity](../admin/media/change-tracking.PNG "Select Change Tracking for an entity")  
  
### See also  
 [](../admin/manage-your-data.md "Manage your data")
