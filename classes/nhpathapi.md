[bcvm](../README.md) > [NhPathApi](../classes/nhpathapi.md)

# Class: NhPathApi

NhPathApi - object-oriented interface

*__export__*: 

*__class__*: NhPathApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ NhPathApi**

## Index

### Constructors

* [constructor](nhpathapi.md#constructor)

### Properties

* [basePath](nhpathapi.md#basepath)
* [configuration](nhpathapi.md#configuration)
* [fetch](nhpathapi.md#fetch)

### Methods

* [nhpathNhpathGet](nhpathapi.md#nhpathnhpathget)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new NhPathApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, fetch?: *[FetchAPI](../interfaces/fetchapi.md)*): [NhPathApi](nhpathapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [typescript-fetch-client-generated/api.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L58)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` fetch | [FetchAPI](../interfaces/fetchapi.md) |  portableFetch |

**Returns:** [NhPathApi](nhpathapi.md)

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

<a id="nhpathnhpathget"></a>

###  nhpathNhpathGet

▸ **nhpathNhpathGet**(nhpath: *`string`*, options?: *`any`*): `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4285](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4285)*

*__summary__*: Get an aaray of neighborhoods

*__throws__*: {RequiredError}

*__memberof__*: NhPathApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhpath | `string` |  nhpath |
| `Optional` options | `any` |

**Returns:** `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

___

