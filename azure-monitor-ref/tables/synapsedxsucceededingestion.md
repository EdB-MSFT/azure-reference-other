---
title: Azure Monitor Logs reference - SynapseDXSucceededIngestion
description: Reference for SynapseDXSucceededIngestion table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SynapseDXSucceededIngestion

Succeeded ingestion operations logs provide information about successfully completed ingest operations. Logs include data source details that together with `Failed ingestion operations` logs can be used for tracking the process of ingestion of each data source. Ingestion logs are supported for queued ingestion to the ingestion endpoint using SDKs, data connections, and connectors

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
| Database | string | The name of the database holding the target table |
| IngestionSourceId | string | The ingestion source ID |
| IngestionSourcePath | string | Azure blob storage URI |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OperationId | string | The ingestion's operation ID |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultType | string | Final state of this data ingestion operation like 'Succeeded' |
| RootActivityId | string | The ingestion's activity ID |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| SucceededOn | datetime | The time this ingest operation ended successfully |
| Table | string | The name of the target table the data is ingested into |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The time (UTC) when this event was generated |
| Type | string | The name of the table |
