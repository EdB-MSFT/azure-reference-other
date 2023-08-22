---
title: Azure Monitor Logs reference - AHDSDicomAuditLogs
description: Reference for AHDSDicomAuditLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AHDSDicomAuditLogs

Data plane audit logs of privileged actions made against Azure Health Data DICOM service. For example, storing a DICOM instance.

## Categories

- Audit
- Azure Resources
## Solutions

- LogManagement
## Resource types

- Health Data Services




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| CorrelationId | string | An identifier used to group together a set of related events. |
| Identity | dynamic | Identity of the issuer of the request. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | The log's severity level. Possible values are Informational, Warning, and Error. |
| OperationName | string | The operation name for which the log entry was generated. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultType | string | Indicates whether the operation started or ended. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| StatusCode | int | Status code returned for the request. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Time (UTC) when the log was created. |
| Type | string | The name of the table |
| Uri | string | URI of the request. |
