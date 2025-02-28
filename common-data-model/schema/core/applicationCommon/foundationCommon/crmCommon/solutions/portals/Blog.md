---
title: Blog - Common Data Model | Microsoft Docs
description: The root entity for a portal blog.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Blog

The root entity for a portal blog.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Blog.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/Blog  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[blogId](#blogId)|Shows the entity instances.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[stateCode](#stateCode)|Shows whether the blog is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[stateCode_display](#stateCode_display)||<a href="Blog.md" target="_blank">portals/Blog</a>|
|[statusCode](#statusCode)|Select the blog's status.
|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[statusCode_display](#statusCode_display)||<a href="Blog.md" target="_blank">portals/Blog</a>|
|[name](#name)|Shows the name or title of the blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[archiveTemplateId](#archiveTemplateId)|Shows the page template to be used to render the archive page (for example, posts by date, tags, and so on) of the blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[homeTemplateId](#homeTemplateId)|Shows the page template to be used to render the home/main page of the Blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[postTemplateId](#postTemplateId)|Shows the page template to be used to render an individual Blog Post belonging to the Blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[commentPolicy](#commentPolicy)|Specifies the post comment policy to be used by this Blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[commentPolicy_display](#commentPolicy_display)||<a href="Blog.md" target="_blank">portals/Blog</a>|
|[displayOrder](#displayOrder)||<a href="Blog.md" target="_blank">portals/Blog</a>|
|[parentPageId](#parentPageId)|Shows the parent webpage associated with this blog, denoting its place in the website site map.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[partialURL](#partialURL)|Shows the URL path fragment to be used to build a URL for this blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[summary](#summary)|A descriptive summary of the Blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[websiteid](#websiteid)|Shows the website associated with the blog.|<a href="Blog.md" target="_blank">portals/Blog</a>|
|[blogPostLanguageId](#blogPostLanguageId)|Option to make blog posts language specific|<a href="Blog.md" target="_blank">portals/Blog</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#blogId name="blogId">blogId</a>

Shows the entity instances.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blog</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_blogid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the blog is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the blog is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the blog's status.
  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the blog's status.
</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Shows the name or title of the blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Shows the name or title of the blog.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#archiveTemplateId name="archiveTemplateId">archiveTemplateId</a>

Shows the page template to be used to render the archive page (for example, posts by date, tags, and so on) of the blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Archive Template</td></tr><tr><td>description</td><td>Shows the page template to be used to render the archive page (for example, posts by date, tags, and so on) of the blog.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_blogarchivepagetemplateid</td></tr></table>

### <a href=#homeTemplateId name="homeTemplateId">homeTemplateId</a>

Shows the page template to be used to render the home/main page of the Blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Home Template</td></tr><tr><td>description</td><td>Shows the page template to be used to render the home/main page of the Blog.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_bloghomepagetemplateid</td></tr></table>

### <a href=#postTemplateId name="postTemplateId">postTemplateId</a>

Shows the page template to be used to render an individual Blog Post belonging to the Blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Template</td></tr><tr><td>description</td><td>Shows the page template to be used to render an individual Blog Post belonging to the Blog.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_blogpostpagetemplateid</td></tr></table>

### <a href=#commentPolicy name="commentPolicy">commentPolicy</a>

Specifies the post comment policy to be used by this Blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment Policy</td></tr><tr><td>description</td><td>Specifies the post comment policy to be used by this Blog.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_commentpolicy</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>100000001</td></tr><tr><td>en</td><td>Open to Authenticated Users</td><td>100000002</td></tr><tr><td>en</td><td>Moderated</td><td>100000003</td></tr><tr><td>en</td><td>Closed</td><td>100000004</td></tr><tr><td>en</td><td>None</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#commentPolicy_display name="commentPolicy_display">commentPolicy_display</a>

First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#displayOrder name="displayOrder">displayOrder</a>

First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Order</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_displayorder</td></tr></table>

### <a href=#parentPageId name="parentPageId">parentPageId</a>

Shows the parent webpage associated with this blog, denoting its place in the website site map.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Page</td></tr><tr><td>description</td><td>Shows the parent webpage associated with this blog, denoting its place in the website site map.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_parentpageid</td></tr></table>

### <a href=#partialURL name="partialURL">partialURL</a>

Shows the URL path fragment to be used to build a URL for this blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partial URL</td></tr><tr><td>description</td><td>Shows the URL path fragment to be used to build a URL for this blog.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_partialurl</td></tr></table>

### <a href=#summary name="summary">summary</a>

A descriptive summary of the Blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary</td></tr><tr><td>description</td><td>A descriptive summary of the Blog.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_summary</td></tr></table>

### <a href=#websiteid name="websiteid">websiteid</a>

Shows the website associated with the blog.  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Shows the website associated with the blog.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_websiteid</td></tr></table>

### <a href=#blogPostLanguageId name="blogPostLanguageId">blogPostLanguageId</a>

Option to make blog posts language specific  
First included in: portals/Blog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blog Language</td></tr><tr><td>description</td><td>Option to make blog posts language specific</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_websitelanguageid</td></tr></table>
