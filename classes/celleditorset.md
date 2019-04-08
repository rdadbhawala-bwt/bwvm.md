[bcvm](../README.md) > [CellEditorSet](../classes/celleditorset.md)

# Class: CellEditorSet

## Hierarchy

 [CellCollBase](cellcollbase.md)<`m.ICellEditor`>

**↳ CellEditorSet**

↳  [CellEditorColl](celleditorcoll.md)

## Implements

* [ICellCollection](../interfaces/icellcollection.md)<`m.ICellEditor`>
* [ICellEditorSet](../interfaces/icelleditorset.md)

## Index

### Constructors

* [constructor](celleditorset.md#constructor)

### Properties

* [cells](celleditorset.md#cells)
* [fm](celleditorset.md#fm)
* [mapCllId](celleditorset.md#mapcllid)
* [mapCol](celleditorset.md#mapcol)
* [mapRow](celleditorset.md#maprow)

### Methods

* [addCellToMaps](celleditorset.md#addcelltomaps)
* [filter](celleditorset.md#filter)
* [getCellById](celleditorset.md#getcellbyid)
* [getCellByRC](celleditorset.md#getcellbyrc)
* [getCells](celleditorset.md#getcells)
* [getCellsByColumnKey](celleditorset.md#getcellsbycolumnkey)
* [getCellsByRowKey](celleditorset.md#getcellsbyrowkey)
* [getFormulaMap](celleditorset.md#getformulamap)
* [isModified](celleditorset.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new CellEditorSet**(les: *`m.ICellEditor`[]*, fmap: *`m.FormulaMap`*): [CellEditorSet](celleditorset.md)

*Overrides [CellCollBase](cellcollbase.md).[constructor](cellcollbase.md#constructor)*

*Defined in [editor.cell.ts:5](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L5)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| les | `m.ICellEditor`[] |
| fmap | `m.FormulaMap` |

**Returns:** [CellEditorSet](celleditorset.md)

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

*Implementation of [ICellEditorSet](../interfaces/icelleditorset.md).[getCellById](../interfaces/icelleditorset.md#getcellbyid)*

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

*Implementation of [ICellEditorSet](../interfaces/icelleditorset.md).[getCellByRC](../interfaces/icelleditorset.md#getcellbyrc)*

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

*Implementation of [ICellEditorSet](../interfaces/icelleditorset.md).[getCells](../interfaces/icelleditorset.md#getcells)*

*Inherited from [CellCollBase](cellcollbase.md).[getCells](cellcollbase.md#getcells)*

*Defined in [model.cell.ts:122](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L122)*

**Returns:** `m.ICellEditor`[]

___
<a id="getcellsbycolumnkey"></a>

###  getCellsByColumnKey

▸ **getCellsByColumnKey**(columnKey: *`number`*): `m.ICellEditor`[]

*Implementation of [ICellEditorSet](../interfaces/icelleditorset.md).[getCellsByColumnKey](../interfaces/icelleditorset.md#getcellsbycolumnkey)*

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

*Implementation of [ICellEditorSet](../interfaces/icelleditorset.md).[getCellsByRowKey](../interfaces/icelleditorset.md#getcellsbyrowkey)*

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

*Implementation of [ICellEditorSet](../interfaces/icelleditorset.md).[getFormulaMap](../interfaces/icelleditorset.md#getformulamap)*

*Defined in [editor.cell.ts:17](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L17)*

**Returns:** `m.FormulaMap`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [ICellEditorSet](../interfaces/icelleditorset.md).[isModified](../interfaces/icelleditorset.md#ismodified)*

*Defined in [editor.cell.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L13)*

**Returns:** `boolean`

___

