[bcvm](../README.md) > [ColumnData](../classes/columndata.md)

# Class: ColumnData

## Hierarchy

**ColumnData**

## Implements

* [IColumnData](../interfaces/icolumndata.md)

## Index

### Constructors

* [constructor](columndata.md#constructor)

### Properties

* [fields](columndata.md#fields)

### Methods

* [getActive](columndata.md#getactive)
* [getColumnCreationTxId](columndata.md#getcolumncreationtxid)
* [getColumnDeletionTxId](columndata.md#getcolumndeletiontxid)
* [getColumnId](columndata.md#getcolumnid)
* [getColumnKey](columndata.md#getcolumnkey)
* [getColumnName](columndata.md#getcolumnname)
* [getColumnSequenceNumber](columndata.md#getcolumnsequencenumber)
* [getPreviousColumnId](columndata.md#getpreviouscolumnid)
* [getPreviousColumnOffset](columndata.md#getpreviouscolumnoffset)
* [merge](columndata.md#merge)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new ColumnData**(flds: *[ColumnFields](../interfaces/columnfields.md)*): [ColumnData](columndata.md)

*Defined in [model.column.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L49)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| flds | [ColumnFields](../interfaces/columnfields.md) |

**Returns:** [ColumnData](columndata.md)

___

## Properties

<a id="fields"></a>

###  fields

**● fields**: *[ColumnFields](../interfaces/columnfields.md)*

*Defined in [model.column.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L49)*

___

## Methods

<a id="getactive"></a>

###  getActive

▸ **getActive**(): `boolean`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getActive](../interfaces/icolumndata.md#getactive)*

*Defined in [model.column.ts:69](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L69)*

**Returns:** `boolean`

___
<a id="getcolumncreationtxid"></a>

###  getColumnCreationTxId

▸ **getColumnCreationTxId**(): `number`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getColumnCreationTxId](../interfaces/icolumndata.md#getcolumncreationtxid)*

*Defined in [model.column.ts:75](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L75)*

**Returns:** `number`

___
<a id="getcolumndeletiontxid"></a>

###  getColumnDeletionTxId

▸ **getColumnDeletionTxId**(): `number`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getColumnDeletionTxId](../interfaces/icolumndata.md#getcolumndeletiontxid)*

*Defined in [model.column.ts:78](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L78)*

**Returns:** `number`

___
<a id="getcolumnid"></a>

###  getColumnId

▸ **getColumnId**(): `number`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getColumnId](../interfaces/icolumndata.md#getcolumnid)*

*Defined in [model.column.ts:54](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L54)*

**Returns:** `number`

___
<a id="getcolumnkey"></a>

###  getColumnKey

▸ **getColumnKey**(): `number`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getColumnKey](../interfaces/icolumndata.md#getcolumnkey)*

*Defined in [model.column.ts:57](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L57)*

**Returns:** `number`

___
<a id="getcolumnname"></a>

###  getColumnName

▸ **getColumnName**(): `string`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getColumnName](../interfaces/icolumndata.md#getcolumnname)*

*Defined in [model.column.ts:72](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L72)*

**Returns:** `string`

___
<a id="getcolumnsequencenumber"></a>

###  getColumnSequenceNumber

▸ **getColumnSequenceNumber**(): `number`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getColumnSequenceNumber](../interfaces/icolumndata.md#getcolumnsequencenumber)*

*Defined in [model.column.ts:60](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L60)*

**Returns:** `number`

___
<a id="getpreviouscolumnid"></a>

###  getPreviousColumnId

▸ **getPreviousColumnId**(): `number`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getPreviousColumnId](../interfaces/icolumndata.md#getpreviouscolumnid)*

*Defined in [model.column.ts:63](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L63)*

**Returns:** `number`

___
<a id="getpreviouscolumnoffset"></a>

###  getPreviousColumnOffset

▸ **getPreviousColumnOffset**(): `number`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[getPreviousColumnOffset](../interfaces/icolumndata.md#getpreviouscolumnoffset)*

*Defined in [model.column.ts:66](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L66)*

**Returns:** `number`

___
<a id="merge"></a>

###  merge

▸ **merge**(newcol: *[ColumnFields](../interfaces/columnfields.md)*): `void`

*Implementation of [IColumnData](../interfaces/icolumndata.md).[merge](../interfaces/icolumndata.md#merge)*

*Defined in [model.column.ts:82](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L82)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newcol | [ColumnFields](../interfaces/columnfields.md) |

**Returns:** `void`

___

