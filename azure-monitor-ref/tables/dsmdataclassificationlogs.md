---
title: Azure Monitor Logs reference - DSMDataClassificationLogs
description: Reference for DSMDataClassificationLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# DSMDataClassificationLogs

Contains data classification information provided by Azure Purview and is used to correlate storage resource logs with data sensitivity information.

## Categories

- Security
- Azure Resources
## Solutions

- LogManagement




## Columns

| Column | Type | Description |
|---|---|---|
| AssetLastScanTime | datetime | The time (UTC) when the resource scan for sensitivity was performed by Azure Purview. |
| AssetType | string | Type of asset that was scanned by Azure Purview (e.g., File, Table). |
| _BilledSize | real | The record size in bytes |
| ClassificationDetails | dynamic | For every classification found in the resource - corresponding Instance Count (i.e. how many occurrences of a specific type of classification was present) and Confidence (i.e. Match Accuracy) is listed. |
| Classifications | dynamic | JSON containing the list of classifications that were discovered. |
| CorrelationId | string | The ID that is used to correlate resource logs with data sensitivity logs. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SourceType | string | Type of resource that was scanned by Azure Purview (Azure Blob, Azure File, etc.). |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The time (UTC) when Azure Purview scan of asset occurred. |
| Type | string | The name of the table |
| Uri | string | Uniform resource identifier representing the asset that was scanned. |
