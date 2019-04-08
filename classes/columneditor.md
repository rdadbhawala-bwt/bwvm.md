[bcvm](../README.md) > [ColumnEditor](../classes/columneditor.md)

# Class: ColumnEditor

## Hierarchy

**ColumnEditor**

## Implements

* [IColumnEditor](../interfaces/icolumneditor.md)

## Index

### Constructors

* [constructor](columneditor.md#constructor)

### Properties

* [active](columneditor.md#active)
* [columnData](columneditor.md#columndata)
* [columnName](columneditor.md#columnname)
* [columnSequenceNo](columneditor.md#columnsequenceno)
* [previousColumnId](columneditor.md#previouscolumnid)
* [previousColumnOffset](columneditor.md#previouscolumnoffset)

### Methods

* [getColumnData](columneditor.md#getcolumndata)
* [getColumnId](columneditor.md#getcolumnid)
* [getColumnKey](columneditor.md#getcolumnkey)
* [isModified](columneditor.md#ismodified)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new ColumnEditor**(p: *`m.IColumnData` \| `string`*): [ColumnEditor](columneditor.md)

*Defined in [editor.column.ts:104](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L104)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| p | `m.IColumnData` \| `string` |

**Returns:** [ColumnEditor](columneditor.md)

___

## Properties

<a id="active"></a>

###  active

**● active**: *`boolean`* = true

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[active](../interfaces/icolumneditor.md#active)*

*Defined in [editor.column.ts:127](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L127)*

___
<a id="columndata"></a>

### `<Private>` columnData

**● columnData**: *`m.IColumnData`*

*Defined in [editor.column.ts:104](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L104)*

___
<a id="columnname"></a>

###  columnName

**● columnName**: *`string`*

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[columnName](../interfaces/icolumneditor.md#columnname)*

*Defined in [editor.column.ts:126](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L126)*

___
<a id="columnsequenceno"></a>

###  columnSequenceNo

**● columnSequenceNo**: *`number`*

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[columnSequenceNo](../interfaces/icolumneditor.md#columnsequenceno)*

*Defined in [editor.column.ts:125](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L125)*

___
<a id="previouscolumnid"></a>

###  previousColumnId

**● previousColumnId**: *`number`* =  m.Constants.NewId

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[previousColumnId](../interfaces/icolumneditor.md#previouscolumnid)*

*Defined in [editor.column.ts:128](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L128)*

___
<a id="previouscolumnoffset"></a>

###  previousColumnOffset

**● previousColumnOffset**: *`number`* =  m.Constants.NewId

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[previousColumnOffset](../interfaces/icolumneditor.md#previouscolumnoffset)*

*Defined in [editor.column.ts:129](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L129)*

___

## Methods

<a id="getcolumndata"></a>

###  getColumnData

▸ **getColumnData**(): `m.IColumnData`

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[getColumnData](../interfaces/icolumneditor.md#getcolumndata)*

*Defined in [editor.column.ts:131](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L131)*

**Returns:** `m.IColumnData`

___
<a id="getcolumnid"></a>

###  getColumnId

▸ **getColumnId**(): `number`

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[getColumnId](../interfaces/icolumneditor.md#getcolumnid)*

*Defined in [editor.column.ts:139](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L139)*

**Returns:** `number`

___
<a id="getcolumnkey"></a>

###  getColumnKey

▸ **getColumnKey**(): `number`

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[getColumnKey](../interfaces/icolumneditor.md#getcolumnkey)*

*Defined in [editor.column.ts:143](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L143)*

**Returns:** `number`

___
<a id="ismodified"></a>

###  isModified

▸ **isModified**(): `boolean`

*Implementation of [IColumnEditor](../interfaces/icolumneditor.md).[isModified](../interfaces/icolumneditor.md#ismodified)*

*Defined in [editor.column.ts:135](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/editor.column.ts#L135)*

**Returns:** `boolean`

___

