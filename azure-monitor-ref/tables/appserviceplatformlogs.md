---
title: Azure Monitor Logs reference - AppServicePlatformLogs
description: Reference for AppServicePlatformLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AppServicePlatformLogs

Logs generated through AppService platform for your application.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- App Services




## Columns

| Column | Type | Description |
|---|---|---|
| ActivityId | string | Activity Id to correlate events |
| _BilledSize | real | The record size in bytes |
| ContainerId | string | Application container id |
| DeploymentId | string | Deployment ID of the application deployment |
| Exception | string | Details of the exception |
| Host | string | Host where the application is running |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | Level of log verbosity |
| Message | string | Log message |
| OperationName | string | The name of the operation represented by this event. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StackTrace | string | Stack trace for the exception |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Time when event is generated |
| Type | string | The name of the table |
