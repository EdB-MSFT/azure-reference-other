---
title: Azure Monitor Logs reference - ADFSSISIntegrationRuntimeLogs
description: Reference for ADFSSISIntegrationRuntimeLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADFSSISIntegrationRuntimeLogs

ADF SSIS integration runtime logs

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
| IntegrationRuntimeName | string | Integration runtime name |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | Verbosity level of log |
| Message | string | Event message |
| OperationName | string | The name of the operation represented by this event |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultType | string | Status of the log |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of the log |
| Type | string | The name of the table |
