[bcvm](../README.md) > [GridTxDelta](../classes/gridtxdelta.md)

# Class: GridTxDelta

## Hierarchy

**GridTxDelta**

## Implements

* [IGridTxDelta](../interfaces/igridtxdelta.md)

## Index

### Constructors

* [constructor](gridtxdelta.md#constructor)

### Properties

* [endTx](gridtxdelta.md#endtx)
* [gridAllData](gridtxdelta.md#gridalldata)
* [startTx](gridtxdelta.md#starttx)

### Methods

* [deletedCells](gridtxdelta.md#deletedcells)
* [deletedColumns](gridtxdelta.md#deletedcolumns)
* [deletedRows](gridtxdelta.md#deletedrows)
* [getCell](gridtxdelta.md#getcell)
* [getCellValue](gridtxdelta.md#getcellvalue)
* [getCells](gridtxdelta.md#getcells)
* [getColumns](gridtxdelta.md#getcolumns)
* [getEndTxId](gridtxdelta.md#getendtxid)
* [getFormulaMap](gridtxdelta.md#getformulamap)
* [getGridId](gridtxdelta.md#getgridid)
* [getGridInfo](gridtxdelta.md#getgridinfo)
* [getRows](gridtxdelta.md#getrows)
* [getStartTxId](gridtxdelta.md#getstarttxid)
* [insertedCells](gridtxdelta.md#insertedcells)
* [insertedColumns](gridtxdelta.md#insertedcolumns)
* [insertedRows](gridtxdelta.md#insertedrows)
* [modifiedCells](gridtxdelta.md#modifiedcells)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new GridTxDelta**(allData: *[IGridAllData](../interfaces/igridalldata.md)*, pEndTxId: *`number`*, pStartTxId?: *`number`*): [GridTxDelta](gridtxdelta.md)

*Defined in [model.grid.ts:161](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L161)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| allData | [IGridAllData](../interfaces/igridalldata.md) |
| pEndTxId | `number` |
| `Optional` pStartTxId | `number` |

**Returns:** [GridTxDelta](gridtxdelta.md)

___

## Properties

<a id="endtx"></a>

### `<Private>` endTx

**● endTx**: *[ITxData](../interfaces/itxdata.md)*

*Defined in [model.grid.ts:160](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L160)*

___
<a id="gridalldata"></a>

### `<Private>` gridAllData

**● gridAllData**: *[IGridAllData](../interfaces/igridalldata.md)*

*Defined in [model.grid.ts:159](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L159)*

___
<a id="starttx"></a>

### `<Private>` startTx

**● startTx**: *[ITxData](../interfaces/itxdata.md)*

*Defined in [model.grid.ts:161](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L161)*

___

## Methods

<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[deletedCells](../interfaces/igridtxdelta.md#deletedcells)*

*Defined in [model.grid.ts:243](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L243)*

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="deletedcolumns"></a>

###  deletedColumns

▸ **deletedColumns**(): [IColumnData](../interfaces/icolumndata.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[deletedColumns](../interfaces/igridtxdelta.md#deletedcolumns)*

*Defined in [model.grid.ts:211](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L211)*

**Returns:** [IColumnData](../interfaces/icolumndata.md)[]

___
<a id="deletedrows"></a>

###  deletedRows

▸ **deletedRows**(): [IRowData](../interfaces/irowdata.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[deletedRows](../interfaces/igridtxdelta.md#deletedrows)*

*Defined in [model.grid.ts:227](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L227)*

**Returns:** [IRowData](../interfaces/irowdata.md)[]

___
<a id="getcell"></a>

###  getCell

▸ **getCell**(cellId: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getCell](../interfaces/igridtxdelta.md#getcell)*

*Defined in [model.grid.ts:205](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L205)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)

___
<a id="getcellvalue"></a>

###  getCellValue

▸ **getCellValue**(cellId: *`number`*, txId: *`number`*): [ICellTxValue](../interfaces/icelltxvalue.md)

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getCellValue](../interfaces/igridtxdelta.md#getcellvalue)*

*Defined in [model.grid.ts:208](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L208)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |
| txId | `number` |

**Returns:** [ICellTxValue](../interfaces/icelltxvalue.md)

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getCells](../interfaces/igridtxdelta.md#getcells)*

*Defined in [model.grid.ts:202](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L202)*

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): [IColumnData](../interfaces/icolumndata.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getColumns](../interfaces/igridtxdelta.md#getcolumns)*

*Defined in [model.grid.ts:196](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L196)*

**Returns:** [IColumnData](../interfaces/icolumndata.md)[]

___
<a id="getendtxid"></a>

###  getEndTxId

▸ **getEndTxId**(): `number`

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getEndTxId](../interfaces/igridtxdelta.md#getendtxid)*

*Defined in [model.grid.ts:187](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L187)*

**Returns:** `number`

___
<a id="getformulamap"></a>

###  getFormulaMap

▸ **getFormulaMap**(): [FormulaMap](formulamap.md)

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getFormulaMap](../interfaces/igridtxdelta.md#getformulamap)*

*Defined in [model.grid.ts:259](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L259)*

**Returns:** [FormulaMap](formulamap.md)

___
<a id="getgridid"></a>

###  getGridId

▸ **getGridId**(): `number`

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getGridId](../interfaces/igridtxdelta.md#getgridid)*

*Defined in [model.grid.ts:190](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L190)*

**Returns:** `number`

___
<a id="getgridinfo"></a>

###  getGridInfo

▸ **getGridInfo**(): [GridInfo](../interfaces/gridinfo.md)

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getGridInfo](../interfaces/igridtxdelta.md#getgridinfo)*

*Defined in [model.grid.ts:193](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L193)*

**Returns:** [GridInfo](../interfaces/gridinfo.md)

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): [IRowData](../interfaces/irowdata.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getRows](../interfaces/igridtxdelta.md#getrows)*

*Defined in [model.grid.ts:199](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L199)*

**Returns:** [IRowData](../interfaces/irowdata.md)[]

___
<a id="getstarttxid"></a>

###  getStartTxId

▸ **getStartTxId**(): `number`

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[getStartTxId](../interfaces/igridtxdelta.md#getstarttxid)*

*Defined in [model.grid.ts:184](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L184)*

**Returns:** `number`

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[insertedCells](../interfaces/igridtxdelta.md#insertedcells)*

*Defined in [model.grid.ts:248](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L248)*

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="insertedcolumns"></a>

###  insertedColumns

▸ **insertedColumns**(): [IColumnData](../interfaces/icolumndata.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[insertedColumns](../interfaces/igridtxdelta.md#insertedcolumns)*

*Defined in [model.grid.ts:219](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L219)*

**Returns:** [IColumnData](../interfaces/icolumndata.md)[]

___
<a id="insertedrows"></a>

###  insertedRows

▸ **insertedRows**(): [IRowData](../interfaces/irowdata.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[insertedRows](../interfaces/igridtxdelta.md#insertedrows)*

*Defined in [model.grid.ts:235](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L235)*

**Returns:** [IRowData](../interfaces/irowdata.md)[]

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [IGridTxDelta](../interfaces/igridtxdelta.md).[modifiedCells](../interfaces/igridtxdelta.md#modifiedcells)*

*Defined in [model.grid.ts:253](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L253)*

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___

