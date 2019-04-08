[bcvm](../README.md) > [ICellEditor](../interfaces/icelleditor.md)

# Interface: ICellEditor

## Hierarchy

 [ICell](icell.md)

**↳ ICellEditor**

## Implemented by

* [CellEditor](../classes/celleditor.md)

## Index

### Properties

* [active](icelleditor.md#active)
* [formulaValue](icelleditor.md#formulavalue)
* [rcChangeFlag](icelleditor.md#rcchangeflag)
* [stringValue](icelleditor.md#stringvalue)

### Methods

* [getCellId](icelleditor.md#getcellid)
* [getChangeFlag](icelleditor.md#getchangeflag)
* [getColumnId](icelleditor.md#getcolumnid)
* [getColumnKey](icelleditor.md#getcolumnkey)
* [getProcessedFormulaValue](icelleditor.md#getprocessedformulavalue)
* [getProcessedStringValue](icelleditor.md#getprocessedstringvalue)
* [getRowId](icelleditor.md#getrowid)
* [getRowKey](icelleditor.md#getrowkey)
* [getStatus](icelleditor.md#getstatus)
* [getValue](icelleditor.md#getvalue)
* [isModified](icelleditor.md#ismodified)

---

## Properties

<a id="active"></a>

###  active

**● active**: *`boolean`*

*Defined in [model.cell.ts:66](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L66)*

___
<a id="formulavalue"></a>

###  formulaValue

**● formulaValue**: *`string`*

*Defined in [model.cell.ts:64](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L64)*

___
<a id="rcchangeflag"></a>

###  rcChangeFlag

**● rcChangeFlag**: *[CellChangeFlag](../enums/cellchangeflag.md)*

*Defined in [model.cell.ts:67](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L67)*

___
<a id="stringvalue"></a>

###  stringValue

**● stringValue**: *`string`*

*Defined in [model.cell.ts:63](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L63)*

___

## Methods

<a id="getcellid"></a>

###  getCellId

▸ **getCellId**(): `number`

*Inherited from [ICell](icell.md).[getCellId](icell.md#getcellid)*

*Defined in [model.cell.ts:9](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L9)*

**Returns:** `number`

___
<a id="getchangeflag"></a>

###  getChangeFlag

▸ **getChangeFlag**(): [CellChangeFlag](../enums/cellchangeflag.md)

*Defined in [model.cell.ts:70](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L70)*

**Returns:** [CellChangeFlag](../enums/cellchangeflag.md)

___
<a id="getcolumnid"></a>

###  getColumnId

▸ **getColumnId**(): `number`

*Inherited from [ICell](icell.md).[getColumnId](icell.md#getcolumnid)*

*Defined in [model.cell.ts:11](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L11)*

**Returns:** `number`

___
<a id="getcolumnkey"></a>

###  getColumnKey

▸ **getColumnKey**(): `number`

*Inherited from [ICell](icell.md).[getColumnKey](icell.md#getcolumnkey)*

*Defined in [model.cell.ts:14](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L14)*

**Returns:** `number`

___
<a id="getprocessedformulavalue"></a>

###  getProcessedFormulaValue

▸ **getProcessedFormulaValue**(): `string`

*Defined in [model.cell.ts:72](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L72)*

**Returns:** `string`

___
<a id="getprocessedstringvalue"></a>

###  getProcessedStringValue

▸ **getProcessedStringValue**(): `string`

*Defined in [model.cell.ts:71](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L71)*

**Returns:** `string`

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Inherited from [ICell](icell.md).[getRowId](icell.md#getrowid)*

*Defined in [model.cell.ts:10](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L10)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Inherited from [ICell](icell.md).[getRowKey](icell.md#getrowkey)*

*Defined in [model.cell.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L13)*

**Returns:** `number`

___
<a id="getstatus"></a>

###  getStatus

▸ **getStatus**(): [ICellStatus](icellstatus.md)

*Defined in [model.cell.ts:60](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L60)*

**Returns:** [ICellStatus](icellstatus.md)

___
<a id="getvalue"></a>

###  getValue

▸ **getValue**(): [ICellTxValue](icelltxvalue.md)

*Defined in [model.cell.ts:59](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L59)*

**Returns:** [ICellTxValue](icelltxvalue.md)

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Defined in [model.cell.ts:69](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L69)*

**Returns:** `boolean`

___

