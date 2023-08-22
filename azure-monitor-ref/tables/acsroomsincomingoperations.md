---
title: Azure Monitor Logs reference - ACSRoomsIncomingOperations
description: Reference for ACSRoomsIncomingOperations table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# ACSRoomsIncomingOperations

Communication Services logs of incoming requests to rooms operations, with summaries of room object, lifespan, participants and roles count etc.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Communication Services




## Columns

| Column | Type | Description |
|---|---|---|
| AddedRoomParticipantsCount | int | The count of participants added to a room. |
| _BilledSize | real | The record size in bytes |
| CorrelationId | string | The unique ID of the request. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | The severity level of the operation. |
| OperationName | string | The operation associated with log record. e.g., CreateRoom, PatchRoom, GetRoom, ListRooms, DeleteRoom, GetParticipants, AddParticipants, UpdateParticipants, or RemoveParticipants. |
| OperationVersion | string | The API-version associated with the operation or version of the operation (if there is no API version). |
| RemovedRoomParticipantsCount | int | The count of participants removed in a room. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResultSignature | string | The sub status of the operation. If this operation corresponds to a REST API call, this field is the HTTP status code of the corresponding REST call. |
| ResultType | string | The status of the operation. |
| RoomId | string | The ID of the room. |
| RoomLifespan | int | The Room lifespan in minutes. |
| RoomParticipantsAttendee | int | The participants count with attendee role. |
| RoomParticipantsConsumer | int | The participants count with consumer role. |
| RoomParticipantsCount | int | The count of participants in a room. |
| RoomParticipantsPresenter | int | The participants count with presenter role. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | The timestamp (UTC) of when the log was generated. |
| Type | string | The name of the table |
| UpsertedRoomParticipantsCount | int | The count of participants upserted in a room. |
