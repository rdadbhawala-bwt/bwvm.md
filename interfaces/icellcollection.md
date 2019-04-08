[bcvm](../README.md) > [ICellCollection](../interfaces/icellcollection.md)

# Interface: ICellCollection

## Type parameters
#### C :  [ICell](icell.md)
## Hierarchy

**ICellCollection**

↳  [ICellDataCollection](icelldatacollection.md)

↳  [ICellEditorSet](icelleditorset.md)

## Implemented by

* [CellCollBase](../classes/cellcollbase.md)
* [CellDataColl](../classes/celldatacoll.md)
* [CellEditorColl](../classes/celleditorcoll.md)
* [CellEditorSet](../classes/celleditorset.md)

## Index

### Methods

* [filter](icellcollection.md#filter)
* [getCellById](icellcollection.md#getcellbyid)
* [getCellByRC](icellcollection.md#getcellbyrc)
* [getCells](icellcollection.md#getcells)
* [getCellsByColumnKey](icellcollection.md#getcellsbycolumnkey)
* [getCellsByRowKey](icellcollection.md#getcellsbyrowkey)

---

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `C`[]

*Defined in [model.cell.ts:84](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L84)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `C`[]

___
<a id="getcellbyid"></a>

###  getCellById

▸ **getCellById**(cellId: *`number`*): `C`

*Defined in [model.cell.ts:77](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L77)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cellId | `number` |

**Returns:** `C`

___
<a id="getcellbyrc"></a>

###  getCellByRC

▸ **getCellByRC**(rowKey: *`number`*, columnKey: *`number`*): `C`

*Defined in [model.cell.ts:82](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L82)*

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

*Defined in [model.cell.ts:78](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L78)*

**Returns:** `C`[]

___
<a id="getcellsbycolumnkey"></a>

###  getCellsByColumnKey

▸ **getCellsByColumnKey**(columnKey: *`number`*): `C`[]

*Defined in [model.cell.ts:81](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L81)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnKey | `number` |

**Returns:** `C`[]

___
<a id="getcellsbyrowkey"></a>

###  getCellsByRowKey

▸ **getCellsByRowKey**(rowKey: *`number`*): `C`[]

*Defined in [model.cell.ts:80](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L80)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rowKey | `number` |

**Returns:** `C`[]

___

