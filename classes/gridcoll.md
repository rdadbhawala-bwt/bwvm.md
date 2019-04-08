[bcvm](../README.md) > [GridColl](../classes/gridcoll.md)

# Class: GridColl

## Hierarchy

**GridColl**

## Implements

* [IGrids](../interfaces/igrids.md)

## Index

### Properties

* [gridMap](gridcoll.md#gridmap)

### Methods

* [getGrid](gridcoll.md#getgrid)
* [getGridAllData](gridcoll.md#getgridalldata)
* [getGridChanges](gridcoll.md#getgridchanges)
* [getGridLatest](gridcoll.md#getgridlatest)
* [getGridTx](gridcoll.md#getgridtx)
* [putGrid](gridcoll.md#putgrid)

---

## Properties

<a id="gridmap"></a>

### `<Private>` gridMap

**● gridMap**: *`Map`<`number`, [IGridAllData](../interfaces/igridalldata.md)>* =  new Map<number, GridAllData>()

*Defined in [model.grid.ts:265](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L265)*

___

## Methods

<a id="getgrid"></a>

###  getGrid

▸ **getGrid**(gridId: *`number`*): [GridTxDelta](gridtxdelta.md)

*Defined in [model.grid.ts:278](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L278)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |

**Returns:** [GridTxDelta](gridtxdelta.md)

___
<a id="getgridalldata"></a>

###  getGridAllData

▸ **getGridAllData**(gridId: *`number`*): [IGridAllData](../interfaces/igridalldata.md)

*Defined in [model.grid.ts:287](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L287)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |

**Returns:** [IGridAllData](../interfaces/igridalldata.md)

___
<a id="getgridchanges"></a>

###  getGridChanges

▸ **getGridChanges**(gridId: *`number`*, startTxId: *`number`*, endTxId: *`number`*): [IGridTxDelta](../interfaces/igridtxdelta.md)

*Implementation of [IGrids](../interfaces/igrids.md).[getGridChanges](../interfaces/igrids.md#getgridchanges)*

*Defined in [model.grid.ts:275](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L275)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |
| startTxId | `number` |
| endTxId | `number` |

**Returns:** [IGridTxDelta](../interfaces/igridtxdelta.md)

___
<a id="getgridlatest"></a>

###  getGridLatest

▸ **getGridLatest**(gridId: *`number`*): [IGridTxDelta](../interfaces/igridtxdelta.md)

*Defined in [model.grid.ts:267](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L267)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |

**Returns:** [IGridTxDelta](../interfaces/igridtxdelta.md)

___
<a id="getgridtx"></a>

###  getGridTx

▸ **getGridTx**(gridId: *`number`*, txId: *`number`*): [IGridTxDelta](../interfaces/igridtxdelta.md)

*Implementation of [IGrids](../interfaces/igrids.md).[getGridTx](../interfaces/igrids.md#getgridtx)*

*Defined in [model.grid.ts:272](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L272)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |
| txId | `number` |

**Returns:** [IGridTxDelta](../interfaces/igridtxdelta.md)

___
<a id="putgrid"></a>

###  putGrid

▸ **putGrid**(pGrid: *[IGridAllData](../interfaces/igridalldata.md)*): `void`

*Defined in [model.grid.ts:283](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L283)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pGrid | [IGridAllData](../interfaces/igridalldata.md) |

**Returns:** `void`

___

