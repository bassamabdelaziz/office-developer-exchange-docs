---
title: "ContactsFolderPermissionLevel"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- ContactsFolderPermissionLevel
api_type:
- schema
ms.assetid: 805f05e7-b320-436a-9965-ba1ee235ac41
description: "The ContactsFolderPermissionLevel element contains the permissions for the default Contacts folder. This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1)."
---

# ContactsFolderPermissionLevel

The **ContactsFolderPermissionLevel** element contains the permissions for the default Contacts folder. This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1). 
  
```xml
<ContactsFolderPermissionLevel>
   None or Editor or Reviewer or Author or Custom
</ContactsFolderPermissionLevel>
```

 **DelegateFolderPermissionLevelType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

None.
  
### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[DelegatePermissions](delegatepermissions.md) <br/> |Contains the delegate permission level settings for a user. This element was introduced in Exchange 2007 SP1.  <br/> |
   
## Text value

The following table lists the text values that represent the permission levels.
  
**Permission level text values**

|**Permission level**|**Description**|
|:-----|:-----|
|None  <br/> |The delegate user has no access permissions to the Contacts folder.  <br/> |
|Reviewer  <br/> |The delegate user can read items in the Contacts folder.  <br/> |
|Author  <br/> |The delegate user can read and create items in the Contacts folder.  <br/> |
|Editor  <br/> |The delegate user can read, create, and modify items in the Contacts folder.  <br/> |
|Custom  <br/> |The delegate user has custom access permissions to the Contacts folder.  <br/> |
   
## Remarks

The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.
  
## Element information

| Element | Example |
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema Name  <br/> |Types schema  <br/> |
|Validation File  <br/> |Types.xsd  <br/> |
|Can be Empty  <br/> |False  <br/> |
   
## See also



[AddDelegate operation](adddelegate-operation.md)
  
[UpdateDelegate operation](updatedelegate-operation.md)


- [EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)


[Adding Delegates](https://msdn.microsoft.com/library/3a744150-66a3-4a13-9433-793603ba5038%28Office.15%29.aspx)

