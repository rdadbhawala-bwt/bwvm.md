[bcvm](../README.md) > [CellDataColl](../classes/celldatacoll.md)

# Class: CellDataColl

## Hierarchy

 [CellCollBase](cellcollbase.md)<[ICellTxChain](../interfaces/icelltxchain.md)>

**↳ CellDataColl**

## Implements

* [ICellCollection](../interfaces/icellcollection.md)<[ICellTxChain](../interfaces/icelltxchain.md)>
* [ICellDataCollection](../interfaces/icelldatacollection.md)

## Index

### Constructors

* [constructor](celldatacoll.md#constructor)

### Properties

* [cells](celldatacoll.md#cells)
* [mapCllId](celldatacoll.md#mapcllid)
* [mapCol](celldatacoll.md#mapcol)
* [mapRow](celldatacoll.md#maprow)

### Methods

* [addCellToMaps](celldatacoll.md#addcelltomaps)
* [deletedCells](celldatacoll.md#deletedcells)
* [filter](celldatacoll.md#filter)
* [getCellById](celldatacoll.md#getcellbyid)
* [getCellByRC](celldatacoll.md#getcellbyrc)
* [getCells](celldatacoll.md#getcells)
* [getCellsByColumnKey](celldatacoll.md#getcellsbycolumnkey)
* [getCellsByRowKey](celldatacoll.md#getcellsbyrowkey)
* [insertedCells](celldatacoll.md#insertedcells)
* [merge](celldatacoll.md#merge)
* [modifiedCells](celldatacoll.md#modifiedcells)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new CellDataColl**(ls: *[ICellTxChain](../interfaces/icelltxchain.md)[]*): [CellDataColl](celldatacoll.md)

*Inherited from [CellCollBase](cellcollbase.md).[constructor](cellcollbase.md#constructor)*

*Defined in [model.cell.ts:91](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L91)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| ls | [ICellTxChain](../interfaces/icelltxchain.md)[] |

**Returns:** [CellDataColl](celldatacoll.md)

___

## Properties

<a id="cells"></a>

###  cells

**● cells**: *[ICellTxChain](../interfaces/icelltxchain.md)[]* =  []

*Inherited from [CellCollBase](cellcollbase.md).[cells](cellcollbase.md#cells)*

*Defined in [model.cell.ts:88](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L88)*

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

▸ **addCellToMaps**(v: *[ICellTxChain](../interfaces/icelltxchain.md)*): `void`

*Inherited from [CellCollBase](cellcollbase.md).[addCellToMaps](cellcollbase.md#addcelltomaps)*

*Defined in [model.cell.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| v | [ICellTxChain](../interfaces/icelltxchain.md) |

**Returns:** `void`

___
<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(endTxId: *`number`*, startTxId: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[deletedCells](../interfaces/icelldatacollection.md#deletedcells)*

*Defined in [model.cell.ts:154](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L154)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Inherited from [CellCollBase](cellcollbase.md).[filter](cellcollbase.md#filter)*

*Defined in [model.cell.ts:140](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L140)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="getcellbyid"></a>

###  getCellById

▸ **getCellById**(cellId: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[getCellById](../interfaces/icelldatacollection.md#getcellbyid)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellById](cellcollbase.md#getcellbyid)*

*Defined in [model.cell.ts:119](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L119)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)

___
<a id="getcellbyrc"></a>

###  getCellByRC

▸ **getCellByRC**(rowKey: *`number`*, columnKey: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[getCellByRC](../interfaces/icelldatacollection.md#getcellbyrc)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellByRC](cellcollbase.md#getcellbyrc)*

*Defined in [model.cell.ts:131](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L131)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |
| columnKey | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[getCells](../interfaces/icelldatacollection.md#getcells)*

*Inherited from [CellCollBase](cellcollbase.md).[getCells](cellcollbase.md#getcells)*

*Defined in [model.cell.ts:122](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L122)*

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="getcellsbycolumnkey"></a>

###  getCellsByColumnKey

▸ **getCellsByColumnKey**(columnKey: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[getCellsByColumnKey](../interfaces/icelldatacollection.md#getcellsbycolumnkey)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellsByColumnKey](cellcollbase.md#getcellsbycolumnkey)*

*Defined in [model.cell.ts:128](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L128)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnKey | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="getcellsbyrowkey"></a>

###  getCellsByRowKey

▸ **getCellsByRowKey**(rowKey: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[getCellsByRowKey](../interfaces/icelldatacollection.md#getcellsbyrowkey)*

*Inherited from [CellCollBase](cellcollbase.md).[getCellsByRowKey](cellcollbase.md#getcellsbyrowkey)*

*Defined in [model.cell.ts:125](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L125)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(endTxId: *`number`*, startTxId: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[insertedCells](../interfaces/icelldatacollection.md#insertedcells)*

*Defined in [model.cell.ts:157](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L157)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___
<a id="merge"></a>

###  merge

▸ **merge**(pCells: *[ICellChainFields](../interfaces/icellchainfields.md)[]*): `void`

*Defined in [model.cell.ts:164](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L164)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCells | [ICellChainFields](../interfaces/icellchainfields.md)[] |

**Returns:** `void`

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(endTxId: *`number`*, startTxId: *`number`*): [ICellTxChain](../interfaces/icelltxchain.md)[]

*Implementation of [ICellDataCollection](../interfaces/icelldatacollection.md).[modifiedCells](../interfaces/icelldatacollection.md#modifiedcells)*

*Defined in [model.cell.ts:160](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L160)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** [ICellTxChain](../interfaces/icelltxchain.md)[]

___

