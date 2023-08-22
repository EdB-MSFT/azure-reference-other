---
title: Azure Monitor Logs reference - AppPlatformContainerEventLogs
description: Reference for AppPlatformContainerEventLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AppPlatformContainerEventLogs

Azure Spring Cloud container event logs of user applications.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Spring Apps




## Columns

| Column | Type | Description |
|---|---|---|
| App | string | The name of the application that emitted the container event. |
| _BilledSize | real | The record size in bytes |
| Count | int | The count of this container event happened. |
| Deployment | string | The name of the deployment that emitted the container event. |
| Event | string | The name of container event, including: 'Backoff', 'Pulled', 'Created', 'Started', 'Unhealty' and so on. |
| FirstTimestamp | datetime | The timestamp when this container event was first seen. |
| Instance | string | The name of the instance that emitted the container event. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LastTimestamp | datetime | The timestamp when this container event was last seen. |
| Message | string | The detailed message of the container event. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) when the log is collected by Azure Spring Cloud. |
| Type | string | The type of container event, including: 'Error', 'Warning' and 'Normal'. |
