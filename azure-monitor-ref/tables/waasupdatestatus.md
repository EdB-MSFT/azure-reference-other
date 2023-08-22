---
title: Azure Monitor Logs reference - WaaSUpdateStatus
description: Reference for WaaSUpdateStatus table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# WaaSUpdateStatus



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
| DownloadMode | string |   |
| FeatureDeferralDays | int |   |
| FeaturePauseDays | int |   |
| FeaturePauseState | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LastScan | datetime |   |
| NeedAttentionStatus | string |   |
| OSArchitecture | string |   |
| OSBuild | string |   |
| OSCurrentStatus | string |   |
| OSEdition | string |   |
| OSFamily | string |   |
| OSFeatureUpdateStatus | string |   |
| OSName | string |   |
| OSQualityUpdateStatus | string |   |
| OSRevisionNumber | int |   |
| OSSecurityUpdateStatus | string |   |
| OSServicingBranch | string |   |
| OSVersion | string |   |
| QualityDeferralDays | int |   |
| QualityPauseDays | int |   |
| QualityPauseState | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
