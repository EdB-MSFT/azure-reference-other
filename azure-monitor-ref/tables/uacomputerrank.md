---
title: Azure Monitor Logs reference - UAComputerRank
description: Reference for UAComputerRank table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UAComputerRank



## Categories

- Desktop Analytics
## Solutions

- CompatibilityAssessment




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| ComputerID | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ItemRank | int |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
