[bcvm](../README.md) > [ColumnEditorSet](../classes/columneditorset.md)

# Class: ColumnEditorSet

## Hierarchy

 [ColumnCollBase](columncollbase.md)<`m.IColumnEditor`>

**↳ ColumnEditorSet**

↳  [ColumnEditorColl](columneditorcoll.md)

## Implements

* [IColumnCollection](../interfaces/icolumncollection.md)<`m.IColumnEditor`>
* [IColumnEditorSet](../interfaces/icolumneditorset.md)

## Index

### Constructors

* [constructor](columneditorset.md#constructor)

### Properties

* [colArr](columneditorset.md#colarr)

### Methods

* [filter](columneditorset.md#filter)
* [getColumnById](columneditorset.md#getcolumnbyid)
* [getColumnByIndex](columneditorset.md#getcolumnbyindex)
* [getColumnByOffset](columneditorset.md#getcolumnbyoffset)
* [getColumns](columneditorset.md#getcolumns)
* [isModified](columneditorset.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new ColumnEditorSet**(pCols: *`m.IColumnEditor`[]*): [ColumnEditorSet](columneditorset.md)

*Overrides [ColumnCollBase](columncollbase.md).[constructor](columncollbase.md#constructor)*

*Defined in [editor.column.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L7)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCols | `m.IColumnEditor`[] |

**Returns:** [ColumnEditorSet](columneditorset.md)

___

## Properties

<a id="colarr"></a>

### `<Protected>` colArr

**● colArr**: *`m.IColumnEditor`[]* =  []

*Inherited from [ColumnCollBase](columncollbase.md).[colArr](columncollbase.md#colarr)*

*Defined in [model.column.ts:137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L137)*

___

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `m.IColumnEditor`[]

*Inherited from [ColumnCollBase](columncollbase.md).[filter](columncollbase.md#filter)*

*Defined in [model.column.ts:163](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L163)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `m.IColumnEditor`[]

___
<a id="getcolumnbyid"></a>

###  getColumnById

▸ **getColumnById**(columnId: *`number`*): `m.IColumnEditor`

*Implementation of [IColumnEditorSet](../interfaces/icolumneditorset.md).[getColumnById](../interfaces/icolumneditorset.md#getcolumnbyid)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumnById](columncollbase.md#getcolumnbyid)*

*Defined in [model.column.ts:143](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L143)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |

**Returns:** `m.IColumnEditor`

___
<a id="getcolumnbyindex"></a>

###  getColumnByIndex

▸ **getColumnByIndex**(index: *`number`*): `m.IColumnEditor`

*Implementation of [IColumnEditorSet](../interfaces/icolumneditorset.md).[getColumnByIndex](../interfaces/icolumneditorset.md#getcolumnbyindex)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumnByIndex](columncollbase.md#getcolumnbyindex)*

*Defined in [model.column.ts:149](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L149)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** `m.IColumnEditor`

___
<a id="getcolumnbyoffset"></a>

###  getColumnByOffset

▸ **getColumnByOffset**(columnId: *`number`*, offset: *`number`*): `m.IColumnEditor`

*Implementation of [IColumnEditorSet](../interfaces/icolumneditorset.md).[getColumnByOffset](../interfaces/icolumneditorset.md#getcolumnbyoffset)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumnByOffset](columncollbase.md#getcolumnbyoffset)*

*Defined in [model.column.ts:155](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L155)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |
| offset | `number` |

**Returns:** `m.IColumnEditor`

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): `m.IColumnEditor`[]

*Implementation of [IColumnEditorSet](../interfaces/icolumneditorset.md).[getColumns](../interfaces/icolumneditorset.md#getcolumns)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumns](columncollbase.md#getcolumns)*

*Defined in [model.column.ts:146](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L146)*

**Returns:** `m.IColumnEditor`[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IColumnEditorSet](../interfaces/icolumneditorset.md).[isModified](../interfaces/icolumneditorset.md#ismodified)*

*Defined in [editor.column.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L12)*

**Returns:** `boolean`

___

