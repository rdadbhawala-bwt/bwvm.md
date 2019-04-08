[bcvm](../README.md) > [RowEditorColl](../classes/roweditorcoll.md)

# Class: RowEditorColl

## Hierarchy

↳  [RowEditorSet](roweditorset.md)

**↳ RowEditorColl**

## Implements

* [IRowCollection](../interfaces/irowcollection.md)<`m.IRowEditor`>
* [IRowEditorSet](../interfaces/iroweditorset.md)
* [IRowEditorCollection](../interfaces/iroweditorcollection.md)

## Index

### Constructors

* [constructor](roweditorcoll.md#constructor)

### Properties

* [rowArr](roweditorcoll.md#rowarr)

### Methods

* [deleteRow](roweditorcoll.md#deleterow)
* [deletedRows](roweditorcoll.md#deletedrows)
* [filter](roweditorcoll.md#filter)
* [getCount](roweditorcoll.md#getcount)
* [getRowById](roweditorcoll.md#getrowbyid)
* [getRowByIndex](roweditorcoll.md#getrowbyindex)
* [getRowByOffset](roweditorcoll.md#getrowbyoffset)
* [getRows](roweditorcoll.md#getrows)
* [insertRow](roweditorcoll.md#insertrow)
* [insertRowAtEnd](roweditorcoll.md#insertrowatend)
* [insertRowAtStart](roweditorcoll.md#insertrowatstart)
* [insertedRows](roweditorcoll.md#insertedrows)
* [isModified](roweditorcoll.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RowEditorColl**(pRows: *`m.IRowData`[]*): [RowEditorColl](roweditorcoll.md)

*Overrides [RowEditorSet](roweditorset.md).[constructor](roweditorset.md#constructor)*

*Defined in [editor.row.ts:20](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L20)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pRows | `m.IRowData`[] |

**Returns:** [RowEditorColl](roweditorcoll.md)

___

## Properties

<a id="rowarr"></a>

### `<Protected>` rowArr

**● rowArr**: *`m.IRowEditor`[]* =  []

*Inherited from [RowCollBase](rowcollbase.md).[rowArr](rowcollbase.md#rowarr)*

*Defined in [model.row.ts:83](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L83)*

___

## Methods

<a id="deleterow"></a>

###  deleteRow

▸ **deleteRow**(row: *`m.IRowEditor`*): `void`

*Defined in [editor.row.ts:74](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L74)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | `m.IRowEditor` |

**Returns:** `void`

___
<a id="deletedrows"></a>

###  deletedRows

▸ **deletedRows**(): `m.IRowEditor`[]

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[deletedRows](../interfaces/iroweditorcollection.md#deletedrows)*

*Defined in [editor.row.ts:92](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L92)*

**Returns:** `m.IRowEditor`[]

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `m.IRowEditor`[]

*Inherited from [RowCollBase](rowcollbase.md).[filter](rowcollbase.md#filter)*

*Defined in [model.row.ts:115](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L115)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `m.IRowEditor`[]

___
<a id="getcount"></a>

###  getCount

▸ **getCount**(): `number`

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[getCount](../interfaces/iroweditorcollection.md#getcount)*

*Inherited from [RowCollBase](rowcollbase.md).[getCount](rowcollbase.md#getcount)*

*Defined in [model.row.ts:96](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L96)*

**Returns:** `number`

___
<a id="getrowbyid"></a>

###  getRowById

▸ **getRowById**(rowId: *`number`*): `m.IRowEditor`

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[getRowById](../interfaces/iroweditorcollection.md#getrowbyid)*

*Inherited from [RowCollBase](rowcollbase.md).[getRowById](rowcollbase.md#getrowbyid)*

*Defined in [model.row.ts:90](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L90)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |

**Returns:** `m.IRowEditor`

___
<a id="getrowbyindex"></a>

###  getRowByIndex

▸ **getRowByIndex**(index: *`number`*): `m.IRowEditor`

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[getRowByIndex](../interfaces/iroweditorcollection.md#getrowbyindex)*

*Inherited from [RowCollBase](rowcollbase.md).[getRowByIndex](rowcollbase.md#getrowbyindex)*

*Defined in [model.row.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** `m.IRowEditor`

___
<a id="getrowbyoffset"></a>

###  getRowByOffset

▸ **getRowByOffset**(rowId: *`number`*, offset: *`number`*): `m.IRowEditor`

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[getRowByOffset](../interfaces/iroweditorcollection.md#getrowbyoffset)*

*Inherited from [RowCollBase](rowcollbase.md).[getRowByOffset](rowcollbase.md#getrowbyoffset)*

*Defined in [model.row.ts:106](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L106)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |
| offset | `number` |

**Returns:** `m.IRowEditor`

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): `m.IRowEditor`[]

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[getRows](../interfaces/iroweditorcollection.md#getrows)*

*Overrides [RowCollBase](rowcollbase.md).[getRows](rowcollbase.md#getrows)*

*Defined in [editor.row.ts:98](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L98)*

**Returns:** `m.IRowEditor`[]

___
<a id="insertrow"></a>

###  insertRow

▸ **insertRow**(rowName: *`string`*, prevRow: *`m.IRowEditor`*): `m.IRowEditor`

*Defined in [editor.row.ts:30](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L30)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |
| prevRow | `m.IRowEditor` |

**Returns:** `m.IRowEditor`

___
<a id="insertrowatend"></a>

###  insertRowAtEnd

▸ **insertRowAtEnd**(rowName: *`string`*): `m.IRowEditor`

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[insertRowAtEnd](../interfaces/iroweditorcollection.md#insertrowatend)*

*Defined in [editor.row.ts:27](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L27)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** `m.IRowEditor`

___
<a id="insertrowatstart"></a>

###  insertRowAtStart

▸ **insertRowAtStart**(rowName: *`string`*): `m.IRowEditor`

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[insertRowAtStart](../interfaces/iroweditorcollection.md#insertrowatstart)*

*Defined in [editor.row.ts:24](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L24)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** `m.IRowEditor`

___
<a id="insertedrows"></a>

###  insertedRows

▸ **insertedRows**(): `m.IRowEditor`[]

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[insertedRows](../interfaces/iroweditorcollection.md#insertedrows)*

*Defined in [editor.row.ts:95](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L95)*

**Returns:** `m.IRowEditor`[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IRowEditorCollection](../interfaces/iroweditorcollection.md).[isModified](../interfaces/iroweditorcollection.md#ismodified)*

*Inherited from [RowEditorSet](roweditorset.md).[isModified](roweditorset.md#ismodified)*

*Defined in [editor.row.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L12)*

**Returns:** `boolean`

___

