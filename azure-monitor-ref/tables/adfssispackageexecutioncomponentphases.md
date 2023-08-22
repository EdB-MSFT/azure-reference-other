---
title: Azure Monitor Logs reference - ADFSSISPackageExecutionComponentPhases
description: Reference for ADFSSISPackageExecutionComponentPhases table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADFSSISPackageExecutionComponentPhases

ADF SSIS package execution component phases

## Solutions

- LogManagement
## Resource types

- Data factories




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string | The name of the log that belongs to |
| CorrelationId | string | correlation id |
| DataFactoryName | string | Data factory name |
| EndTime | datetime | End time |
| ExecutionId | long | Execution id |
| ExecutionPath | string | Execution path |
| IntegrationRuntimeName | string | Integration runtime name |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | Verbosity level of log |
| OperationName | string | The name of the operation represented by this event |
| PackageName | string | Package name |
| Phase | string | Phase |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StartTime | datetime | Start time |
| SubcomponentName | string | Subcomponent name |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TaskName | string | Task name |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of the log |
| Type | string | The name of the table |
