[bcvm](../README.md) > [ICellEditorSet](../interfaces/icelleditorset.md)

# Interface: ICellEditorSet

## Hierarchy

 [ICellCollection](icellcollection.md)<[ICellEditor](icelleditor.md)>

**↳ ICellEditorSet**

↳  [ICellEditorCollection](icelleditorcollection.md)

## Implemented by

* [CellEditorColl](../classes/celleditorcoll.md)
* [CellEditorSet](../classes/celleditorset.md)

## Index

### Methods

* [filter](icelleditorset.md#filter)
* [getCellById](icelleditorset.md#getcellbyid)
* [getCellByRC](icelleditorset.md#getcellbyrc)
* [getCells](icelleditorset.md#getcells)
* [getCellsByColumnKey](icelleditorset.md#getcellsbycolumnkey)
* [getCellsByRowKey](icelleditorset.md#getcellsbyrowkey)
* [getFormulaMap](icelleditorset.md#getformulamap)
* [isModified](icelleditorset.md#ismodified)

---

## Methods

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

*Defined in [model.cell.ts:181](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L181)*

**Returns:** [FormulaMap](../classes/formulamap.md)

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Defined in [model.cell.ts:180](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L180)*

**Returns:** `boolean`

___

