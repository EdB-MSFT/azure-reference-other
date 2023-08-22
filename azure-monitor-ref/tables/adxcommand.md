---
title: Azure Monitor Logs reference - ADXCommand
description: Reference for ADXCommand table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADXCommand

Azure Data Explorer command execution summary.

## Solutions

- LogManagement
## Resource types

- Azure Data Explorer Clusters




## Columns

| Column | Type | Description |
|---|---|---|
| ApplicationName | string | application name invoked the command |
| _BilledSize | real | The record size in bytes |
| Category | string | The category of this log for this events it will be Command |
| CommandType | string | Command type |
| CorrelationId | string | The client request id |
| DatabaseName | string | The name of the database the command ran on |
| Duration | string | Command duration |
| FailureReason | string | The failure reason |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LastUpdatedOn | datetime | Time (UTC) at which this command ended |
| OperationName | string | The name of this operation |
| Principal | string | The principal that invoked the query |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceUtilization | dynamic | Command resource utilization |
| RootActivityId | string | The root activity id |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StartedOn | datetime | Time (UTC) at which this command started |
| State | string | The State the command ended with |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| Text | string | The text of the invoked command |
| TimeGenerated | datetime | The time (UTC) at which this event was generated |
| TotalCPU | string | Total CPU duration |
| Type | string | The name of the table |
| User | string | The user that invoked the query |
| WorkloadGroup | string | The workload group the command was classified to |
