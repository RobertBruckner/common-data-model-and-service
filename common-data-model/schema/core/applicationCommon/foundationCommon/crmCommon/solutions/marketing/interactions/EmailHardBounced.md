---
title: EmailHardBounced - Common Data Model | Microsoft Docs
description: This describes the EmailHardBounced entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Email hard bounced

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailHardBounced.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/EmailHardBounced  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[contactId](#contactId)|Contact|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[accountId](#accountId)|Account|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[messageId](#messageId)|Message|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[customerJourneyId](#customerJourneyId)|Customer journey|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[organizationId](#organizationId)|Organization ID|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[sendingId](#sendingId)|Sending ID|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[usageType](#usageType)|Usage type|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[interactionType](#interactionType)|Interaction type|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[timestamp](#timestamp)|Timestamp|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[bounceCategory](#bounceCategory)|Bounce category|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[remoteBounce](#remoteBounce)|Remote bounce|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|
|[activityId](#activityId)|Activity ID|<a href="EmailHardBounced.md" target="_blank">interactions/EmailHardBounced</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#messageId name="messageId">messageId</a>

Message  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message</td></tr><tr><td>description</td><td>Message</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>MessageId</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Customer journey  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>CustomerJourneyId</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Organization ID  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization ID</td></tr><tr><td>description</td><td>Organization ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sendingId name="sendingId">sendingId</a>

Sending ID  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sending ID</td></tr><tr><td>description</td><td>Sending ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#customerJourneyIterationId name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey iteration ID</td></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#usageType name="usageType">usageType</a>

Usage type  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Usage type</td></tr><tr><td>description</td><td>Usage type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#interactionType name="interactionType">interactionType</a>

Interaction type  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction type</td></tr><tr><td>description</td><td>Interaction type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#bounceCategory name="bounceCategory">bounceCategory</a>

Bounce category  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bounce category</td></tr><tr><td>description</td><td>Bounce category</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#remoteBounce name="remoteBounce">remoteBounce</a>

Remote bounce  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remote bounce</td></tr><tr><td>description</td><td>Remote bounce</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Activity ID  
First included in: interactions/EmailHardBounced (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity ID</td></tr><tr><td>description</td><td>Activity ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
