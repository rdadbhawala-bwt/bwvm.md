[bcvm](../README.md) > [CellTxChain](../classes/celltxchain.md)

# Class: CellTxChain

## Hierarchy

**CellTxChain**

## Implements

* [ICellTxChain](../interfaces/icelltxchain.md)

## Index

### Constructors

* [constructor](celltxchain.md#constructor)

### Properties

* [cellChain](celltxchain.md#cellchain)
* [status](celltxchain.md#status)
* [values](celltxchain.md#values)

### Methods

* [getAccess](celltxchain.md#getaccess)
* [getActive](celltxchain.md#getactive)
* [getCellId](celltxchain.md#getcellid)
* [getColumnId](celltxchain.md#getcolumnid)
* [getColumnKey](celltxchain.md#getcolumnkey)
* [getLatestStatus](celltxchain.md#getlateststatus)
* [getLatestTxId](celltxchain.md#getlatesttxid)
* [getLatestValue](celltxchain.md#getlatestvalue)
* [getRowId](celltxchain.md#getrowid)
* [getRowKey](celltxchain.md#getrowkey)
* [getStatusByTxId](celltxchain.md#getstatusbytxid)
* [getStatuses](celltxchain.md#getstatuses)
* [getValueByTxId](celltxchain.md#getvaluebytxid)
* [getValues](celltxchain.md#getvalues)
* [isDeleted](celltxchain.md#isdeleted)
* [isInserted](celltxchain.md#isinserted)
* [isModified](celltxchain.md#ismodified)
* [merge](celltxchain.md#merge)
* [mergeStatus](celltxchain.md#mergestatus)
* [mergeValues](celltxchain.md#mergevalues)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new CellTxChain**(val: *[ICellChainFields](../interfaces/icellchainfields.md)*): [CellTxChain](celltxchain.md)

*Defined in [model.cell.ts:239](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L239)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| val | [ICellChainFields](../interfaces/icellchainfields.md) |

**Returns:** [CellTxChain](celltxchain.md)

___

## Properties

<a id="cellchain"></a>

###  cellChain

**● cellChain**: *[ICellChainFields](../interfaces/icellchainfields.md)*

*Defined in [model.cell.ts:237](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L237)*

___
<a id="status"></a>

###  status

**● status**: *[CellStatus](cellstatus.md)[]*

*Defined in [model.cell.ts:239](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L239)*

___
<a id="values"></a>

###  values

**● values**: *[CellTxValue](celltxvalue.md)[]*

*Defined in [model.cell.ts:238](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L238)*

___

## Methods

<a id="getaccess"></a>

###  getAccess

▸ **getAccess**(): `number`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getAccess](../interfaces/icelltxchain.md#getaccess)*

*Defined in [model.cell.ts:275](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L275)*

**Returns:** `number`

___
<a id="getactive"></a>

###  getActive

▸ **getActive**(): `boolean`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getActive](../interfaces/icelltxchain.md#getactive)*

*Defined in [model.cell.ts:272](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L272)*

**Returns:** `boolean`

___
<a id="getcellid"></a>

###  getCellId

▸ **getCellId**(): `number`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getCellId](../interfaces/icelltxchain.md#getcellid)*

*Defined in [model.cell.ts:263](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L263)*

**Returns:** `number`

___
<a id="getcolumnid"></a>

###  getColumnId

▸ **getColumnId**(): `number`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getColumnId](../interfaces/icelltxchain.md#getcolumnid)*

*Defined in [model.cell.ts:269](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L269)*

**Returns:** `number`

___
<a id="getcolumnkey"></a>

###  getColumnKey

▸ **getColumnKey**(): `number`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getColumnKey](../interfaces/icelltxchain.md#getcolumnkey)*

*Defined in [model.cell.ts:299](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L299)*

**Returns:** `number`

___
<a id="getlateststatus"></a>

###  getLatestStatus

▸ **getLatestStatus**(): [ICellStatus](../interfaces/icellstatus.md)

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getLatestStatus](../interfaces/icelltxchain.md#getlateststatus)*

*Defined in [model.cell.ts:284](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L284)*

**Returns:** [ICellStatus](../interfaces/icellstatus.md)

___
<a id="getlatesttxid"></a>

###  getLatestTxId

▸ **getLatestTxId**(): `number`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getLatestTxId](../interfaces/icelltxchain.md#getlatesttxid)*

*Defined in [model.cell.ts:256](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L256)*

**Returns:** `number`

___
<a id="getlatestvalue"></a>

###  getLatestValue

▸ **getLatestValue**(): [ICellTxValue](../interfaces/icelltxvalue.md)

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getLatestValue](../interfaces/icelltxchain.md#getlatestvalue)*

*Defined in [model.cell.ts:260](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L260)*

**Returns:** [ICellTxValue](../interfaces/icelltxvalue.md)

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getRowId](../interfaces/icelltxchain.md#getrowid)*

*Defined in [model.cell.ts:266](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L266)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getRowKey](../interfaces/icelltxchain.md#getrowkey)*

*Defined in [model.cell.ts:296](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L296)*

**Returns:** `number`

___
<a id="getstatusbytxid"></a>

###  getStatusByTxId

▸ **getStatusByTxId**(txId: *`number`*): [ICellStatus](../interfaces/icellstatus.md)

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getStatusByTxId](../interfaces/icelltxchain.md#getstatusbytxid)*

*Defined in [model.cell.ts:281](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L281)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ICellStatus](../interfaces/icellstatus.md)

___
<a id="getstatuses"></a>

###  getStatuses

▸ **getStatuses**(): [ICellStatus](../interfaces/icellstatus.md)[]

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getStatuses](../interfaces/icelltxchain.md#getstatuses)*

*Defined in [model.cell.ts:278](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L278)*

**Returns:** [ICellStatus](../interfaces/icellstatus.md)[]

___
<a id="getvaluebytxid"></a>

###  getValueByTxId

▸ **getValueByTxId**(txId: *`number`*): [ICellTxValue](../interfaces/icelltxvalue.md)

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getValueByTxId](../interfaces/icelltxchain.md#getvaluebytxid)*

*Defined in [model.cell.ts:253](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L253)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ICellTxValue](../interfaces/icelltxvalue.md)

___
<a id="getvalues"></a>

###  getValues

▸ **getValues**(): [ICellTxValue](../interfaces/icelltxvalue.md)[]

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[getValues](../interfaces/icelltxchain.md#getvalues)*

*Defined in [model.cell.ts:250](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L250)*

**Returns:** [ICellTxValue](../interfaces/icelltxvalue.md)[]

___
<a id="isdeleted"></a>

###  isDeleted

▸ **isDeleted**(endTxId: *`number`*, startTxId: *`number`*): `boolean`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[isDeleted](../interfaces/icelltxchain.md#isdeleted)*

*Defined in [model.cell.ts:290](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L290)*

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

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[isInserted](../interfaces/icelltxchain.md#isinserted)*

*Defined in [model.cell.ts:293](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L293)*

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

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[isModified](../interfaces/icelltxchain.md#ismodified)*

*Defined in [model.cell.ts:287](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L287)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** `boolean`

___
<a id="merge"></a>

###  merge

▸ **merge**(v: *[ICellChainFields](../interfaces/icellchainfields.md)*): `void`

*Implementation of [ICellTxChain](../interfaces/icelltxchain.md).[merge](../interfaces/icelltxchain.md#merge)*

*Defined in [model.cell.ts:303](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L303)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| v | [ICellChainFields](../interfaces/icellchainfields.md) |

**Returns:** `void`

___
<a id="mergestatus"></a>

### `<Private>` mergeStatus

▸ **mergeStatus**(sts: *[ICellStatusFields](../interfaces/icellstatusfields.md)[]*): `void`

*Defined in [model.cell.ts:320](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L320)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| sts | [ICellStatusFields](../interfaces/icellstatusfields.md)[] |

**Returns:** `void`

___
<a id="mergevalues"></a>

### `<Private>` mergeValues

▸ **mergeValues**(vls: *[ICellTransactionFields](../interfaces/icelltransactionfields.md)[]*): `void`

*Defined in [model.cell.ts:309](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L309)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| vls | [ICellTransactionFields](../interfaces/icelltransactionfields.md)[] |

**Returns:** `void`

___

