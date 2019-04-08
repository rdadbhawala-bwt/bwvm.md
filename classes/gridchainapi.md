[bcvm](../README.md) > [GridchainApi](../classes/gridchainapi.md)

# Class: GridchainApi

GridchainApi - object-oriented interface

*__export__*: 

*__class__*: GridchainApi

*__extends__*: {BaseAPI}

## Hierarchy

 [BaseAPI](baseapi.md)

**↳ GridchainApi**

## Index

### Constructors

* [constructor](gridchainapi.md#constructor)

### Properties

* [basePath](gridchainapi.md#basepath)
* [configuration](gridchainapi.md#configuration)
* [fetch](gridchainapi.md#fetch)

### Methods

* [gridchainGridIdGet](gridchainapi.md#gridchaingrididget)
* [gridchainGridIdPut](gridchainapi.md#gridchaingrididput)
* [gridchainGridIdTransactionsGet](gridchainapi.md#gridchaingrididtransactionsget)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new GridchainApi**(configuration?: *[Configuration](configuration.md)*, basePath?: *`string`*, fetch?: *[FetchAPI](../interfaces/fetchapi.md)*): [GridchainApi](gridchainapi.md)

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [typescript-fetch-client-generated/api.ts:58](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L58)*

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| `Optional` configuration | [Configuration](configuration.md) | - |
| `Default value` basePath | `string` |  BASE_PATH |
| `Default value` fetch | [FetchAPI](../interfaces/fetchapi.md) |  portableFetch |

**Returns:** [GridchainApi](gridchainapi.md)

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

<a id="gridchaingrididget"></a>

###  gridchainGridIdGet

▸ **gridchainGridIdGet**(gridId: *`number`*, viewPref: *`string`*, chainWindow: *`string`*, activityPeriod?: *`string`*, startDate?: *`number`*, endDate?: *`number`*, localTimeAfter111970?: *`number`*, startTxId?: *`number`*, endTxId?: *`number`*, filter?: *`string`*, options?: *`any`*): `Promise`<[GridChain](../interfaces/gridchain.md)>

*Defined in [typescript-fetch-client-generated/api.ts:3211](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3211)*

User can GET all Grid Component, it's status, History, Transactions done on entire grid. Information of the Grid present in the Whiteboard of the Collaboration using his/her memberships details for that Neighborhood. So {email} and user in Authrization must match. Also {nhPath} and nhPath in Authorization should match. The Grid information will have Column Names, sequence Number, Active/inactive & Access Control ( R/W ), Column Count, Row Count, Access Control for Add Row, Delete Row, Insert Column, Delete Column, Edit Data, Cuboid Properties. If user is the Owner then Accesss Control Cuboid information.

*__summary__*: Get a section or the full grid based on specification

*__throws__*: {RequiredError}

*__memberof__*: GridchainApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| gridId | `number` |  \- |
| viewPref | `string` |  \- |
| chainWindow | `string` |  \- |
| `Optional` activityPeriod | `string` |
| `Optional` startDate | `number` |
| `Optional` endDate | `number` |
| `Optional` localTimeAfter111970 | `number` |
| `Optional` startTxId | `number` |
| `Optional` endTxId | `number` |
| `Optional` filter | `string` |
| `Optional` options | `any` |

**Returns:** `Promise`<[GridChain](../interfaces/gridchain.md)>

___
<a id="gridchaingrididput"></a>

###  gridchainGridIdPut

▸ **gridchainGridIdPut**(gridId: *`number`*, cellBufferRequest: *[CellBuffer](../interfaces/cellbuffer.md)*, options?: *`any`*): `Promise`<[GridChain](../interfaces/gridchain.md)>

*Defined in [typescript-fetch-client-generated/api.ts:3224](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3224)*

User submit Changes to Server as CellBuffer along with the ImportTxId. User Changes are saved to Database on Server and current ExportTxId is generated. In response GridChain is returned that has all Grid changes done between ImportTxId and current ExportTxId. The GridChain includes all changed cells, it's status, History, Transactions done on entire grid between the ImportTxId and the Current ExportTxId.

*__summary__*: Submit Changes in GridChain. Also Returns GET GridChain BETWEENTX in response.

*__throws__*: {RequiredError}

*__memberof__*: GridchainApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| gridId | `number` |  \- |
| cellBufferRequest | [CellBuffer](../interfaces/cellbuffer.md) |  Cell buffer details |
| `Optional` options | `any` |

**Returns:** `Promise`<[GridChain](../interfaces/gridchain.md)>

___
<a id="gridchaingrididtransactionsget"></a>

###  gridchainGridIdTransactionsGet

▸ **gridchainGridIdTransactionsGet**(gridId: *`number`*, viewPref: *`string`*, reportType: *`string`*, activityPeriod?: *`string`*, startDate?: *`number`*, endDate?: *`number`*, localTimeAfter111970?: *`number`*, startTxId?: *`number`*, endTxId?: *`number`*, importTxId?: *`number`*, options?: *`any`*): `Promise`<[GridTransaction](../interfaces/gridtransaction.md)[]>

*Defined in [typescript-fetch-client-generated/api.ts:3245](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3245)*

*__summary__*: Get cuboid transactions for time interval for a given specification

*__throws__*: {RequiredError}

*__memberof__*: GridchainApi

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| gridId | `number` |  \- |
| viewPref | `string` |  \- |
| reportType | `string` |  \- |
| `Optional` activityPeriod | `string` |
| `Optional` startDate | `number` |
| `Optional` endDate | `number` |
| `Optional` localTimeAfter111970 | `number` |
| `Optional` startTxId | `number` |
| `Optional` endTxId | `number` |
| `Optional` importTxId | `number` |
| `Optional` options | `any` |

**Returns:** `Promise`<[GridTransaction](../interfaces/gridtransaction.md)[]>

___

