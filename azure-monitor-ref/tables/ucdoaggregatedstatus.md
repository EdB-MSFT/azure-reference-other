---
title: Azure Monitor Logs reference - UCDOAggregatedStatus
description: Reference for UCDOAggregatedStatus table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UCDOAggregatedStatus

Update Compliance - aggregates all individual UCDOStatus records across the tenant and summarizes bandwidth savings across all devices enrolled to delivery.

## Categories

- Desktop Analytics
## Solutions

- LogManagement
- WaaSUpdateInsights




## Columns

| Column | Type | Description |
|---|---|---|
| AzureADDeviceId | string | A GUID corresponding to the AAD tenant to which the device belongs. |
| AzureADTenantId | string | A GUID corresponding to this device's AAD device ID. |
| _BilledSize | real | The record size in bytes |
| BWOptPercent28Days | real | Bandwidth optimization (as a percentage of savings of total bandwidth otherwise incurred) as a result of using delivery optimization for this device, computed on a rolling 28-day basis. |
| BytesFromCache | long | Total number of bytes downloaded from cache. |
| BytesFromCDN | long | Total number of bytes downloaded from a CDN versus a peer. This counts against bandwidth optimization. |
| BytesFromGroupPeers | long | Total number of bytes downloaded from group peers. |
| BytesFromIntPeers | long | Total number of bytes downloaded from internet peers. |
| BytesFromPeers | long | Total number of bytes downloaded from peers. |
| ContentType | string | The type of content being downloaded. |
| DeviceCount | long | Total count of devices. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Time at which this event was generated. |
| Type | string | The name of the table |
