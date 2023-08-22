---
title: Azure Monitor Logs reference - ADFTriggerRun
description: Reference for ADFTriggerRun table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADFTriggerRun



## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Data factories




## Columns

| Column | Type | Description |
|---|---|---|
| Annotations | string |   |
| _BilledSize | real | The record size in bytes |
| Category | string |   |
| CorrelationId | string |   |
| ErrorCode | string |   |
| ErrorMessage | string |   |
| EventMessage | string |   |
| Input | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string |   |
| Location | string |   |
| OperationName | string |   |
| Output | string |   |
| Parameters | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| Start | datetime |   |
| Status | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| SystemParameters | string |   |
| Tags | string |   |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime |   |
| TriggerEvent | string |   |
| TriggerFailureType | string |   |
| TriggerId | string |   |
| TriggerName | string |   |
| TriggerType | string |   |
| Type | string | The name of the table |
| UserProperties | string |   |
