---
title: "Presenters"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
ms.assetid: 01057872-4f1a-4246-86ba-73d10ef854a0
description: "The Presenters element specifies the presenters for an online meeting."
---

# Presenters

The **Presenters** element specifies the presenters for an online meeting. 
  
```XML
<Presenters> Disabled | Internal | Everyone </Presenters>
```

 **PresentersType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

None.
  
### Parent elements

[OnlineMeetingSettings](onlinemeetingsettings.md)
  
## Text value

The text value of **Presenters** element is the type of users that can be a presenter for an online meeting. The text values for the **Presenters** element are described in the following table. 
  
**Presenters element text values**

|**Value**|**Description**|
|:-----|:-----|
|Disabled  <br/> |Presenters are disabled.  <br/> |
|Internal  <br/> |Only internal participants can be presenters.  <br/> |
|Everyone  <br/> |Any participant can be a presenter.  <br/> |
   
## Remarks

This element was introduced in Exchange Server 2013.
  
The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema name  <br/> |Types schema  <br/> |
|Validation file  <br/> |Types.xsd  <br/> |
|Can be empty  <br/> ||
   

