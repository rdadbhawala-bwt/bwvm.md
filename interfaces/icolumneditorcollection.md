[bcvm](../README.md) > [IColumnEditorCollection](../interfaces/icolumneditorcollection.md)

# Interface: IColumnEditorCollection

## Hierarchy

↳  [IColumnEditorSet](icolumneditorset.md)

**↳ IColumnEditorCollection**

## Implemented by

* [ColumnEditorColl](../classes/columneditorcoll.md)

## Index

### Methods

* [deleteColumn](icolumneditorcollection.md#deletecolumn)
* [deletedColumns](icolumneditorcollection.md#deletedcolumns)
* [filter](icolumneditorcollection.md#filter)
* [getColumnById](icolumneditorcollection.md#getcolumnbyid)
* [getColumnByIndex](icolumneditorcollection.md#getcolumnbyindex)
* [getColumnByOffset](icolumneditorcollection.md#getcolumnbyoffset)
* [getColumns](icolumneditorcollection.md#getcolumns)
* [insertColumn](icolumneditorcollection.md#insertcolumn)
* [insertColumnAtEnd](icolumneditorcollection.md#insertcolumnatend)
* [insertColumnAtStart](icolumneditorcollection.md#insertcolumnatstart)
* [insertedColumns](icolumneditorcollection.md#insertedcolumns)
* [isModified](icolumneditorcollection.md#ismodified)

---

## Methods

<a id="deletecolumn"></a>

###  deleteColumn

▸ **deleteColumn**(col: *[IColumnEditor](icolumneditor.md)*): `any`

*Defined in [model.column.ts:130](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L130)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | [IColumnEditor](icolumneditor.md) |

**Returns:** `any`

___
<a id="deletedcolumns"></a>

###  deletedColumns

▸ **deletedColumns**(): [IColumnEditor](icolumneditor.md)[]

*Defined in [model.column.ts:132](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L132)*

**Returns:** [IColumnEditor](icolumneditor.md)[]

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [IColumnEditor](icolumneditor.md)[]

*Inherited from [IColumnCollection](icolumncollection.md).[filter](icolumncollection.md#filter)*

*Defined in [model.column.ts:110](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L110)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [IColumnEditor](icolumneditor.md)[]

___
<a id="getcolumnbyid"></a>

###  getColumnById

▸ **getColumnById**(columnId: *`number`*): [IColumnEditor](icolumneditor.md)

*Inherited from [IColumnCollection](icolumncollection.md).[getColumnById](icolumncollection.md#getcolumnbyid)*

*Defined in [model.column.ts:104](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L104)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="getcolumnbyindex"></a>

###  getColumnByIndex

▸ **getColumnByIndex**(index: *`number`*): [IColumnEditor](icolumneditor.md)

*Inherited from [IColumnCollection](icolumncollection.md).[getColumnByIndex](icolumncollection.md#getcolumnbyindex)*

*Defined in [model.column.ts:107](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L107)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="getcolumnbyoffset"></a>

###  getColumnByOffset

▸ **getColumnByOffset**(columnId: *`number`*, offset: *`number`*): [IColumnEditor](icolumneditor.md)

*Inherited from [IColumnCollection](icolumncollection.md).[getColumnByOffset](icolumncollection.md#getcolumnbyoffset)*

*Defined in [model.column.ts:108](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L108)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |
| offset | `number` |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): [IColumnEditor](icolumneditor.md)[]

*Inherited from [IColumnCollection](icolumncollection.md).[getColumns](icolumncollection.md#getcolumns)*

*Defined in [model.column.ts:105](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L105)*

**Returns:** [IColumnEditor](icolumneditor.md)[]

___
<a id="insertcolumn"></a>

###  insertColumn

▸ **insertColumn**(newColumnName: *`string`*, prevColumn: *[IColumnEditor](icolumneditor.md)*): [IColumnEditor](icolumneditor.md)

*Defined in [model.column.ts:129](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L129)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |
| prevColumn | [IColumnEditor](icolumneditor.md) |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="insertcolumnatend"></a>

###  insertColumnAtEnd

▸ **insertColumnAtEnd**(newColumnName: *`string`*): [IColumnEditor](icolumneditor.md)

*Defined in [model.column.ts:128](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L128)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="insertcolumnatstart"></a>

###  insertColumnAtStart

▸ **insertColumnAtStart**(newColumnName: *`string`*): [IColumnEditor](icolumneditor.md)

*Defined in [model.column.ts:127](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L127)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="insertedcolumns"></a>

###  insertedColumns

▸ **insertedColumns**(): [IColumnEditor](icolumneditor.md)[]

*Defined in [model.column.ts:133](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L133)*

**Returns:** [IColumnEditor](icolumneditor.md)[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Inherited from [IColumnEditorSet](icolumneditorset.md).[isModified](icolumneditorset.md#ismodified)*

*Defined in [model.column.ts:121](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L121)*

**Returns:** `boolean`

___

