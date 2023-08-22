---
title: Azure Monitor Logs reference - AppPlatformLogsforSpring
description: Reference for AppPlatformLogsforSpring table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AppPlatformLogsforSpring

App Platform Logs for Spring.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Spring Apps




## Columns

| Column | Type | Description |
|---|---|---|
| AppName | string | The application name that emitted the log |
| AppTimestamp | datetime | The log timestamp (UTC) from user application log |
| _BilledSize | real | The record size in bytes |
| Category | string | Log Category |
| CustomLevel | string | Verbosity level of log |
| ExceptionClass | string | The exceptionClass of the log |
| InstanceName | string | The instance name that emitted the log |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Log | string | The content of the log |
| Logger | string | The logger from user application log |
| MDC | string | Customized MDC field in the log |
| Message | string | The message of the log |
| OperationName | string | The name of the operation represented by this event |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ServiceName | string | The service name that emitted the log |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SpanId | string | SpanId for tracing |
| StackTrace | string | The stackTrace of the log |
| Stream | string | The stream of the log |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| Thread | string | The thread of the log |
| TimeGenerated | datetime | The timestamp (UTC) when the log is collected by Azure Spring Cloud |
| TraceId | string | TraceId for tracing |
| Type | string | The name of the table |
