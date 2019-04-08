[bcvm](../README.md) > [GridApi](../classes/gridapi.md)

# Class: GridApi

GridApi - object-oriented interface

*__export__*: 

*__class__*: GridApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ GridApi**

## Index

### Constructors

* [constructor](gridapi.md#constructor)

### Properties

* [basePath](gridapi.md#basepath)
* [configuration](gridapi.md#configuration)
* [fetch](gridapi.md#fetch)

### Methods

* [gridDelete](gridapi.md#griddelete)
* [gridGridIdColumnsGet](gridapi.md#gridgrididcolumnsget)
* [gridGridIdGet](gridapi.md#gridgrididget)
* [gridPost](gridapi.md#gridpost)
* [gridPut](gridapi.md#gridput)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new GridApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, fetch?: *[FetchAPI](../interfaces/fetchapi.md)*): [GridApi](gridapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [typescript-fetch-client-generated/api.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L58)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` fetch | [FetchAPI](../interfaces/fetchapi.md) |  portableFetch |

**Returns:** [GridApi](gridapi.md)

___

## Properties

<a id="basepath"></a>

### `<Protected>` basePath

**● basePath**: *`string`*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#basepath)*

*Defined in [typescript-fetch-client-generated/api.ts:60](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L60)*

___
<a id="configuration"></a>

### `<Protected>` configuration

**● configuration**: *[Configuration](configuration.md)*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#configuration)*

*Defined in [typescript-fetch-client-generated/api.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L58)*

___
<a id="fetch"></a>

### `<Protected>` fetch

**● fetch**: *[FetchAPI](../interfaces/fetchapi.md)*

*Inherited from [BaseAPI](baseapi.md).[fetch](baseapi.md#fetch)*

*Defined in [typescript-fetch-client-generated/api.ts:60](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L60)*

___

## Methods

<a id="griddelete"></a>

###  gridDelete

▸ **gridDelete**(gridId: *`number`*, options?: *`any`*): `Promise`<`Response`>

*Defined in [typescript-fetch-client-generated/api.ts:2756](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2756)*

*__summary__*: Delete cuboid by ID

*__throws__*: {RequiredError}

*__memberof__*: GridApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| gridId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`Response`>

___
<a id="gridgrididcolumnsget"></a>

###  gridGridIdColumnsGet

▸ **gridGridIdColumnsGet**(gridId: *`number`*, options?: *`any`*): `Promise`<[ColumnChain](../interfaces/columnchain.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:2768](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2768)*

*__summary__*: Download grid structure

*__throws__*: {RequiredError}

*__memberof__*: GridApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| gridId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[ColumnChain](../interfaces/columnchain.md)[]>

___
<a id="gridgrididget"></a>

###  gridGridIdGet

▸ **gridGridIdGet**(gridId: *`number`*, importTxId: *`number`*, view: *`string`*, mode: *`number`*, baselineId: *`number`*, options?: *`any`*): `Promise`<[CellBuffer](../interfaces/cellbuffer.md)>

*Defined in [typescript-fetch-client-generated/api.ts:2784](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2784)*

*__summary__*: Download latest grid data for a given cell specification

*__throws__*: {RequiredError}

*__memberof__*: GridApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| gridId | `number` |  \- |
| importTxId | `number` |  \- |
| view | `string` |  \- |
| mode | `number` |  \- |
| baselineId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[CellBuffer](../interfaces/cellbuffer.md)>

___
<a id="gridpost"></a>

###  gridPost

▸ **gridPost**(grid: *`Grid`*, options?: *`any`*): `Promise`<`Grid`>

*Defined in [typescript-fetch-client-generated/api.ts:2796](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2796)*

*__summary__*: Create a new cuboid. returns a new grid id

*__throws__*: {RequiredError}

*__memberof__*: GridApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| grid | `Grid` |  Cuboid creation details |
| `Optional` options | `any` |

**Returns:** `Promise`<`Grid`>

___
<a id="gridput"></a>

###  gridPut

▸ **gridPut**(gridId: *`number`*, cellBufferRequest: *[CellBuffer](../interfaces/cellbuffer.md)*, options?: *`any`*): `Promise`<[CellBuffer](../interfaces/cellbuffer.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:2809](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2809)*

*__summary__*: Update a grid

*__throws__*: {RequiredError}

*__memberof__*: GridApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| gridId | `number` |  \- |
| cellBufferRequest | [CellBuffer](../interfaces/cellbuffer.md) |  Cell buffer details |
| `Optional` options | `any` |

**Returns:** `Promise`<[CellBuffer](../interfaces/cellbuffer.md)[]>

___

