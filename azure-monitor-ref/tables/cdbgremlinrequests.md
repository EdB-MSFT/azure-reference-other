---
title: Azure Monitor Logs reference - CDBGremlinRequests
description: Reference for CDBGremlinRequests table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# CDBGremlinRequests

This table details data plane operations, specifically for Graph API accounts.

## Categories

- Azure Resources
- Audit
## Solutions

- LogManagement
## Resource types

- Azure Cosmos DB




## Columns

| Column | Type | Description |
|---|---|---|
| AccountName | string | The name of the Cosmos DB account against which this request was issued. |
| ActivityId | string | The unique identifier (GUID) for this Graph API request. |
| Address | string | The IP address of the client, which issued this request. |
| AuthorizationTokenType | string | The authorization token used  for this request. |
| _BilledSize | real | The record size in bytes |
| CollectionName | string | The name of the Cosmos DB table/container against which this request was issued. |
| DatabaseName | string | The name of the Cosmos DB database against which this request was issued. |
| DurationMs | real | The server-side execution time (in ms) for this request. |
| ErrorCode | string | The error code (if applicable) for this request. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OperationName | string | The name of the Gremlin operation that was executed. |
| PIICommandText | string | Full query with parameters (if opted in) for this request. |
| RateLimitingDelayMs | real | The estimated time (in ms) spent retrying due to rate limited operations. |
| RegionName | string | The region against which this request was issued. |
| RequestCharge | real | The RUs (Request Units) consumed by this operation. |
| RequestLength | real | The payload size (in bytes) of the request. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResponseLength | real | The payload size (in bytes) of the server response. |
| RetriedDueToRateLimiting | bool | Boolean flag indicating if this request was retried server side due to throttles. |
| RetryCount | int | The number of server side retries issued for this request. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp (in UTC) when this Graph API operation was executed on the server. |
| Type | string | The name of the table |
| UserAgent | string | The user agent suffix of the client issuing the request. |
