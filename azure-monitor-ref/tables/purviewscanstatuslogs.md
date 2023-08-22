---
title: Azure Monitor Logs reference - PurviewScanStatusLogs
description: Reference for PurviewScanStatusLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# PurviewScanStatusLogs

Status of the scan on the data sources.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Microsoft.Purview/accounts




## Columns

| Column | Type | Description |
|---|---|---|
| AssetsClassified | long | Number of assets classified from the scan. |
| AssetsDiscovered | long | Number of assets discovered from the scan. |
| _BilledSize | real | The record size in bytes |
| Category | string | Log type category. |
| CorrelationId | string | The ID for correlated events. Can be used to identify correlated events between multiple tables. |
| DataSourceName | string | Name of the data source where the scan is run. |
| DataSourceType | string | Type of data source where the scan is run. For example: AzureDataExplorer, SQLServer etc. |
| ErrorDetails | string | Error detail while running the scan. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LogLevel | string | Log level of message (INFO, WARN, ERROR, etc.). |
| OperationName | string | The operation associated with log record. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultType | string | Result of the scan at the current state. For example: Throttled, Queued etc. |
| RunType | string | Run Type of the scan. For example: Manual, Scheduled etc. |
| ScanName | string | Name of the scan associated with the scan status log event. |
| ScanQueueTimeInSeconds | long | Time spent by this scan waiting in the queue. |
| ScanResultId | string | Guid of the Scan Result. |
| ScanTotalRunTimeInSeconds | long | Total time to complete the scan. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) when the log was generated. |
| Type | string | The name of the table |
