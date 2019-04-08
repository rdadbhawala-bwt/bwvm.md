[bcvm](../README.md) > [TxDataColl](../classes/txdatacoll.md)

# Class: TxDataColl

## Hierarchy

**TxDataColl**

## Implements

* [ITxColl](../interfaces/itxcoll.md)

## Index

### Properties

* [txs](txdatacoll.md#txs)

### Methods

* [filter](txdatacoll.md#filter)
* [getAllTxIds](txdatacoll.md#getalltxids)
* [getPreviousTx](txdatacoll.md#getprevioustx)
* [getPreviousTxId](txdatacoll.md#getprevioustxid)
* [getTxById](txdatacoll.md#gettxbyid)
* [getTxIdsByDateRange](txdatacoll.md#gettxidsbydaterange)
* [merge](txdatacoll.md#merge)

---

## Properties

<a id="txs"></a>

###  txs

**● txs**: *`Array`<[ITxData](../interfaces/itxdata.md)>* =  []

*Defined in [model.tx.ts:21](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L21)*

___

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [ITxData](../interfaces/itxdata.md)[]

*Defined in [model.tx.ts:71](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L71)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [ITxData](../interfaces/itxdata.md)[]

___
<a id="getalltxids"></a>

###  getAllTxIds

▸ **getAllTxIds**(): `number`[]

*Implementation of [ITxColl](../interfaces/itxcoll.md).[getAllTxIds](../interfaces/itxcoll.md#getalltxids)*

*Defined in [model.tx.ts:39](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L39)*

**Returns:** `number`[]

___
<a id="getprevioustx"></a>

###  getPreviousTx

▸ **getPreviousTx**(txId: *`number`*): [ITxData](../interfaces/itxdata.md)

*Implementation of [ITxColl](../interfaces/itxcoll.md).[getPreviousTx](../interfaces/itxcoll.md#getprevioustx)*

*Defined in [model.tx.ts:54](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L54)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ITxData](../interfaces/itxdata.md)

___
<a id="getprevioustxid"></a>

###  getPreviousTxId

▸ **getPreviousTxId**(txId: *`number`*): `number`

*Implementation of [ITxColl](../interfaces/itxcoll.md).[getPreviousTxId](../interfaces/itxcoll.md#getprevioustxid)*

*Defined in [model.tx.ts:66](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L66)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** `number`

___
<a id="gettxbyid"></a>

###  getTxById

▸ **getTxById**(txId: *`number`*): [ITxData](../interfaces/itxdata.md)

*Implementation of [ITxColl](../interfaces/itxcoll.md).[getTxById](../interfaces/itxcoll.md#gettxbyid)*

*Defined in [model.tx.ts:35](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L35)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ITxData](../interfaces/itxdata.md)

___
<a id="gettxidsbydaterange"></a>

###  getTxIdsByDateRange

▸ **getTxIdsByDateRange**(from: *`Date`*, to: *`Date`*): `number`[]

*Implementation of [ITxColl](../interfaces/itxcoll.md).[getTxIdsByDateRange](../interfaces/itxcoll.md#gettxidsbydaterange)*

*Defined in [model.tx.ts:44](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L44)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| from | `Date` |
| to | `Date` |

**Returns:** `number`[]

___
<a id="merge"></a>

###  merge

▸ **merge**(pTxs: *[TransactionFields](../interfaces/transactionfields.md)[]*): `void`

*Defined in [model.tx.ts:23](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L23)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pTxs | [TransactionFields](../interfaces/transactionfields.md)[] |

**Returns:** `void`

___

