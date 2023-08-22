---
title: Azure Monitor Logs reference - SecurityBaselineSummary
description: Reference for SecurityBaselineSummary table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SecurityBaselineSummary



## Categories

- Security
## Solutions

- Security
- SecurityCenter
- SecurityCenterFree
## Resource types

- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager




## Columns

| Column | Type | Description |
|---|---|---|
| AssessmentId | string |   |
| BaselineType | string |   |
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| ComputerEnvironment | string |   |
| CriticalFailedRules | int |   |
| InformationalFailedRules | int |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ManagementGroupName | string |   |
| OSName | string |   |
| PercentageOfPassedRules | int |   |
| Resource | string |   |
| ResourceGroup | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceProvider | string |   |
| ResourceType | string |   |
| SourceComputerId | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubscriptionId | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| TotalAssessedRules | int |   |
| Type | string | The name of the table |
| WarningFailedRules | int |   |
