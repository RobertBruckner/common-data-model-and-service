---
title: AreaOfInterest - Common Data Model | Microsoft Docs
description: This describes the AreaOfInterest entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Area of Interest

The master list of all areas of interest that an institution offers. Areas of interest are higher-level subject groupings, such as astronomy or business.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/AreaOfInterest.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/education/higherEducation/AreaOfInterest  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[ownerId](#ownerId)|Owner Id|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[areaOfInterestId](#areaOfInterestId)|Unique identifier for entity instances|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[stateCode](#stateCode)|Status of the Area of Interest|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[stateCode_display](#stateCode_display)||<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[statusCode](#statusCode)|Reason for the status of the Area of Interest|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[statusCode_display](#statusCode_display)||<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[name](#name)|Area of Interest instance name|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[code](#code)|Abbreviated code for the area of interest.|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[externalIdentifier](#externalIdentifier)|External Identifier|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[externalSourceSystem](#externalSourceSystem)|External Source System|<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|
|[externalSourceSystem_display](#externalSourceSystem_display)||<a href="AreaOfInterest.md" target="_blank">higherEducation/AreaOfInterest</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#areaOfInterestId name="areaOfInterestId">areaOfInterestId</a>

Unique identifier for entity instances  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Area of Interest</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>mshied_areaofinterestid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Area of Interest  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Area of Interest</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Area of Interest  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Area of Interest</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Area of Interest instance name  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Area of Interest Name</td></tr><tr><td>description</td><td>Area of Interest instance name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_name</td></tr></table>

### <a href=#code name="code">code</a>

Abbreviated code for the area of interest.  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>Abbreviated code for the area of interest.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_code</td></tr></table>

### <a href=#externalIdentifier name="externalIdentifier">externalIdentifier</a>

External Identifier  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Identifier</td></tr><tr><td>description</td><td>External Identifier</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_externalidentifier</td></tr></table>

### <a href=#externalSourceSystem name="externalSourceSystem">externalSourceSystem</a>

External Source System  
First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Source System</td></tr><tr><td>description</td><td>External Source System</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_externalsourcesystem</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>System 1</td><td>494280000</td></tr><tr><td>en</td><td>System 2</td><td>494280001</td></tr><tr><td>en</td><td>System 3</td><td>494280002</td></tr></table></td></tr></table>

### <a href=#externalSourceSystem_display name="externalSourceSystem_display">externalSourceSystem_display</a>

First included in: higherEducation/AreaOfInterest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
