[bcvm](../README.md) > [RestUtils](../modules/restutils.md)

# Module: RestUtils

## Index

### Functions

* [EditorToBuffer](restutils.md#editortobuffer)
* [EmptyGc](restutils.md#emptygc)
* [GcToGad](restutils.md#gctogad)
* [GridToGad](restutils.md#gridtogad)
* [checkEmptyArray](restutils.md#checkemptyarray)
* [getCells](restutils.md#getcells)
* [getColumnIds](restutils.md#getcolumnids)
* [getColumns](restutils.md#getcolumns)
* [getRowIds](restutils.md#getrowids)
* [getRows](restutils.md#getrows)
* [getSequencedCells](restutils.md#getsequencedcells)

---

## Functions

<a id="editortobuffer"></a>

###  EditorToBuffer

▸ **EditorToBuffer**(editor: *`m.IGridTxEditor`*, submitPrefs: *[ISubmitPrefs](../interfaces/isubmitprefs.md)*): [CellBuffer](../interfaces/cellbuffer.md)

*Defined in [restApi.adapters.ts:44](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L44)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | `m.IGridTxEditor` |
| submitPrefs | [ISubmitPrefs](../interfaces/isubmitprefs.md) |

**Returns:** [CellBuffer](../interfaces/cellbuffer.md)

___
<a id="emptygc"></a>

###  EmptyGc

▸ **EmptyGc**(): [GridChain](../interfaces/gridchain.md)

*Defined in [restApi.adapters.ts:34](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L34)*

**Returns:** [GridChain](../interfaces/gridchain.md)

___
<a id="gctogad"></a>

###  GcToGad

▸ **GcToGad**(gc: *[GridChain](../interfaces/gridchain.md)*, gad: *`m.IGridAllData`*): `m.IGridAllData`

*Defined in [restApi.adapters.ts:6](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L6)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gc | [GridChain](../interfaces/gridchain.md) |
| gad | `m.IGridAllData` |

**Returns:** `m.IGridAllData`

___
<a id="gridtogad"></a>

###  GridToGad

▸ **GridToGad**(grid: *`Grid`*, gridInfo: *`m.GridInfo`*): `m.IGridAllData`

*Defined in [restApi.adapters.ts:28](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L28)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| grid | `Grid` |
| gridInfo | `m.GridInfo` |

**Returns:** `m.IGridAllData`

___
<a id="checkemptyarray"></a>

###  checkEmptyArray

▸ **checkEmptyArray**<`T`>(arr: *`T`[]*): `T`[]

*Defined in [restApi.adapters.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L25)*

**Type parameters:**

#### T 
**Parameters:**

| Name | Type |
| ------ | ------ |
| arr | `T`[] |

**Returns:** `T`[]

___
<a id="getcells"></a>

###  getCells

▸ **getCells**(editor: *`m.IGridTxEditor`*): [ChangedCell](../interfaces/changedcell.md)[]

*Defined in [restApi.adapters.ts:112](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L112)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | `m.IGridTxEditor` |

**Returns:** [ChangedCell](../interfaces/changedcell.md)[]

___
<a id="getcolumnids"></a>

###  getColumnIds

▸ **getColumnIds**(eCols: *`m.IColumnEditor`[]*): `number`[]

*Defined in [restApi.adapters.ts:77](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L77)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| eCols | `m.IColumnEditor`[] |

**Returns:** `number`[]

___
<a id="getcolumns"></a>

###  getColumns

▸ **getColumns**(editor: *`m.IGridTxEditor`*, eCols: *`m.IColumnEditor`[]*): [ColumnChain](../interfaces/columnchain.md)[]

*Defined in [restApi.adapters.ts:155](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L155)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | `m.IGridTxEditor` |
| eCols | `m.IColumnEditor`[] |

**Returns:** [ColumnChain](../interfaces/columnchain.md)[]

___
<a id="getrowids"></a>

###  getRowIds

▸ **getRowIds**(eRows: *`m.IRowEditor`[]*): `number`[]

*Defined in [restApi.adapters.ts:81](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L81)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| eRows | `m.IRowEditor`[] |

**Returns:** `number`[]

___
<a id="getrows"></a>

###  getRows

▸ **getRows**(editor: *`m.IGridTxEditor`*, eRows: *`m.IRowEditor`[]*): [RowChain](../interfaces/rowchain.md)[]

*Defined in [restApi.adapters.ts:134](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L134)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | `m.IGridTxEditor` |
| eRows | `m.IRowEditor`[] |

**Returns:** [RowChain](../interfaces/rowchain.md)[]

___
<a id="getsequencedcells"></a>

###  getSequencedCells

▸ **getSequencedCells**(editor: *`m.IGridTxEditor`*): [SequencedCellArray](../interfaces/sequencedcellarray.md)[]

*Defined in [restApi.adapters.ts:85](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.adapters.ts#L85)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | `m.IGridTxEditor` |

**Returns:** [SequencedCellArray](../interfaces/sequencedcellarray.md)[]

___

