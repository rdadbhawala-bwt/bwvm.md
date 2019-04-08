[bcvm](../README.md) > [IGridTxEditor](../interfaces/igridtxeditor.md)

# Interface: IGridTxEditor

## Hierarchy

 [IGridChange](igridchange.md)<[ICellEditor](icelleditor.md), [IRowEditor](iroweditor.md), [IColumnEditor](icolumneditor.md)>

↳  [IRangeEditorGrid](irangeeditorgrid.md)

**↳ IGridTxEditor**

## Implemented by

* [GridTxEditor](../classes/gridtxeditor.md)

## Index

### Properties

* [cells](igridtxeditor.md#cells)
* [columns](igridtxeditor.md#columns)
* [rows](igridtxeditor.md#rows)

### Methods

* [createRangeByRC](igridtxeditor.md#createrangebyrc)
* [deleteColumn](igridtxeditor.md#deletecolumn)
* [deleteRow](igridtxeditor.md#deleterow)
* [deletedCells](igridtxeditor.md#deletedcells)
* [deletedColumns](igridtxeditor.md#deletedcolumns)
* [deletedRows](igridtxeditor.md#deletedrows)
* [getCellEditorRC](igridtxeditor.md#getcelleditorrc)
* [getCells](igridtxeditor.md#getcells)
* [getColumns](igridtxeditor.md#getcolumns)
* [getGrid](igridtxeditor.md#getgrid)
* [getGridId](igridtxeditor.md#getgridid)
* [getGridInfo](igridtxeditor.md#getgridinfo)
* [getLastRefreshTxId](igridtxeditor.md#getlastrefreshtxid)
* [getRows](igridtxeditor.md#getrows)
* [insertColumn](igridtxeditor.md#insertcolumn)
* [insertColumnAtEnd](igridtxeditor.md#insertcolumnatend)
* [insertColumnAtStart](igridtxeditor.md#insertcolumnatstart)
* [insertRow](igridtxeditor.md#insertrow)
* [insertRowAtEnd](igridtxeditor.md#insertrowatend)
* [insertRowAtStart](igridtxeditor.md#insertrowatstart)
* [insertedCells](igridtxeditor.md#insertedcells)
* [insertedColumns](igridtxeditor.md#insertedcolumns)
* [insertedRows](igridtxeditor.md#insertedrows)
* [isDirty](igridtxeditor.md#isdirty)
* [isModified](igridtxeditor.md#ismodified)
* [isNew](igridtxeditor.md#isnew)
* [mergeGrid](igridtxeditor.md#mergegrid)
* [modifiedCells](igridtxeditor.md#modifiedcells)
* [setDirty](igridtxeditor.md#setdirty)
* [skuCopy](igridtxeditor.md#skucopy)

---

## Properties

<a id="cells"></a>

###  cells

**● cells**: *[ICellEditorCollection](icelleditorcollection.md)*

*Inherited from [IRange](irange.md).[cells](irange.md#cells)*

*Defined in [model.range.ts:16](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L16)*

___
<a id="columns"></a>

###  columns

**● columns**: *[IColumnEditorCollection](icolumneditorcollection.md)*

*Inherited from [IRange](irange.md).[columns](irange.md#columns)*

*Defined in [model.range.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L15)*

___
<a id="rows"></a>

###  rows

**● rows**: *[IRowEditorCollection](iroweditorcollection.md)*

*Inherited from [IRangeRow](irangerow.md).[rows](irangerow.md#rows)*

*Defined in [model.range.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L7)*

___

## Methods

<a id="createrangebyrc"></a>

###  createRangeByRC

▸ **createRangeByRC**(filterRows: *`function`*, filterCols: *`function`*): [IRangeEditorSet](irangeeditorset.md)

*Inherited from [IRangeEditor](irangeeditor.md).[createRangeByRC](irangeeditor.md#createrangebyrc)*

*Defined in [model.range.ts:26](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L26)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterRows | `function` |
| filterCols | `function` |

**Returns:** [IRangeEditorSet](irangeeditorset.md)

___
<a id="deletecolumn"></a>

###  deleteColumn

▸ **deleteColumn**(col: *[IColumnEditor](icolumneditor.md)*): `void`

*Defined in [model.grid.ts:92](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L92)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | [IColumnEditor](icolumneditor.md) |

**Returns:** `void`

___
<a id="deleterow"></a>

###  deleteRow

▸ **deleteRow**(row: *[IRowEditor](iroweditor.md)*): `void`

*Defined in [model.grid.ts:101](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L101)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | [IRowEditor](iroweditor.md) |

**Returns:** `void`

___
<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(): [ICellEditor](icelleditor.md)[]

*Inherited from [IGridChange](igridchange.md).[deletedCells](igridchange.md#deletedcells)*

*Defined in [model.grid.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L52)*

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="deletedcolumns"></a>

###  deletedColumns

▸ **deletedColumns**(): [IColumnEditor](icolumneditor.md)[]

*Inherited from [IGridChange](igridchange.md).[deletedColumns](igridchange.md#deletedcolumns)*

*Defined in [model.grid.ts:46](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L46)*

**Returns:** [IColumnEditor](icolumneditor.md)[]

___
<a id="deletedrows"></a>

###  deletedRows

▸ **deletedRows**(): [IRowEditor](iroweditor.md)[]

*Inherited from [IGridChange](igridchange.md).[deletedRows](igridchange.md#deletedrows)*

*Defined in [model.grid.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L49)*

**Returns:** [IRowEditor](iroweditor.md)[]

___
<a id="getcelleditorrc"></a>

###  getCellEditorRC

▸ **getCellEditorRC**(rowKey: *`number`*, columnKey: *`number`*): [ICellEditor](icelleditor.md)

*Defined in [model.grid.ts:110](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L110)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |
| columnKey | `number` |

**Returns:** [ICellEditor](icelleditor.md)

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(): [ICellEditor](icelleditor.md)[]

*Defined in [model.grid.ts:82](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L82)*

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): [IColumnEditor](icolumneditor.md)[]

*Defined in [model.grid.ts:93](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L93)*

**Returns:** [IColumnEditor](icolumneditor.md)[]

___
<a id="getgrid"></a>

###  getGrid

▸ **getGrid**(): [Grid](grid.md)

*Defined in [model.grid.ts:85](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L85)*

**Returns:** [Grid](grid.md)

___
<a id="getgridid"></a>

###  getGridId

▸ **getGridId**(): `number`

*Defined in [model.grid.ts:83](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L83)*

**Returns:** `number`

___
<a id="getgridinfo"></a>

###  getGridInfo

▸ **getGridInfo**(): [GridInfo](gridinfo.md)

*Defined in [model.grid.ts:84](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L84)*

**Returns:** [GridInfo](gridinfo.md)

___
<a id="getlastrefreshtxid"></a>

###  getLastRefreshTxId

▸ **getLastRefreshTxId**(): `number`

*Defined in [model.grid.ts:108](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L108)*

**Returns:** `number`

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): [IRowEditor](iroweditor.md)[]

*Defined in [model.grid.ts:102](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L102)*

**Returns:** [IRowEditor](iroweditor.md)[]

___
<a id="insertcolumn"></a>

###  insertColumn

▸ **insertColumn**(newColumnName: *`string`*, prevColumn: *[IColumnEditor](icolumneditor.md)*): [IColumnEditor](icolumneditor.md)

*Defined in [model.grid.ts:91](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L91)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |
| prevColumn | [IColumnEditor](icolumneditor.md) |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="insertcolumnatend"></a>

###  insertColumnAtEnd

▸ **insertColumnAtEnd**(newColumnName: *`string`*): [IColumnEditor](icolumneditor.md)

*Defined in [model.grid.ts:90](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L90)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="insertcolumnatstart"></a>

###  insertColumnAtStart

▸ **insertColumnAtStart**(newColumnName: *`string`*): [IColumnEditor](icolumneditor.md)

*Defined in [model.grid.ts:89](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L89)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** [IColumnEditor](icolumneditor.md)

___
<a id="insertrow"></a>

###  insertRow

▸ **insertRow**(rowName: *`string`*, prevRow: *[IRowEditor](iroweditor.md)*): [IRowEditor](iroweditor.md)

*Defined in [model.grid.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |
| prevRow | [IRowEditor](iroweditor.md) |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="insertrowatend"></a>

###  insertRowAtEnd

▸ **insertRowAtEnd**(rowName: *`string`*): [IRowEditor](iroweditor.md)

*Defined in [model.grid.ts:99](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L99)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="insertrowatstart"></a>

###  insertRowAtStart

▸ **insertRowAtStart**(rowName: *`string`*): [IRowEditor](iroweditor.md)

*Defined in [model.grid.ts:98](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L98)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** [IRowEditor](iroweditor.md)

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(): [ICellEditor](icelleditor.md)[]

*Inherited from [IGridChange](igridchange.md).[insertedCells](igridchange.md#insertedcells)*

*Defined in [model.grid.ts:53](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L53)*

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="insertedcolumns"></a>

###  insertedColumns

▸ **insertedColumns**(): [IColumnEditor](icolumneditor.md)[]

*Inherited from [IGridChange](igridchange.md).[insertedColumns](igridchange.md#insertedcolumns)*

*Defined in [model.grid.ts:47](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L47)*

**Returns:** [IColumnEditor](icolumneditor.md)[]

___
<a id="insertedrows"></a>

###  insertedRows

▸ **insertedRows**(): [IRowEditor](iroweditor.md)[]

*Inherited from [IGridChange](igridchange.md).[insertedRows](igridchange.md#insertedrows)*

*Defined in [model.grid.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L50)*

**Returns:** [IRowEditor](iroweditor.md)[]

___
<a id="isdirty"></a>

###  isDirty

▸ **isDirty**(): `boolean`

*Defined in [model.grid.ts:105](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L105)*

**Returns:** `boolean`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Inherited from [IRangeEditor](irangeeditor.md).[isModified](irangeeditor.md#ismodified)*

*Defined in [model.range.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L25)*

**Returns:** `boolean`

___
<a id="isnew"></a>

###  isNew

▸ **isNew**(): `boolean`

*Defined in [model.grid.ts:104](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L104)*

**Returns:** `boolean`

___
<a id="mergegrid"></a>

###  mergeGrid

▸ **mergeGrid**(newGridObj: *[Grid](grid.md)*): `void`

*Defined in [model.grid.ts:88](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L88)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newGridObj | [Grid](grid.md) |

**Returns:** `void`

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(): [ICellEditor](icelleditor.md)[]

*Inherited from [IGridChange](igridchange.md).[modifiedCells](igridchange.md#modifiedcells)*

*Defined in [model.grid.ts:54](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L54)*

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="setdirty"></a>

###  setDirty

▸ **setDirty**(): `void`

*Defined in [model.grid.ts:106](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L106)*

**Returns:** `void`

___
<a id="skucopy"></a>

###  skuCopy

▸ **skuCopy**(src: *[IRangeEditorSet](irangeeditorset.md)*, dst: *[IRowEditor](iroweditor.md)*): [IRangeEditorSet](irangeeditorset.md)

*Defined in [model.grid.ts:95](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L95)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| src | [IRangeEditorSet](irangeeditorset.md) |
| dst | [IRowEditor](iroweditor.md) |

**Returns:** [IRangeEditorSet](irangeeditorset.md)

___

