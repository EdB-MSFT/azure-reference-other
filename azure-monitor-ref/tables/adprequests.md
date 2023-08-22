---
title: Azure Monitor Logs reference - ADPRequests
description: Reference for ADPRequests table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADPRequests

Requests made to the ADP service.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Autonomous Development Platform workspace




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| CallerIpAddress | string | IP address of the user who has performed the operation. |
| CorrelationId | string | Internal ADP correlation ID used in support scenarios. |
| DurationMs | int | The duration of the operation in milliseconds. |
| HttpStatusCode | int | The HTTP response status code of the corresponding REST call. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Location | string | The location (region) of the resource. |
| OperationName | string | The operation associated with the log record. |
| OperationVersion | string | The API version against which the operation was performed. |
| Properties | dynamic | Additional properties related to the request. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| Success | bool | Whether the request was successful or not. Note that long-running asynchronous operations might fail even when the request is successful. |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of when the log record was generated. |
| TraceContext | dynamic | W3C Trace Context information used for event correlation. |
| Type | string | The name of the table |
| Uri | string | The URI of the request. |
