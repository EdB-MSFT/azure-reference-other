---
title: Azure Monitor Logs reference - AppSystemEvents
description: Reference for AppSystemEvents table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AppSystemEvents

Application Insights system events.

## Categories

- Applications
## Solutions

- LogManagement
## Resource types

- Application Insights




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| EventType | string | Event type |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Measurements | dynamic | Event measurements. |
| Name | string | Event name |
| Properties | dynamic | Event properties. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Date and time when the system event was recorded. |
| Type | string | The name of the table |
