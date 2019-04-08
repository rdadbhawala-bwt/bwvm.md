[bcvm](../README.md) > [ColumnDataColl](../classes/columndatacoll.md)

# Class: ColumnDataColl

## Hierarchy

 [ColumnCollBase](columncollbase.md)<[IColumnData](../interfaces/icolumndata.md)>

**↳ ColumnDataColl**

## Implements

* [IColumnCollection](../interfaces/icolumncollection.md)<[IColumnData](../interfaces/icolumndata.md)>
* [IColumnDataCollection](../interfaces/icolumndatacollection.md)

## Index

### Constructors

* [constructor](columndatacoll.md#constructor)

### Properties

* [colArr](columndatacoll.md#colarr)

### Methods

* [filter](columndatacoll.md#filter)
* [getColumnById](columndatacoll.md#getcolumnbyid)
* [getColumnByIndex](columndatacoll.md#getcolumnbyindex)
* [getColumnByOffset](columndatacoll.md#getcolumnbyoffset)
* [getColumns](columndatacoll.md#getcolumns)
* [getColumnsByTxId](columndatacoll.md#getcolumnsbytxid)
* [merge](columndatacoll.md#merge)
* [sortFn](columndatacoll.md#sortfn)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new ColumnDataColl**(pCols: *[IColumnData](../interfaces/icolumndata.md)[]*): [ColumnDataColl](columndatacoll.md)

*Inherited from [ColumnCollBase](columncollbase.md).[constructor](columncollbase.md#constructor)*

*Defined in [model.column.ts:137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L137)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCols | [IColumnData](../interfaces/icolumndata.md)[] |

**Returns:** [ColumnDataColl](columndatacoll.md)

___

## Properties

<a id="colarr"></a>

### `<Protected>` colArr

**● colArr**: *[IColumnData](../interfaces/icolumndata.md)[]* =  []

*Inherited from [ColumnCollBase](columncollbase.md).[colArr](columncollbase.md#colarr)*

*Defined in [model.column.ts:137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L137)*

___

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [IColumnData](../interfaces/icolumndata.md)[]

*Inherited from [ColumnCollBase](columncollbase.md).[filter](columncollbase.md#filter)*

*Defined in [model.column.ts:163](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L163)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [IColumnData](../interfaces/icolumndata.md)[]

___
<a id="getcolumnbyid"></a>

###  getColumnById

▸ **getColumnById**(columnId: *`number`*): [IColumnData](../interfaces/icolumndata.md)

*Implementation of [IColumnDataCollection](../interfaces/icolumndatacollection.md).[getColumnById](../interfaces/icolumndatacollection.md#getcolumnbyid)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumnById](columncollbase.md#getcolumnbyid)*

*Defined in [model.column.ts:143](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L143)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |

**Returns:** [IColumnData](../interfaces/icolumndata.md)

___
<a id="getcolumnbyindex"></a>

###  getColumnByIndex

▸ **getColumnByIndex**(index: *`number`*): [IColumnData](../interfaces/icolumndata.md)

*Implementation of [IColumnDataCollection](../interfaces/icolumndatacollection.md).[getColumnByIndex](../interfaces/icolumndatacollection.md#getcolumnbyindex)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumnByIndex](columncollbase.md#getcolumnbyindex)*

*Defined in [model.column.ts:149](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L149)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** [IColumnData](../interfaces/icolumndata.md)

___
<a id="getcolumnbyoffset"></a>

###  getColumnByOffset

▸ **getColumnByOffset**(columnId: *`number`*, offset: *`number`*): [IColumnData](../interfaces/icolumndata.md)

*Implementation of [IColumnDataCollection](../interfaces/icolumndatacollection.md).[getColumnByOffset](../interfaces/icolumndatacollection.md#getcolumnbyoffset)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumnByOffset](columncollbase.md#getcolumnbyoffset)*

*Defined in [model.column.ts:155](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L155)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |
| offset | `number` |

**Returns:** [IColumnData](../interfaces/icolumndata.md)

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): [IColumnData](../interfaces/icolumndata.md)[]

*Implementation of [IColumnDataCollection](../interfaces/icolumndatacollection.md).[getColumns](../interfaces/icolumndatacollection.md#getcolumns)*

*Inherited from [ColumnCollBase](columncollbase.md).[getColumns](columncollbase.md#getcolumns)*

*Defined in [model.column.ts:146](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L146)*

**Returns:** [IColumnData](../interfaces/icolumndata.md)[]

___
<a id="getcolumnsbytxid"></a>

###  getColumnsByTxId

▸ **getColumnsByTxId**(txId: *`number`*, includeInactive?: *`boolean`*): [IColumnData](../interfaces/icolumndata.md)[]

*Implementation of [IColumnDataCollection](../interfaces/icolumndatacollection.md).[getColumnsByTxId](../interfaces/icolumndatacollection.md#getcolumnsbytxid)*

*Defined in [model.column.ts:170](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L170)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |
| `Optional` includeInactive | `boolean` |

**Returns:** [IColumnData](../interfaces/icolumndata.md)[]

___
<a id="merge"></a>

###  merge

▸ **merge**(pColumns: *[ColumnFields](../interfaces/columnfields.md)[]*): `void`

*Implementation of [IColumnDataCollection](../interfaces/icolumndatacollection.md).[merge](../interfaces/icolumndatacollection.md#merge)*

*Defined in [model.column.ts:174](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L174)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pColumns | [ColumnFields](../interfaces/columnfields.md)[] |

**Returns:** `void`

___
<a id="sortfn"></a>

### `<Static>``<Private>` sortFn

▸ **sortFn**(a: *[IColumnData](../interfaces/icolumndata.md)*, b: *[IColumnData](../interfaces/icolumndata.md)*): `number`

*Defined in [model.column.ts:192](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L192)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| a | [IColumnData](../interfaces/icolumndata.md) |
| b | [IColumnData](../interfaces/icolumndata.md) |

**Returns:** `number`

___

