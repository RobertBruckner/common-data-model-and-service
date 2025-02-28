---
title: SessionTrack - Common Data Model | Microsoft Docs
description: This describes the SessionTrack entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Session Track

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/SessionTrack.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/SessionTrack  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[ownerId](#ownerId)|Owner Id|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[sessionTrackId](#sessionTrackId)|Unique identifier for entity instances|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[stateCode](#stateCode)|Status of the Session Track|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[stateCode_display](#stateCode_display)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[statusCode](#statusCode)|Reason for the status of the Session Track|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[statusCode_display](#statusCode_display)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[name](#name)|The name of the custom entity.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[audienceType](#audienceType)|Audience Type of the Session Track.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[audienceType_display](#audienceType_display)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[description](#description)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[eventId](#eventId)|Unique identifier for Event associated with Session Track.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[industryType](#industryType)|Industry of the Session Track.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[industryType_display](#industryType_display)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[keywords](#keywords)|Keywords of the Session Track.|<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[numberOfRegistrations](#numberOfRegistrations)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[publishStatus](#publishStatus)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[publishStatus_display](#publishStatus_display)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[sessionsInTrack](#sessionsInTrack)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[targetNumberOfSessions](#targetNumberOfSessions)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[trackCode](#trackCode)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[trackGoal](#trackGoal)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[trackType](#trackType)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|
|[trackType_display](#trackType_display)||<a href="SessionTrack.md" target="_blank">eventManagement/SessionTrack</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#sessionTrackId name="sessionTrackId">sessionTrackId</a>

Unique identifier for entity instances  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Track</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_sessiontrackid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Session Track  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Session Track</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Session Track  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Session Track</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#audienceType name="audienceType">audienceType</a>

Audience Type of the Session Track.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Audience Type</td></tr><tr><td>description</td><td>Audience Type of the Session Track.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_audiencetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>General</td><td>100000000</td></tr><tr><td>en</td><td>Introductory</td><td>100000001</td></tr><tr><td>en</td><td>Intermediate</td><td>100000002</td></tr><tr><td>en</td><td>Advanced</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#audienceType_display name="audienceType_display">audienceType_display</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_description</td></tr></table>

### <a href=#eventId name="eventId">eventId</a>

Unique identifier for Event associated with Session Track.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Unique identifier for Event associated with Session Track.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventid</td></tr></table>

### <a href=#industryType name="industryType">industryType</a>

Industry of the Session Track.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>description</td><td>Industry of the Session Track.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_industrytype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Architecture and Engineering</td><td>100000000</td></tr><tr><td>en</td><td>Financial Services</td><td>100000001</td></tr><tr><td>en</td><td>Manufacturing</td><td>100000002</td></tr><tr><td>en</td><td>Media, Entertainment</td><td>100000003</td></tr><tr><td>en</td><td>Professional Services</td><td>100000004</td></tr><tr><td>en</td><td>Public Sector</td><td>100000005</td></tr><tr><td>en</td><td>Retail</td><td>100000006</td></tr><tr><td>en</td><td>Wholesale and Distribution</td><td>100000007</td></tr><tr><td>en</td><td>Other</td><td>100000008</td></tr></table></td></tr></table>

### <a href=#industryType_display name="industryType_display">industryType_display</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#keywords name="keywords">keywords</a>

Keywords of the Session Track.  
First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Keywords</td></tr><tr><td>description</td><td>Keywords of the Session Track.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_keywords</td></tr></table>

### <a href=#numberOfRegistrations name="numberOfRegistrations">numberOfRegistrations</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Registrations</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofregistrations</td></tr></table>

### <a href=#publishStatus name="publishStatus">publishStatus</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publish Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publishstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>100000000</td></tr><tr><td>en</td><td>Ready to publish</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Published</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#publishStatus_display name="publishStatus_display">publishStatus_display</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sessionsInTrack name="sessionsInTrack">sessionsInTrack</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sessions in track</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionsintrack</td></tr></table>

### <a href=#targetNumberOfSessions name="targetNumberOfSessions">targetNumberOfSessions</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target number of sessions</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_targetnumberofsessions</td></tr></table>

### <a href=#trackCode name="trackCode">trackCode</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Track code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_trackcode</td></tr></table>

### <a href=#trackGoal name="trackGoal">trackGoal</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Track goal</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_trackgoal</td></tr></table>

### <a href=#trackType name="trackType">trackType</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Track Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_tracktype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Internal</td><td>100000000</td></tr><tr><td>en</td><td>External</td><td>100000001</td></tr></table></td></tr></table>

### <a href=#trackType_display name="trackType_display">trackType_display</a>

First included in: eventManagement/SessionTrack (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
