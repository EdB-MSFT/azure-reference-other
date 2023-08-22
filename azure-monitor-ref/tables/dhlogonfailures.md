---
title: Azure Monitor Logs reference - DHLogonFailures
description: Reference for DHLogonFailures table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# DHLogonFailures



## Categories

- Desktop Analytics
## Solutions

- DeviceHealthProd




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| ComputerID | string |   |
| Country | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LogonStatus | string |   |
| LogonSubStatus | string |   |
| Manufacturer | string |   |
| Model | string |   |
| ModelFamily | string |   |
| OSArchitecture | string |   |
| OSBuildNumber | int |   |
| OSEdition | string |   |
| OSRevisionNumber | int |   |
| OSVersion | string |   |
| ProviderId | string |   |
| ProviderName | string |   |
| SignInFailureCount | long |   |
| SignInFailureReason | string |   |
| SignInUserError | string |   |
| SuggestedSignInRemediation | string |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
