---
title: Azure Monitor Logs reference - VMProcess
description: Reference for VMProcess table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# VMProcess

Process data for servers collected by the Service Map and VM Insights solutions using the Dependency agent and Log analytics agent.

## Categories

- Virtual Machines
## Solutions

- AzureResources
- ServiceMap
- VMInsights
## Resource types

- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager
- Virtual Machine Scale Sets




## Columns

| Column | Type | Description |
|---|---|---|
| AgentId | string | Unique ID for the dependency agent installed on the server. |
| _BilledSize | real | The record size in bytes |
| CommandLine | string | The command line |
| CompanyName | string | The name of the company |
| Computer | string | The name of the computer. |
| Description | string | The process description |
| DisplayName | string | The friendly display name of the process |
| ExecutableName | string | The name of the process executable |
| ExecutablePath | string | The path to the executable file |
| FileVersion | string | The file version |
| FirstPid | int | The first PID in the process pool |
| Group | string | The process group name for the process |
| InternalName | string | The internal name |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Machine | string | The machine name of the server. |
| Process | string | The name of the process. |
| ProductName | string | The name of the product |
| ProductVersion | string | The product version |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| Role | string | The role of the process. |
| Services | dynamic | A list of services associated with the process. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StartTime | datetime | The process pool start time |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime | Date and time the record was created. |
| Type | string | The name of the table |
| UserDomain | string | The domain under which the process is executing |
| UserName | string | The account under which the process is executing |
| WorkingDirectory | string | The working directory |
