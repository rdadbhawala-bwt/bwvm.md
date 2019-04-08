[bcvm](../README.md) > [ColumnCollBase](../classes/columncollbase.md)

# Class: ColumnCollBase

## Type parameters
#### L :  [IColumn](../interfaces/icolumn.md)
## Hierarchy

**ColumnCollBase**

↳  [ColumnDataColl](columndatacoll.md)

↳  [ColumnEditorSet](columneditorset.md)

## Implements

* [IColumnCollection](../interfaces/icolumncollection.md)<`L`>

## Index

### Constructors

* [constructor](columncollbase.md#constructor)

### Properties

* [colArr](columncollbase.md#colarr)

### Methods

* [filter](columncollbase.md#filter)
* [getColumnById](columncollbase.md#getcolumnbyid)
* [getColumnByIndex](columncollbase.md#getcolumnbyindex)
* [getColumnByOffset](columncollbase.md#getcolumnbyoffset)
* [getColumns](columncollbase.md#getcolumns)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new ColumnCollBase**(pCols: *`L`[]*): [ColumnCollBase](columncollbase.md)

*Defined in [model.column.ts:137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L137)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCols | `L`[] |

**Returns:** [ColumnCollBase](columncollbase.md)

___

## Properties

<a id="colarr"></a>

### `<Protected>` colArr

**● colArr**: *`L`[]* =  []

*Defined in [model.column.ts:137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L137)*

___

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `L`[]

*Defined in [model.column.ts:163](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L163)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `L`[]

___
<a id="getcolumnbyid"></a>

###  getColumnById

▸ **getColumnById**(columnId: *`number`*): `L`

*Implementation of [IColumnCollection](../interfaces/icolumncollection.md).[getColumnById](../interfaces/icolumncollection.md#getcolumnbyid)*

*Defined in [model.column.ts:143](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L143)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |

**Returns:** `L`

___
<a id="getcolumnbyindex"></a>

###  getColumnByIndex

▸ **getColumnByIndex**(index: *`number`*): `L`

*Implementation of [IColumnCollection](../interfaces/icolumncollection.md).[getColumnByIndex](../interfaces/icolumncollection.md#getcolumnbyindex)*

*Defined in [model.column.ts:149](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L149)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** `L`

___
<a id="getcolumnbyoffset"></a>

###  getColumnByOffset

▸ **getColumnByOffset**(columnId: *`number`*, offset: *`number`*): `L`

*Implementation of [IColumnCollection](../interfaces/icolumncollection.md).[getColumnByOffset](../interfaces/icolumncollection.md#getcolumnbyoffset)*

*Defined in [model.column.ts:155](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L155)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |
| offset | `number` |

**Returns:** `L`

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(): `L`[]

*Implementation of [IColumnCollection](../interfaces/icolumncollection.md).[getColumns](../interfaces/icolumncollection.md#getcolumns)*

*Defined in [model.column.ts:146](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L146)*

**Returns:** `L`[]

___

