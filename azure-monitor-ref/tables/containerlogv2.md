---
title: Azure Monitor Logs reference - ContainerLogV2
description: Reference for ContainerLogV2 table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ContainerLogV2

Kubernetes Container logs in V2 schema. This is the successor for ContainerLog. This has more friendlier schema, specifically for kubernetes orchestrated containers in pods.

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
| Computer | string | Name of the Computer/Node generating the log. |
| ContainerId | string | Container ID of the log source as seen by the Container engine. |
| ContainerName | string | Name of the Container generating the log. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LogMessage | dynamic | Log message from stdout or stderr. Being a dynmic field, json log messages can be queried without parse_json. |
| LogSource | string | Source of the Log message. Possible vlaues are stdout or stderr. |
| PodName | string | Kubernetes Pod name for the Container generating the log. |
| PodNamespace | string | Kubernetes Namespace for the container's pod. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of when the log was generated. |
| Type | string | The name of the table |
