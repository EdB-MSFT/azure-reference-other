---
title: Azure Monitor Logs reference - StorageCacheWarningEvents
description: Reference for StorageCacheWarningEvents table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# StorageCacheWarningEvents

Logs for Azure HPC Cache warning events.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure HPC Cache




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| CorrelationId | string | Unique identifier to be used to correlate logs, if available. |
| Description | string | The description of the warning event. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | The severity level of the event: Informational, Warning, Error, or Critical. |
| Location | string | The region of the resource associated with the event. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| State | string | The state of the warning: Active or Cleared. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp (UTC) when the log was created. |
| Type | string | The name of the table |
