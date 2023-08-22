---
title: Azure Monitor Logs reference - SecurityBaseline
description: Reference for SecurityBaseline table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SecurityBaseline



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
- Virtual Machine Scale Sets




## Columns

| Column | Type | Description |
|---|---|---|
| ActualResult | string |   |
| AnalyzeOperation | string |   |
| AnalyzeResult | string |   |
| AssessmentId | string |   |
| AzId | string |   |
| BaselineRuleType | string |   |
| BaselineType | string |   |
| _BilledSize | real | The record size in bytes |
| CceId | string |   |
| Computer | string |   |
| ComputerEnvironment | string |   |
| Description | string |   |
| ExpectedResult | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ManagementGroupName | string |   |
| OSName | string |   |
| Resource | string |   |
| ResourceGroup | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceProvider | string |   |
| ResourceType | string |   |
| RuleSetting | string |   |
| RuleSeverity | string |   |
| SitePath | string |   |
| SourceComputerId | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubscriptionId | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
