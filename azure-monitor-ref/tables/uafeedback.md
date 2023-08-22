---
title: Azure Monitor Logs reference - UAFeedback
description: Reference for UAFeedback table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# UAFeedback



## Categories

- Desktop Analytics
## Solutions

- CompatibilityAssessment




## Columns

| Column | Type | Description |
|---|---|---|
| AppName | string |   |
| AppVersion | string |   |
| _BilledSize | real | The record size in bytes |
| Category | string |   |
| Computer | string |   |
| ComputerID | string |   |
| Feedback | string |   |
| FeedbackSubmittedDate | datetime |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| MicrosoftResponse | string |   |
| Sentiment | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TimeGenerated | datetime |   |
| Title | string |   |
| TotalUpvotes | int |   |
| Type | string | The name of the table |
