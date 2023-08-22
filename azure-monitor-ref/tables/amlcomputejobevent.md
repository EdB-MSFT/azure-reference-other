---
title: Azure Monitor Logs reference - AmlComputeJobEvent
description: Reference for AmlComputeJobEvent table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AmlComputeJobEvent

AmlCompute Job events

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Machine Learning




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| ClusterId | string |   |
| ClusterName | string |   |
| ClusterResourceGroupName | string |   |
| CreationApiVersion | string |   |
| CustomerSubscriptionId | string |   |
| ErrorDetails | string |   |
| EventType | string |   |
| ExecutionState | string |   |
| ExperimentId | string |   |
| ExperimentName | string |   |
| InternalOperationName | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| JobErrorMessage | string |   |
| JobId | string |   |
| JobName | string |   |
| NodeId | string |   |
| OperationName | string |   |
| ProvisioningState | string |   |
| ResourceGroupName | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultSignature | string |   |
| RunInContainer | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TFParameterServerCount | string |   |
| TFWorkerCount | string |   |
| TimeGenerated | datetime |   |
| ToolType | string |   |
| Type | string | The name of the table |
| WorkspaceName | string |   |
