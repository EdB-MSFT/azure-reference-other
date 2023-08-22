---
title: Azure Monitor Logs reference - DHAppReliability
description: Reference for DHAppReliability table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# DHAppReliability



## Categories

- Desktop Analytics
## Solutions

- DeviceHealthProd




## Columns

| Column | Type | Description |
|---|---|---|
| AppFileDisplayName | string |   |
| AppFileName | string |   |
| AppFileVersion | string |   |
| AppName | string |   |
| AppVersion | string |   |
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| ComputerID | string |   |
| ConfigMgrClientID | string |   |
| CrashFreeDevicesPercentForIndustryTrailing | real |   |
| DeviceLastSeenTime | datetime |   |
| HangFreeDevicesPercentForIndustryTrailing | real |   |
| HasCrashesDaily | bool |   |
| HasCrashesTrailing | bool |   |
| HasHangsDaily | bool |   |
| HasHangsTrailing | bool |   |
| HasIncidentsDaily | bool |   |
| HasIncidentsTrailing | bool |   |
| HasUsageDaily | bool |   |
| HasUsageTrailing | bool |   |
| IncidentFreeDevicesPercentForIndustryTrailing | real |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OSBuildNumber | int |   |
| OSRevisionNumber | int |   |
| OSVersion | string |   |
| Publisher | string |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
