[bcvm](../README.md) > [IRowCollection](../interfaces/irowcollection.md)

# Interface: IRowCollection

## Type parameters
#### R :  [IRow](irow.md)
## Hierarchy

**IRowCollection**

↳  [IRowDataCollection](irowdatacollection.md)

↳  [IRowEditorSet](iroweditorset.md)

## Implemented by

* [RowCollBase](../classes/rowcollbase.md)
* [RowDataColl](../classes/rowdatacoll.md)
* [RowEditorColl](../classes/roweditorcoll.md)
* [RowEditorSet](../classes/roweditorset.md)

## Index

### Methods

* [filter](irowcollection.md#filter)
* [getCount](irowcollection.md#getcount)
* [getRowById](irowcollection.md#getrowbyid)
* [getRowByIndex](irowcollection.md#getrowbyindex)
* [getRowByOffset](irowcollection.md#getrowbyoffset)
* [getRows](irowcollection.md#getrows)

---

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `R`[]

*Defined in [model.row.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L52)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `R`[]

___
<a id="getcount"></a>

###  getCount

▸ **getCount**(): `number`

*Defined in [model.row.ts:47](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L47)*

**Returns:** `number`

___
<a id="getrowbyid"></a>

###  getRowById

▸ **getRowById**(rowId: *`number`*): `R`

*Defined in [model.row.ts:45](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L45)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |

**Returns:** `R`

___
<a id="getrowbyindex"></a>

###  getRowByIndex

▸ **getRowByIndex**(index: *`number`*): `R`

*Defined in [model.row.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L49)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** `R`

___
<a id="getrowbyoffset"></a>

###  getRowByOffset

▸ **getRowByOffset**(rowId: *`number`*, offset: *`number`*): `R`

*Defined in [model.row.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L50)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |
| offset | `number` |

**Returns:** `R`

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): `R`[]

*Defined in [model.row.ts:46](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L46)*

**Returns:** `R`[]

___

