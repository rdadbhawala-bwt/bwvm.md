[bcvm](../README.md) > [RowDataColl](../classes/rowdatacoll.md)

# Class: RowDataColl

## Hierarchy

 [RowCollBase](rowcollbase.md)<[IRowData](../interfaces/irowdata.md)>

**↳ RowDataColl**

## Implements

* [IRowCollection](../interfaces/irowcollection.md)<[IRowData](../interfaces/irowdata.md)>
* [IRowDataCollection](../interfaces/irowdatacollection.md)

## Index

### Constructors

* [constructor](rowdatacoll.md#constructor)

### Properties

* [rowArr](rowdatacoll.md#rowarr)

### Methods

* [filter](rowdatacoll.md#filter)
* [getCount](rowdatacoll.md#getcount)
* [getRowById](rowdatacoll.md#getrowbyid)
* [getRowByIndex](rowdatacoll.md#getrowbyindex)
* [getRowByOffset](rowdatacoll.md#getrowbyoffset)
* [getRows](rowdatacoll.md#getrows)
* [getRowsByTxId](rowdatacoll.md#getrowsbytxid)
* [merge](rowdatacoll.md#merge)
* [sortFn](rowdatacoll.md#sortfn)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RowDataColl**(pRows: *[IRowData](../interfaces/irowdata.md)[]*): [RowDataColl](rowdatacoll.md)

*Inherited from [RowCollBase](rowcollbase.md).[constructor](rowcollbase.md#constructor)*

*Defined in [model.row.ts:83](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L83)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pRows | [IRowData](../interfaces/irowdata.md)[] |

**Returns:** [RowDataColl](rowdatacoll.md)

___

## Properties

<a id="rowarr"></a>

### `<Protected>` rowArr

**● rowArr**: *[IRowData](../interfaces/irowdata.md)[]* =  []

*Inherited from [RowCollBase](rowcollbase.md).[rowArr](rowcollbase.md#rowarr)*

*Defined in [model.row.ts:83](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L83)*

___

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [IRowData](../interfaces/irowdata.md)[]

*Inherited from [RowCollBase](rowcollbase.md).[filter](rowcollbase.md#filter)*

*Defined in [model.row.ts:115](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L115)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [IRowData](../interfaces/irowdata.md)[]

___
<a id="getcount"></a>

###  getCount

▸ **getCount**(): `number`

*Implementation of [IRowDataCollection](../interfaces/irowdatacollection.md).[getCount](../interfaces/irowdatacollection.md#getcount)*

*Inherited from [RowCollBase](rowcollbase.md).[getCount](rowcollbase.md#getcount)*

*Defined in [model.row.ts:96](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L96)*

**Returns:** `number`

___
<a id="getrowbyid"></a>

###  getRowById

▸ **getRowById**(rowId: *`number`*): [IRowData](../interfaces/irowdata.md)

*Implementation of [IRowDataCollection](../interfaces/irowdatacollection.md).[getRowById](../interfaces/irowdatacollection.md#getrowbyid)*

*Inherited from [RowCollBase](rowcollbase.md).[getRowById](rowcollbase.md#getrowbyid)*

*Defined in [model.row.ts:90](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L90)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |

**Returns:** [IRowData](../interfaces/irowdata.md)

___
<a id="getrowbyindex"></a>

###  getRowByIndex

▸ **getRowByIndex**(index: *`number`*): [IRowData](../interfaces/irowdata.md)

*Implementation of [IRowDataCollection](../interfaces/irowdatacollection.md).[getRowByIndex](../interfaces/irowdatacollection.md#getrowbyindex)*

*Inherited from [RowCollBase](rowcollbase.md).[getRowByIndex](rowcollbase.md#getrowbyindex)*

*Defined in [model.row.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** [IRowData](../interfaces/irowdata.md)

___
<a id="getrowbyoffset"></a>

###  getRowByOffset

▸ **getRowByOffset**(rowId: *`number`*, offset: *`number`*): [IRowData](../interfaces/irowdata.md)

*Implementation of [IRowDataCollection](../interfaces/irowdatacollection.md).[getRowByOffset](../interfaces/irowdatacollection.md#getrowbyoffset)*

*Inherited from [RowCollBase](rowcollbase.md).[getRowByOffset](rowcollbase.md#getrowbyoffset)*

*Defined in [model.row.ts:106](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L106)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |
| offset | `number` |

**Returns:** [IRowData](../interfaces/irowdata.md)

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): [IRowData](../interfaces/irowdata.md)[]

*Implementation of [IRowDataCollection](../interfaces/irowdatacollection.md).[getRows](../interfaces/irowdatacollection.md#getrows)*

*Inherited from [RowCollBase](rowcollbase.md).[getRows](rowcollbase.md#getrows)*

*Defined in [model.row.ts:93](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L93)*

**Returns:** [IRowData](../interfaces/irowdata.md)[]

___
<a id="getrowsbytxid"></a>

###  getRowsByTxId

▸ **getRowsByTxId**(txId: *`number`*, includeInactive?: *`boolean`*): [IRowData](../interfaces/irowdata.md)[]

*Implementation of [IRowDataCollection](../interfaces/irowdatacollection.md).[getRowsByTxId](../interfaces/irowdatacollection.md#getrowsbytxid)*

*Defined in [model.row.ts:122](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L122)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| txId | `number` | - |
| `Default value` includeInactive | `boolean` | false |

**Returns:** [IRowData](../interfaces/irowdata.md)[]

___
<a id="merge"></a>

###  merge

▸ **merge**(pRows: *[RowFields](../interfaces/rowfields.md)[]*): `void`

*Implementation of [IRowDataCollection](../interfaces/irowdatacollection.md).[merge](../interfaces/irowdatacollection.md#merge)*

*Defined in [model.row.ts:126](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L126)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pRows | [RowFields](../interfaces/rowfields.md)[] |

**Returns:** `void`

___
<a id="sortfn"></a>

### `<Static>``<Private>` sortFn

▸ **sortFn**(a: *[IRowData](../interfaces/irowdata.md)*, b: *[IRowData](../interfaces/irowdata.md)*): `number`

*Defined in [model.row.ts:142](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L142)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| a | [IRowData](../interfaces/irowdata.md) |
| b | [IRowData](../interfaces/irowdata.md) |

**Returns:** `number`

___

