---
title: Azure Monitor Logs reference - SqlDataClassification
description: Reference for SqlDataClassification table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SqlDataClassification



## Solutions

- SQLDataClassification




## Columns

| Column | Type | Description |
|---|---|---|
| AgentId | string |   |
| _BilledSize | real | The record size in bytes |
| ColumnName | string |   |
| ColumnsCount | int |   |
| ColumnType | string |   |
| Computer | string |   |
| DatabaseName | string |   |
| InformationType | string |   |
| InformationTypeId | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Label | string |   |
| LabelId | string |   |
| ManagementGroupName | string |   |
| Rank | string |   |
| RecordType | string |   |
| ResourceGroup | string |   |
| ResourceId | string |   |
| ResourceProvider | string |   |
| ResourceType | string |   |
| ScanStartTime | datetime |   |
| SchemaName | string |   |
| ServerInstanceName | string |   |
| ServerInstanceType | string |   |
| ServerVersion | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubscriptionId | string |   |
| TableName | string |   |
| TablesCount | int |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
