---
title: Azure Monitor Logs reference - AZFWFatFlow
description: Reference for AZFWFatFlow table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AZFWFatFlow

This query returns the top flows across Azure Firewall instances. Log contains flow information, date transmission rate (in Megabits per second units) and the time period when the flows were recorded. Please follow the documentation to enable Top flow logging and details on how it is recorded.

## Categories

- Security
## Solutions

- LogManagement
## Resource types

- Firewalls




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| DestinationIp | string | Flow's destination IP address. |
| DestinationPort | int | Flow's destination port. |
| FlowRate | real | Flow's bandwidth consumption rate in Megabits per second unit. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Protocol | string | Flow's network protocol. For example: UDP, TCP. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceIp | string | Flow's source IP address. |
| SourcePort | int | Flow's source port. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp (UTC) when the data plane log was created. |
| Type | string | The name of the table |
