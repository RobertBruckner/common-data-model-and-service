---
title: MarketingEmail - Common Data Model | Microsoft Docs
description: This describes the MarketingEmail entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Marketing Email

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/MarketingEmail.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/MarketingEmail  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[marketingEmailId](#marketingEmailId)|Unique ID for entity instances.|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[stateCode](#stateCode)|Status of the Marketing Email|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[stateCode_display](#stateCode_display)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[statusCode](#statusCode)|Marketing email status reason|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[statusCode_display](#statusCode_display)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[name](#name)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[automaticallyGeneratePlainText](#automaticallyGeneratePlainText)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[clickMap](#clickMap)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[description](#description)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[designerHTML](#designerHTML)|Clean email body: HTML with no CSS inlining and no compression|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[emailBody](#emailBody)|The body of the email|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[fromEmail](#fromEmail)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[fromName](#fromName)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[fromUser](#fromUser)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[insightsPlaceholder](#insightsPlaceholder)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[istemplategalleryneeded](#istemplategalleryneeded)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[legalDesignation](#legalDesignation)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[legalDesignation_display](#legalDesignation_display)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[replyToEmail](#replyToEmail)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[subject](#subject)|The subject of the marketing email|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[templateId](#templateId)|Template for the Email|<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[plainText](#plainText)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[to](#to)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|
|[UICEntityID](#UICEntityID)||<a href="MarketingEmail.md" target="_blank">marketing/MarketingEmail</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#marketingEmailId name="marketingEmailId">marketingEmailId</a>

Unique ID for entity instances.  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing email</td></tr><tr><td>description</td><td>Unique ID for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingemailid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Marketing Email  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Marketing Email</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Marketing email status reason  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status reason</td></tr><tr><td>description</td><td>Marketing email status reason</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td><td>0</td></tr><tr><td>en</td><td>Live</td><td>192350001</td><td>0</td></tr><tr><td>en</td><td>Stopped</td><td>192350002</td><td>0</td></tr><tr><td>en</td><td>Live, Editable</td><td>192350003</td><td>0</td></tr><tr><td>en</td><td>Expired</td><td>192350004</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#automaticallyGeneratePlainText name="automaticallyGeneratePlainText">automaticallyGeneratePlainText</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatically generate plain text</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_automaticallygeneratetextpart</td></tr></table>

### <a href=#clickMap name="clickMap">clickMap</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Click map</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_clickmap</td></tr></table>

### <a href=#description name="description">description</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_description</td></tr></table>

### <a href=#designerHTML name="designerHTML">designerHTML</a>

Clean email body: HTML with no CSS inlining and no compression  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designer HTML</td></tr><tr><td>description</td><td>Clean email body: HTML with no CSS inlining and no compression</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_designerhtml</td></tr></table>

### <a href=#emailBody name="emailBody">emailBody</a>

The body of the email  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email body</td></tr><tr><td>description</td><td>The body of the email</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_emailbody</td></tr></table>

### <a href=#fromEmail name="fromEmail">fromEmail</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email from address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_fromemail</td></tr></table>

### <a href=#fromName name="fromName">fromName</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email from name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_fromname</td></tr></table>

### <a href=#fromUser name="fromUser">fromUser</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From user</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_fromuser</td></tr></table>

### <a href=#insightsPlaceholder name="insightsPlaceholder">insightsPlaceholder</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insights</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_insights_placeholder</td></tr></table>

### <a href=#istemplategalleryneeded name="istemplategalleryneeded">istemplategalleryneeded</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is template gallery needed</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_istemplategalleryneeded</td></tr></table>

### <a href=#legalDesignation name="legalDesignation">legalDesignation</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal designation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_messagedesignation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Commercial</td><td>0</td></tr><tr><td>en</td><td>Transactional</td><td>1</td></tr></table></td></tr></table>

### <a href=#legalDesignation_display name="legalDesignation_display">legalDesignation_display</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#replyToEmail name="replyToEmail">replyToEmail</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reply-to email</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>762</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_replytoemail</td></tr></table>

### <a href=#subject name="subject">subject</a>

The subject of the marketing email  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>The subject of the marketing email</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_subject</td></tr></table>

### <a href=#templateId name="templateId">templateId</a>

Template for the Email  
First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Template</td></tr><tr><td>description</td><td>Template for the Email</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_templateid</td></tr></table>

### <a href=#plainText name="plainText">plainText</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Plain text</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_textpart</td></tr></table>

### <a href=#to name="to">to</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_to</td></tr></table>

### <a href=#UICEntityID name="UICEntityID">UICEntityID</a>

First included in: marketing/MarketingEmail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UIC Entity ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_uicentityid</td></tr></table>
