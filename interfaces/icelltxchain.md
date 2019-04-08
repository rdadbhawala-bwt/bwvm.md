[bcvm](../README.md) > [ICellTxChain](../interfaces/icelltxchain.md)

# Interface: ICellTxChain

## Hierarchy

 [ICell](icell.md)

**↳ ICellTxChain**

## Implemented by

* [CellTxChain](../classes/celltxchain.md)

## Index

### Methods

* [getAccess](icelltxchain.md#getaccess)
* [getActive](icelltxchain.md#getactive)
* [getCellId](icelltxchain.md#getcellid)
* [getColumnId](icelltxchain.md#getcolumnid)
* [getColumnKey](icelltxchain.md#getcolumnkey)
* [getLatestStatus](icelltxchain.md#getlateststatus)
* [getLatestTxId](icelltxchain.md#getlatesttxid)
* [getLatestValue](icelltxchain.md#getlatestvalue)
* [getRowId](icelltxchain.md#getrowid)
* [getRowKey](icelltxchain.md#getrowkey)
* [getStatusByTxId](icelltxchain.md#getstatusbytxid)
* [getStatuses](icelltxchain.md#getstatuses)
* [getValueByTxId](icelltxchain.md#getvaluebytxid)
* [getValues](icelltxchain.md#getvalues)
* [isDeleted](icelltxchain.md#isdeleted)
* [isInserted](icelltxchain.md#isinserted)
* [isModified](icelltxchain.md#ismodified)
* [merge](icelltxchain.md#merge)

---

## Methods

<a id="getaccess"></a>

###  getAccess

▸ **getAccess**(): `number`

*Defined in [model.cell.ts:39](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L39)*

**Returns:** `number`

___
<a id="getactive"></a>

###  getActive

▸ **getActive**(): `boolean`

*Defined in [model.cell.ts:38](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L38)*

**Returns:** `boolean`

___
<a id="getcellid"></a>

###  getCellId

▸ **getCellId**(): `number`

*Inherited from [ICell](icell.md).[getCellId](icell.md#getcellid)*

*Defined in [model.cell.ts:9](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L9)*

**Returns:** `number`

___
<a id="getcolumnid"></a>

###  getColumnId

▸ **getColumnId**(): `number`

*Inherited from [ICell](icell.md).[getColumnId](icell.md#getcolumnid)*

*Defined in [model.cell.ts:11](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L11)*

**Returns:** `number`

___
<a id="getcolumnkey"></a>

###  getColumnKey

▸ **getColumnKey**(): `number`

*Inherited from [ICell](icell.md).[getColumnKey](icell.md#getcolumnkey)*

*Defined in [model.cell.ts:14](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L14)*

**Returns:** `number`

___
<a id="getlateststatus"></a>

###  getLatestStatus

▸ **getLatestStatus**(): [ICellStatus](icellstatus.md)

*Defined in [model.cell.ts:48](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L48)*

**Returns:** [ICellStatus](icellstatus.md)

___
<a id="getlatesttxid"></a>

###  getLatestTxId

▸ **getLatestTxId**(): `number`

*Defined in [model.cell.ts:41](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L41)*

**Returns:** `number`

___
<a id="getlatestvalue"></a>

###  getLatestValue

▸ **getLatestValue**(): [ICellTxValue](icelltxvalue.md)

*Defined in [model.cell.ts:44](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L44)*

**Returns:** [ICellTxValue](icelltxvalue.md)

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Inherited from [ICell](icell.md).[getRowId](icell.md#getrowid)*

*Defined in [model.cell.ts:10](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L10)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Inherited from [ICell](icell.md).[getRowKey](icell.md#getrowkey)*

*Defined in [model.cell.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L13)*

**Returns:** `number`

___
<a id="getstatusbytxid"></a>

###  getStatusByTxId

▸ **getStatusByTxId**(txId: *`number`*): [ICellStatus](icellstatus.md)

*Defined in [model.cell.ts:47](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L47)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ICellStatus](icellstatus.md)

___
<a id="getstatuses"></a>

###  getStatuses

▸ **getStatuses**(): [ICellStatus](icellstatus.md)[]

*Defined in [model.cell.ts:46](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L46)*

**Returns:** [ICellStatus](icellstatus.md)[]

___
<a id="getvaluebytxid"></a>

###  getValueByTxId

▸ **getValueByTxId**(txId: *`number`*): [ICellTxValue](icelltxvalue.md)

*Defined in [model.cell.ts:43](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L43)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ICellTxValue](icelltxvalue.md)

___
<a id="getvalues"></a>

###  getValues

▸ **getValues**(): [ICellTxValue](icelltxvalue.md)[]

*Defined in [model.cell.ts:42](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L42)*

**Returns:** [ICellTxValue](icelltxvalue.md)[]

___
<a id="isdeleted"></a>

###  isDeleted

▸ **isDeleted**(endTxId: *`number`*, startTxId: *`number`*): `boolean`

*Defined in [model.cell.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L52)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** `boolean`

___
<a id="isinserted"></a>

###  isInserted

▸ **isInserted**(endTxId: *`number`*, startTxId: *`number`*): `boolean`

*Defined in [model.cell.ts:53](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L53)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** `boolean`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(endTxId: *`number`*, startTxId: *`number`*): `boolean`

*Defined in [model.cell.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L50)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** `boolean`

___
<a id="merge"></a>

###  merge

▸ **merge**(v: *[ICellChainFields](icellchainfields.md)*): `any`

*Defined in [model.cell.ts:36](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L36)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| v | [ICellChainFields](icellchainfields.md) |

**Returns:** `any`

___

