[bcvm](../README.md) > [IGridAllData](../interfaces/igridalldata.md)

# Interface: IGridAllData

## Hierarchy

**IGridAllData**

## Implemented by

* [GridAllData](../classes/gridalldata.md)

## Index

### Properties

* [cells](igridalldata.md#cells)
* [columns](igridalldata.md#columns)
* [formulaMap](igridalldata.md#formulamap)
* [grid](igridalldata.md#grid)
* [gridInfo](igridalldata.md#gridinfo)
* [rows](igridalldata.md#rows)
* [txs](igridalldata.md#txs)

### Methods

* [getAllTxIds](igridalldata.md#getalltxids)
* [getGridChanges](igridalldata.md#getgridchanges)
* [getGridTx](igridalldata.md#getgridtx)
* [getLatestTxId](igridalldata.md#getlatesttxid)
* [getTxIdsByDateRange](igridalldata.md#gettxidsbydaterange)
* [mergeData](igridalldata.md#mergedata)
* [mergeGrid](igridalldata.md#mergegrid)
* [mergeGridInfo](igridalldata.md#mergegridinfo)

---

## Properties

<a id="cells"></a>

###  cells

**● cells**: *[ICellDataCollection](icelldatacollection.md)*

*Defined in [model.grid.ts:26](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L26)*

___
<a id="columns"></a>

###  columns

**● columns**: *[IColumnDataCollection](icolumndatacollection.md)*

*Defined in [model.grid.ts:24](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L24)*

___
<a id="formulamap"></a>

###  formulaMap

**● formulaMap**: *[FormulaMap](../classes/formulamap.md)*

*Defined in [model.grid.ts:28](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L28)*

___
<a id="grid"></a>

###  grid

**● grid**: *[Grid](grid.md)*

*Defined in [model.grid.ts:31](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L31)*

___
<a id="gridinfo"></a>

###  gridInfo

**● gridInfo**: *[GridInfo](gridinfo.md)*

*Defined in [model.grid.ts:30](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L30)*

___
<a id="rows"></a>

###  rows

**● rows**: *[IRowDataCollection](irowdatacollection.md)*

*Defined in [model.grid.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L25)*

___
<a id="txs"></a>

###  txs

**● txs**: *[ITxColl](itxcoll.md)*

*Defined in [model.grid.ts:27](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L27)*

___

## Methods

<a id="getalltxids"></a>

###  getAllTxIds

▸ **getAllTxIds**(): `number`[]

*Defined in [model.grid.ts:33](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L33)*

**Returns:** `number`[]

___
<a id="getgridchanges"></a>

###  getGridChanges

▸ **getGridChanges**(startTxId: *`number`*, endTxId: *`number`*): [IGridTxDelta](igridtxdelta.md)

*Defined in [model.grid.ts:21](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L21)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| startTxId | `number` |
| endTxId | `number` |

**Returns:** [IGridTxDelta](igridtxdelta.md)

___
<a id="getgridtx"></a>

###  getGridTx

▸ **getGridTx**(txId: *`number`*): [IGridTxDelta](igridtxdelta.md)

*Defined in [model.grid.ts:20](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L20)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [IGridTxDelta](igridtxdelta.md)

___
<a id="getlatesttxid"></a>

###  getLatestTxId

▸ **getLatestTxId**(): `number`

*Defined in [model.grid.ts:35](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L35)*

**Returns:** `number`

___
<a id="gettxidsbydaterange"></a>

###  getTxIdsByDateRange

▸ **getTxIdsByDateRange**(from: *`Date`*, to: *`Date`*): `number`[]

*Defined in [model.grid.ts:34](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L34)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| from | `Date` |
| to | `Date` |

**Returns:** `number`[]

___
<a id="mergedata"></a>

###  mergeData

▸ **mergeData**(pTxs: *[TransactionFields](transactionfields.md)[]*, pCols: *[ColumnFields](columnfields.md)[]*, pRows: *[RowFields](rowfields.md)[]*, pCells: *[ICellChainFields](icellchainfields.md)[]*, pFormulas: *[IFormulaValueFields](iformulavaluefields.md)[]*): `any`

*Defined in [model.grid.ts:39](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L39)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pTxs | [TransactionFields](transactionfields.md)[] |
| pCols | [ColumnFields](columnfields.md)[] |
| pRows | [RowFields](rowfields.md)[] |
| pCells | [ICellChainFields](icellchainfields.md)[] |
| pFormulas | [IFormulaValueFields](iformulavaluefields.md)[] |

**Returns:** `any`

___
<a id="mergegrid"></a>

###  mergeGrid

▸ **mergeGrid**(pGrid: *[Grid](grid.md)*): `any`

*Defined in [model.grid.ts:38](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L38)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pGrid | [Grid](grid.md) |

**Returns:** `any`

___
<a id="mergegridinfo"></a>

###  mergeGridInfo

▸ **mergeGridInfo**(info: *[GridInfo](gridinfo.md)*): `any`

*Defined in [model.grid.ts:37](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L37)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| info | [GridInfo](gridinfo.md) |

**Returns:** `any`

___

