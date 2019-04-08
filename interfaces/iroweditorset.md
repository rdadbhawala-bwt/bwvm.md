[bcvm](../README.md) > [IRowEditorSet](../interfaces/iroweditorset.md)

# Interface: IRowEditorSet

## Hierarchy

 [IRowCollection](irowcollection.md)<[IRowEditor](iroweditor.md)>

**↳ IRowEditorSet**

↳  [IRowEditorCollection](iroweditorcollection.md)

## Implemented by

* [RowEditorColl](../classes/roweditorcoll.md)
* [RowEditorSet](../classes/roweditorset.md)

## Index

### Methods

* [filter](iroweditorset.md#filter)
* [getCount](iroweditorset.md#getcount)
* [getRowById](iroweditorset.md#getrowbyid)
* [getRowByIndex](iroweditorset.md#getrowbyindex)
* [getRowByOffset](iroweditorset.md#getrowbyoffset)
* [getRows](iroweditorset.md#getrows)
* [isModified](iroweditorset.md#ismodified)

---

## Methods

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
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Defined in [model.row.ts:65](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L65)*

**Returns:** `boolean`

___

