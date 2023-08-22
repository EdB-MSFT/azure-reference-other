---
title: Azure Monitor Logs reference - SynapseSqlPoolSqlRequests
description: Reference for SynapseSqlPoolSqlRequests table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SynapseSqlPoolSqlRequests

Information about query distributions of the steps of SQL requests/queries in an Azure Synapse dedicated SQL pool.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Synapse Workspaces




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string | The category of the log. |
| Command | string | The command of the SQL requests. |
| DistributionId | int | The distribution id of the SQL requests. |
| EndTime | datetime | The end time (UTC) for the SQL requests. |
| ErrorId | string | The error id of the SQL requests. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LogicalServerName | string | The logical server name of the SQL DW. |
| OperationName | string | The operation associated with log record. |
| PdwNodeId | int | The PdwNodeId of the SQL requests. |
| RequestId | string | The request Id of the SQL requests. |
| ResourceGroup | string | The azure resourceGroup of the SQL DW. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| RowCount | int | The row count of the SQL requests. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SpId | int | The sp id of the SQL requests. |
| StartTime | datetime | The startTime (UTC) of the SQL requests. |
| Status | string | The Status of the SQL requests. |
| StepIndex | int | The step index of the SQL requests. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of when the log was generated. |
| Type | string | The name of the table |
