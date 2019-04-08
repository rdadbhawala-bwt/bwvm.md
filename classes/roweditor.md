[bcvm](../README.md) > [RowEditor](../classes/roweditor.md)

# Class: RowEditor

## Hierarchy

**RowEditor**

## Implements

* [IRowEditor](../interfaces/iroweditor.md)

## Index

### Constructors

* [constructor](roweditor.md#constructor)

### Properties

* [active](roweditor.md#active)
* [previousRowId](roweditor.md#previousrowid)
* [previousRowOffset](roweditor.md#previousrowoffset)
* [rowData](roweditor.md#rowdata)
* [rowName](roweditor.md#rowname)
* [rowSequenceNo](roweditor.md#rowsequenceno)

### Methods

* [getRowData](roweditor.md#getrowdata)
* [getRowId](roweditor.md#getrowid)
* [getRowKey](roweditor.md#getrowkey)
* [isModified](roweditor.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RowEditor**(p: *`m.IRowData` \| `string`*): [RowEditor](roweditor.md)

*Defined in [editor.row.ts:110](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L110)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| p | `m.IRowData` \| `string` |

**Returns:** [RowEditor](roweditor.md)

___

## Properties

<a id="active"></a>

###  active

**● active**: *`boolean`* = true

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[active](../interfaces/iroweditor.md#active)*

*Defined in [editor.row.ts:108](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L108)*

___
<a id="previousrowid"></a>

###  previousRowId

**● previousRowId**: *`number`* =  m.Constants.NewId

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[previousRowId](../interfaces/iroweditor.md#previousrowid)*

*Defined in [editor.row.ts:109](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L109)*

___
<a id="previousrowoffset"></a>

###  previousRowOffset

**● previousRowOffset**: *`number`* = 0

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[previousRowOffset](../interfaces/iroweditor.md#previousrowoffset)*

*Defined in [editor.row.ts:110](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L110)*

___
<a id="rowdata"></a>

### `<Private>` rowData

**● rowData**: *`m.IRowData`*

*Defined in [editor.row.ts:104](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L104)*

___
<a id="rowname"></a>

###  rowName

**● rowName**: *`string`*

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[rowName](../interfaces/iroweditor.md#rowname)*

*Defined in [editor.row.ts:107](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L107)*

___
<a id="rowsequenceno"></a>

###  rowSequenceNo

**● rowSequenceNo**: *`number`* = 0

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[rowSequenceNo](../interfaces/iroweditor.md#rowsequenceno)*

*Defined in [editor.row.ts:106](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L106)*

___

## Methods

<a id="getrowdata"></a>

###  getRowData

▸ **getRowData**(): `m.IRowData`

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[getRowData](../interfaces/iroweditor.md#getrowdata)*

*Defined in [editor.row.ts:131](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L131)*

**Returns:** `m.IRowData`

___
<a id="getrowid"></a>

###  getRowId

▸ **getRowId**(): `number`

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[getRowId](../interfaces/iroweditor.md#getrowid)*

*Defined in [editor.row.ts:138](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L138)*

**Returns:** `number`

___
<a id="getrowkey"></a>

###  getRowKey

▸ **getRowKey**(): `number`

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[getRowKey](../interfaces/iroweditor.md#getrowkey)*

*Defined in [editor.row.ts:141](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L141)*

**Returns:** `number`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IRowEditor](../interfaces/iroweditor.md).[isModified](../interfaces/iroweditor.md#ismodified)*

*Defined in [editor.row.ts:135](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.row.ts#L135)*

**Returns:** `boolean`

___

