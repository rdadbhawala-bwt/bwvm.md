[bcvm](../README.md) > [IRowDataCollection](../interfaces/irowdatacollection.md)

# Interface: IRowDataCollection

## Hierarchy

 [IRowCollection](irowcollection.md)<[IRowData](irowdata.md)>

**↳ IRowDataCollection**

## Implemented by

* [RowDataColl](../classes/rowdatacoll.md)

## Index

### Methods

* [filter](irowdatacollection.md#filter)
* [getCount](irowdatacollection.md#getcount)
* [getRowById](irowdatacollection.md#getrowbyid)
* [getRowByIndex](irowdatacollection.md#getrowbyindex)
* [getRowByOffset](irowdatacollection.md#getrowbyoffset)
* [getRows](irowdatacollection.md#getrows)
* [getRowsByTxId](irowdatacollection.md#getrowsbytxid)
* [merge](irowdatacollection.md#merge)

---

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [IRowData](irowdata.md)[]

*Inherited from [IRowCollection](irowcollection.md).[filter](irowcollection.md#filter)*

*Defined in [model.row.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L52)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [IRowData](irowdata.md)[]

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

▸ **getRowById**(rowId: *`number`*): [IRowData](irowdata.md)

*Inherited from [IRowCollection](irowcollection.md).[getRowById](irowcollection.md#getrowbyid)*

*Defined in [model.row.ts:45](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L45)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |

**Returns:** [IRowData](irowdata.md)

___
<a id="getrowbyindex"></a>

###  getRowByIndex

▸ **getRowByIndex**(index: *`number`*): [IRowData](irowdata.md)

*Inherited from [IRowCollection](irowcollection.md).[getRowByIndex](irowcollection.md#getrowbyindex)*

*Defined in [model.row.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L49)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** [IRowData](irowdata.md)

___
<a id="getrowbyoffset"></a>

###  getRowByOffset

▸ **getRowByOffset**(rowId: *`number`*, offset: *`number`*): [IRowData](irowdata.md)

*Inherited from [IRowCollection](irowcollection.md).[getRowByOffset](irowcollection.md#getrowbyoffset)*

*Defined in [model.row.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L50)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowId | `number` |
| offset | `number` |

**Returns:** [IRowData](irowdata.md)

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): [IRowData](irowdata.md)[]

*Inherited from [IRowCollection](irowcollection.md).[getRows](irowcollection.md#getrows)*

*Defined in [model.row.ts:46](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L46)*

**Returns:** [IRowData](irowdata.md)[]

___
<a id="getrowsbytxid"></a>

###  getRowsByTxId

▸ **getRowsByTxId**(txId: *`number`*, includeInactive?: *`boolean`*): [IRowData](irowdata.md)[]

*Defined in [model.row.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L58)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |
| `Optional` includeInactive | `boolean` |

**Returns:** [IRowData](irowdata.md)[]

___
<a id="merge"></a>

###  merge

▸ **merge**(pRows: *[RowFields](rowfields.md)[]*): `any`

*Defined in [model.row.ts:59](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L59)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pRows | [RowFields](rowfields.md)[] |

**Returns:** `any`

___

