[bcvm](../README.md) > [RangeEditorMatrix](../classes/rangeeditormatrix.md)

# Class: RangeEditorMatrix

## Hierarchy

**RangeEditorMatrix**

## Implements

* [IRangeEditorSet](../interfaces/irangeeditorset.md)

## Index

### Constructors

* [constructor](rangeeditormatrix.md#constructor)

### Properties

* [cells](rangeeditormatrix.md#cells)
* [columns](rangeeditormatrix.md#columns)
* [rows](rangeeditormatrix.md#rows)

### Methods

* [createRangeByRC](rangeeditormatrix.md#createrangebyrc)
* [fillMap](rangeeditormatrix.md#fillmap)
* [isModified](rangeeditormatrix.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RangeEditorMatrix**(src: *`m.IRangeEditorSet`*, filterRows: *`function`*, filterCols: *`function`*): [RangeEditorMatrix](rangeeditormatrix.md)

*Defined in [editor.range.ts:10](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.range.ts#L10)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| src | `m.IRangeEditorSet` |
| filterRows | `function` |
| filterCols | `function` |

**Returns:** [RangeEditorMatrix](rangeeditormatrix.md)

___

## Properties

<a id="cells"></a>

###  cells

**● cells**: *[CellEditorSet](celleditorset.md)*

*Implementation of [IRangeEditorSet](../interfaces/irangeeditorset.md).[cells](../interfaces/irangeeditorset.md#cells)*

*Defined in [editor.range.ts:10](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.range.ts#L10)*

___
<a id="columns"></a>

###  columns

**● columns**: *[ColumnEditorSet](columneditorset.md)*

*Implementation of [IRangeEditorSet](../interfaces/irangeeditorset.md).[columns](../interfaces/irangeeditorset.md#columns)*

*Defined in [editor.range.ts:9](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.range.ts#L9)*

___
<a id="rows"></a>

###  rows

**● rows**: *[RowEditorSet](roweditorset.md)*

*Implementation of [IRangeEditorSet](../interfaces/irangeeditorset.md).[rows](../interfaces/irangeeditorset.md#rows)*

*Defined in [editor.range.ts:8](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.range.ts#L8)*

___

## Methods

<a id="createrangebyrc"></a>

###  createRangeByRC

▸ **createRangeByRC**(filterRows: *`function`*, filterCols: *`function`*): `m.IRangeEditorSet`

*Defined in [editor.range.ts:35](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.range.ts#L35)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterRows | `function` |
| filterCols | `function` |

**Returns:** `m.IRangeEditorSet`

___
<a id="fillmap"></a>

### `<Private>` fillMap

▸ **fillMap**(m: *`Map`<`number`, `number`>*, id: *`number`*, fill: *`boolean`*): `boolean`

*Defined in [editor.range.ts:22](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.range.ts#L22)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| m | `Map`<`number`, `number`> |
| id | `number` |
| fill | `boolean` |

**Returns:** `boolean`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IRangeEditorSet](../interfaces/irangeeditorset.md).[isModified](../interfaces/irangeeditorset.md#ismodified)*

*Defined in [editor.range.ts:29](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.range.ts#L29)*

**Returns:** `boolean`

___

