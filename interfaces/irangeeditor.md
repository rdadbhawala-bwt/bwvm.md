[bcvm](../README.md) > [IRangeEditor](../interfaces/irangeeditor.md)

# Interface: IRangeEditor

## Type parameters
#### REC :  [IRowEditorSet](iroweditorset.md)
#### CEC :  [IColumnEditorSet](icolumneditorset.md)
#### LEC :  [ICellEditorSet](icelleditorset.md)
## Hierarchy

↳  [IRange](irange.md)<[IRowEditor](iroweditor.md), [IColumnEditor](icolumneditor.md), [ICellEditor](icelleditor.md), `REC`, `CEC`, `LEC`>

**↳ IRangeEditor**

↳  [IRangeEditorSet](irangeeditorset.md)

↳  [IRangeEditorGrid](irangeeditorgrid.md)

## Index

### Properties

* [cells](irangeeditor.md#cells)
* [columns](irangeeditor.md#columns)
* [rows](irangeeditor.md#rows)

### Methods

* [createRangeByRC](irangeeditor.md#createrangebyrc)
* [isModified](irangeeditor.md#ismodified)

---

## Properties

<a id="cells"></a>

###  cells

**● cells**: *`LEC`*

*Inherited from [IRange](irange.md).[cells](irange.md#cells)*

*Defined in [model.range.ts:16](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L16)*

___
<a id="columns"></a>

###  columns

**● columns**: *`CEC`*

*Inherited from [IRange](irange.md).[columns](irange.md#columns)*

*Defined in [model.range.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L15)*

___
<a id="rows"></a>

###  rows

**● rows**: *`REC`*

*Inherited from [IRangeRow](irangerow.md).[rows](irangerow.md#rows)*

*Defined in [model.range.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L7)*

___

## Methods

<a id="createrangebyrc"></a>

###  createRangeByRC

▸ **createRangeByRC**(filterRows: *`function`*, filterCols: *`function`*): [IRangeEditorSet](irangeeditorset.md)

*Defined in [model.range.ts:26](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L26)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterRows | `function` |
| filterCols | `function` |

**Returns:** [IRangeEditorSet](irangeeditorset.md)

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Defined in [model.range.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L25)*

**Returns:** `boolean`

___

