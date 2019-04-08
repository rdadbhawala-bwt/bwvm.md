[bcvm](../README.md) > [Modified](../classes/modified.md)

# Class: Modified

## Hierarchy

**Modified**

## Implements

* [IModified](../interfaces/imodified.md)

## Index

### Methods

* [getChangeFlag](modified.md#getchangeflag)
* [isCellModified](modified.md#iscellmodified)
* [isColumnModified](modified.md#iscolumnmodified)
* [isFormulaModified](modified.md#isformulamodified)
* [isRowModified](modified.md#isrowmodified)

---

## Methods

<a id="getchangeflag"></a>

###  getChangeFlag

▸ **getChangeFlag**(old: *`m.ICellTxValue`*, oldSt: *`m.ICellStatus`*, oldFormula: *`m.IFormula`*, mod: *`m.ICellEditor`*): `m.CellChangeFlag`

*Defined in [impl.modified.ts:37](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.modified.ts#L37)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | `m.ICellTxValue` |
| oldSt | `m.ICellStatus` |
| oldFormula | `m.IFormula` |
| mod | `m.ICellEditor` |

**Returns:** `m.CellChangeFlag`

___
<a id="iscellmodified"></a>

###  isCellModified

▸ **isCellModified**(old: *`m.ICellTxValue`*, oldSt: *`m.ICellStatus`*, oldFormula: *`m.IFormula`*, mod: *`m.ICellEditor`*): `boolean`

*Defined in [impl.modified.ts:19](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.modified.ts#L19)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | `m.ICellTxValue` |
| oldSt | `m.ICellStatus` |
| oldFormula | `m.IFormula` |
| mod | `m.ICellEditor` |

**Returns:** `boolean`

___
<a id="iscolumnmodified"></a>

###  isColumnModified

▸ **isColumnModified**(old: *`m.IColumnData`*, mod: *`m.IColumnEditor`*): `boolean`

*Defined in [impl.modified.ts:6](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.modified.ts#L6)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | `m.IColumnData` |
| mod | `m.IColumnEditor` |

**Returns:** `boolean`

___
<a id="isformulamodified"></a>

###  isFormulaModified

▸ **isFormulaModified**(old: *`m.ICellTxValue`*, oldSt: *`m.ICellStatus`*, oldFormula: *`m.IFormula`*, mod: *`m.ICellEditor`*): `boolean`

*Defined in [impl.modified.ts:27](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.modified.ts#L27)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | `m.ICellTxValue` |
| oldSt | `m.ICellStatus` |
| oldFormula | `m.IFormula` |
| mod | `m.ICellEditor` |

**Returns:** `boolean`

___
<a id="isrowmodified"></a>

###  isRowModified

▸ **isRowModified**(old: *`m.IRowData`*, mod: *`m.IRowEditor`*): `boolean`

*Defined in [impl.modified.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.modified.ts#L13)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | `m.IRowData` |
| mod | `m.IRowEditor` |

**Returns:** `boolean`

___

