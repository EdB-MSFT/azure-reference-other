---
title: Azure Monitor Logs reference - ServiceFabricReliableActorEvent
description: Reference for ServiceFabricReliableActorEvent table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ServiceFabricReliableActorEvent



## Categories

- Azure Resources
## Solutions

- LogManagement




## Columns

| Column | Type | Description |
|---|---|---|
| ActorId | string |   |
| ActorIdKind | int |   |
| ActorType | string |   |
| ApplicationName | string |   |
| ApplicationTypeName | string |   |
| AzureDeploymentID | string |   |
| _BilledSize | real | The record size in bytes |
| ChannelName | string |   |
| Computer | string |   |
| CountOfWaitingMethodCalls | long |   |
| EventId | int |   |
| EventMessage | string |   |
| EventSourceName | string |   |
| Exception | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| IsStateful | bool |   |
| KeywordName | string |   |
| Level | string |   |
| MethodExecutionTimeTicks | long |   |
| MethodName | string |   |
| MethodSignature | string |   |
| NodeId | string |   |
| NodeName | string |   |
| OpcodeName | string |   |
| PartitionId | string |   |
| Pid | int |   |
| ProviderGuid | string |   |
| ReplicaId | long |   |
| ReplicaOrInstanceId | long |   |
| Role | string |   |
| SaveStateExecutionTimeTicks | long |   |
| ServiceName | string |   |
| ServiceTypeName | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TaskName | string |   |
| Tid | int |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
