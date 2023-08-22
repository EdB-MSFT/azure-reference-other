---
title: Azure Monitor Logs reference - ADXQuery
description: Reference for ADXQuery table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADXQuery

Azure Data Explorer query execution summary.

## Solutions

- LogManagement
## Resource types

- Azure Data Explorer Clusters




## Columns

| Column | Type | Description |
|---|---|---|
| ApplicationName | string | application name invoked the query |
| _BilledSize | real | The record size in bytes |
| CacheDiskHits | long | Disk cache hits |
| CacheDiskMisses | long | Disk cache misses |
| CacheMemoryHits | long | Memory cache hits |
| CacheMemoryMisses | long | Memory cache misses |
| CacheShardsBypassBytes | long | Shards cache bypass bytes |
| CacheShardsColdHits | long | Shards cold cache hits |
| CacheShardsColdMisses | long | Shards cold cache misses |
| CacheShardsHotHits | long | Shards hot cache hits |
| CacheShardsHotMisses | long | Shards hot cache misses |
| Category | string | The category of this log for this events it will be Query |
| ComponentFault | string | The entity that caused the query to fail. For example, if the query result is too large, the ComponentFault will be 'Client'. If an internal error occured, it will be 'Server' |
| CorrelationId | string | The client request id |
| DatabaseName | string | The name of the database the command ran on |
| Duration | string | Command duration |
| ExtentsMaxDataScannedTime | datetime | Maximum data scan time |
| ExtentsMinDataScannedTime | datetime | Minimum data scan time |
| FailureReason | string | The failure reason |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LastUpdatedOn | datetime | Time (UTC) at which this command ended |
| MemoryPeak | long | Memory peak |
| OperationName | string | The name of this operation |
| Principal | string | The principal that invoked the query |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| RootActivityId | string | The root activity id |
| ScannedExtentsCount | long | Scanned extents count |
| ScannedRowsCount | long | Scanned rows count |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StartedOn | datetime | Time (UTC) at which this command started |
| State | string | The State the command ended with |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TableCount | int | Table count |
| TablesStatistics | dynamic | Tables statistics |
| TenantId | string | The Log Analytics workspace ID |
| Text | string | The text of the invoked query |
| TimeGenerated | datetime | The time (UTC) at which this event was generated |
| TotalCPU | string | Total CPU duration |
| TotalExtentsCount | long | Total extents count |
| TotalRowsCount | long | Total rows count |
| Type | string | The name of the table |
| User | string | The user that invoked the query |
| WorkloadGroup | string | The workload group the query was classified to |
