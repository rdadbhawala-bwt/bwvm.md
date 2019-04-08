[bcvm](../README.md) > [IModified](../interfaces/imodified.md)

# Interface: IModified

## Hierarchy

**IModified**

## Implemented by

* [Modified](../classes/modified.md)

## Index

### Methods

* [getChangeFlag](imodified.md#getchangeflag)
* [isCellModified](imodified.md#iscellmodified)
* [isColumnModified](imodified.md#iscolumnmodified)
* [isRowModified](imodified.md#isrowmodified)

---

## Methods

<a id="getchangeflag"></a>

###  getChangeFlag

▸ **getChangeFlag**(old: *[ICellTxValue](icelltxvalue.md)*, oldSt: *[ICellStatus](icellstatus.md)*, oldFormula: *[IFormula](iformula.md)*, mod: *[ICellEditor](icelleditor.md)*): [CellChangeFlag](../enums/cellchangeflag.md)

*Defined in [model.ts:78](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L78)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | [ICellTxValue](icelltxvalue.md) |
| oldSt | [ICellStatus](icellstatus.md) |
| oldFormula | [IFormula](iformula.md) |
| mod | [ICellEditor](icelleditor.md) |

**Returns:** [CellChangeFlag](../enums/cellchangeflag.md)

___
<a id="iscellmodified"></a>

###  isCellModified

▸ **isCellModified**(old: *[ICellTxValue](icelltxvalue.md)*, oldSt: *[ICellStatus](icellstatus.md)*, oldFormula: *[IFormula](iformula.md)*, mod: *[ICellEditor](icelleditor.md)*): `boolean`

*Defined in [model.ts:77](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L77)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | [ICellTxValue](icelltxvalue.md) |
| oldSt | [ICellStatus](icellstatus.md) |
| oldFormula | [IFormula](iformula.md) |
| mod | [ICellEditor](icelleditor.md) |

**Returns:** `boolean`

___
<a id="iscolumnmodified"></a>

###  isColumnModified

▸ **isColumnModified**(old: *[IColumnData](icolumndata.md)*, mod: *[IColumnEditor](icolumneditor.md)*): `boolean`

*Defined in [model.ts:75](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L75)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | [IColumnData](icolumndata.md) |
| mod | [IColumnEditor](icolumneditor.md) |

**Returns:** `boolean`

___
<a id="isrowmodified"></a>

###  isRowModified

▸ **isRowModified**(old: *[IRowData](irowdata.md)*, mod: *[IRowEditor](iroweditor.md)*): `boolean`

*Defined in [model.ts:76](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L76)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| old | [IRowData](irowdata.md) |
| mod | [IRowEditor](iroweditor.md) |

**Returns:** `boolean`

___

