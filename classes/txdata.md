[bcvm](../README.md) > [TxData](../classes/txdata.md)

# Class: TxData

## Hierarchy

**TxData**

## Implements

* [ITxData](../interfaces/itxdata.md)

## Index

### Constructors

* [constructor](txdata.md#constructor)

### Properties

* [txChain](txdata.md#txchain)

### Methods

* [getComment](txdata.md#getcomment)
* [getTxId](txdata.md#gettxid)
* [getTxTimeUTC](txdata.md#gettxtimeutc)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new TxData**(pTx: *[TransactionFields](../interfaces/transactionfields.md)*): [TxData](txdata.md)

*Defined in [model.tx.ts:86](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L86)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pTx | [TransactionFields](../interfaces/transactionfields.md) |

**Returns:** [TxData](txdata.md)

___

## Properties

<a id="txchain"></a>

###  txChain

**● txChain**: *[TransactionFields](../interfaces/transactionfields.md)*

*Defined in [model.tx.ts:86](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L86)*

___

## Methods

<a id="getcomment"></a>

###  getComment

▸ **getComment**(): `string`

*Implementation of [ITxData](../interfaces/itxdata.md).[getComment](../interfaces/itxdata.md#getcomment)*

*Defined in [model.tx.ts:97](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L97)*

**Returns:** `string`

___
<a id="gettxid"></a>

###  getTxId

▸ **getTxId**(): `number`

*Implementation of [ITxData](../interfaces/itxdata.md).[getTxId](../interfaces/itxdata.md#gettxid)*

*Defined in [model.tx.ts:91](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L91)*

**Returns:** `number`

___
<a id="gettxtimeutc"></a>

###  getTxTimeUTC

▸ **getTxTimeUTC**(): `Date`

*Implementation of [ITxData](../interfaces/itxdata.md).[getTxTimeUTC](../interfaces/itxdata.md#gettxtimeutc)*

*Defined in [model.tx.ts:94](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.tx.ts#L94)*

**Returns:** `Date`

___

