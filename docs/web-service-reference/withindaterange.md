---
title: "WithinDateRange"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- WithinDateRange
api_type:
- schema
ms.assetid: 226aeb15-016f-45ca-992a-c137ba09ca08
description: "The WithinDateRange element specifies the date range within which incoming messages have to have been received in order for the condition or exception to apply."
---

# WithinDateRange

The **WithinDateRange** element specifies the date range within which incoming messages have to have been received in order for the condition or exception to apply. 
  
```XML
<WithinDateRange>
     <StartDateTime/>
     <EndDateTime/>
</WithinDateRange>
```

 **RulePredicateDateRangeType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

|**Element**|**Description**|
|:-----|:-----|
|[StartDateTime](startdatetime.md) <br/> |Specifies the rule time period and indicates that the rule condition is met after this value.  <br/> |
|[EndDateTime](enddatetime.md) <br/> |Specifies the rule time period and indicates that the rule condition is met before this value.  <br/> |
   
### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[Conditions](conditions.md) <br/> |Represents the conditions that, when fulfilled, will trigger the rule actions for a rule.  <br/> |
|[Exceptions](exceptions.md) <br/> |Represents all the available rule exception conditions for an Inbox rule.  <br/> |
   
## Text value

None.
  
## Remarks

The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Schema Name  <br/> |Messages schema  <br/> |
|Validation File  <br/> |Messages.xsd  <br/> |
|Can be Empty  <br/> |True  <br/> |
   
## See also



- [EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)

