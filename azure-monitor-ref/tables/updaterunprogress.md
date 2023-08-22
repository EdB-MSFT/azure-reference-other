---
title: Azure Monitor Logs reference - UpdateRunProgress
description: Reference for UpdateRunProgress table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UpdateRunProgress

Breaks down each run of your update schedule by the patches available at the time with details on the installation status of each patch.

## Categories

- IT & Management Tools
## Solutions

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
| CorrelationId | string |   |
| EndTime | datetime |   |
| ErrorResult | string |   |
| InstallationStatus | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| KBID | string |   |
| ManagementGroupName | string |   |
| OSType | string |   |
| Product | string |   |
| Resource | string |   |
| ResourceGroup | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceProvider | string |   |
| ResourceType | string |   |
| SourceComputerId | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StartTime | datetime |   |
| SubscriptionId | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| SucceededOnRetry | bool |   |
| TimeGenerated | datetime |   |
| Title | string |   |
| Type | string | The name of the table |
| UpdateId | string |   |
| UpdateRunName | string |   |
| VMUUID | string |   |
