---
title: Azure Monitor Logs reference - SynapseIntegrationPipelineRuns
description: Reference for SynapseIntegrationPipelineRuns table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SynapseIntegrationPipelineRuns

Logs for Synapse integration pipeline runs.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Synapse Workspaces




## Columns

| Column | Type | Description |
|---|---|---|
| Annotations | dynamic | The annotation details of the log record. |
| _BilledSize | real | The record size in bytes |
| Category | string | The category of the log. |
| CorrelationId | string | The correlationId for the log record. |
| End | datetime | The end time (UTC) for the pipelien run. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | The log type info level of the record. |
| Location | string | The location of the resource in the cloud where this log is originated. |
| OperationName | string | The operation associated with log record. |
| Parameters | dynamic | The parameter details of the pipeline run. |
| PipelineName | string | The name of the pipeline flow. |
| PipelineTenantId | string | The tenantId details of the pipeline run. |
| Predecessors | dynamic | The predecessors information of the pipeline log. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| RunId | string | The run id of the pipeline job. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| Start | datetime | The start time (UTC) of the pipeline run. |
| Status | string | The Status of the SQL requests. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| SystemParameters | dynamic | The system parameter details of the pipeline run. |
| Tags | dynamic | The associated tags of the log record. |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of when the log was generated. |
| Type | string | The type of the pipeline run. |
| UserProperties | dynamic | The user properties of the log record. |
