[bcvm](../README.md) > [IGrids](../interfaces/igrids.md)

# Interface: IGrids

## Hierarchy

**IGrids**

## Implemented by

* [GridColl](../classes/gridcoll.md)

## Index

### Methods

* [getGrid](igrids.md#getgrid)
* [getGridChanges](igrids.md#getgridchanges)
* [getGridTx](igrids.md#getgridtx)

---

## Methods

<a id="getgrid"></a>

###  getGrid

▸ **getGrid**(gridId: *`any`*): [IGridTxDelta](igridtxdelta.md)

*Defined in [model.grid.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L12)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `any` |

**Returns:** [IGridTxDelta](igridtxdelta.md)

___
<a id="getgridchanges"></a>

###  getGridChanges

▸ **getGridChanges**(gridId: *`number`*, startTxId: *`number`*, endTxId: *`number`*): [IGridTxDelta](igridtxdelta.md)

*Defined in [model.grid.ts:14](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L14)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |
| startTxId | `number` |
| endTxId | `number` |

**Returns:** [IGridTxDelta](igridtxdelta.md)

___
<a id="getgridtx"></a>

###  getGridTx

▸ **getGridTx**(gridId: *`number`*, txId: *`number`*): [IGridTxDelta](igridtxdelta.md)

*Defined in [model.grid.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.grid.ts#L13)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |
| txId | `number` |

**Returns:** [IGridTxDelta](igridtxdelta.md)

___

