---
title: Azure Monitor Logs reference - AegDeliveryFailureLogs
description: Reference for AegDeliveryFailureLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AegDeliveryFailureLogs

Azure Event Grid - event delivery failure logs.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Event Grid Topics
- Event Grid Domains
- Event Grid Partner Topics
- Event Grid System Topics




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string | Log category name. |
| EventSubscriptionName | string | Name of the event subscription. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Message | string | Log message for the user. |
| OperationName | string | Name of the operation. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubResourceName | string | Name of the sub resource. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Time when log was generated. |
| Type | string | The name of the table |
