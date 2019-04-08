[bcvm](../README.md) > [RowData](../classes/rowdata.md)

# Class: RowData

## Hierarchy

**RowData**

## Implements

* [IRowData](../interfaces/irowdata.md)

## Index

### Constructors

* [constructor](rowdata.md#constructor)

### Properties

* [r](rowdata.md#r)

### Methods

* [getActive](rowdata.md#getactive)
* [getPreviousRowId](rowdata.md#getpreviousrowid)
* [getPreviousRowOffset](rowdata.md#getpreviousrowoffset)
* [getRowCreationTxId](rowdata.md#getrowcreationtxid)
* [getRowDeletionTxId](rowdata.md#getrowdeletiontxid)
* [getRowId](rowdata.md#getrowid)
* [getRowKey](rowdata.md#getrowkey)
* [getRowName](rowdata.md#getrowname)
* [getRowSequenceNumber](rowdata.md#getrowsequencenumber)
* [merge](rowdata.md#merge)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RowData**(row: *[RowFields](../interfaces/rowfields.md)*): [RowData](rowdata.md)

*Defined in [model.row.ts:167](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L167)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | [RowFields](../interfaces/rowfields.md) |

**Returns:** [RowData](rowdata.md)

___

## Properties

<a id="r"></a>

### `<Private>` r

**● r**: *[RowFields](../interfaces/rowfields.md)*

*Defined in [model.row.ts:167](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L167)*

___

## Methods

<a id="getactive"></a>

###  getActive

▸ **getActive**(): `boolean`

*Implementation of [IRowData](../interfaces/irowdata.md).[getActive](../interfaces/irowdata.md#getactive)*

*Defined in [model.row.ts:187](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L187)*

**Returns:** `boolean`

___
<a id="getpreviousrowid"></a>

###  getPreviousRowId

▸ **getPreviousRowId**(): `number`

*Implementation of [IRowData](../interfaces/irowdata.md).[getPreviousRowId](../interfaces/irowdata.md#getpreviousrowid)*

*Defined in [model.row.ts:181](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L181)*

**Returns:** `number`

___
<a id="getpreviousrowoffset"></a>

###  getPreviousRowOffset

▸ **getPreviousRowOffset**(): `number`

*Implementation of [IRowData](../interfaces/irowdata.md).[getPreviousRowOffset](../interfaces/irowdata.md#getpreviousrowoffset)*

*Defined in [model.row.ts:184](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L184)*

**Returns:** `number`

___
<a id="getrowcreationtxid"></a>

###  getRowCreationTxId

▸ **getRowCreationTxId**(): `number`

*Implementation of [IRowData](../interfaces/irowdata.md).[getRowCreationTxId](../interfaces/irowdata.md#getrowcreationtxid)*

*Defined in [model.row.ts:193](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L193)*

**Returns:** `number`

___
<a id="getrowdeletiontxid"></a>

###  getRowDeletionTxId

▸ **getRowDeletionTxId**(): `number`

*Implementation of [IRowData](../interfaces/irowdata.md).[getRowDeletionTxId](../interfaces/irowdata.md#getrowdeletiontxid)*

*Defined in [model.row.ts:196](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L196)*

**Returns:** `number`

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Implementation of [IRowData](../interfaces/irowdata.md).[getRowId](../interfaces/irowdata.md#getrowid)*

*Defined in [model.row.ts:172](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L172)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Implementation of [IRowData](../interfaces/irowdata.md).[getRowKey](../interfaces/irowdata.md#getrowkey)*

*Defined in [model.row.ts:175](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L175)*

**Returns:** `number`

___
<a id="getrowname"></a>

###  getRowName

▸ **getRowName**(): `string`

*Implementation of [IRowData](../interfaces/irowdata.md).[getRowName](../interfaces/irowdata.md#getrowname)*

*Defined in [model.row.ts:190](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L190)*

**Returns:** `string`

___
<a id="getrowsequencenumber"></a>

###  getRowSequenceNumber

▸ **getRowSequenceNumber**(): `number`

*Implementation of [IRowData](../interfaces/irowdata.md).[getRowSequenceNumber](../interfaces/irowdata.md#getrowsequencenumber)*

*Defined in [model.row.ts:178](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L178)*

**Returns:** `number`

___
<a id="merge"></a>

###  merge

▸ **merge**(newRow: *[RowFields](../interfaces/rowfields.md)*): `void`

*Implementation of [IRowData](../interfaces/irowdata.md).[merge](../interfaces/irowdata.md#merge)*

*Defined in [model.row.ts:200](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L200)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newRow | [RowFields](../interfaces/rowfields.md) |

**Returns:** `void`

___

