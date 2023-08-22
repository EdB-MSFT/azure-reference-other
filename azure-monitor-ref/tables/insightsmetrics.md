---
title: Azure Monitor Logs reference - InsightsMetrics
description: Reference for InsightsMetrics table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# InsightsMetrics



## Categories

- Virtual Machines
- Containers
- Azure Resources
## Solutions

- AzureResources
- ContainerInsights
- InfrastructureInsights
- LogManagement
- ServiceMap
- VMInsights
## Resource types

- Kubernetes Services
- Workload Monitoring of Azure Monitor Insights
- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager
- Virtual Machine Scale Sets
- Azure Arc Enabled Kubernetes
- Azure Arc Provisioned Clusters
- IoT Hub




## Columns

| Column | Type | Description |
|---|---|---|
| AgentId | string |   |
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Name | string |   |
| Namespace | string |   |
| Origin | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| Tags | string |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
| Val | real |   |
| Value | string |   |
