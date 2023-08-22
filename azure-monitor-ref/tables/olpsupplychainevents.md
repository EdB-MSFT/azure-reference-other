---
title: Azure Monitor Logs reference - OLPSupplyChainEvents
description: Reference for OLPSupplyChainEvents table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# OLPSupplyChainEvents

The events table captures every event that was dispatched from the Open Logistics Platform workspace. Events can be a result of a data plane API call (e.g. Shipment Created, Item Deleted, Notification sent, etc.) or a long running job operation completion (e.g. Data ingestion results in NewDataAvailable event).

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Microsoft.OpenLogisticsPlatform/Workspaces




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| CorrelationId | string | Unique identifier to be used to correlate logs with OLPSupplyChainEntityOperations. |
| DurationMs | real | Time it took to service the REST API request, in milliseconds. |
| EventBody | dynamic | The event body. |
| EventId | string | Unique identifier for each event. |
| EventType | string | The type of the event, can be Microsoft.OpenLogisticsPlatform.EntityCreated, Microsoft.OpenLogisticsPlatform.EntityUpdated etc. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OperationName | string | The operation name for which the log entry was created. |
| RequestId | string | Unique identifier to be used to correlate request logs. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| SupplyChainResourceType | string | The type of supplychain resource for which the event is generated, can be Item, Warehouse, WarehouseItem etc. |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp (UTC) when the log was created. |
| Type | string | The name of the table |
