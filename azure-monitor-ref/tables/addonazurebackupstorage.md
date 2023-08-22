---
title: Azure Monitor Logs reference - AddonAzureBackupStorage
description: Reference for AddonAzureBackupStorage table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# AddonAzureBackupStorage



## Categories

- IT & Management Tools
- Azure Resources
## Solutions

- LogManagement
## Resource types

- Recovery Services Vaults




## Columns

| Column | Type | Description |
|---|---|---|
| ArchiveTierStorageConsumedInMBs | string |   |
| BackupItemUniqueId | string |   |
| BackupManagementServerUniqueId | string |   |
| BackupManagementType | string |   |
| _BilledSize | real | The record size in bytes |
| Category | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OperationName | string |   |
| PreferredWorkloadOnVolume | string |   |
| ProtectedContainerUniqueId | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SchemaVersion | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| State | string |   |
| StorageAllocatedInMBs | real |   |
| StorageConsumedInMBs | real |   |
| StorageName | string |   |
| StorageTotalSizeInGBs | real |   |
| StorageType | string |   |
| StorageUniqueId | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
| VaultUniqueId | string |   |
| VolumeFriendlyName | string |   |
