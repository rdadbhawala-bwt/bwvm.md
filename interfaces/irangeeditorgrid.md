[bcvm](../README.md) > [IRangeEditorGrid](../interfaces/irangeeditorgrid.md)

# Interface: IRangeEditorGrid

## Hierarchy

↳  [IRangeEditor](irangeeditor.md)<[IRowEditorCollection](iroweditorcollection.md), [IColumnEditorCollection](icolumneditorcollection.md), [ICellEditorCollection](icelleditorcollection.md)>

**↳ IRangeEditorGrid**

↳  [IGridTxEditor](igridtxeditor.md)

## Index

### Properties

* [cells](irangeeditorgrid.md#cells)
* [columns](irangeeditorgrid.md#columns)
* [rows](irangeeditorgrid.md#rows)

### Methods

* [createRangeByRC](irangeeditorgrid.md#createrangebyrc)
* [isModified](irangeeditorgrid.md#ismodified)

---

## Properties

<a id="cells"></a>

###  cells

**● cells**: *[ICellEditorCollection](icelleditorcollection.md)*

*Inherited from [IRange](irange.md).[cells](irange.md#cells)*

*Defined in [model.range.ts:16](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L16)*

___
<a id="columns"></a>

###  columns

**● columns**: *[IColumnEditorCollection](icolumneditorcollection.md)*

*Inherited from [IRange](irange.md).[columns](irange.md#columns)*

*Defined in [model.range.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L15)*

___
<a id="rows"></a>

###  rows

**● rows**: *[IRowEditorCollection](iroweditorcollection.md)*

*Inherited from [IRangeRow](irangerow.md).[rows](irangerow.md#rows)*

*Defined in [model.range.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L7)*

___

## Methods

<a id="createrangebyrc"></a>

###  createRangeByRC

▸ **createRangeByRC**(filterRows: *`function`*, filterCols: *`function`*): [IRangeEditorSet](irangeeditorset.md)

*Inherited from [IRangeEditor](irangeeditor.md).[createRangeByRC](irangeeditor.md#createrangebyrc)*

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

*Inherited from [IRangeEditor](irangeeditor.md).[isModified](irangeeditor.md#ismodified)*

*Defined in [model.range.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L25)*

**Returns:** `boolean`

___

