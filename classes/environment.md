[bcvm](../README.md) > [Environment](../classes/environment.md)

# Class: Environment

## Hierarchy

**Environment**

## Implements

* [IEnvironment](../interfaces/ienvironment.md)

## Index

### Constructors

* [constructor](environment.md#constructor)

### Properties

* [cred](environment.md#cred)
* [grids](environment.md#grids)

### Methods

* [createGridEditor](environment.md#creategrideditor)
* [getGridEditor](environment.md#getgrideditor)
* [getGrids](environment.md#getgrids)
* [loadGridById](environment.md#loadgridbyid)
* [loadGridByIdSuccess](environment.md#loadgridbyidsuccess)
* [loadGridsById](environment.md#loadgridsbyid)
* [submitGrid](environment.md#submitgrid)
* [submitUpdate](environment.md#submitupdate)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new Environment**(pCred: *`m.Credentials`*): [Environment](environment.md)

*Defined in [impl.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L13)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCred | `m.Credentials` |

**Returns:** [Environment](environment.md)

___

## Properties

<a id="cred"></a>

###  cred

**● cred**: *`m.Credentials`*

*Defined in [impl.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L12)*

___
<a id="grids"></a>

###  grids

**● grids**: *`m.GridColl`* =  new m.GridColl()

*Defined in [impl.ts:13](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L13)*

___

## Methods

<a id="creategrideditor"></a>

###  createGridEditor

▸ **createGridEditor**(grid: *`m.Grid`*): `m.IGridTxEditor`

*Defined in [impl.ts:62](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L62)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| grid | `m.Grid` |

**Returns:** `m.IGridTxEditor`

___
<a id="getgrideditor"></a>

###  getGridEditor

▸ **getGridEditor**(gridId: *`number`*): `m.IGridTxEditor`

*Implementation of [IEnvironment](../interfaces/ienvironment.md).[getGridEditor](../interfaces/ienvironment.md#getgrideditor)*

*Defined in [impl.ts:49](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L49)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |

**Returns:** `m.IGridTxEditor`

___
<a id="getgrids"></a>

###  getGrids

▸ **getGrids**(): `m.IGrids`

*Implementation of [IEnvironment](../interfaces/ienvironment.md).[getGrids](../interfaces/ienvironment.md#getgrids)*

*Defined in [impl.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L58)*

**Returns:** `m.IGrids`

___
<a id="loadgridbyid"></a>

###  loadGridById

▸ **loadGridById**(gridId: *`number`*): `Promise`<`never`>

*Implementation of [IEnvironment](../interfaces/ienvironment.md).[loadGridById](../interfaces/ienvironment.md#loadgridbyid)*

*Defined in [impl.ts:24](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L24)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridId | `number` |

**Returns:** `Promise`<`never`>

___
<a id="loadgridbyidsuccess"></a>

###  loadGridByIdSuccess

▸ **loadGridByIdSuccess**(gad: *`m.IGridAllData`*): `void`

*Defined in [impl.ts:45](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L45)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gad | `m.IGridAllData` |

**Returns:** `void`

___
<a id="loadgridsbyid"></a>

###  loadGridsById

▸ **loadGridsById**(gridIds: *`number`[]*): `void`

*Defined in [impl.ts:37](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L37)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| gridIds | `number`[] |

**Returns:** `void`

___
<a id="submitgrid"></a>

###  submitGrid

▸ **submitGrid**(editor: *`m.IGridTxEditor`*, submitPrefs: *[ISubmitPrefs](../interfaces/isubmitprefs.md)*): `Promise`<`m.SubmitStatus`>

*Defined in [impl.ts:66](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L66)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| editor | `m.IGridTxEditor` |
| submitPrefs | [ISubmitPrefs](../interfaces/isubmitprefs.md) |

**Returns:** `Promise`<`m.SubmitStatus`>

___
<a id="submitupdate"></a>

### `<Static>``<Private>` submitUpdate

▸ **submitUpdate**(rest: *[IRestApi](../interfaces/irestapi.md)*, editor: *`m.IGridTxEditor`*, submitPrefs: *[ISubmitPrefs](../interfaces/isubmitprefs.md)*, grids: *`m.GridColl`*, gs: *`m.SubmitStatus`*): `Promise`<`m.SubmitStatus`>

*Defined in [impl.ts:97](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L97)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| rest | [IRestApi](../interfaces/irestapi.md) |
| editor | `m.IGridTxEditor` |
| submitPrefs | [ISubmitPrefs](../interfaces/isubmitprefs.md) |
| grids | `m.GridColl` |
| gs | `m.SubmitStatus` |

**Returns:** `Promise`<`m.SubmitStatus`>

___

