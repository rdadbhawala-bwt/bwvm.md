[bcvm](../README.md) > [IGridChange](../interfaces/igridchange.md)

# Interface: IGridChange

## Type parameters
#### C :  [ICell](icell.md)
#### R :  [IRow](irow.md)
#### M :  [IColumn](icolumn.md)
## Hierarchy

**IGridChange**

↳  [IGridTxDelta](igridtxdelta.md)

↳  [IGridTxEditor](igridtxeditor.md)

## Index

### Methods

* [deletedCells](igridchange.md#deletedcells)
* [deletedColumns](igridchange.md#deletedcolumns)
* [deletedRows](igridchange.md#deletedrows)
* [insertedCells](igridchange.md#insertedcells)
* [insertedColumns](igridchange.md#insertedcolumns)
* [insertedRows](igridchange.md#insertedrows)
* [modifiedCells](igridchange.md#modifiedcells)

---

## Methods

<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(): `C`[]

*Defined in [model.grid.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L52)*

**Returns:** `C`[]

___
<a id="deletedcolumns"></a>

###  deletedColumns

▸ **deletedColumns**(): `M`[]

*Defined in [model.grid.ts:46](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L46)*

**Returns:** `M`[]

___
<a id="deletedrows"></a>

###  deletedRows

▸ **deletedRows**(): `R`[]

*Defined in [model.grid.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L49)*

**Returns:** `R`[]

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(): `C`[]

*Defined in [model.grid.ts:53](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L53)*

**Returns:** `C`[]

___
<a id="insertedcolumns"></a>

###  insertedColumns

▸ **insertedColumns**(): `M`[]

*Defined in [model.grid.ts:47](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L47)*

**Returns:** `M`[]

___
<a id="insertedrows"></a>

###  insertedRows

▸ **insertedRows**(): `R`[]

*Defined in [model.grid.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L50)*

**Returns:** `R`[]

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(): `C`[]

*Defined in [model.grid.ts:54](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L54)*

**Returns:** `C`[]

___

