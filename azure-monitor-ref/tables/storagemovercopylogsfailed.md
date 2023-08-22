---
title: Azure Monitor Logs reference - StorageMoverCopyLogsFailed
description: Reference for StorageMoverCopyLogsFailed table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# StorageMoverCopyLogsFailed

The result logs generated during the execution of Storage Mover job runs where the transfer result is 'Failed'. The logs include the details of the scanned items and their transfer result.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Storage Mover




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Details | string | The error description and any additional details if available. |
| FileSize | long | The file size in bytes (if available). Only applicable when item type is File. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ItemPath | string | Relative path of the item from the migration source, and target root directories. |
| ItemType | string | Type of the item, either 'F' for file, or 'D' for directory. |
| JobRunName | string | Unique name of the job run which generated this log. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StatusCode | string | The storage mover status code. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Time in UTC when the log was generated on the Storage Mover agent. |
| TransferResult | string | The final transfer result of the item. One of: Excluded, Failed, Transferred, NoCopyNecessary, Unsupported. |
| Type | string | The name of the table |
