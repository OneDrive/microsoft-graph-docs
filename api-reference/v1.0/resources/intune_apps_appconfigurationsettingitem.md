# appConfigurationSettingItem resource type

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Contains properties for App configuration setting item.
## Properties
|Property|Type|Description|
|:---|:---|:---|
|appConfigKey|String|app configuration key.|
|appConfigKeyType|mdmAppConfigKeyType|app configuration key type. Possible values are: `stringType`, `integerType`, `realType`, `booleanType`, `tokenType`.|
|appConfigKeyValue|String|app configuration key value.|

### mdmAppConfigKeyType values

| Value
|:-------------------------
| stringType
| integerType
| realType
| booleanType
| tokenType


## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.appConfigurationSettingItem"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.appConfigurationSettingItem",
  "appConfigKey": "String",
  "appConfigKeyType": "String",
  "appConfigKeyValue": "String"
}
```



