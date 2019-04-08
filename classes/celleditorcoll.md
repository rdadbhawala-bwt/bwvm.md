[bcvm](../README.md) > [CellEditorColl](../classes/celleditorcoll.md)

# Class: CellEditorColl

## Hierarchy

↳  [CellEditorSet](celleditorset.md)

**↳ CellEditorColl**

## Implements

* [ICellCollection](../interfaces/icellcollection.md)<`m.ICellEditor`>
* [ICellEditorSet](../interfaces/icelleditorset.md)
* [ICellEditorCollection](../interfaces/icelleditorcollection.md)

## Index

### Constructors

* [constructor](celleditorcoll.md#constructor)

### Properties

* [cells](celleditorcoll.md#cells)
* [fm](celleditorcoll.md#fm)
* [mapCllId](celleditorcoll.md#mapcllid)
* [mapCol](celleditorcoll.md#mapcol)
* [mapRow](celleditorcoll.md#maprow)

### Methods

* [addCellToMaps](celleditorcoll.md#addcelltomaps)
* [deleteCellsFor](celleditorcoll.md#deletecellsfor)
* [deleteCellsForColumn](celleditorcoll.md#deletecellsforcolumn)
* [deleteCellsForRow](celleditorcoll.md#deletecellsforrow)
* [deletedCells](celleditorcoll.md#deletedcells)
* [filter](celleditorcoll.md#filter)
* [getCellById](celleditorcoll.md#getcellbyid)
* [getCellByRC](celleditorcoll.md#getcellbyrc)
* [getCells](celleditorcoll.md#getcells)
* [getCellsByColumnKey](celleditorcoll.md#getcellsbycolumnkey)
* [getCellsByRowKey](celleditorcoll.md#getcellsbyrowkey)
* [getFormulaMap](celleditorcoll.md#getformulamap)
* [insertCellsFor](celleditorcoll.md#insertcellsfor)
* [insertCellsForColumn](celleditorcoll.md#insertcellsforcolumn)
* [insertCellsForRow](celleditorcoll.md#insertcellsforrow)
* [insertedCells](celleditorcoll.md#insertedcells)
* [isModified](celleditorcoll.md#ismodified)
* [modifiedCells](celleditorcoll.md#modifiedcells)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new CellEditorColl**(txId: *`number`*, pCells: *`m.ICellTxChain`[]*, rf: *`m.IRowEditorCollection`*, cf: *`m.IColumnEditorCollection`*, fmap: *`m.FormulaMap`*): [CellEditorColl](celleditorcoll.md)

*Overrides [CellEditorSet](celleditorset.md).[constructor](celleditorset.md#constructor)*

*Defined in [editor.cell.ts:22](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L22)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txId | `number` |
| pCells | `m.ICellTxChain`[] |
| rf | `m.IRowEditorCollection` |
| cf | `m.IColumnEditorCollection` |
| fmap | `m.FormulaMap` |

**Returns:** [CellEditorColl](celleditorcoll.md)

___

## Properties

<a id="cells"></a>

###  cells

**● cells**: *`m.ICellEditor`[]* =  []

*Inherited from [CellCollBase](cellcollbase.md).[cells](cellcollbase.md#cells)*

*Defined in [model.cell.ts:88](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L88)*

___
<a id="fm"></a>

### `<Protected>` fm

**● fm**: *`m.FormulaMap`*

*Inherited from [CellEditorSet](celleditorset.md).[fm](celleditorset.md#fm)*

*Defined in [editor.cell.ts:11](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L11)*

___
<a id="mapcllid"></a>

###  mapCllId

**● mapCllId**: *`Map`<`number`, `C`>* =  new Map<number, C>()

*Inherited from [CellCollBase](cellcollbase.md).[mapCllId](cellcollbase.md#mapcllid)*

*Defined in [model.cell.ts:89](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L89)*

___
<a id="mapcol"></a>

###  mapCol

**● mapCol**: *`Map`<`number`, `C`[]>* =  new Map<number, C[]>()

*Inherited from [CellCollBase](cellcollbase.md).[mapCol](cellcollbase.md#mapcol)*

*Defined in [model.cell.ts:91](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L91)*

___
<a id="maprow"></a>

###  mapRow

**● mapRow**: *`Map`<`number`, `C`[]>* =  new Map<number, C[]>()

*Inherited from [CellCollBase](cellcollbase.md).[mapRow](cellcollbase.md#maprow)*

*Defined in [model.cell.ts:90](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L90)*

___

## Methods

<a id="addcelltomaps"></a>

### `<Protected>` addCellToMaps

▸ **addCellToMaps**(v: *`m.ICellEditor`*): `void`

*Inherited from [CellCollBase](cellcollbase.md).[addCellToMaps](cellcollbase.md#addcelltomaps)*

*Defined in [model.cell.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| v | `m.ICellEditor` |

**Returns:** `void`

___
<a id="deletecellsfor"></a>

### `<Private>` deleteCellsFor

▸ **deleteCellsFor**(cell: *`m.ICellEditor`*, rccf: *`m.CellChangeFlag`*): `void`

*Defined in [editor.cell.ts:80](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L80)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cell | `m.ICellEditor` |
| rccf | `m.CellChangeFlag` |

**Returns:** `void`

___
<a id="deletecellsforcolumn"></a>

###  deleteCellsForColumn

▸ **deleteCellsForColumn**(col: *`m.IColumnEditor`*): `void`

*Defined in [editor.cell.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L50)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | `m.IColumnEditor` |

**Returns:** `void`

___
<a id="deletecellsforrow"></a>

###  deleteCellsForRow

▸ **deleteCellsForRow**(row: *`m.IRowEditor`*): `void`

*Defined in [editor.cell.ts:64](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L64)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | `m.IRowEditor` |

**Returns:** `void`

___
<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(): `m.ICellEditor`[]

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[deletedCells](../interfaces/icelleditorcollection.md#deletedcells)*

*Defined in [editor.cell.ts:34](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L34)*

**Returns:** `m.ICellEditor`[]

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `m.ICellEditor`[]

*Inherited from [CellCollBase](cellcollbase.md).[filter](cellcollbase.md#filter)*

*Defined in [model.cell.ts:140](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L140)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `m.ICellEditor`[]

___
<a id="getcellbyid"></a>

###  getCellById

▸ **getCellById**(cellId: *`number`*): `m.ICellEditor`

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[getCellById](../interfaces/icelleditorcollection.md#getcellbyid)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellById](cellcollbase.md#getcellbyid)*

*Defined in [model.cell.ts:119](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L119)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** `m.ICellEditor`

___
<a id="getcellbyrc"></a>

###  getCellByRC

▸ **getCellByRC**(rowKey: *`number`*, columnKey: *`number`*): `m.ICellEditor`

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[getCellByRC](../interfaces/icelleditorcollection.md#getcellbyrc)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellByRC](cellcollbase.md#getcellbyrc)*

*Defined in [model.cell.ts:131](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L131)*

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

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[getCells](../interfaces/icelleditorcollection.md#getcells)*

*Inherited from [CellCollBase](cellcollbase.md).[getCells](cellcollbase.md#getcells)*

*Defined in [model.cell.ts:122](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L122)*

**Returns:** `m.ICellEditor`[]

___
<a id="getcellsbycolumnkey"></a>

###  getCellsByColumnKey

▸ **getCellsByColumnKey**(columnKey: *`number`*): `m.ICellEditor`[]

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[getCellsByColumnKey](../interfaces/icelleditorcollection.md#getcellsbycolumnkey)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellsByColumnKey](cellcollbase.md#getcellsbycolumnkey)*

*Defined in [model.cell.ts:128](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L128)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnKey | `number` |

**Returns:** `m.ICellEditor`[]

___
<a id="getcellsbyrowkey"></a>

###  getCellsByRowKey

▸ **getCellsByRowKey**(rowKey: *`number`*): `m.ICellEditor`[]

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[getCellsByRowKey](../interfaces/icelleditorcollection.md#getcellsbyrowkey)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellsByRowKey](cellcollbase.md#getcellsbyrowkey)*

*Defined in [model.cell.ts:125](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L125)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |

**Returns:** `m.ICellEditor`[]

___
<a id="getformulamap"></a>

###  getFormulaMap

▸ **getFormulaMap**(): `m.FormulaMap`

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[getFormulaMap](../interfaces/icelleditorcollection.md#getformulamap)*

*Inherited from [CellEditorSet](celleditorset.md).[getFormulaMap](celleditorset.md#getformulamap)*

*Defined in [editor.cell.ts:17](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L17)*

**Returns:** `m.FormulaMap`

___
<a id="insertcellsfor"></a>

### `<Private>` insertCellsFor

▸ **insertCellsFor**(row: *`m.IRowEditor`*, col: *`m.IColumnEditor`*, rccf: *`m.CellChangeFlag`*): `void`

*Defined in [editor.cell.ts:72](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L72)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | `m.IRowEditor` |
| col | `m.IColumnEditor` |
| rccf | `m.CellChangeFlag` |

**Returns:** `void`

___
<a id="insertcellsforcolumn"></a>

###  insertCellsForColumn

▸ **insertCellsForColumn**(col: *`m.IColumnEditor`*, rows: *`m.IRowEditor`[]*): `m.ICellEditor`[]

*Defined in [editor.cell.ts:44](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L44)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| col | `m.IColumnEditor` |
| rows | `m.IRowEditor`[] |

**Returns:** `m.ICellEditor`[]

___
<a id="insertcellsforrow"></a>

###  insertCellsForRow

▸ **insertCellsForRow**(row: *`m.IRowEditor`*, cols: *`m.IColumnEditor`[]*): `m.ICellEditor`[]

*Defined in [editor.cell.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L58)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| row | `m.IRowEditor` |
| cols | `m.IColumnEditor`[] |

**Returns:** `m.ICellEditor`[]

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(): `m.ICellEditor`[]

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[insertedCells](../interfaces/icelleditorcollection.md#insertedcells)*

*Defined in [editor.cell.ts:37](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L37)*

**Returns:** `m.ICellEditor`[]

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[isModified](../interfaces/icelleditorcollection.md#ismodified)*

*Inherited from [CellEditorSet](celleditorset.md).[isModified](celleditorset.md#ismodified)*

*Defined in [editor.cell.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L13)*

**Returns:** `boolean`

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(): `m.ICellEditor`[]

*Implementation of [ICellEditorCollection](../interfaces/icelleditorcollection.md).[modifiedCells](../interfaces/icelleditorcollection.md#modifiedcells)*

*Defined in [editor.cell.ts:40](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L40)*

**Returns:** `m.ICellEditor`[]

___

