---
title: LinkedInFormSubmissionAnswer - Common Data Model | Microsoft Docs
description: Answers to individual questions on a form submitted by a LinkedIn member
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# LinkedIn Form Submission Answer

Answers to individual questions on a form submitted by a LinkedIn member  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInFormSubmissionAnswer.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInFormSubmissionAnswer  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[ownerId](#ownerId)|Owner Id|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[linkedInFormAnswerId](#linkedInFormAnswerId)|Unique identifier for entity instances|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[stateCode](#stateCode)|Status of the LinkedIn Form Answer|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[stateCode_display](#stateCode_display)||<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[statusCode](#statusCode)|Reason for the status of the LinkedIn Form Answer|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[statusCode_display](#statusCode_display)||<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[name](#name)|The name of the custom entity.|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[answerId](#answerId)||<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[answerFormat](#answerFormat)|Format of the answer provided|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[answerText](#answerText)|Text of submitted response|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[linkedInQuestion](#linkedInQuestion)|LinkedIn question associated with this answer|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[linkedInFormSubmissionID](#linkedInFormSubmissionID)|Unique identifier for the LinkedIn form containing this answer|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|
|[linkedInQuestionID](#linkedInQuestionID)|Unique identifier of the LinkedIn question|<a href="LinkedInFormSubmissionAnswer.md" target="_blank">LinkedInLeads/LinkedInFormSubmissionAnswer</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#linkedInFormAnswerId name="linkedInFormAnswerId">linkedInFormAnswerId</a>

Unique identifier for entity instances  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Form Answer</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformanswerid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the LinkedIn Form Answer  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the LinkedIn Form Answer</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the LinkedIn Form Answer  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the LinkedIn Form Answer</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#answerId name="answerId">answerId</a>

First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Answer Id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_answer_textid</td></tr></table>

### <a href=#answerFormat name="answerFormat">answerFormat</a>

Format of the answer provided  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Answer format</td></tr><tr><td>description</td><td>Format of the answer provided</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_answerformat</td></tr></table>

### <a href=#answerText name="answerText">answerText</a>

Text of submitted response  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Answer text</td></tr><tr><td>description</td><td>Text of submitted response</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_answertext</td></tr></table>

### <a href=#linkedInQuestion name="linkedInQuestion">linkedInQuestion</a>

LinkedIn question associated with this answer  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn question</td></tr><tr><td>description</td><td>LinkedIn question associated with this answer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformquestion</td></tr></table>

### <a href=#linkedInFormSubmissionID name="linkedInFormSubmissionID">linkedInFormSubmissionID</a>

Unique identifier for the LinkedIn form containing this answer  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn form submission ID</td></tr><tr><td>description</td><td>Unique identifier for the LinkedIn form containing this answer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformsubmission</td></tr></table>

### <a href=#linkedInQuestionID name="linkedInQuestionID">linkedInQuestionID</a>

Unique identifier of the LinkedIn question  
First included in: LinkedInLeads/LinkedInFormSubmissionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn question ID</td></tr><tr><td>description</td><td>Unique identifier of the LinkedIn question</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinquestionid</td></tr></table>
