---
title: Azure Monitor Logs reference - Heartbeat
description: Reference for Heartbeat table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# Heartbeat

Records logged by Log Analytics agents once per minute to report on agent health.

## Categories

- Virtual Machines
- Containers
- IT & Management Tools
## Solutions

- LogManagement
## Resource types

- Virtual machines
- Kubernetes Services
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager
- Virtual Machine Scale Sets
- Azure Arc Enabled Kubernetes
- Azure Arc Provisioned Clusters
- Automation account




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string | Possible values include Azure Monitor Agent, Direct Agent, SCOM Agent or SCOM Management Server. |
| Computer | string | Computer name |
| ComputerEnvironment | string | Environment that hosts the computer: Azure or Non-Azure |
| ComputerIP | string | IP address of the computer. Note that public IP is used |
| ComputerPrivateIPs | dynamic | The list of private IP addresses of the computer. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| IsGatewayInstalled | bool | If Log Analytics gateway is installed the value is true, otherwise false. |
| ManagementGroupName | string | Name of Operations Manager management group. |
| OSMajorVersion | string | Operating system major version. |
| OSMinorVersion | string | Operating system minor version. |
| OSName | string | Name of OS. |
| OSType | string | Type of OS. Possible values are Windows or Linux . |
| RemoteIPCountry | string | Geographic location where computer is deployed. |
| RemoteIPLatitude | real | Latitude of computer's geographic location. |
| RemoteIPLongitude | real | Longitude of computer's geographic location. |
| Resource | string | Resource group name of the Azure resource running the agent. |
| ResourceGroup | string | Resource name of the Azure resource running the agent. |
| ResourceId | string | Resource ID of the Azure resource running the agent. Retained for for backward compatibility. _ResourceId should be used. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceProvider | string | Resource provider of the Azure resource running the agent |
| ResourceType | string | Type of the Azure resource running the agent. Examples include virtualmachines or managedclusters. |
| SCAgentChannel | string | Specfies how agent is connected to workspace. Possible values are Direct or SCManagementServer. |
| Solutions | string | List of solutions deployed on the agent at the moment when Heartbeat was issued. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubscriptionId | string | Subscription ID of the Azure resource running the agent |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime | Date and time the record was created. |
| Type | string | The name of the table |
| Version | string | Version of the agent. |
| VMUUID | string | Unique identifier of the virtual machine. |
