[bcvm](../README.md) > [IGridTxDelta](../interfaces/igridtxdelta.md)

# Interface: IGridTxDelta

## Hierarchy

 [IGridChange](igridchange.md)<[ICellTxChain](icelltxchain.md), [IRowData](irowdata.md), [IColumnData](icolumndata.md)>

**↳ IGridTxDelta**

## Implemented by

* [GridTxDelta](../classes/gridtxdelta.md)

## Index

### Methods

* [deletedCells](igridtxdelta.md#deletedcells)
* [deletedColumns](igridtxdelta.md#deletedcolumns)
* [deletedRows](igridtxdelta.md#deletedrows)
* [getCell](igridtxdelta.md#getcell)
* [getCellValue](igridtxdelta.md#getcellvalue)
* [getCells](igridtxdelta.md#getcells)
* [getColumns](igridtxdelta.md#getcolumns)
* [getEndTxId](igridtxdelta.md#getendtxid)
* [getFormulaMap](igridtxdelta.md#getformulamap)
* [getGridId](igridtxdelta.md#getgridid)
* [getGridInfo](igridtxdelta.md#getgridinfo)
* [getRows](igridtxdelta.md#getrows)
* [getStartTxId](igridtxdelta.md#getstarttxid)
* [insertedCells](igridtxdelta.md#insertedcells)
* [insertedColumns](igridtxdelta.md#insertedcolumns)
* [insertedRows](igridtxdelta.md#insertedrows)
* [modifiedCells](igridtxdelta.md#modifiedcells)

---

## Methods

<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(): [ICellTxChain](icelltxchain.md)[]

*Inherited from [IGridChange](igridchange.md).[deletedCells](igridchange.md#deletedcells)*

*Defined in [model.grid.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L52)*

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="deletedcolumns"></a>

###  deletedColumns

▸ **deletedColumns**(): [IColumnData](icolumndata.md)[]

*Inherited from [IGridChange](igridchange.md).[deletedColumns](igridchange.md#deletedcolumns)*

*Defined in [model.grid.ts:46](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L46)*

**Returns:** [IColumnData](icolumndata.md)[]

___
<a id="deletedrows"></a>

###  deletedRows

▸ **deletedRows**(): [IRowData](irowdata.md)[]

*Inherited from [IGridChange](igridchange.md).[deletedRows](igridchange.md#deletedrows)*

*Defined in [model.grid.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L49)*

**Returns:** [IRowData](irowdata.md)[]

___
<a id="getcell"></a>

###  getCell

▸ **getCell**(cellId: *`number`*): [ICellTxChain](icelltxchain.md)

*Defined in [model.grid.ts:72](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L72)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)

___
<a id="getcellvalue"></a>

###  getCellValue

▸ **getCellValue**(cellId: *`number`*, txId: *`number`*): [ICellTxValue](icelltxvalue.md)

*Defined in [model.grid.ts:73](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L73)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |
| txId | `number` |

**Returns:** [ICellTxValue](icelltxvalue.md)

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(): [ICellTxChain](icelltxchain.md)[]

*Defined in [model.grid.ts:71](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L71)*

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): [IColumnData](icolumndata.md)[]

*Defined in [model.grid.ts:68](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L68)*

**Returns:** [IColumnData](icolumndata.md)[]

___
<a id="getendtxid"></a>

###  getEndTxId

▸ **getEndTxId**(): `number`

*Defined in [model.grid.ts:62](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L62)*

**Returns:** `number`

___
<a id="getformulamap"></a>

###  getFormulaMap

▸ **getFormulaMap**(): [FormulaMap](../classes/formulamap.md)

*Defined in [model.grid.ts:75](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L75)*

**Returns:** [FormulaMap](../classes/formulamap.md)

___
<a id="getgridid"></a>

###  getGridId

▸ **getGridId**(): `number`

*Defined in [model.grid.ts:64](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L64)*

**Returns:** `number`

___
<a id="getgridinfo"></a>

###  getGridInfo

▸ **getGridInfo**(): [GridInfo](gridinfo.md)

*Defined in [model.grid.ts:65](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L65)*

**Returns:** [GridInfo](gridinfo.md)

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): [IRowData](irowdata.md)[]

*Defined in [model.grid.ts:69](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L69)*

**Returns:** [IRowData](irowdata.md)[]

___
<a id="getstarttxid"></a>

###  getStartTxId

▸ **getStartTxId**(): `number`

*Defined in [model.grid.ts:61](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L61)*

**Returns:** `number`

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(): [ICellTxChain](icelltxchain.md)[]

*Inherited from [IGridChange](igridchange.md).[insertedCells](igridchange.md#insertedcells)*

*Defined in [model.grid.ts:53](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L53)*

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="insertedcolumns"></a>

###  insertedColumns

▸ **insertedColumns**(): [IColumnData](icolumndata.md)[]

*Inherited from [IGridChange](igridchange.md).[insertedColumns](igridchange.md#insertedcolumns)*

*Defined in [model.grid.ts:47](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L47)*

**Returns:** [IColumnData](icolumndata.md)[]

___
<a id="insertedrows"></a>

###  insertedRows

▸ **insertedRows**(): [IRowData](irowdata.md)[]

*Inherited from [IGridChange](igridchange.md).[insertedRows](igridchange.md#insertedrows)*

*Defined in [model.grid.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L50)*

**Returns:** [IRowData](irowdata.md)[]

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(): [ICellTxChain](icelltxchain.md)[]

*Inherited from [IGridChange](igridchange.md).[modifiedCells](igridchange.md#modifiedcells)*

*Defined in [model.grid.ts:54](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L54)*

**Returns:** [ICellTxChain](icelltxchain.md)[]

___

