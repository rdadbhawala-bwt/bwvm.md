[bcvm](../README.md) > [IRowEditorCollection](../interfaces/iroweditorcollection.md)

# Interface: IRowEditorCollection

## Hierarchy

↳  [IRowEditorSet](iroweditorset.md)

**↳ IRowEditorCollection**

## Implemented by

* [RowEditorColl](../classes/roweditorcoll.md)

## Index

### Methods

* [deleteRow](iroweditorcollection.md#deleterow)
* [deletedRows](iroweditorcollection.md#deletedrows)
* [filter](iroweditorcollection.md#filter)
* [getCount](iroweditorcollection.md#getcount)
* [getRowById](iroweditorcollection.md#getrowbyid)
* [getRowByIndex](iroweditorcollection.md#getrowbyindex)
* [getRowByOffset](iroweditorcollection.md#getrowbyoffset)
* [getRows](iroweditorcollection.md#getrows)
* [insertRow](iroweditorcollection.md#insertrow)
* [insertRowAtEnd](iroweditorcollection.md#insertrowatend)
* [insertRowAtStart](iroweditorcollection.md#insertrowatstart)
* [insertedRows](iroweditorcollection.md#insertedrows)
* [isModified](iroweditorcollection.md#ismodified)

---

## Methods

<a id="deleterow"></a>

###  deleteRow

▸ **deleteRow**(row: *[IRowEditor](iroweditor.md)*): `any`

*Defined in [model.row.ts:75](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L75)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | [IRowEditor](iroweditor.md) |

**Returns:** `any`

___
<a id="deletedrows"></a>

###  deletedRows

▸ **deletedRows**(): [IRowEditor](iroweditor.md)[]

*Defined in [model.row.ts:77](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L77)*

**Returns:** [IRowEditor](iroweditor.md)[]

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [IRowEditor](iroweditor.md)[]

*Inherited from [IRowCollection](irowcollection.md).[filter](irowcollection.md#filter)*

*Defined in [model.row.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L52)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [IRowEditor](iroweditor.md)[]

___
<a id="getcount"></a>

###  getCount

▸ **getCount**(): `number`

*Inherited from [IRowCollection](irowcollection.md).[getCount](irowcollection.md#getcount)*

*Defined in [model.row.ts:47](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L47)*

**Returns:** `number`

___
<a id="getrowbyid"></a>

###  getRowById

▸ **getRowById**(rowId: *`number`*): [IRowEditor](iroweditor.md)

*Inherited from [IRowCollection](irowcollection.md).[getRowById](irowcollection.md#getrowbyid)*

*Defined in [model.row.ts:45](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L45)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="getrowbyindex"></a>

###  getRowByIndex

▸ **getRowByIndex**(index: *`number`*): [IRowEditor](iroweditor.md)

*Inherited from [IRowCollection](irowcollection.md).[getRowByIndex](irowcollection.md#getrowbyindex)*

*Defined in [model.row.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L49)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="getrowbyoffset"></a>

###  getRowByOffset

▸ **getRowByOffset**(rowId: *`number`*, offset: *`number`*): [IRowEditor](iroweditor.md)

*Inherited from [IRowCollection](irowcollection.md).[getRowByOffset](irowcollection.md#getrowbyoffset)*

*Defined in [model.row.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L50)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |
| offset | `number` |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): [IRowEditor](iroweditor.md)[]

*Inherited from [IRowCollection](irowcollection.md).[getRows](irowcollection.md#getrows)*

*Defined in [model.row.ts:46](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L46)*

**Returns:** [IRowEditor](iroweditor.md)[]

___
<a id="insertrow"></a>

###  insertRow

▸ **insertRow**(rowName: *`string`*, prevRow: *[IRowEditor](iroweditor.md)*): [IRowEditor](iroweditor.md)

*Defined in [model.row.ts:73](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L73)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |
| prevRow | [IRowEditor](iroweditor.md) |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="insertrowatend"></a>

###  insertRowAtEnd

▸ **insertRowAtEnd**(rowName: *`string`*): [IRowEditor](iroweditor.md)

*Defined in [model.row.ts:72](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L72)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="insertrowatstart"></a>

###  insertRowAtStart

▸ **insertRowAtStart**(rowName: *`string`*): [IRowEditor](iroweditor.md)

*Defined in [model.row.ts:71](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L71)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="insertedrows"></a>

###  insertedRows

▸ **insertedRows**(): [IRowEditor](iroweditor.md)[]

*Defined in [model.row.ts:78](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L78)*

**Returns:** [IRowEditor](iroweditor.md)[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Inherited from [IRowEditorSet](iroweditorset.md).[isModified](iroweditorset.md#ismodified)*

*Defined in [model.row.ts:65](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L65)*

**Returns:** `boolean`

___

