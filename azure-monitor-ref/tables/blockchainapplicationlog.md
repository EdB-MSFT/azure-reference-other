---
title: Azure Monitor Logs reference - BlockchainApplicationLog
description: Reference for BlockchainApplicationLog table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# BlockchainApplicationLog



## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Azure Blockchain Service




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| BlockchainMessage | string |   |
| BlockchainNodeName | string |   |
| Category | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string |   |
| NodeLocation | string |   |
| OperationName | string |   |
| Resource | string |   |
| ResourceGroup | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceProvider | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubscriptionId | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
