[bcvm](../README.md) > [UserApi](../classes/userapi.md)

# Class: UserApi

UserApi - object-oriented interface

*__export__*: 

*__class__*: UserApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ UserApi**

## Index

### Constructors

* [constructor](userapi.md#constructor)

### Properties

* [basePath](userapi.md#basepath)
* [configuration](userapi.md#configuration)
* [fetch](userapi.md#fetch)

### Methods

* [userGet](userapi.md#userget)
* [userMembershipsGet](userapi.md#usermembershipsget)
* [userPost](userapi.md#userpost)
* [userPut](userapi.md#userput)
* [userUserIdDelete](userapi.md#useruseriddelete)
* [userUserIdGet](userapi.md#useruseridget)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new UserApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, fetch?: *[FetchAPI](../interfaces/fetchapi.md)*): [UserApi](userapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [typescript-fetch-client-generated/api.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L58)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` fetch | [FetchAPI](../interfaces/fetchapi.md) |  portableFetch |

**Returns:** [UserApi](userapi.md)

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

<a id="userget"></a>

###  userGet

▸ **userGet**(active?: *`boolean`*, options?: *`any`*): `Promise`<[User](../interfaces/user.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4722](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4722)*

Gets all users in the system, can be filtered by active/inactive users

*__summary__*: Get all users in the system

*__throws__*: {RequiredError}

*__memberof__*: UserApi

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` active | `boolean` |
| `Optional` options | `any` |

**Returns:** `Promise`<[User](../interfaces/user.md)[]>

___
<a id="usermembershipsget"></a>

###  userMembershipsGet

▸ **userMembershipsGet**(email: *`string`*, options?: *`any`*): `Promise`<[Membership](../interfaces/membership.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4734](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4734)*

Gets all user memberships in the system. User can Get only his/her memberships details. So {email} and user in Authrization must match.

*__summary__*: Get all user memberships in the system

*__throws__*: {RequiredError}

*__memberof__*: UserApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| email | `string` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[Membership](../interfaces/membership.md)[]>

___
<a id="userpost"></a>

###  userPost

▸ **userPost**(user: *[User](../interfaces/user.md)*, options?: *`any`*): `Promise`<[User](../interfaces/user.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4746](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4746)*

*__summary__*: Create new user

*__throws__*: {RequiredError}

*__memberof__*: UserApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| user | [User](../interfaces/user.md) |  User creation details |
| `Optional` options | `any` |

**Returns:** `Promise`<[User](../interfaces/user.md)[]>

___
<a id="userput"></a>

###  userPut

▸ **userPut**(user: *[User](../interfaces/user.md)*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:4758](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4758)*

*__summary__*: Update user profile

*__throws__*: {RequiredError}

*__memberof__*: UserApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| user | [User](../interfaces/user.md) |  User creation details |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="useruseriddelete"></a>

###  userUserIdDelete

▸ **userUserIdDelete**(userId: *`number`*, options?: *`any`*): `Promise`<`string`>

*Defined in [typescript-fetch-client-generated/api.ts:4770](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4770)*

*__summary__*: De-activate user by ID

*__throws__*: {RequiredError}

*__memberof__*: UserApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| userId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<`string`>

___
<a id="useruseridget"></a>

###  userUserIdGet

▸ **userUserIdGet**(userId: *`number`*, options?: *`any`*): `Promise`<[User](../interfaces/user.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:4782](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4782)*

*__summary__*: Get a specific user profile from the systems

*__throws__*: {RequiredError}

*__memberof__*: UserApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| userId | `number` |  \- |
| `Optional` options | `any` |

**Returns:** `Promise`<[User](../interfaces/user.md)[]>

___

