[bcvm](../README.md) > [ICellEditorCollection](../interfaces/icelleditorcollection.md)

# Interface: ICellEditorCollection

## Hierarchy

↳  [ICellEditorSet](icelleditorset.md)

**↳ ICellEditorCollection**

## Implemented by

* [CellEditorColl](../classes/celleditorcoll.md)

## Index

### Methods

* [deleteCellsForColumn](icelleditorcollection.md#deletecellsforcolumn)
* [deleteCellsForRow](icelleditorcollection.md#deletecellsforrow)
* [deletedCells](icelleditorcollection.md#deletedcells)
* [filter](icelleditorcollection.md#filter)
* [getCellById](icelleditorcollection.md#getcellbyid)
* [getCellByRC](icelleditorcollection.md#getcellbyrc)
* [getCells](icelleditorcollection.md#getcells)
* [getCellsByColumnKey](icelleditorcollection.md#getcellsbycolumnkey)
* [getCellsByRowKey](icelleditorcollection.md#getcellsbyrowkey)
* [getFormulaMap](icelleditorcollection.md#getformulamap)
* [insertCellsForColumn](icelleditorcollection.md#insertcellsforcolumn)
* [insertCellsForRow](icelleditorcollection.md#insertcellsforrow)
* [insertedCells](icelleditorcollection.md#insertedcells)
* [isModified](icelleditorcollection.md#ismodified)
* [modifiedCells](icelleditorcollection.md#modifiedcells)

---

## Methods

<a id="deletecellsforcolumn"></a>

###  deleteCellsForColumn

▸ **deleteCellsForColumn**(col: *[IColumnEditor](icolumneditor.md)*): `any`

*Defined in [model.cell.ts:195](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L195)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | [IColumnEditor](icolumneditor.md) |

**Returns:** `any`

___
<a id="deletecellsforrow"></a>

###  deleteCellsForRow

▸ **deleteCellsForRow**(row: *[IRowEditor](iroweditor.md)*): `any`

*Defined in [model.cell.ts:192](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L192)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | [IRowEditor](iroweditor.md) |

**Returns:** `any`

___
<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(): [ICellEditor](icelleditor.md)[]

*Defined in [model.cell.ts:187](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L187)*

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [ICellEditor](icelleditor.md)[]

*Inherited from [ICellCollection](icellcollection.md).[filter](icellcollection.md#filter)*

*Defined in [model.cell.ts:84](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L84)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="getcellbyid"></a>

###  getCellById

▸ **getCellById**(cellId: *`number`*): [ICellEditor](icelleditor.md)

*Inherited from [ICellCollection](icellcollection.md).[getCellById](icellcollection.md#getcellbyid)*

*Defined in [model.cell.ts:77](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L77)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** [ICellEditor](icelleditor.md)

___
<a id="getcellbyrc"></a>

###  getCellByRC

▸ **getCellByRC**(rowKey: *`number`*, columnKey: *`number`*): [ICellEditor](icelleditor.md)

*Inherited from [ICellCollection](icellcollection.md).[getCellByRC](icellcollection.md#getcellbyrc)*

*Defined in [model.cell.ts:82](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L82)*

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

*Inherited from [ICellCollection](icellcollection.md).[getCells](icellcollection.md#getcells)*

*Defined in [model.cell.ts:78](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L78)*

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="getcellsbycolumnkey"></a>

###  getCellsByColumnKey

▸ **getCellsByColumnKey**(columnKey: *`number`*): [ICellEditor](icelleditor.md)[]

*Inherited from [ICellCollection](icellcollection.md).[getCellsByColumnKey](icellcollection.md#getcellsbycolumnkey)*

*Defined in [model.cell.ts:81](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L81)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnKey | `number` |

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="getcellsbyrowkey"></a>

###  getCellsByRowKey

▸ **getCellsByRowKey**(rowKey: *`number`*): [ICellEditor](icelleditor.md)[]

*Inherited from [ICellCollection](icellcollection.md).[getCellsByRowKey](icellcollection.md#getcellsbyrowkey)*

*Defined in [model.cell.ts:80](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L80)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="getformulamap"></a>

###  getFormulaMap

▸ **getFormulaMap**(): [FormulaMap](../classes/formulamap.md)

*Inherited from [ICellEditorSet](icelleditorset.md).[getFormulaMap](icelleditorset.md#getformulamap)*

*Defined in [model.cell.ts:181](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L181)*

**Returns:** [FormulaMap](../classes/formulamap.md)

___
<a id="insertcellsforcolumn"></a>

###  insertCellsForColumn

▸ **insertCellsForColumn**(col: *[IColumnEditor](icolumneditor.md)*, rows: *[IRowEditor](iroweditor.md)[]*): [ICellEditor](icelleditor.md)[]

*Defined in [model.cell.ts:194](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L194)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | [IColumnEditor](icolumneditor.md) |
| rows | [IRowEditor](iroweditor.md)[] |

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="insertcellsforrow"></a>

###  insertCellsForRow

▸ **insertCellsForRow**(row: *[IRowEditor](iroweditor.md)*, cols: *[IColumnEditor](icolumneditor.md)[]*): [ICellEditor](icelleditor.md)[]

*Defined in [model.cell.ts:191](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L191)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | [IRowEditor](iroweditor.md) |
| cols | [IColumnEditor](icolumneditor.md)[] |

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(): [ICellEditor](icelleditor.md)[]

*Defined in [model.cell.ts:188](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L188)*

**Returns:** [ICellEditor](icelleditor.md)[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Inherited from [ICellEditorSet](icelleditorset.md).[isModified](icelleditorset.md#ismodified)*

*Defined in [model.cell.ts:180](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L180)*

**Returns:** `boolean`

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(): [ICellEditor](icelleditor.md)[]

*Defined in [model.cell.ts:189](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L189)*

**Returns:** [ICellEditor](icelleditor.md)[]

___

