---
title: Azure Monitor Logs reference - WVDSessionHostManagement
description: Reference for WVDSessionHostManagement table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# WVDSessionHostManagement

Windows Virtual Desktop session host management data.

## Categories

- Azure Virtual Desktop
## Solutions

- LogManagement
## Resource types

- Desktop Virtualization Host Pools




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| ClientType | string | Information about the client that initiated the update (portal, Powershell etc.). |
| CorrelationId | string | The correlation ID for the activity. |
| CustomScriptAdded | string | A URL for the customer provided custom script or 'False' if none was provided. |
| ImageSource | string | The source for the Azure virtual machine - either Marketplace or Custom. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| MaxVMsUnavailableDuringUpdate | int | The maximum number of virtual machines that might become unavailable during the host pool update operation. |
| NewVMSize | string | The desired Azure virtual machine size (e.g.: Standard_D2s_v4) after the host pool update. |
| NewVMSku | string | The desired Azure virtual machine SKU that will be used for the host pool update. |
| OSDiskSaved | bool | Property indicates whether the original disk is saved. |
| OSDiskType | string | The Azure storage disk type used for the host pool update. |
| ParentUpdateId | string | When the current host pool update is a retry or a resume of a previous host pool update operation, this represents the previous host pool update correlation ID. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ScheduledTime | string | When the host pool update is scheduled, the scheduled time. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of the event. |
| Type | string | The name of the table |
| UpdateMethod | string | The method that is used for the host pool update operation (e.g.: DiskSwap). |
| UpdateStatus | string | The current status of the host pool update operation. |
| UpdateType | string | The type of host pool update requested by the customer - whether Immediate or Scheduled. |
