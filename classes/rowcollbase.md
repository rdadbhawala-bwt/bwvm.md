[bcvm](../README.md) > [RowCollBase](../classes/rowcollbase.md)

# Class: RowCollBase

## Type parameters
#### R :  [IRow](../interfaces/irow.md)
## Hierarchy

**RowCollBase**

↳  [RowDataColl](rowdatacoll.md)

↳  [RowEditorSet](roweditorset.md)

## Implements

* [IRowCollection](../interfaces/irowcollection.md)<`R`>

## Index

### Constructors

* [constructor](rowcollbase.md#constructor)

### Properties

* [rowArr](rowcollbase.md#rowarr)

### Methods

* [filter](rowcollbase.md#filter)
* [getCount](rowcollbase.md#getcount)
* [getRowById](rowcollbase.md#getrowbyid)
* [getRowByIndex](rowcollbase.md#getrowbyindex)
* [getRowByOffset](rowcollbase.md#getrowbyoffset)
* [getRows](rowcollbase.md#getrows)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RowCollBase**(pRows: *`R`[]*): [RowCollBase](rowcollbase.md)

*Defined in [model.row.ts:83](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L83)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pRows | `R`[] |

**Returns:** [RowCollBase](rowcollbase.md)

___

## Properties

<a id="rowarr"></a>

### `<Protected>` rowArr

**● rowArr**: *`R`[]* =  []

*Defined in [model.row.ts:83](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L83)*

___

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `R`[]

*Defined in [model.row.ts:115](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L115)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `R`[]

___
<a id="getcount"></a>

###  getCount

▸ **getCount**(): `number`

*Implementation of [IRowCollection](../interfaces/irowcollection.md).[getCount](../interfaces/irowcollection.md#getcount)*

*Defined in [model.row.ts:96](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L96)*

**Returns:** `number`

___
<a id="getrowbyid"></a>

###  getRowById

▸ **getRowById**(rowId: *`number`*): `R`

*Implementation of [IRowCollection](../interfaces/irowcollection.md).[getRowById](../interfaces/irowcollection.md#getrowbyid)*

*Defined in [model.row.ts:90](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L90)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |

**Returns:** `R`

___
<a id="getrowbyindex"></a>

###  getRowByIndex

▸ **getRowByIndex**(index: *`number`*): `R`

*Implementation of [IRowCollection](../interfaces/irowcollection.md).[getRowByIndex](../interfaces/irowcollection.md#getrowbyindex)*

*Defined in [model.row.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** `R`

___
<a id="getrowbyoffset"></a>

###  getRowByOffset

▸ **getRowByOffset**(rowId: *`number`*, offset: *`number`*): `R`

*Implementation of [IRowCollection](../interfaces/irowcollection.md).[getRowByOffset](../interfaces/irowcollection.md#getrowbyoffset)*

*Defined in [model.row.ts:106](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L106)*

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

*Implementation of [IRowCollection](../interfaces/irowcollection.md).[getRows](../interfaces/irowcollection.md#getrows)*

*Defined in [model.row.ts:93](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L93)*

**Returns:** `R`[]

___

