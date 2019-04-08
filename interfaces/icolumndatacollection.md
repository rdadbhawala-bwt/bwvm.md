[bcvm](../README.md) > [IColumnDataCollection](../interfaces/icolumndatacollection.md)

# Interface: IColumnDataCollection

## Hierarchy

 [IColumnCollection](icolumncollection.md)<[IColumnData](icolumndata.md)>

**↳ IColumnDataCollection**

## Implemented by

* [ColumnDataColl](../classes/columndatacoll.md)

## Index

### Methods

* [filter](icolumndatacollection.md#filter)
* [getColumnById](icolumndatacollection.md#getcolumnbyid)
* [getColumnByIndex](icolumndatacollection.md#getcolumnbyindex)
* [getColumnByOffset](icolumndatacollection.md#getcolumnbyoffset)
* [getColumns](icolumndatacollection.md#getcolumns)
* [getColumnsByTxId](icolumndatacollection.md#getcolumnsbytxid)
* [merge](icolumndatacollection.md#merge)

---

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [IColumnData](icolumndata.md)[]

*Inherited from [IColumnCollection](icolumncollection.md).[filter](icolumncollection.md#filter)*

*Defined in [model.column.ts:110](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L110)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [IColumnData](icolumndata.md)[]

___
<a id="getcolumnbyid"></a>

###  getColumnById

▸ **getColumnById**(columnId: *`number`*): [IColumnData](icolumndata.md)

*Inherited from [IColumnCollection](icolumncollection.md).[getColumnById](icolumncollection.md#getcolumnbyid)*

*Defined in [model.column.ts:104](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L104)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |

**Returns:** [IColumnData](icolumndata.md)

___
<a id="getcolumnbyindex"></a>

###  getColumnByIndex

▸ **getColumnByIndex**(index: *`number`*): [IColumnData](icolumndata.md)

*Inherited from [IColumnCollection](icolumncollection.md).[getColumnByIndex](icolumncollection.md#getcolumnbyindex)*

*Defined in [model.column.ts:107](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L107)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** [IColumnData](icolumndata.md)

___
<a id="getcolumnbyoffset"></a>

###  getColumnByOffset

▸ **getColumnByOffset**(columnId: *`number`*, offset: *`number`*): [IColumnData](icolumndata.md)

*Inherited from [IColumnCollection](icolumncollection.md).[getColumnByOffset](icolumncollection.md#getcolumnbyoffset)*

*Defined in [model.column.ts:108](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L108)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |
| offset | `number` |

**Returns:** [IColumnData](icolumndata.md)

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): [IColumnData](icolumndata.md)[]

*Inherited from [IColumnCollection](icolumncollection.md).[getColumns](icolumncollection.md#getcolumns)*

*Defined in [model.column.ts:105](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L105)*

**Returns:** [IColumnData](icolumndata.md)[]

___
<a id="getcolumnsbytxid"></a>

###  getColumnsByTxId

▸ **getColumnsByTxId**(txId: *`number`*, includeInactive?: *`boolean`*): [IColumnData](icolumndata.md)[]

*Defined in [model.column.ts:115](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L115)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |
| `Optional` includeInactive | `boolean` |

**Returns:** [IColumnData](icolumndata.md)[]

___
<a id="merge"></a>

###  merge

▸ **merge**(pColumns: *[ColumnFields](columnfields.md)[]*): `any`

*Defined in [model.column.ts:116](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L116)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pColumns | [ColumnFields](columnfields.md)[] |

**Returns:** `any`

___

