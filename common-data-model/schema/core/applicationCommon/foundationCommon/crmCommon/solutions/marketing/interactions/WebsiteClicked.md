---
title: WebsiteClicked - Common Data Model | Microsoft Docs
description: This describes the WebsiteClicked entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Website clicked

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/WebsiteClicked.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/WebsiteClicked  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[customerJourneyId](#customerJourneyId)|Customer journey|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[contactId](#contactId)|Contact|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[accountId](#accountId)|Account|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[websiteId](#websiteId)|Website|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[pageAddress](#pageAddress)|Page address|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[pageId](#pageId)|Page ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[referrerUri](#referrerUri)|Referrer URL|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[searchPhrase](#searchPhrase)|Search phrase|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[searchEngineName](#searchEngineName)|Search engine name|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[link](#link)|Link|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[linkFriendlyName](#linkFriendlyName)|Link friendly name|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[interactionType](#interactionType)|Interaction type|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[organizationId](#organizationId)|Organization ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[timestamp](#timestamp)|Timestamp|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[visitorId](#visitorId)|Visitor ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[sessionId](#sessionId)|Session ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[countryIsoCode](#countryIsoCode)|Country ISO code|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[state](#state)|State|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[city](#city)|City|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[postalCode](#postalCode)|Postal code|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[browserId](#browserId)|Browser ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[browserVersion](#browserVersion)|Browser version|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[operatingSystemId](#operatingSystemId)|Operating system ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[operatingSystemVersion](#operatingSystemVersion)|Operating system version|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[sendingId](#sendingId)|Sending ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[visitDuration](#visitDuration)|Visit duration|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[visitorReturningStatus](#visitorReturningStatus)|Visitor returning status|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[visitorAnonymousStatus](#visitorAnonymousStatus)|Visitor anonymous status|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|
|[leadId](#leadId)|Lead ID|<a href="WebsiteClicked.md" target="_blank">interactions/WebsiteClicked</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Customer journey  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>CustomerJourneyId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#websiteId name="websiteId">websiteId</a>

Website  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Website</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>WebsiteId</td></tr></table>

### <a href=#customerJourneyIterationId name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey iteration ID</td></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#pageAddress name="pageAddress">pageAddress</a>

Page address  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Page address</td></tr><tr><td>description</td><td>Page address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#pageId name="pageId">pageId</a>

Page ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Page ID</td></tr><tr><td>description</td><td>Page ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#referrerUri name="referrerUri">referrerUri</a>

Referrer URL  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referrer URL</td></tr><tr><td>description</td><td>Referrer URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchPhrase name="searchPhrase">searchPhrase</a>

Search phrase  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search phrase</td></tr><tr><td>description</td><td>Search phrase</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchEngineName name="searchEngineName">searchEngineName</a>

Search engine name  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search engine name</td></tr><tr><td>description</td><td>Search engine name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#link name="link">link</a>

Link  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Link</td></tr><tr><td>description</td><td>Link</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#linkFriendlyName name="linkFriendlyName">linkFriendlyName</a>

Link friendly name  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Link friendly name</td></tr><tr><td>description</td><td>Link friendly name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#interactionType name="interactionType">interactionType</a>

Interaction type  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction type</td></tr><tr><td>description</td><td>Interaction type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Organization ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization ID</td></tr><tr><td>description</td><td>Organization ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorId name="visitorId">visitorId</a>

Visitor ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor ID</td></tr><tr><td>description</td><td>Visitor ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sessionId name="sessionId">sessionId</a>

Session ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session ID</td></tr><tr><td>description</td><td>Session ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#countryIsoCode name="countryIsoCode">countryIsoCode</a>

Country ISO code  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country ISO code</td></tr><tr><td>description</td><td>Country ISO code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#state name="state">state</a>

State  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

City  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Postal code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserId name="browserId">browserId</a>

Browser ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser ID</td></tr><tr><td>description</td><td>Browser ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserVersion name="browserVersion">browserVersion</a>

Browser version  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser version</td></tr><tr><td>description</td><td>Browser version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemId name="operatingSystemId">operatingSystemId</a>

Operating system ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system ID</td></tr><tr><td>description</td><td>Operating system ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemVersion name="operatingSystemVersion">operatingSystemVersion</a>

Operating system version  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system version</td></tr><tr><td>description</td><td>Operating system version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sendingId name="sendingId">sendingId</a>

Sending ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sending ID</td></tr><tr><td>description</td><td>Sending ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitDuration name="visitDuration">visitDuration</a>

Visit duration  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visit duration</td></tr><tr><td>description</td><td>Visit duration</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorReturningStatus name="visitorReturningStatus">visitorReturningStatus</a>

Visitor returning status  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor returning status</td></tr><tr><td>description</td><td>Visitor returning status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorAnonymousStatus name="visitorAnonymousStatus">visitorAnonymousStatus</a>

Visitor anonymous status  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor anonymous status</td></tr><tr><td>description</td><td>Visitor anonymous status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

Lead ID  
First included in: interactions/WebsiteClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead ID</td></tr><tr><td>description</td><td>Lead ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
