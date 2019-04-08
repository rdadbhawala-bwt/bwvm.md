[bcvm](../README.md) > [ColumnEditorColl](../classes/columneditorcoll.md)

# Class: ColumnEditorColl

## Hierarchy

↳  [ColumnEditorSet](columneditorset.md)

**↳ ColumnEditorColl**

## Implements

* [IColumnCollection](../interfaces/icolumncollection.md)<`m.IColumnEditor`>
* [IColumnEditorSet](../interfaces/icolumneditorset.md)
* [IColumnEditorCollection](../interfaces/icolumneditorcollection.md)

## Index

### Constructors

* [constructor](columneditorcoll.md#constructor)

### Properties

* [colArr](columneditorcoll.md#colarr)

### Methods

* [deleteColumn](columneditorcoll.md#deletecolumn)
* [deletedColumns](columneditorcoll.md#deletedcolumns)
* [filter](columneditorcoll.md#filter)
* [getColumnById](columneditorcoll.md#getcolumnbyid)
* [getColumnByIndex](columneditorcoll.md#getcolumnbyindex)
* [getColumnByOffset](columneditorcoll.md#getcolumnbyoffset)
* [getColumns](columneditorcoll.md#getcolumns)
* [insertColumn](columneditorcoll.md#insertcolumn)
* [insertColumnAtEnd](columneditorcoll.md#insertcolumnatend)
* [insertColumnAtStart](columneditorcoll.md#insertcolumnatstart)
* [insertedColumns](columneditorcoll.md#insertedcolumns)
* [isModified](columneditorcoll.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new ColumnEditorColl**(pCols: *`m.IColumnData`[]*): [ColumnEditorColl](columneditorcoll.md)

*Overrides [ColumnEditorSet](columneditorset.md).[constructor](columneditorset.md#constructor)*

*Defined in [editor.column.ts:20](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L20)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCols | `m.IColumnData`[] |

**Returns:** [ColumnEditorColl](columneditorcoll.md)

___

## Properties

<a id="colarr"></a>

### `<Protected>` colArr

**● colArr**: *`m.IColumnEditor`[]* =  []

*Inherited from [ColumnCollBase](columncollbase.md).[colArr](columncollbase.md#colarr)*

*Defined in [model.column.ts:137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L137)*

___

## Methods

<a id="deletecolumn"></a>

###  deleteColumn

▸ **deleteColumn**(col: *`m.IColumnEditor`*): `void`

*Defined in [editor.column.ts:74](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L74)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | `m.IColumnEditor` |

**Returns:** `void`

___
<a id="deletedcolumns"></a>

###  deletedColumns

▸ **deletedColumns**(): `m.IColumnEditor`[]

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[deletedColumns](../interfaces/icolumneditorcollection.md#deletedcolumns)*

*Defined in [editor.column.ts:92](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L92)*

**Returns:** `m.IColumnEditor`[]

___
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

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[getColumnById](../interfaces/icolumneditorcollection.md#getcolumnbyid)*

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

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[getColumnByIndex](../interfaces/icolumneditorcollection.md#getcolumnbyindex)*

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

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[getColumnByOffset](../interfaces/icolumneditorcollection.md#getcolumnbyoffset)*

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

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[getColumns](../interfaces/icolumneditorcollection.md#getcolumns)*

*Overrides [ColumnCollBase](columncollbase.md).[getColumns](columncollbase.md#getcolumns)*

*Defined in [editor.column.ts:98](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L98)*

**Returns:** `m.IColumnEditor`[]

___
<a id="insertcolumn"></a>

###  insertColumn

▸ **insertColumn**(newColumnName: *`string`*, prevColumn: *`m.IColumnEditor`*): `m.IColumnEditor`

*Defined in [editor.column.ts:31](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L31)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |
| prevColumn | `m.IColumnEditor` |

**Returns:** `m.IColumnEditor`

___
<a id="insertcolumnatend"></a>

###  insertColumnAtEnd

▸ **insertColumnAtEnd**(newColumnName: *`string`*): `m.IColumnEditor`

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[insertColumnAtEnd](../interfaces/icolumneditorcollection.md#insertcolumnatend)*

*Defined in [editor.column.ts:28](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L28)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** `m.IColumnEditor`

___
<a id="insertcolumnatstart"></a>

###  insertColumnAtStart

▸ **insertColumnAtStart**(newColumnName: *`string`*): `m.IColumnEditor`

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[insertColumnAtStart](../interfaces/icolumneditorcollection.md#insertcolumnatstart)*

*Defined in [editor.column.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L25)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** `m.IColumnEditor`

___
<a id="insertedcolumns"></a>

###  insertedColumns

▸ **insertedColumns**(): `m.IColumnEditor`[]

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[insertedColumns](../interfaces/icolumneditorcollection.md#insertedcolumns)*

*Defined in [editor.column.ts:95](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L95)*

**Returns:** `m.IColumnEditor`[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IColumnEditorCollection](../interfaces/icolumneditorcollection.md).[isModified](../interfaces/icolumneditorcollection.md#ismodified)*

*Inherited from [ColumnEditorSet](columneditorset.md).[isModified](columneditorset.md#ismodified)*

*Defined in [editor.column.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L12)*

**Returns:** `boolean`

___

