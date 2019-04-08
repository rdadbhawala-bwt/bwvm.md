[bcvm](../README.md) > [RowEditorSet](../classes/roweditorset.md)

# Class: RowEditorSet

## Hierarchy

 [RowCollBase](rowcollbase.md)<`m.IRowEditor`>

**↳ RowEditorSet**

↳  [RowEditorColl](roweditorcoll.md)

## Implements

* [IRowCollection](../interfaces/irowcollection.md)<`m.IRowEditor`>
* [IRowEditorSet](../interfaces/iroweditorset.md)

## Index

### Constructors

* [constructor](roweditorset.md#constructor)

### Properties

* [rowArr](roweditorset.md#rowarr)

### Methods

* [filter](roweditorset.md#filter)
* [getCount](roweditorset.md#getcount)
* [getRowById](roweditorset.md#getrowbyid)
* [getRowByIndex](roweditorset.md#getrowbyindex)
* [getRowByOffset](roweditorset.md#getrowbyoffset)
* [getRows](roweditorset.md#getrows)
* [isModified](roweditorset.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RowEditorSet**(pRows: *`m.IRowEditor`[]*): [RowEditorSet](roweditorset.md)

*Overrides [RowCollBase](rowcollbase.md).[constructor](rowcollbase.md#constructor)*

*Defined in [editor.row.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L7)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pRows | `m.IRowEditor`[] |

**Returns:** [RowEditorSet](roweditorset.md)

___

## Properties

<a id="rowarr"></a>

### `<Protected>` rowArr

**● rowArr**: *`m.IRowEditor`[]* =  []

*Inherited from [RowCollBase](rowcollbase.md).[rowArr](rowcollbase.md#rowarr)*

*Defined in [model.row.ts:83](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L83)*

___

## Methods

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

*Implementation of [IRowEditorSet](../interfaces/iroweditorset.md).[getCount](../interfaces/iroweditorset.md#getcount)*

*Inherited from [RowCollBase](rowcollbase.md).[getCount](rowcollbase.md#getcount)*

*Defined in [model.row.ts:96](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L96)*

**Returns:** `number`

___
<a id="getrowbyid"></a>

###  getRowById

▸ **getRowById**(rowId: *`number`*): `m.IRowEditor`

*Implementation of [IRowEditorSet](../interfaces/iroweditorset.md).[getRowById](../interfaces/iroweditorset.md#getrowbyid)*

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

*Implementation of [IRowEditorSet](../interfaces/iroweditorset.md).[getRowByIndex](../interfaces/iroweditorset.md#getrowbyindex)*

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

*Implementation of [IRowEditorSet](../interfaces/iroweditorset.md).[getRowByOffset](../interfaces/iroweditorset.md#getrowbyoffset)*

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

*Implementation of [IRowEditorSet](../interfaces/iroweditorset.md).[getRows](../interfaces/iroweditorset.md#getrows)*

*Inherited from [RowCollBase](rowcollbase.md).[getRows](rowcollbase.md#getrows)*

*Defined in [model.row.ts:93](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L93)*

**Returns:** `m.IRowEditor`[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IRowEditorSet](../interfaces/iroweditorset.md).[isModified](../interfaces/iroweditorset.md#ismodified)*

*Defined in [editor.row.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L12)*

**Returns:** `boolean`

___

