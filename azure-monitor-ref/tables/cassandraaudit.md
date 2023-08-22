---
title: Azure Monitor Logs reference - CassandraAudit
description: Reference for CassandraAudit table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# CassandraAudit

Detailed audit records for CQL operations and login attempts.

## Categories

- Audit
## Solutions

- LogManagement
## Resource types

- Azure Managed Instance for Apache Cassandra




## Columns

| Column | Type | Description |
|---|---|---|
| BatchId | string | Internal identifier shared by all statements in a batch operation. |
| _BilledSize | real | The record size in bytes |
| ClientIP | string | Client IP address. |
| ClientPort | string | Client port. |
| ClusterName | string | Cluster name. |
| CoordinatorIP | string | Host address of the coordinator node. |
| ExternalUserId | string | External user identity. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Operation | string | The CQL statement or a textual description of the operation. |
| OperationNaked | string | The CQL statement or a textual description of the operation, without bound values appended to prepared statements. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| Status | string | Value is either ATTEMPT or FAILED. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Date and time the record was created. |
| Type | string | The name of the table |
| User | string | Username of the authenticated user. |
