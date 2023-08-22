---
title: Azure Monitor Logs reference - SynapseDXIngestionBatching
description: Reference for SynapseDXIngestionBatching table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SynapseDXIngestionBatching

Azure data explore synapse ingestion batching operations. These logs have detailed statistics of batches ready for ingestion (duration, batch size and blobs count)

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Synapse Workspaces




## Columns

| Column | Type | Description |
|---|---|---|
| BatchingType | string | Batching type: Whether the batch reached the limit of batching time, data size, or number of files set by the the batching policy |
| BatchSizeBytes | long | Total uncompressed size of data in this batch (bytes) |
| BatchTimeSeconds | real | Total batching time of this batch (seconds) |
| _BilledSize | real | The record size in bytes |
| Database | string | The name of the database holding the target table |
| DataSourcesInBatch | int | Number of data sources in this batch |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| RootActivityId | string | The operation's activity ID |
| SourceCreationTime | datetime | When the first blobs in this batch were created (UTC time) |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| Table | string | The name of the target table the data is ingested into |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The time (UTC) this event was generated |
| Type | string | The name of the table |
