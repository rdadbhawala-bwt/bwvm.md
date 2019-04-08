[bcvm](../README.md) > [RestApi](../classes/restapi.md)

# Class: RestApi

## Hierarchy

 [BaseApi](baseapi.md)

**↳ RestApi**

## Implements

* [IRestApi](../interfaces/irestapi.md)

## Index

### Constructors

* [constructor](restapi.md#constructor)

### Properties

* [creds](restapi.md#creds)

### Methods

* [createFetchConfig](restapi.md#createfetchconfig)
* [createFetchOptions](restapi.md#createfetchoptions)
* [retrieveGridAllData](restapi.md#retrievegridalldata)
* [submitCreate](restapi.md#submitcreate)
* [submitUpdate](restapi.md#submitupdate)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RestApi**(pCred: *`m.Credentials`*): [RestApi](restapi.md)

*Overrides [BaseApi](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [restApi.ts:47](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L47)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCred | `m.Credentials` |

**Returns:** [RestApi](restapi.md)

___

## Properties

<a id="creds"></a>

###  creds

**● creds**: *`m.Credentials`*

*Inherited from [BaseApi](baseapi.md).[creds](baseapi.md#creds)*

*Defined in [restApi.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L25)*

___

## Methods

<a id="createfetchconfig"></a>

###  createFetchConfig

▸ **createFetchConfig**(): `any`

*Inherited from [BaseApi](baseapi.md).[createFetchConfig](baseapi.md#createfetchconfig)*

*Defined in [restApi.ts:31](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L31)*

**Returns:** `any`

___
<a id="createfetchoptions"></a>

###  createFetchOptions

▸ **createFetchOptions**(): `any`

*Inherited from [BaseApi](baseapi.md).[createFetchOptions](baseapi.md#createfetchoptions)*

*Defined in [restApi.ts:37](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L37)*

**Returns:** `any`

___
<a id="retrievegridalldata"></a>

###  retrieveGridAllData

▸ **retrieveGridAllData**(gridId: *`number`*, gad: *`m.IGridAllData`*): `Promise`<`m.IGridAllData`>

*Defined in [restApi.ts:53](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L53)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |
| gad | `m.IGridAllData` |

**Returns:** `Promise`<`m.IGridAllData`>

___
<a id="submitcreate"></a>

###  submitCreate

▸ **submitCreate**(grid: *`m.Grid`*): `Promise`<`m.IGridAllData`>

*Defined in [restApi.ts:90](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L90)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| grid | `m.Grid` |

**Returns:** `Promise`<`m.IGridAllData`>

___
<a id="submitupdate"></a>

###  submitUpdate

▸ **submitUpdate**(editor: *`m.IGridTxEditor`*, gridAllData: *`m.IGridAllData`*, submitPrefs: *[ISubmitPrefs](../interfaces/isubmitprefs.md)*): `Promise`<`never`>

*Defined in [restApi.ts:69](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L69)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | `m.IGridTxEditor` |
| gridAllData | `m.IGridAllData` |
| submitPrefs | [ISubmitPrefs](../interfaces/isubmitprefs.md) |

**Returns:** `Promise`<`never`>

___

