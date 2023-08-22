---
title: Azure Monitor Logs reference - WDAVThreat
description: Reference for WDAVThreat table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# WDAVThreat



## Categories

- Desktop Analytics
## Solutions

- WaaSUpdateInsights




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| ComputerID | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| IsCloudSignature | bool |   |
| LastScan | datetime |   |
| MoreInformation | string |   |
| RemediationAction | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| ThreatAction | string |   |
| ThreatAlertLevel | string |   |
| ThreatCategory | string |   |
| ThreatEncyclopediaLink | string |   |
| ThreatError | string |   |
| ThreatFamily | string |   |
| ThreatId | int |   |
| ThreatName | string |   |
| ThreatReportId | string |   |
| ThreatStatus | string |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
