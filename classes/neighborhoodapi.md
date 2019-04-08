[bcvm](../README.md) > [NeighborhoodApi](../classes/neighborhoodapi.md)

# Class: NeighborhoodApi

NeighborhoodApi - object-oriented interface

*__export__*: 

*__class__*: NeighborhoodApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ NeighborhoodApi**

## Index

### Constructors

* [constructor](neighborhoodapi.md#constructor)

### Properties

* [basePath](neighborhoodapi.md#basepath)
* [configuration](neighborhoodapi.md#configuration)
* [fetch](neighborhoodapi.md#fetch)

### Methods

* [neighborhoodGet](neighborhoodapi.md#neighborhoodget)
* [neighborhoodNhIdDelete](neighborhoodapi.md#neighborhoodnhiddelete)
* [neighborhoodNhIdGet](neighborhoodapi.md#neighborhoodnhidget)
* [neighborhoodNhIdMemberGet](neighborhoodapi.md#neighborhoodnhidmemberget)
* [neighborhoodNhIdMemberMemberIdDelete](neighborhoodapi.md#neighborhoodnhidmembermemberiddelete)
* [neighborhoodNhIdMemberPost](neighborhoodapi.md#neighborhoodnhidmemberpost)
* [neighborhoodNhIdRelationDelete](neighborhoodapi.md#neighborhoodnhidrelationdelete)
* [neighborhoodNhIdRelationGet](neighborhoodapi.md#neighborhoodnhidrelationget)
* [neighborhoodNhIdRelationPost](neighborhoodapi.md#neighborhoodnhidrelationpost)
* [neighborhoodNhIdRelationRelationNeighborhoodGet](neighborhoodapi.md#neighborhoodnhidrelationrelationneighborhoodget)
* [neighborhoodPost](neighborhoodapi.md#neighborhoodpost)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new NeighborhoodApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, fetch?: *[FetchAPI](../interfaces/fetchapi.md)*): [NeighborhoodApi](neighborhoodapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [typescript-fetch-client-generated/api.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L58)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` fetch | [FetchAPI](../interfaces/fetchapi.md) |  portableFetch |

**Returns:** [NeighborhoodApi](neighborhoodapi.md)

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

<a id="neighborhoodget"></a>

###  neighborhoodGet

▸ **neighborhoodGet**(neighborhoodSpec?: *`string`*, options?: *`any`*): `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4048](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4048)*

*__summary__*: Get an aaray of neighborhoods

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` neighborhoodSpec | `string` |
| `Optional` options | `any` |

**Returns:** `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

___
<a id="neighborhoodnhiddelete"></a>

###  neighborhoodNhIdDelete

▸ **neighborhoodNhIdDelete**(nhId: *`number`*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:4060](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4060)*

*__summary__*: Delete neighborhood by ID

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="neighborhoodnhidget"></a>

###  neighborhoodNhIdGet

▸ **neighborhoodNhIdGet**(nhId: *`number`*, options?: *`any`*): `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4072](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4072)*

*__summary__*: Get the entire neighborhood heirarchy below this neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

___
<a id="neighborhoodnhidmemberget"></a>

###  neighborhoodNhIdMemberGet

▸ **neighborhoodNhIdMemberGet**(nhId: *`number`*, options?: *`any`*): `Promise`<[Member](../interfaces/member.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4084](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4084)*

*__summary__*: Get list of members for neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[Member](../interfaces/member.md)[]>

___
<a id="neighborhoodnhidmembermemberiddelete"></a>

###  neighborhoodNhIdMemberMemberIdDelete

▸ **neighborhoodNhIdMemberMemberIdDelete**(nhId: *`number`*, memberId: *`number`*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:4097](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4097)*

*__summary__*: Delete member from neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| memberId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="neighborhoodnhidmemberpost"></a>

###  neighborhoodNhIdMemberPost

▸ **neighborhoodNhIdMemberPost**(nhId: *`number`*, member: *[Member](../interfaces/member.md)*, options?: *`any`*): `Promise`<[Member](../interfaces/member.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4110](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4110)*

*__summary__*: Add a member to neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| member | [Member](../interfaces/member.md) |  Member creation details |
| `Optional` options | `any` |

**Returns:** `Promise`<[Member](../interfaces/member.md)[]>

___
<a id="neighborhoodnhidrelationdelete"></a>

###  neighborhoodNhIdRelationDelete

▸ **neighborhoodNhIdRelationDelete**(nhId: *`number`*, relation: *`string`*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:4123](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4123)*

*__summary__*: Delete all custom relations from neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| relation | `string` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="neighborhoodnhidrelationget"></a>

###  neighborhoodNhIdRelationGet

▸ **neighborhoodNhIdRelationGet**(nhId: *`number`*, options?: *`any`*): `Promise`<[Relation](../interfaces/relation.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4135](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4135)*

*__summary__*: Get list of relations in a neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[Relation](../interfaces/relation.md)[]>

___
<a id="neighborhoodnhidrelationpost"></a>

###  neighborhoodNhIdRelationPost

▸ **neighborhoodNhIdRelationPost**(nhId: *`number`*, relationship: *[Relation](../interfaces/relation.md)*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:4148](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4148)*

*__summary__*: Add a custom relation to neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| relationship | [Relation](../interfaces/relation.md) |  Relationship creation details |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="neighborhoodnhidrelationrelationneighborhoodget"></a>

###  neighborhoodNhIdRelationRelationNeighborhoodGet

▸ **neighborhoodNhIdRelationRelationNeighborhoodGet**(nhId: *`number`*, relation: *`string`*, options?: *`any`*): `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4161](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4161)*

Returns the Neighborhood for the given path

*__summary__*: Get Neighborhood for the specific path.

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| relation | `string` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[Neighborhood](../interfaces/neighborhood.md)[]>

___
<a id="neighborhoodpost"></a>

###  neighborhoodPost

▸ **neighborhoodPost**(neighborhood: *[Neighborhood](../interfaces/neighborhood.md)*, options?: *`any`*): `Promise`<[Neighborhood](../interfaces/neighborhood.md)>

*Defined in [typescript-fetch-client-generated/api.ts:4173](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4173)*

*__summary__*: Creates a new neighborhood

*__throws__*: {RequiredError}

*__memberof__*: NeighborhoodApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| neighborhood | [Neighborhood](../interfaces/neighborhood.md) |  Neighborhood creation detail |
| `Optional` options | `any` |

**Returns:** `Promise`<[Neighborhood](../interfaces/neighborhood.md)>

___

