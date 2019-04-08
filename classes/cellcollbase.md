[bcvm](../README.md) > [CellCollBase](../classes/cellcollbase.md)

# Class: CellCollBase

## Type parameters
#### C :  [ICell](../interfaces/icell.md)
## Hierarchy

**CellCollBase**

↳  [CellDataColl](celldatacoll.md)

↳  [CellEditorSet](celleditorset.md)

## Implements

* [ICellCollection](../interfaces/icellcollection.md)<`C`>

## Index

### Constructors

* [constructor](cellcollbase.md#constructor)

### Properties

* [cells](cellcollbase.md#cells)
* [mapCllId](cellcollbase.md#mapcllid)
* [mapCol](cellcollbase.md#mapcol)
* [mapRow](cellcollbase.md#maprow)

### Methods

* [addCellToMaps](cellcollbase.md#addcelltomaps)
* [filter](cellcollbase.md#filter)
* [getCellById](cellcollbase.md#getcellbyid)
* [getCellByRC](cellcollbase.md#getcellbyrc)
* [getCells](cellcollbase.md#getcells)
* [getCellsByColumnKey](cellcollbase.md#getcellsbycolumnkey)
* [getCellsByRowKey](cellcollbase.md#getcellsbyrowkey)
* [setupMapArray](cellcollbase.md#setupmaparray)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new CellCollBase**(ls: *`C`[]*): [CellCollBase](cellcollbase.md)

*Defined in [model.cell.ts:91](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L91)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| ls | `C`[] |

**Returns:** [CellCollBase](cellcollbase.md)

___

## Properties

<a id="cells"></a>

###  cells

**● cells**: *`C`[]* =  []

*Defined in [model.cell.ts:88](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L88)*

___
<a id="mapcllid"></a>

###  mapCllId

**● mapCllId**: *`Map`<`number`, `C`>* =  new Map<number, C>()

*Defined in [model.cell.ts:89](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L89)*

___
<a id="mapcol"></a>

###  mapCol

**● mapCol**: *`Map`<`number`, `C`[]>* =  new Map<number, C[]>()

*Defined in [model.cell.ts:91](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L91)*

___
<a id="maprow"></a>

###  mapRow

**● mapRow**: *`Map`<`number`, `C`[]>* =  new Map<number, C[]>()

*Defined in [model.cell.ts:90](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L90)*

___

## Methods

<a id="addcelltomaps"></a>

### `<Protected>` addCellToMaps

▸ **addCellToMaps**(v: *`C`*): `void`

*Defined in [model.cell.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| v | `C` |

**Returns:** `void`

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `C`[]

*Defined in [model.cell.ts:140](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L140)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `C`[]

___
<a id="getcellbyid"></a>

###  getCellById

▸ **getCellById**(cellId: *`number`*): `C`

*Implementation of [ICellCollection](../interfaces/icellcollection.md).[getCellById](../interfaces/icellcollection.md#getcellbyid)*

*Defined in [model.cell.ts:119](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L119)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** `C`

___
<a id="getcellbyrc"></a>

###  getCellByRC

▸ **getCellByRC**(rowKey: *`number`*, columnKey: *`number`*): `C`

*Implementation of [ICellCollection](../interfaces/icellcollection.md).[getCellByRC](../interfaces/icellcollection.md#getcellbyrc)*

*Defined in [model.cell.ts:131](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L131)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |
| columnKey | `number` |

**Returns:** `C`

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(): `C`[]

*Implementation of [ICellCollection](../interfaces/icellcollection.md).[getCells](../interfaces/icellcollection.md#getcells)*

*Defined in [model.cell.ts:122](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L122)*

**Returns:** `C`[]

___
<a id="getcellsbycolumnkey"></a>

###  getCellsByColumnKey

▸ **getCellsByColumnKey**(columnKey: *`number`*): `C`[]

*Implementation of [ICellCollection](../interfaces/icellcollection.md).[getCellsByColumnKey](../interfaces/icellcollection.md#getcellsbycolumnkey)*

*Defined in [model.cell.ts:128](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L128)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnKey | `number` |

**Returns:** `C`[]

___
<a id="getcellsbyrowkey"></a>

###  getCellsByRowKey

▸ **getCellsByRowKey**(rowKey: *`number`*): `C`[]

*Implementation of [ICellCollection](../interfaces/icellcollection.md).[getCellsByRowKey](../interfaces/icellcollection.md#getcellsbyrowkey)*

*Defined in [model.cell.ts:125](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L125)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |

**Returns:** `C`[]

___
<a id="setupmaparray"></a>

### `<Private>` setupMapArray

▸ **setupMapArray**(map: *`Map`<`number`, `C`[]>*, key: *`number`*, value: *`C`*): `void`

*Defined in [model.cell.ts:108](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L108)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| map | `Map`<`number`, `C`[]> |
| key | `number` |
| value | `C` |

**Returns:** `void`

___

