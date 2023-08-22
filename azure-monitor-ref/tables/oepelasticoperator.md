---
title: Azure Monitor Logs reference - OEPElasticOperator
description: Reference for OEPElasticOperator table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# OEPElasticOperator

Diagnostic logs for elastic operator. Elastic operator manages all the elasticsearch clusters in the oak instance. These logs can be helpful in identifing what operations are performed by the operator on the cluster. It could be upgrades, reconciliation, resource update etc.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Data Manager for Energy




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string | Logs generated as a result of operations executed using OAK APIs are grouped into categories. Categories in OAK are logical groupings based on the data source. |
| Content | string | Log details as a result of operation performed. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Location | string | The region of the resource emitting the event. |
| Namespace | string | Namespace from which logs were generated, represents the data partition. |
| OperationName | string | The operation name for which the log entry was created. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp (in UTC) when the log was created. |
| Type | string | The name of the table |
