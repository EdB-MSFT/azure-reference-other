---
title: Azure Monitor Logs reference - AEWComputePipelinesLogs
description: Reference for AEWComputePipelinesLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AEWComputePipelinesLogs

AEWComputePipelines Events for the Experiment Workspace.

## Categories

- Azure Resources
- Audit
## Solutions

- LogManagement
## Resource types

- Experiment Workspace




## Columns

| Column | Type | Description |
|---|---|---|
| AnalysisId | string | The ID of your experiment study. |
| AnalysisType | string | The type of your analysis. |
| _BilledSize | real | The record size in bytes |
| EventName | string | The event name. |
| ExperimentationGroup | string | Experimentation group name of your experiment. |
| ExperimentId | string | The GUID of your experiment. |
| ExperimentStepId | string | The GUID of your experiment step. |
| ExperimentWorkspaceId | string | The Guid ID of your experimentation workspace. |
| FeatureId | string | The GUID of your experiment feature. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Properties | dynamic | Event properties in Experimentation Platform Compute Pipeline with json format. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ScorecardId | string | The ID of your experiment scorecard. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Time (UTC) of the HTTP request. |
| Type | string | The name of the table |
