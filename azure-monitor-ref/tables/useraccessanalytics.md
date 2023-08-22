---
title: Azure Monitor Logs reference - UserAccessAnalytics
description: Reference for UserAccessAnalytics table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UserAccessAnalytics

This analytics table, for a given user, provides the direct or transitive access to Azure resources. For example, if the user under investigation is Jane Smith, Access Analytics calculates all the Azure subscriptions that she either can access directly, via groups or serviceprincipals.

## Categories

- Security
## Solutions

- BehaviorAnalyticsInsights




## Columns

| Column | Type | Description |
|---|---|---|
| AADTenantId | string | Unique identifier of the Azure Tenant |
| AccessEndReason | string | Reason why the source entity's access to the target entity was revoked |
| AccessEndTime | datetime | Timestamp when the source entity's access to the target entity was revoked |
| AccessId | string | Unique identifier for the access between source and target entity |
| AccessLevel | string | The level of access that the source entity has to the target entity |
| AccessStartTime | datetime | Timestamp when the source entity was provided access to the target entity |
| AccessType | string | The type of access that the source entity has to the target entity |
| _BilledSize | real | The record size in bytes |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceEntityId | string | Unique identifier of entity which has access to the target entity |
| SourceEntityName | string | Display name of entity which has access to the target entity |
| SourceEntityType | string | Type of entity which has access to the target entity |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TargetEntityId | string | Unique identifier of the entity which the source entity can access |
| TargetEntityName | string | Display name of the entity which the source entity can access |
| TargetEntityType | string | Type of the entity which the source entity can access |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp when the access analytics is calculated |
| Type | string | The name of the table |
