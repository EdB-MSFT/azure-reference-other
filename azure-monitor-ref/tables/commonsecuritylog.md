---
title: Azure Monitor Logs reference - CommonSecurityLog
description: Reference for CommonSecurityLog table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/09/2023
---

# CommonSecurityLog

This table is for collecting events in the Common Event Format, that are most often sent from different security appliances such as Check Point, Palo Alto and more.

## Categories

- Security
## Solutions

- Security
- SecurityInsights
## Resource types

- Azure Sentinel CEF Table
- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager
- Virtual Machine Scale Sets




## Columns

| Column | Type | Description |
|---|---|---|
| Activity | string | A string that represents a human-readable and understandable description of the event. |
| AdditionalExtensions | string | A placeholder for additional fields. Fields are logged as key-value pairs. |
| ApplicationProtocol | string | The protocol used in the application, such as HTTP, HTTPS, SSHv2, Telnet, POP, IMPA, IMAPS, and so on. |
| _BilledSize | real | The record size in bytes |
| CollectorHostName | string | The hostname of the collector machine running the agent. |
| CommunicationDirection | string | Any information about the direction the observed communication has taken. Valid values: 0 = Inbound, 1 = Outbound. |
| Computer | string | Host, from Syslog. |
| DestinationDnsDomain | string | The DNS part of the fully-qualified domain name (FQDN). |
| DestinationHostName | string | The destination that the event refers to in an IP network. The format should be an FQDN associated with the destination node, when a node is available. For example: host.domain.com or host. |
| DestinationIP | string | The destination IpV4 address that the event refers to in an IP network. |
| DestinationMACAddress | string | The destination MAC address (FQDN). |
| DestinationNTDomain | string | The Windows domain name of the destination address. |
| DestinationPort | int | Destination port. Valid values: 0 - 65535. |
| DestinationProcessId | int | The ID of the destination process associated with the event. |
| DestinationProcessName | string | The name of the event’s destination process, such as telnetd or sshd. |
| DestinationServiceName | string | The service that is targeted by the event. For example: sshd. |
| DestinationTranslatedAddress | string | Identifies the translated destination referred to by the event in an IP network, as an IPv4 IP address. |
| DestinationTranslatedPort | int | Port after translation, such as a firewall Valid port numbers: 0 - 65535. |
| DestinationUserID | string | Identifies the destination user by ID. For example: in Unix, the root user is generally associated with the user ID 0. |
| DestinationUserName | string | Identifies the destination user by name. |
| DestinationUserPrivileges | string | Defines the destination use's privileges. Valid values: Admninistrator, User, Guest. |
| DeviceAction | string | The action mentioned in the event. |
| DeviceAddress | string | The IPv4 address of the device generating the event. |
| DeviceCustomDate1 | string | One of two timestamp fields available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomDate1Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomDate2 | string | One of two timestamp fields available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomDate2Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomFloatingPoint1 | real | One of four floating point fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomFloatingPoint1Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomFloatingPoint2 | real | One of four floating point fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomFloatingPoint2Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomFloatingPoint3 | real | One of four floating point fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomFloatingPoint3Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomFloatingPoint4 | real | One of four floating point fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomFloatingPoint4Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomIPv6Address1 | string | One of four IPv6 address fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomIPv6Address1Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomIPv6Address2 | string | One of four IPv6 address fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomIPv6Address2Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomIPv6Address3 | string | One of four IPv6 address fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomIPv6Address3Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomIPv6Address4 | string | One of four IPv6 address fields available to map fields that do not apply to any other in this dictionary. |
| DeviceCustomIPv6Address4Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomNumber1 | int | Soon to be a deprecated field. Will be replaced by FieldDeviceCustomNumber1. |
| DeviceCustomNumber1Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomNumber2 | int | Soon to be a deprecated field. Will be replaced by FieldDeviceCustomNumber2. |
| DeviceCustomNumber2Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomNumber3 | int | Soon to be a deprecated field. Will be replaced by FieldDeviceCustomNumber3. |
| DeviceCustomNumber3Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomString1 | string | One of six strings available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomString1Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomString2 | string | One of six strings available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomString2Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomString3 | string | One of six strings available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomString3Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomString4 | string | One of six strings available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomString4Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomString5 | string | One of six strings available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomString5Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceCustomString6 | string | One of six strings available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. |
| DeviceCustomString6Label | string | All custom fields have a corresponding label field. Each of these fields is a string and describes the purpose of the custom field. |
| DeviceDnsDomain | string | The DNS domain part of the full qualified domain name (FQDN). |
| DeviceEventCategory | string | Represents the category assigned by the originating device. Devices often use their own categorization schema to classify event. Example: '/Monitor/Disk/Read'. |
| DeviceEventClassID | string | String or integer that serves as a unique identifier per event type. |
| DeviceExternalID | string | A name that uniquely identifies the device generating the event. |
| DeviceFacility | string | The facility generating the event. For example: auth or local1. |
| DeviceInboundInterface | string | The interface on which the packet or data entered the device. For example: ethernet1/2. |
| DeviceMacAddress | string | The MAC address of the device generating the event. |
| DeviceName | string | The FQDN associated with the device node, when a node is available. For example: host.domain.com or host. |
| DeviceNtDomain | string | The Windows domain of the device address. |
| DeviceOutboundInterface | string | Interface on which the packet or data left the device. |
| DevicePayloadId | string | Unique identifier for the payload associated with the event. |
| DeviceProduct | string | String that together with device product and version definitions, uniquely identifies the type of sending device. |
| DeviceTimeZone | string | Timezone of the device generating the event. |
| DeviceTranslatedAddress | string | Identifies the translated device address that the event refers to, in an IP network. The format is an Ipv4 address. |
| DeviceVendor | string | String that together with device product and version definitions, uniquely identifies the type of sending device. |
| DeviceVersion | string | String that together with device product and version definitions, uniquely identifies the type of sending device. |
| EndTime | datetime | The time at which the activity related to the event ended. |
| EventCount | int | A count associated with the event, showing how many times the same event was observed. |
| EventOutcome | string | Displays the outcome, usually as ‘success’ or ‘failure’. |
| EventType | int | Event type. Value values include: 0: base event, 1: aggregated, 2: correlation event, 3: action event. Note: This event can be omitted for base events. |
| ExternalID | int | Soon to be a deprecated field. Will be replaced by ExtID. |
| ExtID | string | An ID used by the originating device (will replace legacy ExternalID). Typically, these values have increasing values that are each associated with an event. |
| FieldDeviceCustomNumber1 | long | One of three number fields available to map fields that do not apply to any other in this dictionary (will replace legacy DeviceCustomNumber1). Use sparingly and seek a more specific, dictionary supplied field when possible. |
| FieldDeviceCustomNumber2 | long | One of three number fields available to map fields that do not apply to any other in this dictionary (will replace legacy DeviceCustomNumber2). Use sparingly and seek a more specific, dictionary supplied field when possible. |
| FieldDeviceCustomNumber3 | long | One of three number fields available to map fields that do not apply to any other in this dictionary (will replace legacy DeviceCustomNumber3). Use sparingly and seek a more specific, dictionary supplied field when possible. |
| FileCreateTime | string | Time when the file was created. |
| FileHash | string | Hash of a file. |
| FileID | string | An ID associated with a file, such as the inode. |
| FileModificationTime | string | Time when the file was last modified. |
| FileName | string | The file's name, without the path. |
| FilePath | string | Full path to the file, including the filename. For example: C:\ProgramFiles\WindowsNT\Accessories\wordpad.exe or /usr/bin/zip. |
| FilePermission | string | The file's permissions. For example: '2,1,1'. |
| FileSize | int | The size of the file in bytes. |
| FileType | string | File type, such as pipe, socket, and so on. |
| FlexDate1 | string | A timestamp field available to map a timestamp that does not apply to any other defined timestamp field in this dictionary. Use all flex fields sparingly and seek a more specific, dictionary supplied field when possible. These fields are typically reserved for customer use and should not be set by vendors unless necessary. |
| FlexDate1Label | string | The label field is a string and describes the purpose of the flex field. |
| FlexNumber1 | int | Number fields available to map Int data that does not apply to any other field in this dictionary. |
| FlexNumber1Label | string | The label that describes the value in FlexNumber1 |
| FlexNumber2 | int | Number fields available to map Int data that does not apply to any other field in this dictionary. |
| FlexNumber2Label | string | The label that describes the value in FlexNumber2 |
| FlexString1 | string | One of four floating point fields available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. These fields are typically reserved for customer use and should not be set by vendors unless necessary. |
| FlexString1Label | string | The label field is a string and describes the purpose of the flex field. |
| FlexString2 | string | One of four floating point fields available to map fields that do not apply to any other in this dictionary. Use sparingly and seek a more specific, dictionary supplied field when possible. These fields are typically reserved for customer use and should not be set by vendors unless necessary. |
| FlexString2Label | string | The label field is a string and describes the purpose of the flex field. |
| IndicatorThreatType | string | The threat type of the MaliciousIP according to our TI feed. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| LogSeverity | string | A string or integer that describes the importance of the event. Valid string values: Unknown , Low, Medium, High, Very-High Valid integer values are: 0-3 = Low, 4-6 = Medium, 7-8 = High, 9-10 = Very-High. |
| MaliciousIP | string | If one of the IP in the message was correlate with the current TI feed we have it will show up here. |
| MaliciousIPCountry | string | The country of the MaliciousIP according to the GEO information at the time of the record ingestion. |
| MaliciousIPLatitude | real | The Latitude of the MaliciousIP according to the GEO information at the time of the record ingestion. |
| MaliciousIPLongitude | real | The Longitude of the MaliciousIP according to the GEO information at the time of the record ingestion. |
| Message | string | A message that gives more details about the event. |
| OldFileCreateTime | string | Time when the old file was created. |
| OldFileHash | string | Hash of the old file. |
| OldFileID | string | And ID associated with the old file, such as the inode. |
| OldFileModificationTime | string | Time when the old file was last modified. |
| OldFileName | string | Name of the old file. |
| OldFilePath | string | Full path to the old file, including the filename. For example: C:\ProgramFiles\WindowsNT\Accessories\wordpad.exe or /usr/bin/zip. |
| OldFilePermission | string | Permissions of the old file. For example: '2,1,1'. |
| OldFileSize | int | The size of the old file in bytes. |
| OldFileType | string | File type of the old file, such as a pipe, socket, and so on. |
| OriginalLogSeverity | string | A non-mapped version of LogSeverity. For example: Warning/Critical/Info insted of the normilized Low/Medium/High in the LogSeverity Field |
| ProcessID | int | Defines the ID of the process on the device generating the event. |
| ProcessName | string | Process name associated with the event. For example: in UNIX, the process generating the syslog entry. |
| Protocol | string | Transport protocol that identifies the Layer-4 protocol used. Possible values include protocol names, such as TCP or UDP. |
| Reason | string | The reason an audit event was generated. For example 'bad password' or 'unknown user'. This could also be an error or return code. Example: '0x1234'. |
| ReceiptTime | string | The time at which the event related to the activity was received. Different then the 'Timegenerated' field, which is when the event was recieved in the log collector machine. |
| ReceivedBytes | long | Number of bytes transferred inbound. |
| RemoteIP | string | The remote IP address, derived from the event's direction value, if possible. |
| RemotePort | string | The remote port, derived from the event's direction value, if possible. |
| ReportReferenceLink | string | Link to the report of the TI feed. |
| RequestClientApplication | string | The user agent associated with the request. |
| RequestContext | string | Describes the content from which the request originated, such as the HTTP Referrer. |
| RequestCookies | string | Cookies associated with the request. |
| RequestMethod | string | The method used to access a URL. Valid values include methods such as POST, GET, and so on. |
| RequestURL | string | The URL accessed for an HTTP request, including the protocol. For example: http://www/secure.com. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SentBytes | long | Number of bytes transferred outbound. |
| SimplifiedDeviceAction | string | A mapped version of DeviceAction, such as Denied > Deny. |
| SourceDnsDomain | string | The DNS domain part of the complete FQDN. |
| SourceHostName | string | Identifies the source that event refers to in an IP network. Format should be a fully qualified domain name (DQDN) associated with the source node, when a node is available. For example: host or host.domain.com. |
| SourceIP | string | The source that an event refers to in an IP network, as an IPv4 address. |
| SourceMACAddress | string | Source MAC address. |
| SourceNTDomain | string | The Windows domain name for the source address. |
| SourcePort | int | The source port number. Valid port numbers are 0 - 65535. |
| SourceProcessId | int | The ID of the source process associated with the event. |
| SourceProcessName | string | The name of the event's source process. |
| SourceServiceName | string | The service responsible for generating the event. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SourceTranslatedAddress | string | Identifies the translated source that the event refers to in an IP network. |
| SourceTranslatedPort | int | Source port after translation, such as a firewall. Valid port numbers are 0 - 65535. |
| SourceUserID | string | Identifies the source user by ID. |
| SourceUserName | string | Identifies the source user by name. Email addresses are also mapped into the UserName fields. The sender is a candidate to put into this field. |
| SourceUserPrivileges | string | The source user's privileges. Valid values include: Administrator, User, Guest. |
| StartTime | datetime | The time when the activity that the event refers to started. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| ThreatConfidence | string | The threat confidence of the MaliciousIP according to our TI feed. |
| ThreatDescription | string | The threat description of the MaliciousIP according to our TI feed. |
| ThreatSeverity | int | The threat severity of the MaliciousIP according to our TI feed at the time of the record ingestion. |
| TimeGenerated | datetime | Event collection time in UTC. |
| Type | string | The name of the table |
