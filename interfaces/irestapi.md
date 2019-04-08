[bcvm](../README.md) > [IRestApi](../interfaces/irestapi.md)

# Interface: IRestApi

## Hierarchy

**IRestApi**

## Implemented by

* [RestApi](../classes/restapi.md)

## Index

### Methods

* [retrieveGridAllData](irestapi.md#retrievegridalldata)
* [submitCreate](irestapi.md#submitcreate)
* [submitUpdate](irestapi.md#submitupdate)

---

## Methods

<a id="retrievegridalldata"></a>

###  retrieveGridAllData

▸ **retrieveGridAllData**(gridId: *`number`*, gad: *[IGridAllData](igridalldata.md)*): `Promise`<[IGridAllData](igridalldata.md)>

*Defined in [model.ts:69](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L69)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |
| gad | [IGridAllData](igridalldata.md) |

**Returns:** `Promise`<[IGridAllData](igridalldata.md)>

___
<a id="submitcreate"></a>

###  submitCreate

▸ **submitCreate**(grid: *[Grid](grid.md)*): `Promise`<[IGridAllData](igridalldata.md)>

*Defined in [model.ts:71](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L71)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| grid | [Grid](grid.md) |

**Returns:** `Promise`<[IGridAllData](igridalldata.md)>

___
<a id="submitupdate"></a>

###  submitUpdate

▸ **submitUpdate**(editor: *[IGridTxEditor](igridtxeditor.md)*, gridAllData: *[IGridAllData](igridalldata.md)*, submitPrefs: *[ISubmitPrefs](isubmitprefs.md)*): `Promise`<`void`>

*Defined in [model.ts:70](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L70)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | [IGridTxEditor](igridtxeditor.md) |
| gridAllData | [IGridAllData](igridalldata.md) |
| submitPrefs | [ISubmitPrefs](isubmitprefs.md) |

**Returns:** `Promise`<`void`>

___

