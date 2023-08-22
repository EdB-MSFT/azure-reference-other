---
title: Azure Monitor Logs reference - WebPubSubConnectivity
description: Reference for WebPubSubConnectivity table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# WebPubSubConnectivity

Connectivity logs provide detailed information for Azure Web PubSub hub connections. For example, basic information (user ID, connection ID, and so on) and event information (connect, disconnect, and abort event, and so on) and can be used to troubleshoot connection-related issues.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- SignalR Service WebPubSub




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| CallerIpAddress | string | The IP of the client or server connects to Web PubSub service. |
| ConnectionId | string | The unique identifier of the connection connected to service. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | The level of the log. Can be 'Informational', 'Warning', 'Error' or 'Critical'. |
| Location | string | The location of Azure Web PubSub service. |
| Message | string | The message of the log event. It provides details about the event. |
| OperationName | string | The operation of the log event. It can be used to filter the log based on a specific operation name. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of the log. |
| Type | string | The name of the table |
| UserId | string | The unique identifier of the user. It is defined by the client or app server. |
