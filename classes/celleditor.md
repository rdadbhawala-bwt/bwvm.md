[bcvm](../README.md) > [CellEditor](../classes/celleditor.md)

# Class: CellEditor

## Hierarchy

**CellEditor**

## Implements

* [ICellEditor](../interfaces/icelleditor.md)

## Index

### Constructors

* [constructor](celleditor.md#constructor)

### Properties

* [active](celleditor.md#active)
* [cellId](celleditor.md#cellid)
* [cellStatus](celleditor.md#cellstatus)
* [cellValue](celleditor.md#cellvalue)
* [columnId](celleditor.md#columnid)
* [columnSequenceNo](celleditor.md#columnsequenceno)
* [formula](celleditor.md#formula)
* [formulaValue](celleditor.md#formulavalue)
* [rcChangeFlag](celleditor.md#rcchangeflag)
* [rowId](celleditor.md#rowid)
* [rowSequenceNo](celleditor.md#rowsequenceno)
* [stringValue](celleditor.md#stringvalue)

### Methods

* [getCellId](celleditor.md#getcellid)
* [getChangeFlag](celleditor.md#getchangeflag)
* [getColumnId](celleditor.md#getcolumnid)
* [getColumnKey](celleditor.md#getcolumnkey)
* [getProcessedFormulaValue](celleditor.md#getprocessedformulavalue)
* [getProcessedStringValue](celleditor.md#getprocessedstringvalue)
* [getRowId](celleditor.md#getrowid)
* [getRowKey](celleditor.md#getrowkey)
* [getStatus](celleditor.md#getstatus)
* [getValue](celleditor.md#getvalue)
* [isModified](celleditor.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new CellEditor**(v: *`m.ICellTxChain`*, txId: *`number`*, pRow: *`m.IRowEditor`*, pColumn: *`m.IColumnEditor`*, fm: *`m.FormulaMap`*, rccf: *`m.CellChangeFlag`*): [CellEditor](celleditor.md)

*Defined in [editor.cell.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L100)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| v | `m.ICellTxChain` |
| txId | `number` |
| pRow | `m.IRowEditor` |
| pColumn | `m.IColumnEditor` |
| fm | `m.FormulaMap` |
| rccf | `m.CellChangeFlag` |

**Returns:** [CellEditor](celleditor.md)

___

## Properties

<a id="active"></a>

###  active

**● active**: *`boolean`*

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[active](../interfaces/icelleditor.md#active)*

*Defined in [editor.cell.ts:129](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L129)*

___
<a id="cellid"></a>

### `<Private>` cellId

**● cellId**: *`number`*

*Defined in [editor.cell.ts:93](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L93)*

___
<a id="cellstatus"></a>

### `<Private>` cellStatus

**● cellStatus**: *`m.ICellStatus`*

*Defined in [editor.cell.ts:97](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L97)*

___
<a id="cellvalue"></a>

### `<Private>` cellValue

**● cellValue**: *`m.ICellTxValue`*

*Defined in [editor.cell.ts:96](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L96)*

___
<a id="columnid"></a>

### `<Private>` columnId

**● columnId**: *`number`*

*Defined in [editor.cell.ts:95](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L95)*

___
<a id="columnsequenceno"></a>

### `<Private>` columnSequenceNo

**● columnSequenceNo**: *`number`*

*Defined in [editor.cell.ts:99](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L99)*

___
<a id="formula"></a>

### `<Private>` formula

**● formula**: *`m.IFormula`*

*Defined in [editor.cell.ts:100](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L100)*

___
<a id="formulavalue"></a>

###  formulaValue

**● formulaValue**: *`string`*

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[formulaValue](../interfaces/icelleditor.md#formulavalue)*

*Defined in [editor.cell.ts:128](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L128)*

___
<a id="rcchangeflag"></a>

###  rcChangeFlag

**● rcChangeFlag**: *`m.CellChangeFlag`*

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[rcChangeFlag](../interfaces/icelleditor.md#rcchangeflag)*

*Defined in [editor.cell.ts:130](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L130)*

___
<a id="rowid"></a>

### `<Private>` rowId

**● rowId**: *`number`*

*Defined in [editor.cell.ts:94](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L94)*

___
<a id="rowsequenceno"></a>

### `<Private>` rowSequenceNo

**● rowSequenceNo**: *`number`*

*Defined in [editor.cell.ts:98](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L98)*

___
<a id="stringvalue"></a>

###  stringValue

**● stringValue**: *`string`*

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[stringValue](../interfaces/icelleditor.md#stringvalue)*

*Defined in [editor.cell.ts:127](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L127)*

___

## Methods

<a id="getcellid"></a>

###  getCellId

▸ **getCellId**(): `number`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getCellId](../interfaces/icelleditor.md#getcellid)*

*Defined in [editor.cell.ts:144](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L144)*

**Returns:** `number`

___
<a id="getchangeflag"></a>

###  getChangeFlag

▸ **getChangeFlag**(): `m.CellChangeFlag`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getChangeFlag](../interfaces/icelleditor.md#getchangeflag)*

*Defined in [editor.cell.ts:132](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L132)*

**Returns:** `m.CellChangeFlag`

___
<a id="getcolumnid"></a>

###  getColumnId

▸ **getColumnId**(): `number`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getColumnId](../interfaces/icelleditor.md#getcolumnid)*

*Defined in [editor.cell.ts:150](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L150)*

**Returns:** `number`

___
<a id="getcolumnkey"></a>

###  getColumnKey

▸ **getColumnKey**(): `number`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getColumnKey](../interfaces/icelleditor.md#getcolumnkey)*

*Defined in [editor.cell.ts:156](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L156)*

**Returns:** `number`

___
<a id="getprocessedformulavalue"></a>

###  getProcessedFormulaValue

▸ **getProcessedFormulaValue**(): `string`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getProcessedFormulaValue](../interfaces/icelleditor.md#getprocessedformulavalue)*

*Defined in [editor.cell.ts:162](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L162)*

**Returns:** `string`

___
<a id="getprocessedstringvalue"></a>

###  getProcessedStringValue

▸ **getProcessedStringValue**(): `string`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getProcessedStringValue](../interfaces/icelleditor.md#getprocessedstringvalue)*

*Defined in [editor.cell.ts:159](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L159)*

**Returns:** `string`

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getRowId](../interfaces/icelleditor.md#getrowid)*

*Defined in [editor.cell.ts:147](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L147)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getRowKey](../interfaces/icelleditor.md#getrowkey)*

*Defined in [editor.cell.ts:153](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L153)*

**Returns:** `number`

___
<a id="getstatus"></a>

###  getStatus

▸ **getStatus**(): `m.ICellStatus`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getStatus](../interfaces/icelleditor.md#getstatus)*

*Defined in [editor.cell.ts:138](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L138)*

**Returns:** `m.ICellStatus`

___
<a id="getvalue"></a>

###  getValue

▸ **getValue**(): `m.ICellTxValue`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[getValue](../interfaces/icelleditor.md#getvalue)*

*Defined in [editor.cell.ts:135](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L135)*

**Returns:** `m.ICellTxValue`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [ICellEditor](../interfaces/icelleditor.md).[isModified](../interfaces/icelleditor.md#ismodified)*

*Defined in [editor.cell.ts:141](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.cell.ts#L141)*

**Returns:** `boolean`

___

