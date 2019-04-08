[bcvm](../README.md) > [ITxColl](../interfaces/itxcoll.md)

# Interface: ITxColl

## Hierarchy

**ITxColl**

## Implemented by

* [TxDataColl](../classes/txdatacoll.md)

## Index

### Methods

* [filter](itxcoll.md#filter)
* [getAllTxIds](itxcoll.md#getalltxids)
* [getPreviousTx](itxcoll.md#getprevioustx)
* [getPreviousTxId](itxcoll.md#getprevioustxid)
* [getTxById](itxcoll.md#gettxbyid)
* [getTxIdsByDateRange](itxcoll.md#gettxidsbydaterange)

---

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [ITxData](itxdata.md)[]

*Defined in [model.tx.ts:10](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L10)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [ITxData](itxdata.md)[]

___
<a id="getalltxids"></a>

###  getAllTxIds

▸ **getAllTxIds**(): `number`[]

*Defined in [model.tx.ts:6](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L6)*

**Returns:** `number`[]

___
<a id="getprevioustx"></a>

###  getPreviousTx

▸ **getPreviousTx**(txId: *`number`*): [ITxData](itxdata.md)

*Defined in [model.tx.ts:5](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L5)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ITxData](itxdata.md)

___
<a id="getprevioustxid"></a>

###  getPreviousTxId

▸ **getPreviousTxId**(txId: *`number`*): `number`

*Defined in [model.tx.ts:8](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L8)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** `number`

___
<a id="gettxbyid"></a>

###  getTxById

▸ **getTxById**(txId: *`number`*): [ITxData](itxdata.md)

*Defined in [model.tx.ts:4](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L4)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [ITxData](itxdata.md)

___
<a id="gettxidsbydaterange"></a>

###  getTxIdsByDateRange

▸ **getTxIdsByDateRange**(from: *`Date`*, to: *`Date`*): `number`[]

*Defined in [model.tx.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L7)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| from | `Date` |
| to | `Date` |

**Returns:** `number`[]

___

