---
title: Azure Monitor Logs reference - AADDomainServicesPrivilegeUse
description: Reference for AADDomainServicesPrivilegeUse table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AADDomainServicesPrivilegeUse



## Categories

- Azure Resources
- Security
## Solutions

- LogManagement
## Resource types

- Azure AD Domain Services




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string |   |
| CorrelationId | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| NewState | int | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName.  Please see the Windows Server description of this event for the meaning of this field. |
| OperationName | string |   |
| ProcessId | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName.  Please see the Windows Server description of this event for the meaning of this field. |
| ProcessName | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName.  Please see the Windows Server description of this event for the meaning of this field. |
| RecordId | string | A unique identifier corresponding to this record. |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceManager | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName.  Please see the Windows Server description of this event for the meaning of this field. |
| ResultDescription | string |   |
| ResultType | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| TransactionId | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName.  Please see the Windows Server description of this event for the meaning of this field. |
| Type | string | The name of the table |
