[bcvm](../README.md) > [IColumnCollection](../interfaces/icolumncollection.md)

# Interface: IColumnCollection

## Type parameters
#### L :  [IColumn](icolumn.md)
## Hierarchy

**IColumnCollection**

↳  [IColumnDataCollection](icolumndatacollection.md)

↳  [IColumnEditorSet](icolumneditorset.md)

## Implemented by

* [ColumnCollBase](../classes/columncollbase.md)
* [ColumnDataColl](../classes/columndatacoll.md)
* [ColumnEditorColl](../classes/columneditorcoll.md)
* [ColumnEditorSet](../classes/columneditorset.md)

## Index

### Methods

* [filter](icolumncollection.md#filter)
* [getColumnById](icolumncollection.md#getcolumnbyid)
* [getColumnByIndex](icolumncollection.md#getcolumnbyindex)
* [getColumnByOffset](icolumncollection.md#getcolumnbyoffset)
* [getColumns](icolumncollection.md#getcolumns)

---

## Methods

<a id="filter"></a>

###  filter

▸ **filter**(filterFunc: *`function`*): `L`[]

*Defined in [model.column.ts:110](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L110)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| filterFunc | `function` |

**Returns:** `L`[]

___
<a id="getcolumnbyid"></a>

###  getColumnById

▸ **getColumnById**(columnId: *`number`*): `L`

*Defined in [model.column.ts:104](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L104)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| columnId | `number` |

**Returns:** `L`

___
<a id="getcolumnbyindex"></a>

###  getColumnByIndex

▸ **getColumnByIndex**(index: *`number`*): `L`

*Defined in [model.column.ts:107](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L107)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| index | `number` |

**Returns:** `L`

___
<a id="getcolumnbyoffset"></a>

###  getColumnByOffset

▸ **getColumnByOffset**(columnId: *`number`*, offset: *`number`*): `L`

*Defined in [model.column.ts:108](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L108)*

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

*Defined in [model.column.ts:105](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.column.ts#L105)*

**Returns:** `L`[]

___

