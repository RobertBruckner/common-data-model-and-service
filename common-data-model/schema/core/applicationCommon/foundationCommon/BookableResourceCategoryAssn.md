---
title: BookableResourceCategoryAssn - Common Data Model | Microsoft Docs
description: Association entity to model the categorization of resources.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Bookable Resource Category Assn

Association entity to model the categorization of resources.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/BookableResourceCategoryAssn.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/BookableResourceCategoryAssn  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[ownerId](#ownerId)|Owner Id|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[bookableResourceCategoryAssnId](#bookableResourceCategoryAssnId)|Unique identifier of the resource and category association.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[name](#name)|The name of the association beween a resource and a category.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[resource](#resource)|Shows the resource associated with the category.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[resourceCategory](#resourceCategory)|Choose a category to associate with the resource.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[stateCode](#stateCode)|Status of the Resource Category Assn|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[stateCode_display](#stateCode_display)||<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[statusCode](#statusCode)|Reason for the status of the Resource Category Assn|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[statusCode_display](#statusCode_display)||<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the bookableresourcecategoryassn with respect to the base currency.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the BookableResourceCategoryAssn with respect to the base currency.|<a href="BookableResourceCategoryAssn.md" target="_blank">foundationCommon/BookableResourceCategoryAssn</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#bookableResourceCategoryAssnId name="bookableResourceCategoryAssnId">bookableResourceCategoryAssnId</a>

Unique identifier of the resource and category association.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Category Assn</td></tr><tr><td>description</td><td>Unique identifier of the resource and category association.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bookableresourcecategoryassnid</td></tr></table>

### <a href=#name name="name">name</a>

The name of the association beween a resource and a category.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the association beween a resource and a category.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#resource name="resource">resource</a>

Shows the resource associated with the category.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>description</td><td>Shows the resource associated with the category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resource</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Choose a category to associate with the resource.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Category</td></tr><tr><td>description</td><td>Choose a category to associate with the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resourcecategory</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Resource Category Assn  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Resource Category Assn</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Resource Category Assn  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Resource Category Assn</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the bookableresourcecategoryassn with respect to the base currency.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the bookableresourcecategoryassn with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the BookableResourceCategoryAssn with respect to the base currency.  
First included in: foundationCommon/BookableResourceCategoryAssn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the BookableResourceCategoryAssn with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
