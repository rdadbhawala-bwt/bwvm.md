[bcvm](../README.md) > [CollaborationApi](../classes/collaborationapi.md)

# Class: CollaborationApi

CollaborationApi - object-oriented interface

*__export__*: 

*__class__*: CollaborationApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ CollaborationApi**

## Index

### Constructors

* [constructor](collaborationapi.md#constructor)

### Properties

* [basePath](collaborationapi.md#basepath)
* [configuration](collaborationapi.md#configuration)
* [fetch](collaborationapi.md#fetch)

### Methods

* [collaborationCollabIdDelete](collaborationapi.md#collaborationcollabiddelete)
* [collaborationCollabIdGridsGet](collaborationapi.md#collaborationcollabidgridsget)
* [collaborationCollabIdWhiteboardGet](collaborationapi.md#collaborationcollabidwhiteboardget)
* [collaborationCollabIdWhiteboardPost](collaborationapi.md#collaborationcollabidwhiteboardpost)
* [collaborationCollabIdWhiteboardWhiteboardIdDelete](collaborationapi.md#collaborationcollabidwhiteboardwhiteboardiddelete)
* [collaborationCollabIdWhiteboardWhiteboardIdGridsGet](collaborationapi.md#collaborationcollabidwhiteboardwhiteboardidgridsget)
* [collaborationPost](collaborationapi.md#collaborationpost)
* [neighborhoodNhIdCollaborationGet](collaborationapi.md#neighborhoodnhidcollaborationget)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new CollaborationApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, fetch?: *[FetchAPI](../interfaces/fetchapi.md)*): [CollaborationApi](collaborationapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [typescript-fetch-client-generated/api.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L58)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` fetch | [FetchAPI](../interfaces/fetchapi.md) |  portableFetch |

**Returns:** [CollaborationApi](collaborationapi.md)

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

<a id="collaborationcollabiddelete"></a>

###  collaborationCollabIdDelete

▸ **collaborationCollabIdDelete**(collabId: *`number`*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:2240](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2240)*

*__summary__*: Delete collaboration by ID

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| collabId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="collaborationcollabidgridsget"></a>

###  collaborationCollabIdGridsGet

▸ **collaborationCollabIdGridsGet**(collabId: *`number`*, options?: *`any`*): `Promise`<`GridInfo`[]>

*Defined in [typescript-fetch-client-generated/api.ts:2252](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2252)*

User can GET the list of Grids present in the Whiteboard of the Collaboration using his/her memberships details for that Neighborhood.

*__summary__*: Get the list of all Grids present in the Whiteboard of the Collaboration in Neighborhood that user can access using his/her Neighborhood memberships.

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| collabId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`GridInfo`[]>

___
<a id="collaborationcollabidwhiteboardget"></a>

###  collaborationCollabIdWhiteboardGet

▸ **collaborationCollabIdWhiteboardGet**(collabId: *`number`*, options?: *`any`*): `Promise`<[Whiteboard](../interfaces/whiteboard.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:2264](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2264)*

*__summary__*: Get the whiteboards for a collaboration

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| collabId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[Whiteboard](../interfaces/whiteboard.md)[]>

___
<a id="collaborationcollabidwhiteboardpost"></a>

###  collaborationCollabIdWhiteboardPost

▸ **collaborationCollabIdWhiteboardPost**(collabId: *`number`*, wb: *[Whiteboard](../interfaces/whiteboard.md)*, options?: *`any`*): `Promise`<`number`>

*Defined in [typescript-fetch-client-generated/api.ts:2277](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2277)*

*__summary__*: Create new Whiteboard

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| collabId | `number` |  \- |
| wb | [Whiteboard](../interfaces/whiteboard.md) |  Whiteboard creation details |
| `Optional` options | `any` |

**Returns:** `Promise`<`number`>

___
<a id="collaborationcollabidwhiteboardwhiteboardiddelete"></a>

###  collaborationCollabIdWhiteboardWhiteboardIdDelete

▸ **collaborationCollabIdWhiteboardWhiteboardIdDelete**(collabId: *`number`*, whiteboardId: *`number`*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:2290](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2290)*

*__summary__*: Delete whiteboard by ID

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| collabId | `number` |  \- |
| whiteboardId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="collaborationcollabidwhiteboardwhiteboardidgridsget"></a>

###  collaborationCollabIdWhiteboardWhiteboardIdGridsGet

▸ **collaborationCollabIdWhiteboardWhiteboardIdGridsGet**(collabId: *`number`*, whiteboardId: *`number`*, options?: *`any`*): `Promise`<`GridInfo`[]>

*Defined in [typescript-fetch-client-generated/api.ts:2303](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2303)*

User can GET the list of Grids present in the Whiteboard of the Collaboration using his/her memberships details for that Neighborhood.

*__summary__*: Get the list of all Grids present in the Whiteboard of the Collaboration in Neighborhood that user can access using his/her Neighborhood memberships.

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| collabId | `number` |  \- |
| whiteboardId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`GridInfo`[]>

___
<a id="collaborationpost"></a>

###  collaborationPost

▸ **collaborationPost**(collab: *[Collaboration](../interfaces/collaboration.md)*, options?: *`any`*): `Promise`<[Collaboration](../interfaces/collaboration.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:2315](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2315)*

*__summary__*: Create new collaboration

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| collab | [Collaboration](../interfaces/collaboration.md) |  Collaboration creation details |
| `Optional` options | `any` |

**Returns:** `Promise`<[Collaboration](../interfaces/collaboration.md)[]>

___
<a id="neighborhoodnhidcollaborationget"></a>

###  neighborhoodNhIdCollaborationGet

▸ **neighborhoodNhIdCollaborationGet**(nhId: *`number`*, options?: *`any`*): `Promise`<[Collaboration](../interfaces/collaboration.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:2327](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2327)*

*__summary__*: Get the collaboration heirarchy

*__throws__*: {RequiredError}

*__memberof__*: CollaborationApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| nhId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[Collaboration](../interfaces/collaboration.md)[]>

___

