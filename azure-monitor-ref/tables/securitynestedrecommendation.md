---
title: Azure Monitor Logs reference - SecurityNestedRecommendation
description: Reference for SecurityNestedRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# SecurityNestedRecommendation

Nested recommendations can be thought of as 'sub' recommendations grouped into a 'parent' recommendation. To view nested recommendations, open the 'parent' from the recommendations page in Security Center. For example, if a vulnerability scan of your SQL databases returns 100 findings, each finding will be available as a nested recommendation within the parent recommendation 'Vulnerabilities on your SQL databases should be remediated'.

## Solutions

- Security
- SecurityCenter
- SecurityCenterFree




## Columns

| Column | Type | Description |
|---|---|---|
| AdditionalData | dynamic | Additional details of the sub-assessment |
| AssessedResourceId | string | Id of the assessed resource |
| _BilledSize | real | The record size in bytes |
| Category | string | Category of the sub-assessment |
| Cause | string | Cause of the assessment status |
| Description | string | Description of the assessment status |
| Id | string | Id of the assessed recommendation |
| Impact | string | Description of the impact of this sub-assessment |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| IsSnapshot | bool | Indicates whether the data was exported as part of a snapshot when 'true', or streamed in real-time when 'false'. |
| NestedRecommendationId | string | Id of the nested-recommendation |
| ParentRecommendationId | string | Id of the parent recommendation |
| RecommendationLink | string | Recommendation link URL |
| RecommendationName | string | Display name of the sub-assessment |
| RecommendationSeverity | string | The sub-assessment severity level |
| RecommendationState | string | The sub-assessment state |
| RecommendationSubscriptionId | string | Recommendation's subscription Id |
| RemediationDescription | string | Information on how to remediate this sub-assessment |
| RemidiationDescription | string | Information on how to remediate this sub-assessment |
| ResourceDetails | dynamic | Details of the resource that was assessed |
| ResourceGroup | string | Resource group name |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceProviderType | string | Resource provider type of the assessed resource |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubAssessmentTimeGeneration | datetime | The date and time the sub-assessment was generated |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The date and time the sub-assessment was exported |
| Type | string | Resource type |
| VulnerabilityId | string | Vulnerability Id |
