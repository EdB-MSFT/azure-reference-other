---
title: Azure Monitor Logs reference - AutoscaleScaleActionsLog
description: Reference for AutoscaleScaleActionsLog table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AutoscaleScaleActionsLog



## Categories

- Azure Monitor
- Virtual Machines
- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Monitor autoscale settings




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string |   |
| CorrelationId | string |   |
| CreatedAsyncScaleActionJob | bool |   |
| CreatedAsyncScaleActionJobId | string |   |
| CurrentInstanceCount | int |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| NewInstanceCount | int |   |
| OperationName | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultDescription | string |   |
| ResultType | string |   |
| ScaleActionMessage | string |   |
| ScaleActionOperationId | string |   |
| ScaleActionOperationStatus | string |   |
| ScaleDirection | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TargetResourceId | string |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
