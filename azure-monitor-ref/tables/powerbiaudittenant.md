---
title: Azure Monitor Logs reference - PowerBIAuditTenant
description: Reference for PowerBIAuditTenant table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# PowerBIAuditTenant

Contains Power BI audit events as per the Activity Log and Office365 Audit Log. Covers operations over full lifecycle of Power BI assets such as creation, modification and deletion.

## Categories

- Azure Resources
- Audit
## Solutions

- LogManagement
## Resource types

- Power BI Datasets




## Columns

| Column | Type | Description |
|---|---|---|
| AuditData | string | The complete audit record containing relevant operation details such as workspace name or dataset name. |
| _BilledSize | real | The record size in bytes |
| CorrelationId | string | An event ID that can be used to correlated events between multiple tables. |
| CustomerTenantId | string | Customer's Power BI tenant identifier. |
| ExecutingUser | string | The user executing the operation. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | Contains the severity level of the operation being logged. Success, Informational, Warning, or Error. |
| LogAnalyticsCategory | string | Unique category of the events like like Audit/Security/Request. |
| OperationName | string | The operation associated with the log record. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp(UTC) of when the log entry was generated. |
| Type | string | The name of the table |
