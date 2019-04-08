[bcvm](../README.md) > [IEnvironment](../interfaces/ienvironment.md)

# Interface: IEnvironment

## Hierarchy

**IEnvironment**

## Implemented by

* [Environment](../classes/environment.md)

## Index

### Methods

* [createGridEditor](ienvironment.md#creategrideditor)
* [getGridEditor](ienvironment.md#getgrideditor)
* [getGrids](ienvironment.md#getgrids)
* [loadGridById](ienvironment.md#loadgridbyid)
* [loadGridsById](ienvironment.md#loadgridsbyid)
* [submitGrid](ienvironment.md#submitgrid)

---

## Methods

<a id="creategrideditor"></a>

###  createGridEditor

▸ **createGridEditor**(grid: *[Grid](grid.md)*): [IGridTxEditor](igridtxeditor.md)

*Defined in [model.ts:62](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L62)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| grid | [Grid](grid.md) |

**Returns:** [IGridTxEditor](igridtxeditor.md)

___
<a id="getgrideditor"></a>

###  getGridEditor

▸ **getGridEditor**(gridId: *`number`*): [IGridTxEditor](igridtxeditor.md)

*Defined in [model.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L58)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |

**Returns:** [IGridTxEditor](igridtxeditor.md)

___
<a id="getgrids"></a>

###  getGrids

▸ **getGrids**(): [IGrids](igrids.md)

*Defined in [model.ts:59](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L59)*

**Returns:** [IGrids](igrids.md)

___
<a id="loadgridbyid"></a>

###  loadGridById

▸ **loadGridById**(gridId: *`number`*): `Promise`<`never`>

*Defined in [model.ts:56](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L56)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |

**Returns:** `Promise`<`never`>

___
<a id="loadgridsbyid"></a>

###  loadGridsById

▸ **loadGridsById**(gridIds: *`number`[]*, success: *`function`*, faliure: *`function`*): `void`

*Defined in [model.ts:57](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L57)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridIds | `number`[] |
| success | `function` |
| faliure | `function` |

**Returns:** `void`

___
<a id="submitgrid"></a>

###  submitGrid

▸ **submitGrid**(editor: *[IGridTxEditor](igridtxeditor.md)*, submitPrefs: *[ISubmitPrefs](isubmitprefs.md)*): `Promise`<[SubmitStatus](../classes/submitstatus.md)>

*Defined in [model.ts:64](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L64)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | [IGridTxEditor](igridtxeditor.md) |
| submitPrefs | [ISubmitPrefs](isubmitprefs.md) |

**Returns:** `Promise`<[SubmitStatus](../classes/submitstatus.md)>

___

