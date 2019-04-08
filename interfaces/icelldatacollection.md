[bcvm](../README.md) > [ICellDataCollection](../interfaces/icelldatacollection.md)

# Interface: ICellDataCollection

## Hierarchy

 [ICellCollection](icellcollection.md)<[ICellTxChain](icelltxchain.md)>

**↳ ICellDataCollection**

## Implemented by

* [CellDataColl](../classes/celldatacoll.md)

## Index

### Methods

* [deletedCells](icelldatacollection.md#deletedcells)
* [filter](icelldatacollection.md#filter)
* [getCellById](icelldatacollection.md#getcellbyid)
* [getCellByRC](icelldatacollection.md#getcellbyrc)
* [getCells](icelldatacollection.md#getcells)
* [getCellsByColumnKey](icelldatacollection.md#getcellsbycolumnkey)
* [getCellsByRowKey](icelldatacollection.md#getcellsbyrowkey)
* [insertedCells](icelldatacollection.md#insertedcells)
* [modifiedCells](icelldatacollection.md#modifiedcells)

---

## Methods

<a id="deletedcells"></a>

###  deletedCells

▸ **deletedCells**(endTxId: *`number`*, startTxId: *`number`*): [ICellTxChain](icelltxchain.md)[]

*Defined in [model.cell.ts:148](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L148)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): [ICellTxChain](icelltxchain.md)[]

*Inherited from [ICellCollection](icellcollection.md).[filter](icellcollection.md#filter)*

*Defined in [model.cell.ts:84](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L84)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="getcellbyid"></a>

###  getCellById

▸ **getCellById**(cellId: *`number`*): [ICellTxChain](icelltxchain.md)

*Inherited from [ICellCollection](icellcollection.md).[getCellById](icellcollection.md#getcellbyid)*

*Defined in [model.cell.ts:77](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L77)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)

___
<a id="getcellbyrc"></a>

###  getCellByRC

▸ **getCellByRC**(rowKey: *`number`*, columnKey: *`number`*): [ICellTxChain](icelltxchain.md)

*Inherited from [ICellCollection](icellcollection.md).[getCellByRC](icellcollection.md#getcellbyrc)*

*Defined in [model.cell.ts:82](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L82)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |
| columnKey | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(): [ICellTxChain](icelltxchain.md)[]

*Inherited from [ICellCollection](icellcollection.md).[getCells](icellcollection.md#getcells)*

*Defined in [model.cell.ts:78](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L78)*

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="getcellsbycolumnkey"></a>

###  getCellsByColumnKey

▸ **getCellsByColumnKey**(columnKey: *`number`*): [ICellTxChain](icelltxchain.md)[]

*Inherited from [ICellCollection](icellcollection.md).[getCellsByColumnKey](icellcollection.md#getcellsbycolumnkey)*

*Defined in [model.cell.ts:81](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L81)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnKey | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="getcellsbyrowkey"></a>

###  getCellsByRowKey

▸ **getCellsByRowKey**(rowKey: *`number`*): [ICellTxChain](icelltxchain.md)[]

*Inherited from [ICellCollection](icellcollection.md).[getCellsByRowKey](icellcollection.md#getcellsbyrowkey)*

*Defined in [model.cell.ts:80](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L80)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="insertedcells"></a>

###  insertedCells

▸ **insertedCells**(endTxId: *`number`*, startTxId: *`number`*): [ICellTxChain](icelltxchain.md)[]

*Defined in [model.cell.ts:149](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L149)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)[]

___
<a id="modifiedcells"></a>

###  modifiedCells

▸ **modifiedCells**(endTxId: *`number`*, startTxId: *`number`*): [ICellTxChain](icelltxchain.md)[]

*Defined in [model.cell.ts:150](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L150)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| endTxId | `number` |
| startTxId | `number` |

**Returns:** [ICellTxChain](icelltxchain.md)[]

___

