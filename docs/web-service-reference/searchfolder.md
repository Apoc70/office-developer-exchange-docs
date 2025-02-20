---
title: "SearchFolder"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- SearchFolder
api_type:
- schema
ms.assetid: 1a7d408b-2e98-4391-8834-085ed6d5757c
description: "The SearchFolder element represents a search folder that is contained in a mailbox."
---

# SearchFolder

The **SearchFolder** element represents a search folder that is contained in a mailbox. 
  
```xml
<SearchFolder>
   <FolderId/>
   <ParentFolderId/>
   <FolderClass/>
   <DisplayName/>
   <TotalCount/>
   <ChildFolderCount/>
   <ExtendedProperty/>
   <ManagedFolderInformation/>
   <UnreadCount/>
   <SearchParameters/>
   <PermissionSet/>
      <EffectiveRights/>
</SearchFolder>
```

 **SearchFolderType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

|**Element**|**Description**|
|:-----|:-----|
|[FolderId](folderid.md) <br/> |Contains the identifier and change key of a folder.  <br/> |
|[ParentFolderId](parentfolderid.md) <br/> |Represents the identifier of the parent folder that contains the folder.  <br/> |
|[FolderClass](folderclass.md) <br/> |Represents the folder class for a given folder.  <br/> |
|[DisplayName (string)](displayname-string.md) <br/> |Contains the display name of a folder.  <br/> |
|[TotalCount](totalcount.md) <br/> |Represents the total count of items within a given folder.  <br/> |
|[ChildFolderCount](childfoldercount.md) <br/> |Represents the number of child folders contained within a folder. This property is read-only.  <br/> |
|[ExtendedProperty](extendedproperty.md) <br/> |Identifies extended properties on folders.  <br/> |
|[ManagedFolderInformation](managedfolderinformation.md) <br/> |Contains information about a managed folder.  <br/> |
|[UnreadCount](unreadcount.md) <br/> |Represents the count of unread items within a given folder.  <br/> |
|[SearchParameters](searchparameters.md) <br/> |Contains the parameters that define a search folder.  <br/> |
|[PermissionSet (PermissionSetType)](permissionset-permissionsettype.md) <br/> |Contains all the configured permissions for a folder. This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1).  <br/> |
|[EffectiveRights](effectiverights.md) <br/> |Contains the client's rights based on the permission settings for the item or folder. This element is read-only. This element was introduced in Exchange 2007 SP1.  <br/> |
   
### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[AppendToFolderField](appendtofolderfield.md) <br/> |Specifies data to append to a folder property during an [UpdateFolder operation](updatefolder-operation.md).  <br/> |
|[Create (FolderSync)](create-foldersync.md) <br/> |Identifies a single folder to create in the local client store.  <br/> |
|[SetFolderField](setfolderfield.md) <br/> |Represents an update to a single property on a folder in an [UpdateFolder operation](updatefolder-operation.md).  <br/> |
|[Update (FolderSync)](update-foldersync.md) <br/> |Identifies a single folder to update in the local client store.  <br/> |
|[Folders](folders-ex15websvcsotherref.md) <br/> |Contains an array of folders used in folder operations.  <br/> |
   
## Remarks

 **SearchFolder** is used for both regular search folders and MicrosoftOfficeOutlook and Outlook Web Access visible search folders. For a search folder to be visible to Outlook and Outlook Web Access, the folder must be created under the SearchFolders distinguished folder. 
  
The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema Name  <br/> |Types schema  <br/> |
|Validation File  <br/> |Types.xsd  <br/> |
|Can be Empty  <br/> |False  <br/> |
   
## See also



- [EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)

