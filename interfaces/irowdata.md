[bcvm](../README.md) > [IRowData](../interfaces/irowdata.md)

# Interface: IRowData

## Hierarchy

 [IRow](irow.md)

**↳ IRowData**

## Implemented by

* [RowData](../classes/rowdata.md)

## Index

### Methods

* [getActive](irowdata.md#getactive)
* [getPreviousRowId](irowdata.md#getpreviousrowid)
* [getPreviousRowOffset](irowdata.md#getpreviousrowoffset)
* [getRowCreationTxId](irowdata.md#getrowcreationtxid)
* [getRowDeletionTxId](irowdata.md#getrowdeletiontxid)
* [getRowId](irowdata.md#getrowid)
* [getRowKey](irowdata.md#getrowkey)
* [getRowName](irowdata.md#getrowname)
* [getRowSequenceNumber](irowdata.md#getrowsequencenumber)
* [merge](irowdata.md#merge)

---

## Methods

<a id="getactive"></a>

###  getActive

▸ **getActive**(): `boolean`

*Defined in [model.row.ts:19](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L19)*

**Returns:** `boolean`

___
<a id="getpreviousrowid"></a>

###  getPreviousRowId

▸ **getPreviousRowId**(): `number`

*Defined in [model.row.ts:17](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L17)*

**Returns:** `number`

___
<a id="getpreviousrowoffset"></a>

###  getPreviousRowOffset

▸ **getPreviousRowOffset**(): `number`

*Defined in [model.row.ts:18](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L18)*

**Returns:** `number`

___
<a id="getrowcreationtxid"></a>

###  getRowCreationTxId

▸ **getRowCreationTxId**(): `number`

*Defined in [model.row.ts:14](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L14)*

**Returns:** `number`

___
<a id="getrowdeletiontxid"></a>

###  getRowDeletionTxId

▸ **getRowDeletionTxId**(): `number`

*Defined in [model.row.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L15)*

**Returns:** `number`

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Inherited from [IRow](irow.md).[getRowId](irow.md#getrowid)*

*Defined in [model.row.ts:8](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L8)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Inherited from [IRow](irow.md).[getRowKey](irow.md#getrowkey)*

*Defined in [model.row.ts:9](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L9)*

**Returns:** `number`

___
<a id="getrowname"></a>

###  getRowName

▸ **getRowName**(): `string`

*Defined in [model.row.ts:20](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L20)*

**Returns:** `string`

___
<a id="getrowsequencenumber"></a>

###  getRowSequenceNumber

▸ **getRowSequenceNumber**(): `number`

*Defined in [model.row.ts:16](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L16)*

**Returns:** `number`

___
<a id="merge"></a>

###  merge

▸ **merge**(v: *[RowFields](rowfields.md)*): `any`

*Defined in [model.row.ts:22](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L22)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| v | [RowFields](rowfields.md) |

**Returns:** `any`

___

