---
title: "deviceRegistrationPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceRegistrationPolicy resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List deviceRegistrationPolicies](../api/deviceregistrationpolicy-list.md)|[deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) collection|Get a list of the [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) objects and their properties.|
|[Create deviceRegistrationPolicy](../api/deviceregistrationpolicy-create.md)|[deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md)|Create a new [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) object.|
|[Get deviceRegistrationPolicy](../api/deviceregistrationpolicy-get.md)|[deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md)|Read the properties and relationships of a [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) object.|
|[Update deviceRegistrationPolicy](../api/deviceregistrationpolicy-update.md)|[deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md)|Update the properties of a [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) object.|
|[Delete deviceRegistrationPolicy](../api/deviceregistrationpolicy-delete.md)|None|Deletes a [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|azureADJoin|[azureAdJoinPolicy](../resources/azureadjoinpolicy.md)|**TODO: Add Description**|
|azureADRegistration|[azureADRegistrationPolicy](../resources/azureadregistrationpolicy.md)|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|multiFactorAuthConfiguration|multiFactorAuthConfiguration|**TODO: Add Description**. Possible values are: `notRequired`, `required`, `unknownFutureValue`.|
|userDeviceQuota|Int32|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceRegistrationPolicy",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceRegistrationPolicy",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "userDeviceQuota": "Integer",
  "multiFactorAuthConfiguration": "String",
  "azureADRegistration": {
    "@odata.type": "microsoft.graph.azureADRegistrationPolicy"
  },
  "azureADJoin": {
    "@odata.type": "microsoft.graph.azureAdJoinPolicy"
  }
}
```
