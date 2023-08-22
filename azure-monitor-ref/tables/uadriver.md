---
title: Azure Monitor Logs reference - UADriver
description: Reference for UADriver table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UADriver



## Categories

- Desktop Analytics
## Solutions

- CompatibilityAssessment




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| ComputerID | string |   |
| DriverAvailability | string |   |
| DriverDate | string |   |
| DriverName | string |   |
| DriverVendor | string |   |
| DriverVersion | string |   |
| Guidance | string |   |
| HardwareID | string |   |
| HardwareName | string |   |
| HardwareType | string |   |
| Importance | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| IsRollup | bool |   |
| Issue | string |   |
| RollupLevel | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TimeGenerated | datetime |   |
| TotalComputers | int |   |
| Type | string | The name of the table |
| UpgradeAssessment | string |   |
| UpgradeDecision | string |   |
