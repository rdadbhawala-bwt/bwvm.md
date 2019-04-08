[bcvm](../README.md) > [IRowEditor](../interfaces/iroweditor.md)

# Interface: IRowEditor

## Hierarchy

 [IRow](irow.md)

**↳ IRowEditor**

## Implemented by

* [RowEditor](../classes/roweditor.md)

## Index

### Properties

* [active](iroweditor.md#active)
* [previousRowId](iroweditor.md#previousrowid)
* [previousRowOffset](iroweditor.md#previousrowoffset)
* [rowName](iroweditor.md#rowname)
* [rowSequenceNo](iroweditor.md#rowsequenceno)

### Methods

* [getRowData](iroweditor.md#getrowdata)
* [getRowId](iroweditor.md#getrowid)
* [getRowKey](iroweditor.md#getrowkey)
* [isModified](iroweditor.md#ismodified)

---

## Properties

<a id="active"></a>

###  active

**● active**: *`boolean`*

*Defined in [model.row.ts:35](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L35)*

___
<a id="previousrowid"></a>

###  previousRowId

**● previousRowId**: *`number`*

*Defined in [model.row.ts:33](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L33)*

___
<a id="previousrowoffset"></a>

###  previousRowOffset

**● previousRowOffset**: *`number`*

*Defined in [model.row.ts:34](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L34)*

___
<a id="rowname"></a>

###  rowName

**● rowName**: *`string`*

*Defined in [model.row.ts:36](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L36)*

___
<a id="rowsequenceno"></a>

###  rowSequenceNo

**● rowSequenceNo**: *`number`*

*Defined in [model.row.ts:32](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L32)*

___

## Methods

<a id="getrowdata"></a>

###  getRowData

▸ **getRowData**(): [IRowData](irowdata.md)

*Defined in [model.row.ts:38](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L38)*

**Returns:** [IRowData](irowdata.md)

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Overrides [IRow](irow.md).[getRowId](irow.md#getrowid)*

*Defined in [model.row.ts:30](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L30)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Inherited from [IRow](irow.md).[getRowKey](irow.md#getrowkey)*

*Defined in [model.row.ts:9](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L9)*

**Returns:** `number`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Defined in [model.row.ts:40](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.row.ts#L40)*

**Returns:** `boolean`

___

