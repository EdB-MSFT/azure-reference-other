---
title: Azure Monitor Logs reference - AZKVPolicyEvaluationDetailsLogs
description: Reference for AZKVPolicyEvaluationDetailsLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AZKVPolicyEvaluationDetailsLogs

Contains details of Azure Policy Evaluation including the outcome and details of what checks were performed.

## Categories

- Azure Resources
- Audit
## Solutions

- LogManagement
## Resource types

- Key Vaults




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| DurationMs | int | Time it took to service the REST API request, in milliseconds. This does not include the network latency, so the time you measure on the client side might not match this time |
| EvaluationDetails | dynamic | Details of evaluation |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| IsComplianceCheck | bool | Is Compliance check enabled |
| ObjectName | string | Name of the object |
| ObjectType | string | Type of object |
| OperationName | string | Name of the operation |
| Properties | dynamic | Information that varies based on the operation (operationName). In most cases, this field contains client information (the user agent string passed by the client), the exact REST API request URI, and the HTTP status code. In addition, when an object is returned as a result of a request (for example, KeyCreate or VaultGet), it also contains the key URI (as id), vault URI, or secret URI |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultDescription | string | Additional description about the result, when available |
| ResultSignature | string | HTTP status of the request/response |
| ResultType | string | Result of the REST API request |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp (in UTC) when operation occured. |
| Type | string | The name of the table |
