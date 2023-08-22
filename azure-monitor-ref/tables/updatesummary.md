---
title: Azure Monitor Logs reference - UpdateSummary
description: Reference for UpdateSummary table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UpdateSummary

Summary for each update schedule run. Includes information such as how many updates were not installed.

## Categories

- Virtual Machines
## Solutions

- Security
- SecurityCenter
- SecurityCenterFree
- Updates
## Resource types

- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager
- Virtual Machine Scale Sets
- Automation account




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| ComputerEnvironment | string |   |
| CriticalUpdatesMissing | int |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| ManagementGroupName | string |   |
| NETRuntimeVersion | string |   |
| OldestMissingSecurityUpdateBucket | string |   |
| OldestMissingSecurityUpdateInDays | int |   |
| OsVersion | string |   |
| OtherUpdatesMissing | int |   |
| Resource | string |   |
| ResourceGroup | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceProvider | string |   |
| ResourceType | string |   |
| RestartPending | bool |   |
| SecurityUpdatesMissing | int |   |
| SourceComputerId | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubscriptionId | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| TotalUpdatesMissing | int |   |
| Type | string | The name of the table |
| VMUUID | string |   |
| WindowsUpdateAgentVersion | string |   |
| WindowsUpdateSetting | string |   |
| WSUSServer | string |   |
