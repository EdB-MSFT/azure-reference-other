---
title: Azure Monitor Logs reference - WVDAutoscaleEvaluationPooled
description: Reference for WVDAutoscaleEvaluationPooled table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# WVDAutoscaleEvaluationPooled

The results of an Azure Virtual Desktop Autoscale scaling plan evaluation on a hostpool. This includes information on the actions Autoscale took on the sessions hosts, such as starting or deallocating them, and why it took those actions. The column names that start with 'Config' contain the scaling plan configuration values for the current Autoscale schedule phase. If the ResultType column value is 'Failed' then join to the WVDErrors table using the CorrelationId column to get more details. For Autoscale documentation see https://go.microsoft.com/fwlink/?linkid=2169532 .

## Categories

- Azure Virtual Desktop
## Solutions

- LogManagement
## Resource types

- Desktop Virtualization Host Pools




## Columns

| Column | Type | Description |
|---|---|---|
| ActiveSessionHostCount | int | Number of session hosts accepting user connections. |
| ActiveSessionHostsPercent | real | Percent of session hosts in the host pool considered active by Autoscale. |
| _BilledSize | real | The record size in bytes |
| ConfigCapacityThresholdPercent | real | Capacity threshold percent. |
| ConfigMinActiveSessionHostsPercent | real | Minimum percent of session hosts that should be active. |
| ConfigScheduleName | string | Name of schedule used in the evaluation. |
| ConfigSchedulePhase | string | Schedule phase at the time of evaluation. |
| CorrelationId | string | A GUID generated for this Autoscale evaluation. |
| ExcludedSessionHostCount | int | Number of session hosts excluded from being managed by Autoscale. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| MaxSessionLimitPerSessionHost | int | The 'MaxSessionLimit' value defined on the host pool. The is the maximum number of user sessions allowed per session host. |
| Properties | dynamic | Additional information. The fields included here may be changed in the future. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultType | string | Status of this evaluation event. |
| ScalingEvaluationStartTime | datetime | The timestamp (UTC) when the Autoscale evaluation started. |
| ScalingPlanResourceId | string | Resource ID of the Autoscale scaling plan. |
| ScalingReasonMessage | string | The actions Autoscale decided to perform and why it took those actions. |
| SessionCount | int | Number of user sessions, only the user sessions from session hosts which considered active by Autoscale are included. |
| SessionOccupancyPercent | real | Percent of session host capacity occupied by user sessions. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) this event was generated. |
| TotalSessionHostCount | int | Number of session hosts in the host pool. |
| Type | string | The name of the table |
| UnhealthySessionHostCount | int | Number of session hosts in a faulty state. |
