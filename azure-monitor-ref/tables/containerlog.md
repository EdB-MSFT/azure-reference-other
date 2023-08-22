---
title: Azure Monitor Logs reference - ContainerLog
description: Reference for ContainerLog table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ContainerLog

Log lines collected from stdout and stderr streams for containers.

## Categories

- Containers
- Applications
## Solutions

- AzureResources
- ContainerInsights
- Containers
## Resource types

- Kubernetes Services
- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager
- Virtual Machine Scale Sets
- Azure Arc Enabled Kubernetes
- Azure Arc Provisioned Clusters




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Computer | string | Computer/node that's generating the log. |
| ContainerID | string | Container ID for log source as seen by Docker engine. |
| Image | string | Container Image for log source as seen by Docker engine. |
| ImageTag | string | Used by Container solution only. Not populated by Azure Monitor for Containers. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LogEntry | string | Actual log line. |
| LogEntrySource | string | Source of the log line. Possible values are stdout or stderr. |
| Name | string | Unique name of the container the form  PODUid/ContainerName. |
| Repository | string | Used by Container solution only. Not populated by Azure Monitor for Containers. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime | Date and time the record was created. |
| TimeOfCommand | datetime | Time that the agent processed the log. This is an optional field mainly useful for troubleshooting latency issues on the agent. |
| Type | string | The name of the table |
