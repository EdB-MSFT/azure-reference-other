---
ms.service: azure-monitor
ms.topic: include
ms.date: 02/19/2024
ms.author: edbaynash
author: EdB-MSFT
ms.custom: microsoft.azuresphere/catalogs, naam

# NOTE:  This content is automatically generated using API calls to Azure. Any edits made on these files will be overwritten in the next run of the script. 
 
---


|Category|Metric|Name in REST API|Unit|Aggregation|Dimensions|Time Grains|DS Export|
|---|---|---|---|---|---|---|---|
|Device|**Device Events**<br><br>Count of all the events generated by an Azure Sphere device. |`DeviceEventsCount` |Count |Count |`DeviceId`, `EventCategory`, `EventClass`, `EventType`|PT1M |Yes|
|Device|**Device Requests**<br><br>Count of all the requests sent by an Azure Sphere device. |`DeviceRequestsCount` |Count |Count |`DeviceId`, `OperationName`, `ResultType`|PT1M |Yes|