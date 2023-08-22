---
title: Azure Monitor Logs reference - DHWipAppLearning
description: Reference for DHWipAppLearning table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# DHWipAppLearning



## Categories

- Desktop Analytics
## Solutions

- DeviceHealthProd




## Columns

| Column | Type | Description |
|---|---|---|
| AppName | string |   |
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| ComputerID | string |   |
| ConfigMgrClientID | string |   |
| EventFiredTime | datetime |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
| WipActionType | string |   |
| WipAppId | string |   |
| WipAppIdType | string |   |
| WipAppRuleType | string |   |
