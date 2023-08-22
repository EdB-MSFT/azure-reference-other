---
title: Azure Monitor Logs reference - ADXJournal
description: Reference for ADXJournal table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADXJournal

Azure Data Explorer journal (metadata operations).

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Data Explorer Clusters




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| ChangeCommand | string | The executed control command that triggered the metadata change |
| CorrelationId | string | The client request ID |
| DatabaseName | string | The name of the database changed following the event |
| EntityContainerName | string | The entity container name (entity=column, container=table), or the database name |
| EntityName | string | The entity name that the operation was executed on, before the change |
| EntityVersion | string | The new metadata version (DB/cluster) following the change |
| Event | string | The metadata change event name |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OperationTimestamp | datetime | The timestamp (UTC) at which the metadata operation completed |
| OriginalEntityState | string | The state of the entity (entity properties) before the change |
| OriginalEntityVersion | string | The version of the entity (entity properties) before the change |
| Principal | string | The principal (user/app) that executed the control command |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| RootActivityId | string | The root activity ID of the operation which caused metadata change (for example: 2217ed0d-888f-4c3d-8776-973471be556e) |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The time (UTC) at which this log was sent to Log Analytics |
| Type | string | The name of the table |
| UpdatedEntityName | string | The new entity name after the change |
| UpdatedEntityState | string | The new state after the change |
| User | string | The user that executed the control command |
