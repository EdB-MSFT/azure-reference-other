---
title: Azure Monitor Logs reference - ADFAirflowTaskLogs
description: Reference for ADFAirflowTaskLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ADFAirflowTaskLogs

ADF Airflow task logs

## Solutions

- LogManagement




## Columns

| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string | The category of the log that belongs to Airflow application. |
| CorrelationId | string | The correlation id of the event. |
| DagId | string | The dag ID of the Airflow task run. |
| DataFactoryName | string | The name of the Data factory. |
| IntegrationRuntimeName | string | The name of the Integration runtime. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Message | string | The application log of the Airflow event. |
| OperationName | string | The name of the operation represented by this event. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TaskId | string | The task ID of the Airflow task run. |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of the log. |
| Type | string | The name of the table |
