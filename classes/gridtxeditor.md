[bcvm](../README.md) > [GridTxEditor](../classes/gridtxeditor.md)

# Class: GridTxEditor

## Hierarchy

**GridTxEditor**

## Implements

* [IGridTxEditor](../interfaces/igridtxeditor.md)

## Index

### Constructors

* [constructor](gridtxeditor.md#constructor)

### Properties

* [cells](gridtxeditor.md#cells)
* [columns](gridtxeditor.md#columns)
* [dirty](gridtxeditor.md#dirty)
* [grid](gridtxeditor.md#grid)
* [gridInfo](gridtxeditor.md#gridinfo)
* [gridTx](gridtxeditor.md#gridtx)
* [rows](gridtxeditor.md#rows)

### Methods

* [checkColumnName](gridtxeditor.md#checkcolumnname)
* [createRangeByRC](gridtxeditor.md#createrangebyrc)
* [deleteColumn](gridtxeditor.md#deletecolumn)
* [deleteRow](gridtxeditor.md#deleterow)
* [deletedCells](gridtxeditor.md#deletedcells)
* [deletedColumns](gridtxeditor.md#deletedcolumns)
* [deletedRows](gridtxeditor.md#deletedrows)
* [getCellEditorRC](gridtxeditor.md#getcelleditorrc)
* [getCells](gridtxeditor.md#getcells)
* [getColumns](gridtxeditor.md#getcolumns)
* [getGrid](gridtxeditor.md#getgrid)
* [getGridId](gridtxeditor.md#getgridid)
* [getGridInfo](gridtxeditor.md#getgridinfo)
* [getLastRefreshTxId](gridtxeditor.md#getlastrefreshtxid)
* [getRows](gridtxeditor.md#getrows)
* [insertColumn](gridtxeditor.md#insertcolumn)
* [insertColumnAtEnd](gridtxeditor.md#insertcolumnatend)
* [insertColumnAtStart](gridtxeditor.md#insertcolumnatstart)
* [insertRow](gridtxeditor.md#insertrow)
* [insertRowAtEnd](gridtxeditor.md#insertrowatend)
* [insertRowAtStart](gridtxeditor.md#insertrowatstart)
* [insertedCells](gridtxeditor.md#insertedcells)
* [insertedColumns](gridtxeditor.md#insertedcolumns)
* [insertedRows](gridtxeditor.md#insertedrows)
* [isDirty](gridtxeditor.md#isdirty)
* [isModified](gridtxeditor.md#ismodified)
* [isNew](gridtxeditor.md#isnew)
* [mergeGrid](gridtxeditor.md#mergegrid)
* [modifiedCells](gridtxeditor.md#modifiedcells)
* [setDirty](gridtxeditor.md#setdirty)
* [skuCopy](gridtxeditor.md#skucopy)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new GridTxEditor**(g: *`m.IGridTxDelta`*, i?: *`m.Grid`*): [GridTxEditor](gridtxeditor.md)

*Defined in [editor.ts:17](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L17)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| g | `m.IGridTxDelta` |
| `Optional` i | `m.Grid` |

**Returns:** [GridTxEditor](gridtxeditor.md)

___

## Properties

<a id="cells"></a>

###  cells

**● cells**: *`m.ICellEditorCollection`*

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[cells](../interfaces/igridtxeditor.md#cells)*

*Defined in [editor.ts:16](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L16)*

___
<a id="columns"></a>

###  columns

**● columns**: *`m.IColumnEditorCollection`*

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[columns](../interfaces/igridtxeditor.md#columns)*

*Defined in [editor.ts:14](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L14)*

___
<a id="dirty"></a>

### `<Private>` dirty

**● dirty**: *`boolean`* = false

*Defined in [editor.ts:17](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L17)*

___
<a id="grid"></a>

### `<Private>` grid

**● grid**: *`m.Grid`*

*Defined in [editor.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L12)*

___
<a id="gridinfo"></a>

### `<Private>` gridInfo

**● gridInfo**: *`m.GridInfo`*

*Defined in [editor.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L13)*

___
<a id="gridtx"></a>

### `<Private>` gridTx

**● gridTx**: *`m.IGridTxDelta`*

*Defined in [editor.ts:11](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L11)*

___
<a id="rows"></a>

###  rows

**● rows**: *`m.IRowEditorCollection`*

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[rows](../interfaces/igridtxeditor.md#rows)*

*Defined in [editor.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L15)*

___

## Methods

<a id="checkcolumnname"></a>

###  checkColumnName

▸ **checkColumnName**(newColumnName: *`string`*): `void`

*Defined in [editor.ts:75](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L75)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** `void`

___
<a id="createrangebyrc"></a>

###  createRangeByRC

▸ **createRangeByRC**(filterRows: *`function`*, filterCols: *`function`*): `m.IRangeEditorSet`

*Defined in [editor.ts:190](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L190)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterRows | `function` |
| filterCols | `function` |

**Returns:** `m.IRangeEditorSet`

___
<a id="deletecolumn"></a>

###  deleteColumn

▸ **deleteColumn**(col: *`m.IColumnEditor`*): `void`

*Defined in [editor.ts:89](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L89)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | `m.IColumnEditor` |

**Returns:** `void`

___
<a id="deleterow"></a>

###  deleteRow

▸ **deleteRow**(row: *`m.IRowEditor`*): `void`

*Defined in [editor.ts:108](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L108)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | `m.IRowEditor` |

**Returns:** `void`

___
<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(): `m.ICellEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[deletedCells](../interfaces/igridtxeditor.md#deletedcells)*

*Defined in [editor.ts:174](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L174)*

**Returns:** `m.ICellEditor`[]

___
<a id="deletedcolumns"></a>

###  deletedColumns

▸ **deletedColumns**(): `m.IColumnEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[deletedColumns](../interfaces/igridtxeditor.md#deletedcolumns)*

*Defined in [editor.ts:156](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L156)*

**Returns:** `m.IColumnEditor`[]

___
<a id="deletedrows"></a>

###  deletedRows

▸ **deletedRows**(): `m.IRowEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[deletedRows](../interfaces/igridtxeditor.md#deletedrows)*

*Defined in [editor.ts:165](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L165)*

**Returns:** `m.IRowEditor`[]

___
<a id="getcelleditorrc"></a>

###  getCellEditorRC

▸ **getCellEditorRC**(rowKey: *`number`*, columnKey: *`number`*): `m.ICellEditor`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getCellEditorRC](../interfaces/igridtxeditor.md#getcelleditorrc)*

*Defined in [editor.ts:186](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L186)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |
| columnKey | `number` |

**Returns:** `m.ICellEditor`

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(): `m.ICellEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getCells](../interfaces/igridtxeditor.md#getcells)*

*Defined in [editor.ts:183](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L183)*

**Returns:** `m.ICellEditor`[]

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): `m.IColumnEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getColumns](../interfaces/igridtxeditor.md#getcolumns)*

*Defined in [editor.ts:162](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L162)*

**Returns:** `m.IColumnEditor`[]

___
<a id="getgrid"></a>

###  getGrid

▸ **getGrid**(): `m.Grid`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getGrid](../interfaces/igridtxeditor.md#getgrid)*

*Defined in [editor.ts:53](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L53)*

**Returns:** `m.Grid`

___
<a id="getgridid"></a>

###  getGridId

▸ **getGridId**(): `number`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getGridId](../interfaces/igridtxeditor.md#getgridid)*

*Defined in [editor.ts:45](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L45)*

**Returns:** `number`

___
<a id="getgridinfo"></a>

###  getGridInfo

▸ **getGridInfo**(): `m.GridInfo`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getGridInfo](../interfaces/igridtxeditor.md#getgridinfo)*

*Defined in [editor.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L49)*

**Returns:** `m.GridInfo`

___
<a id="getlastrefreshtxid"></a>

###  getLastRefreshTxId

▸ **getLastRefreshTxId**(): `number`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getLastRefreshTxId](../interfaces/igridtxeditor.md#getlastrefreshtxid)*

*Defined in [editor.ts:153](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L153)*

**Returns:** `number`

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(): `m.IRowEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[getRows](../interfaces/igridtxeditor.md#getrows)*

*Defined in [editor.ts:171](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L171)*

**Returns:** `m.IRowEditor`[]

___
<a id="insertcolumn"></a>

###  insertColumn

▸ **insertColumn**(newColumnName: *`string`*, prevColumn: *`m.IColumnEditor`*): `m.IColumnEditor`

*Defined in [editor.ts:69](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L69)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |
| prevColumn | `m.IColumnEditor` |

**Returns:** `m.IColumnEditor`

___
<a id="insertcolumnatend"></a>

###  insertColumnAtEnd

▸ **insertColumnAtEnd**(newColumnName: *`string`*): [IColumnEditor](../interfaces/icolumneditor.md)

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[insertColumnAtEnd](../interfaces/igridtxeditor.md#insertcolumnatend)*

*Defined in [editor.ts:63](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L63)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** [IColumnEditor](../interfaces/icolumneditor.md)

___
<a id="insertcolumnatstart"></a>

###  insertColumnAtStart

▸ **insertColumnAtStart**(newColumnName: *`string`*): [IColumnEditor](../interfaces/icolumneditor.md)

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[insertColumnAtStart](../interfaces/igridtxeditor.md#insertcolumnatstart)*

*Defined in [editor.ts:57](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L57)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newColumnName | `string` |

**Returns:** [IColumnEditor](../interfaces/icolumneditor.md)

___
<a id="insertrow"></a>

###  insertRow

▸ **insertRow**(rowName: *`string`*, prevRow: *`m.IRowEditor`*): `m.IRowEditor`

*Defined in [editor.ts:103](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L103)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |
| prevRow | `m.IRowEditor` |

**Returns:** `m.IRowEditor`

___
<a id="insertrowatend"></a>

###  insertRowAtEnd

▸ **insertRowAtEnd**(rowName: *`string`*): `m.IRowEditor`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[insertRowAtEnd](../interfaces/igridtxeditor.md#insertrowatend)*

*Defined in [editor.ts:98](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L98)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** `m.IRowEditor`

___
<a id="insertrowatstart"></a>

###  insertRowAtStart

▸ **insertRowAtStart**(rowName: *`string`*): `m.IRowEditor`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[insertRowAtStart](../interfaces/igridtxeditor.md#insertrowatstart)*

*Defined in [editor.ts:93](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L93)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowName | `string` |

**Returns:** `m.IRowEditor`

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(): `m.ICellEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[insertedCells](../interfaces/igridtxeditor.md#insertedcells)*

*Defined in [editor.ts:177](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L177)*

**Returns:** `m.ICellEditor`[]

___
<a id="insertedcolumns"></a>

###  insertedColumns

▸ **insertedColumns**(): `m.IColumnEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[insertedColumns](../interfaces/igridtxeditor.md#insertedcolumns)*

*Defined in [editor.ts:159](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L159)*

**Returns:** `m.IColumnEditor`[]

___
<a id="insertedrows"></a>

###  insertedRows

▸ **insertedRows**(): `m.IRowEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[insertedRows](../interfaces/igridtxeditor.md#insertedrows)*

*Defined in [editor.ts:168](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L168)*

**Returns:** `m.IRowEditor`[]

___
<a id="isdirty"></a>

###  isDirty

▸ **isDirty**(): `boolean`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[isDirty](../interfaces/igridtxeditor.md#isdirty)*

*Defined in [editor.ts:150](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L150)*

**Returns:** `boolean`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[isModified](../interfaces/igridtxeditor.md#ismodified)*

*Defined in [editor.ts:139](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L139)*

**Returns:** `boolean`

___
<a id="isnew"></a>

###  isNew

▸ **isNew**(): `boolean`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[isNew](../interfaces/igridtxeditor.md#isnew)*

*Defined in [editor.ts:144](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L144)*

**Returns:** `boolean`

___
<a id="mergegrid"></a>

###  mergeGrid

▸ **mergeGrid**(newGridObj: *`m.Grid`*): `void`

*Defined in [editor.ts:40](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L40)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| newGridObj | `m.Grid` |

**Returns:** `void`

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(): `m.ICellEditor`[]

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[modifiedCells](../interfaces/igridtxeditor.md#modifiedcells)*

*Defined in [editor.ts:180](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L180)*

**Returns:** `m.ICellEditor`[]

___
<a id="setdirty"></a>

###  setDirty

▸ **setDirty**(): `void`

*Implementation of [IGridTxEditor](../interfaces/igridtxeditor.md).[setDirty](../interfaces/igridtxeditor.md#setdirty)*

*Defined in [editor.ts:147](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L147)*

**Returns:** `void`

___
<a id="skucopy"></a>

###  skuCopy

▸ **skuCopy**(src: *`m.IRangeEditorSet`*, dst: *`m.IRowEditor`*): `m.IRangeEditorSet`

*Defined in [editor.ts:113](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.ts#L113)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| src | `m.IRangeEditorSet` |
| dst | `m.IRowEditor` |

**Returns:** `m.IRangeEditorSet`

___

