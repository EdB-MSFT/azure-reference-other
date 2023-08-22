---
title: Azure Monitor Logs reference - KubeNodeInventory
description: Reference for KubeNodeInventory table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# KubeNodeInventory

Details for nodes that are part of kubernetes cluster.

## Categories

- Containers
## Solutions

- AzureResources
- ContainerInsights
## Resource types

- Kubernetes Services
- Azure Arc Enabled Kubernetes
- Azure Arc Provisioned Clusters




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| ClusterId | string |   |
| ClusterName | string |   |
| Computer | string |   |
| CreationTimeStamp | datetime |   |
| DockerVersion | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| KubeletVersion | string |   |
| KubeProxyVersion | string |   |
| KubernetesProviderID | string |   |
| Labels | string |   |
| LastTransitionTimeReady | datetime |   |
| OperatingSystem | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| Status | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
