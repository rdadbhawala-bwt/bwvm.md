[bcvm](../README.md) > [GridAllData](../classes/gridalldata.md)

# Class: GridAllData

## Hierarchy

**GridAllData**

## Implements

* [IGridAllData](../interfaces/igridalldata.md)

## Index

### Properties

* [cells](gridalldata.md#cells)
* [columns](gridalldata.md#columns)
* [formulaMap](gridalldata.md#formulamap)
* [grid](gridalldata.md#grid)
* [gridInfo](gridalldata.md#gridinfo)
* [rows](gridalldata.md#rows)
* [txs](gridalldata.md#txs)

### Methods

* [getAllTxIds](gridalldata.md#getalltxids)
* [getGridChanges](gridalldata.md#getgridchanges)
* [getGridTx](gridalldata.md#getgridtx)
* [getLatestTxId](gridalldata.md#getlatesttxid)
* [getTxIdsByDateRange](gridalldata.md#gettxidsbydaterange)
* [mergeData](gridalldata.md#mergedata)
* [mergeGrid](gridalldata.md#mergegrid)
* [mergeGridInfo](gridalldata.md#mergegridinfo)

---

## Properties

<a id="cells"></a>

###  cells

**● cells**: *[CellDataColl](celldatacoll.md)* =  new CellDataColl([])

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[cells](../interfaces/igridalldata.md#cells)*

*Defined in [model.grid.ts:134](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L134)*

___
<a id="columns"></a>

###  columns

**● columns**: *[ColumnDataColl](columndatacoll.md)* =  new ColumnDataColl([])

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[columns](../interfaces/igridalldata.md#columns)*

*Defined in [model.grid.ts:132](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L132)*

___
<a id="formulamap"></a>

###  formulaMap

**● formulaMap**: *[FormulaMap](formulamap.md)* =  new FormulaMap()

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[formulaMap](../interfaces/igridalldata.md#formulamap)*

*Defined in [model.grid.ts:136](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L136)*

___
<a id="grid"></a>

###  grid

**● grid**: *[Grid](../interfaces/grid.md)*

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[grid](../interfaces/igridalldata.md#grid)*

*Defined in [model.grid.ts:138](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L138)*

___
<a id="gridinfo"></a>

###  gridInfo

**● gridInfo**: *[GridInfo](../interfaces/gridinfo.md)*

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[gridInfo](../interfaces/igridalldata.md#gridinfo)*

*Defined in [model.grid.ts:137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L137)*

___
<a id="rows"></a>

###  rows

**● rows**: *[RowDataColl](rowdatacoll.md)* =  new RowDataColl([])

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[rows](../interfaces/igridalldata.md#rows)*

*Defined in [model.grid.ts:133](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L133)*

___
<a id="txs"></a>

###  txs

**● txs**: *[TxDataColl](txdatacoll.md)* =  new TxDataColl()

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[txs](../interfaces/igridalldata.md#txs)*

*Defined in [model.grid.ts:135](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L135)*

___

## Methods

<a id="getalltxids"></a>

###  getAllTxIds

▸ **getAllTxIds**(): `number`[]

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[getAllTxIds](../interfaces/igridalldata.md#getalltxids)*

*Defined in [model.grid.ts:146](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L146)*

**Returns:** `number`[]

___
<a id="getgridchanges"></a>

###  getGridChanges

▸ **getGridChanges**(startTxId: *`number`*, endTxId: *`number`*): [IGridTxDelta](../interfaces/igridtxdelta.md)

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[getGridChanges](../interfaces/igridalldata.md#getgridchanges)*

*Defined in [model.grid.ts:143](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L143)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| startTxId | `number` |
| endTxId | `number` |

**Returns:** [IGridTxDelta](../interfaces/igridtxdelta.md)

___
<a id="getgridtx"></a>

###  getGridTx

▸ **getGridTx**(txId: *`number`*): [IGridTxDelta](../interfaces/igridtxdelta.md)

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[getGridTx](../interfaces/igridalldata.md#getgridtx)*

*Defined in [model.grid.ts:140](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L140)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |

**Returns:** [IGridTxDelta](../interfaces/igridtxdelta.md)

___
<a id="getlatesttxid"></a>

###  getLatestTxId

▸ **getLatestTxId**(): `number`

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[getLatestTxId](../interfaces/igridalldata.md#getlatesttxid)*

*Defined in [model.grid.ts:153](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L153)*

**Returns:** `number`

___
<a id="gettxidsbydaterange"></a>

###  getTxIdsByDateRange

▸ **getTxIdsByDateRange**(from: *`Date`*, to: *`Date`*): `number`[]

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[getTxIdsByDateRange](../interfaces/igridalldata.md#gettxidsbydaterange)*

*Defined in [model.grid.ts:150](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L150)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| from | `Date` |
| to | `Date` |

**Returns:** `number`[]

___
<a id="mergedata"></a>

###  mergeData

▸ **mergeData**(pTxs: *[TransactionFields](../interfaces/transactionfields.md)[]*, pCols: *[ColumnFields](../interfaces/columnfields.md)[]*, pRows: *[RowFields](../interfaces/rowfields.md)[]*, pCells: *[ICellChainFields](../interfaces/icellchainfields.md)[]*, pFormulas: *[IFormulaValueFields](../interfaces/iformulavaluefields.md)[]*): `void`

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[mergeData](../interfaces/igridalldata.md#mergedata)*

*Defined in [model.grid.ts:122](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L122)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pTxs | [TransactionFields](../interfaces/transactionfields.md)[] |
| pCols | [ColumnFields](../interfaces/columnfields.md)[] |
| pRows | [RowFields](../interfaces/rowfields.md)[] |
| pCells | [ICellChainFields](../interfaces/icellchainfields.md)[] |
| pFormulas | [IFormulaValueFields](../interfaces/iformulavaluefields.md)[] |

**Returns:** `void`

___
<a id="mergegrid"></a>

###  mergeGrid

▸ **mergeGrid**(pGrid: *[Grid](../interfaces/grid.md)*): `void`

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[mergeGrid](../interfaces/igridalldata.md#mergegrid)*

*Defined in [model.grid.ts:114](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L114)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pGrid | [Grid](../interfaces/grid.md) |

**Returns:** `void`

___
<a id="mergegridinfo"></a>

###  mergeGridInfo

▸ **mergeGridInfo**(info: *[GridInfo](../interfaces/gridinfo.md)*): `void`

*Implementation of [IGridAllData](../interfaces/igridalldata.md).[mergeGridInfo](../interfaces/igridalldata.md#mergegridinfo)*

*Defined in [model.grid.ts:118](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L118)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| info | [GridInfo](../interfaces/gridinfo.md) |

**Returns:** `void`

___

