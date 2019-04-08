[bcvm](../README.md) > [IColumnData](../interfaces/icolumndata.md)

# Interface: IColumnData

## Hierarchy

 [IColumn](icolumn.md)

**↳ IColumnData**

## Implemented by

* [ColumnData](../classes/columndata.md)

## Index

### Methods

* [getActive](icolumndata.md#getactive)
* [getColumnCreationTxId](icolumndata.md#getcolumncreationtxid)
* [getColumnDeletionTxId](icolumndata.md#getcolumndeletiontxid)
* [getColumnId](icolumndata.md#getcolumnid)
* [getColumnKey](icolumndata.md#getcolumnkey)
* [getColumnName](icolumndata.md#getcolumnname)
* [getColumnSequenceNumber](icolumndata.md#getcolumnsequencenumber)
* [getPreviousColumnId](icolumndata.md#getpreviouscolumnid)
* [getPreviousColumnOffset](icolumndata.md#getpreviouscolumnoffset)
* [merge](icolumndata.md#merge)

---

## Methods

<a id="getactive"></a>

###  getActive

▸ **getActive**(): `boolean`

*Defined in [model.column.ts:16](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L16)*

**Returns:** `boolean`

___
<a id="getcolumncreationtxid"></a>

###  getColumnCreationTxId

▸ **getColumnCreationTxId**(): `number`

*Defined in [model.column.ts:19](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L19)*

**Returns:** `number`

___
<a id="getcolumndeletiontxid"></a>

###  getColumnDeletionTxId

▸ **getColumnDeletionTxId**(): `number`

*Defined in [model.column.ts:20](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L20)*

**Returns:** `number`

___
<a id="getcolumnid"></a>

###  getColumnId

▸ **getColumnId**(): `number`

*Inherited from [IColumn](icolumn.md).[getColumnId](icolumn.md#getcolumnid)*

*Defined in [model.column.ts:6](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L6)*

**Returns:** `number`

___
<a id="getcolumnkey"></a>

###  getColumnKey

▸ **getColumnKey**(): `number`

*Inherited from [IColumn](icolumn.md).[getColumnKey](icolumn.md#getcolumnkey)*

*Defined in [model.column.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L7)*

**Returns:** `number`

___
<a id="getcolumnname"></a>

###  getColumnName

▸ **getColumnName**(): `string`

*Defined in [model.column.ts:17](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L17)*

**Returns:** `string`

___
<a id="getcolumnsequencenumber"></a>

###  getColumnSequenceNumber

▸ **getColumnSequenceNumber**(): `number`

*Defined in [model.column.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L13)*

**Returns:** `number`

___
<a id="getpreviouscolumnid"></a>

###  getPreviousColumnId

▸ **getPreviousColumnId**(): `number`

*Defined in [model.column.ts:14](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L14)*

**Returns:** `number`

___
<a id="getpreviouscolumnoffset"></a>

###  getPreviousColumnOffset

▸ **getPreviousColumnOffset**(): `number`

*Defined in [model.column.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L15)*

**Returns:** `number`

___
<a id="merge"></a>

###  merge

▸ **merge**(newCol: *[ColumnFields](columnfields.md)*): `any`

*Defined in [model.column.ts:23](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L23)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newCol | [ColumnFields](columnfields.md) |

**Returns:** `any`

___

