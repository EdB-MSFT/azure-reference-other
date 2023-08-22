---
title: Azure Monitor Logs reference - OEPAuditLogs
description: Reference for OEPAuditLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# OEPAuditLogs

Audit Logs for Microsoft Energy Data Services.

## Categories

- Audit
- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Data Manager for Energy




## Columns

| Column | Type | Description |
|---|---|---|
| Action | string | Action performed,which can be CREATE,PUBLISH,UPDATE,DELETE,READ and JOB_RUN. |
| ActionId | string | ID of the action performed. |
| _BilledSize | real | The record size in bytes |
| Category | string | Logs generated as a result of operations executed using OAK APIs are grouped into categories. Categories in OAK are logical groupings based on the data source. |
| DataPartitionId | string | Represents the data partition ID. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Location | string | The region of the resource emitting the event. |
| Message | string | The message about the operation. |
| OperationDescription | string | Description of operation that was performed. |
| OperationName | string | The operation name for which the log entry was created. |
| Puid | string | The client ID. |
| RequestId | string | The request ID uniquely identify the request made to Microsoft Energy Data Services for an operation. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultType | string | Result of the REST API request. |
| ServiceName | string | The name of service which is emitting the event. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp (UTC) when the log was created. |
| Type | string | The name of the table |
