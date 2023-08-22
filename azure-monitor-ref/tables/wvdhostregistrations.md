---
title: Azure Monitor Logs reference - WVDHostRegistrations
description: Reference for WVDHostRegistrations table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# WVDHostRegistrations

Windows Virtual Desktop Host Registration Activity

## Categories

- Azure Virtual Desktop
## Solutions

- LogManagement
## Resource types

- Desktop Virtualization Host Pools




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| CorrelationId | string | The activity Id. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| IsSessionHostPrivateLink | string | True if the session host side of this connection used a private link endpoint during orchestration. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SessionHostIPAddress | string | The IP address of the session host that was registered with the WVD service. |
| SessionHostName | string | The name of the session host that was registered with the WVD service. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of the event. |
| Type | string | The name of the table |
