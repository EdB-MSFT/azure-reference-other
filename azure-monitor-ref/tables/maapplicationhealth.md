---
title: Azure Monitor Logs reference - MAApplicationHealth
description: Reference for MAApplicationHealth table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# MAApplicationHealth



## Categories

- Desktop Analytics
## Solutions

- Microsoft365Analytics




## Columns

| Column | Type | Description |
|---|---|---|
| ActiveDevicesOnSource | int |   |
| ActiveDevicesOnTarget | int |   |
| AppLanguage | string |   |
| AppName | string |   |
| AppVendor | string |   |
| AppVersion | string |   |
| _BilledSize | real | The record size in bytes |
| DevicesWithCrashesOnSource | int |   |
| DevicesWithCrashesOnTarget | int |   |
| DevicesWithCrashesPercentOnTargetForCommercial | real |   |
| HealthStatus | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OSVersion | string |   |
| ProgramId | string |   |
| SessionsWithCrashesOnSource | int |   |
| SessionsWithCrashesOnTarget | int |   |
| SessionsWithCrashesPercentOnTargetForCommercial | real |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TimeGenerated | datetime |   |
| TotalDevicesInstalledOnSource | int |   |
| TotalDevicesInstalledOnTarget | int |   |
| TotalSessionsOnSource | int |   |
| TotalSessionsOnTarget | int |   |
| Type | string | The name of the table |
