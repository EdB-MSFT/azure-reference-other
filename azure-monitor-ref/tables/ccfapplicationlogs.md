---
title: Azure Monitor Logs reference - CCFApplicationLogs
description: Reference for CCFApplicationLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# CCFApplicationLogs

Contains the logs generated in the CCF application.

## Categories

- Azure Resources
- Audit
## Solutions

- LogManagement
## Resource types

- Azure Managed CCF




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| File | string | The file name that generated the log message. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | An error or informational message indicating if the service processed the request. |
| LineNumber | int | The line number in the file that the message refers to. |
| Location | string | The Azure datacenter region where the pod is deployed. |
| Message | string | The Log message. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Date and time the record was created. |
| Type | string | The name of the table |
