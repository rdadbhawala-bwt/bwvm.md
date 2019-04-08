[bcvm](../README.md) > [IColumnEditorSet](../interfaces/icolumneditorset.md)

# Interface: IColumnEditorSet

## Hierarchy

 [IColumnCollection](icolumncollection.md)<[IColumnEditor](icolumneditor.md)>

**↳ IColumnEditorSet**

↳  [IColumnEditorCollection](icolumneditorcollection.md)

## Implemented by

* [ColumnEditorColl](../classes/columneditorcoll.md)
* [ColumnEditorSet](../classes/columneditorset.md)

## Index

### Methods

* [filter](icolumneditorset.md#filter)
* [getColumnById](icolumneditorset.md#getcolumnbyid)
* [getColumnByIndex](icolumneditorset.md#getcolumnbyindex)
* [getColumnByOffset](icolumneditorset.md#getcolumnbyoffset)
* [getColumns](icolumneditorset.md#getcolumns)
* [isModified](icolumneditorset.md#ismodified)

---

## Methods

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
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Defined in [model.column.ts:121](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L121)*

**Returns:** `boolean`

___

