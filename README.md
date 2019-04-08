
Code Walkthrough
================

File Organization
-----------------

All files are prefixed according to the nature of code in it.

File Group

Description

model\*

Interfaces and Data Structures that are used across all layers of the code.

restApi\*

REST API implementation. Currently based on TypeScript-Fetch client library generated from SwaggerHub. Contains code that manipulates API data structures into model data structures. Also contains the REST Stub which can be used to mock this layer.

impl\*

This is the implementation and orchestration layer. This is where all other components/ layers are brought together. Contains the IEnvironment implementation, which is tne entry point into this library.

editor\*

All implementations that support editing and manipulating a grid. Practically, it should be considered a part of the impl layer.

The folder "typescript-fetch-client-generated" contains the code generation from SwaggerHub, explained in the next section.

Using this Library
------------------

### Code Generation from SwaggerHub

The Boardwalk Server REST APIs are defined in SwaggerHub. Open the "Boardwalk\_Cuboid\_Services" REST API specification. In the SwaggerHub interface, one can see an option to export/ generate server and client side code. The BWVM uses the code generated using the "typescript-fetch" Client SDK. Following custom code generation options were configured:

*   **Supports ES6:** true

Download the package into the `typescript\\src\\typescript-fetch-client-generated\\` folder, and extract all its contents directly into that folder (and not in any sub-folder). The `restApi*` files consume this API and hide the low level calls from the rest of the library. Any change required to adapt to the newly generated code should ideally be isolated to these files only.

### Setting up the Factories (Dependency Injection)

First, the factories must be setup which implement the basic dependency injection between the layers. Look at `indexTest.ts` for an example. Note that it uses a RestStub instead of the real API implementation in RestApi. A 'production' setup is defined in `index.ts`.

### Invoking the Environment

After setting up the factories, create an instance of IEnvironment from the Factories. This is your entry point into the library's functionality. `indexTest.ts` contains a function `callTest` that shows how the IEnvironment can be initialized. `loadGrid` method is the way to

### Important Interfaces:

*   **IGridAllData** is the comprehensive data structure containing all grid information. It is derived from the response of the GridChain API.
    
*   **IGridTxDelta** is a view on Grid information as of a specific transaction ID. Currently, the implementation is designed to just store the specific transaction based on which rows/ columns/ cells get filtered. It is not a new cache of the data structures.
    
*   **IGridTxEditor** is an editor that provides a mechanism to manipulate the grid and track changes. The REST API layer uses this instance to submit all grid changes to the server.
    

### Running Tests

All Unit Tests are stored in the "Unit Tests" folder. To run just the unit tests:

```
> npm run run.unitTests
```

To measure code coverage along with the Unit Tests:

```
> npm run run.testCover
```

The scripts use mocha (testing), chai (asserting) and nyc (coverage) for executing the tests.

## Index

### Modules

* [ImplUtils](modules/implutils.md)
* [RestUtils](modules/restutils.md)

### Enumerations

* [ActionStatus](enums/actionstatus.md)
* [CellChangeFlag](enums/cellchangeflag.md)
* [ChainWindowEnum](enums/chainwindowenum.md)
* [ChangeType](enums/changetype.md)
* [ErrorCode](enums/errorcode.md)

### Classes

* [BaseAPI](classes/baseapi.md)
* [BaseApi](classes/baseapi.md)
* [CellCollBase](classes/cellcollbase.md)
* [CellDataColl](classes/celldatacoll.md)
* [CellEditor](classes/celleditor.md)
* [CellEditorColl](classes/celleditorcoll.md)
* [CellEditorSet](classes/celleditorset.md)
* [CellStatus](classes/cellstatus.md)
* [CellTxChain](classes/celltxchain.md)
* [CellTxValue](classes/celltxvalue.md)
* [CollaborationApi](classes/collaborationapi.md)
* [ColumnCollBase](classes/columncollbase.md)
* [ColumnData](classes/columndata.md)
* [ColumnDataColl](classes/columndatacoll.md)
* [ColumnEditor](classes/columneditor.md)
* [ColumnEditorColl](classes/columneditorcoll.md)
* [ColumnEditorSet](classes/columneditorset.md)
* [Configuration](classes/configuration.md)
* [Constants](classes/constants.md)
* [Environment](classes/environment.md)
* [FormulaData](classes/formuladata.md)
* [FormulaMap](classes/formulamap.md)
* [GridAllData](classes/gridalldata.md)
* [GridApi](classes/gridapi.md)
* [GridColl](classes/gridcoll.md)
* [GridTxDelta](classes/gridtxdelta.md)
* [GridTxEditor](classes/gridtxeditor.md)
* [GridchainApi](classes/gridchainapi.md)
* [Modified](classes/modified.md)
* [NeighborhoodApi](classes/neighborhoodapi.md)
* [NhPathApi](classes/nhpathapi.md)
* [ProdFactories](classes/prodfactories.md)
* [RangeEditorMatrix](classes/rangeeditormatrix.md)
* [RequiredError](classes/requirederror.md)
* [RestApi](classes/restapi.md)
* [RowCollBase](classes/rowcollbase.md)
* [RowData](classes/rowdata.md)
* [RowDataColl](classes/rowdatacoll.md)
* [RowEditor](classes/roweditor.md)
* [RowEditorColl](classes/roweditorcoll.md)
* [RowEditorSet](classes/roweditorset.md)
* [SubmitStatus](classes/submitstatus.md)
* [TxData](classes/txdata.md)
* [TxDataColl](classes/txdatacoll.md)
* [UserApi](classes/userapi.md)
* [VmError](classes/vmerror.md)

### Interfaces

* [CellBuffer](interfaces/cellbuffer.md)
* [CellChain](interfaces/cellchain.md)
* [CellTransaction](interfaces/celltransaction.md)
* [ChangedCell](interfaces/changedcell.md)
* [Collaboration](interfaces/collaboration.md)
* [ColumnChain](interfaces/columnchain.md)
* [ColumnFields](interfaces/columnfields.md)
* [ConfigurationParameters](interfaces/configurationparameters.md)
* [Credentials](interfaces/credentials.md)
* [ErrorRequestObject](interfaces/errorrequestobject.md)
* [FetchAPI](interfaces/fetchapi.md)
* [FetchArgs](interfaces/fetchargs.md)
* [FormulaValue](interfaces/formulavalue.md)
* [Grid](interfaces/grid.md)
* [GridChain](interfaces/gridchain.md)
* [GridChangeBuffer](interfaces/gridchangebuffer.md)
* [GridChanges](interfaces/gridchanges.md)
* [GridInfo](interfaces/gridinfo.md)
* [GridTransaction](interfaces/gridtransaction.md)
* [ICell](interfaces/icell.md)
* [ICellChainFields](interfaces/icellchainfields.md)
* [ICellCollection](interfaces/icellcollection.md)
* [ICellDataCollection](interfaces/icelldatacollection.md)
* [ICellEditor](interfaces/icelleditor.md)
* [ICellEditorCollection](interfaces/icelleditorcollection.md)
* [ICellEditorSet](interfaces/icelleditorset.md)
* [ICellStatus](interfaces/icellstatus.md)
* [ICellStatusFields](interfaces/icellstatusfields.md)
* [ICellTransactionFields](interfaces/icelltransactionfields.md)
* [ICellTxChain](interfaces/icelltxchain.md)
* [ICellTxValue](interfaces/icelltxvalue.md)
* [IColumn](interfaces/icolumn.md)
* [IColumnCollection](interfaces/icolumncollection.md)
* [IColumnData](interfaces/icolumndata.md)
* [IColumnDataCollection](interfaces/icolumndatacollection.md)
* [IColumnEditor](interfaces/icolumneditor.md)
* [IColumnEditorCollection](interfaces/icolumneditorcollection.md)
* [IColumnEditorSet](interfaces/icolumneditorset.md)
* [IEnvironment](interfaces/ienvironment.md)
* [IFactories](interfaces/ifactories.md)
* [IFormula](interfaces/iformula.md)
* [IFormulaValueFields](interfaces/iformulavaluefields.md)
* [IGridAllData](interfaces/igridalldata.md)
* [IGridChange](interfaces/igridchange.md)
* [IGridTxDelta](interfaces/igridtxdelta.md)
* [IGridTxEditor](interfaces/igridtxeditor.md)
* [IGrids](interfaces/igrids.md)
* [IModified](interfaces/imodified.md)
* [IPaginator](interfaces/ipaginator.md)
* [IRange](interfaces/irange.md)
* [IRangeData](interfaces/irangedata.md)
* [IRangeEditor](interfaces/irangeeditor.md)
* [IRangeEditorGrid](interfaces/irangeeditorgrid.md)
* [IRangeEditorSet](interfaces/irangeeditorset.md)
* [IRangeRow](interfaces/irangerow.md)
* [IRestApi](interfaces/irestapi.md)
* [IRow](interfaces/irow.md)
* [IRowCollection](interfaces/irowcollection.md)
* [IRowData](interfaces/irowdata.md)
* [IRowDataCollection](interfaces/irowdatacollection.md)
* [IRowEditor](interfaces/iroweditor.md)
* [IRowEditorCollection](interfaces/iroweditorcollection.md)
* [IRowEditorSet](interfaces/iroweditorset.md)
* [ISubmitPrefs](interfaces/isubmitprefs.md)
* [ITxColl](interfaces/itxcoll.md)
* [ITxData](interfaces/itxdata.md)
* [Member](interfaces/member.md)
* [Membership](interfaces/membership.md)
* [MessageDetail](interfaces/messagedetail.md)
* [Neighborhood](interfaces/neighborhood.md)
* [NeighborhoodPath](interfaces/neighborhoodpath.md)
* [Relation](interfaces/relation.md)
* [RequestErrorInfo](interfaces/requesterrorinfo.md)
* [ResponseErrorInfo](interfaces/responseerrorinfo.md)
* [ResponseInfo](interfaces/responseinfo.md)
* [RowChain](interfaces/rowchain.md)
* [RowFields](interfaces/rowfields.md)
* [SampleDataTypes](interfaces/sampledatatypes.md)
* [SequencedCellArray](interfaces/sequencedcellarray.md)
* [StatusChange](interfaces/statuschange.md)
* [Transaction](interfaces/transaction.md)
* [TransactionFields](interfaces/transactionfields.md)
* [User](interfaces/user.md)
* [Whiteboard](interfaces/whiteboard.md)

### Variables

* [BASE_PATH](#base_path)
* [Factories](#factories)
* [fetchHeaders](#fetchheaders)
* [fetchOptions](#fetchoptions)

### Functions

* [CollaborationApiFactory](#collaborationapifactory)
* [CollaborationApiFetchParamCreator](#collaborationapifetchparamcreator)
* [CollaborationApiFp](#collaborationapifp)
* [CreateEnvironment](#createenvironment)
* [CreateRestApi](#createrestapi)
* [GridApiFactory](#gridapifactory)
* [GridApiFetchParamCreator](#gridapifetchparamcreator)
* [GridApiFp](#gridapifp)
* [GridchainApiFactory](#gridchainapifactory)
* [GridchainApiFetchParamCreator](#gridchainapifetchparamcreator)
* [GridchainApiFp](#gridchainapifp)
* [NeighborhoodApiFactory](#neighborhoodapifactory)
* [NeighborhoodApiFetchParamCreator](#neighborhoodapifetchparamcreator)
* [NeighborhoodApiFp](#neighborhoodapifp)
* [NhPathApiFactory](#nhpathapifactory)
* [NhPathApiFetchParamCreator](#nhpathapifetchparamcreator)
* [NhPathApiFp](#nhpathapifp)
* [SetDefaultHeaders](#setdefaultheaders)
* [SetDefaultOptions](#setdefaultoptions)
* [SetupProdFactories](#setupprodfactories)
* [UserApiFactory](#userapifactory)
* [UserApiFetchParamCreator](#userapifetchparamcreator)
* [UserApiFp](#userapifp)
* [setFactories](#setfactories)

### Object literals

* [COLLECTION_FORMATS](#collection_formats)

---

## Variables

<a id="base_path"></a>

### `<Const>` BASE_PATH

**● BASE_PATH**: *`string`* =  "https://api.boardwalktech.com/v2".replace(/\/+$/, "")

*Defined in [typescript-fetch-client-generated/api.ts:20](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L20)*

___
<a id="factories"></a>

###  Factories

**● Factories**: *[IFactories](interfaces/ifactories.md)*

*Defined in [model.ts:48](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L48)*

Factories is a public static reference to an instance of IFactories. IFactories must be setup at the beginning of the application with the setFactories method.

*__var__*: 

*__static__*: 

___
<a id="fetchheaders"></a>

### `<Let>` fetchHeaders

**● fetchHeaders**: *`object`*

*Defined in [restApi.ts:12](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L12)*

#### Type declaration

___
<a id="fetchoptions"></a>

### `<Let>` fetchOptions

**● fetchOptions**: *`object`*

*Defined in [restApi.ts:11](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L11)*

#### Type declaration

___

## Functions

<a id="collaborationapifactory"></a>

### `<Const>` CollaborationApiFactory

▸ **CollaborationApiFactory**(configuration?: *[Configuration](classes/configuration.md)*, fetch?: *[FetchAPI](interfaces/fetchapi.md)*, basePath?: *`string`*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:2137](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2137)*

CollaborationApi - factory interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |
| `Optional` fetch | [FetchAPI](interfaces/fetchapi.md) |
| `Optional` basePath | `string` |

**Returns:** `object`

___
<a id="collaborationapifetchparamcreator"></a>

### `<Const>` CollaborationApiFetchParamCreator

▸ **CollaborationApiFetchParamCreator**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:1660](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L1660)*

CollaborationApi - fetch parameter creator

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="collaborationapifp"></a>

### `<Const>` CollaborationApiFp

▸ **CollaborationApiFp**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:1973](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L1973)*

CollaborationApi - functional programming interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="createenvironment"></a>

###  CreateEnvironment

▸ **CreateEnvironment**(cred: *`m.Credentials`*): [IEnvironment](interfaces/ienvironment.md)

*Defined in [impl.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/impl.ts#L7)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cred | `m.Credentials` |

**Returns:** [IEnvironment](interfaces/ienvironment.md)

___
<a id="createrestapi"></a>

###  CreateRestApi

▸ **CreateRestApi**(cred: *`m.Credentials`*): [IRestApi](interfaces/irestapi.md)

*Defined in [restApi.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L7)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| cred | `m.Credentials` |

**Returns:** [IRestApi](interfaces/irestapi.md)

___
<a id="gridapifactory"></a>

### `<Const>` GridApiFactory

▸ **GridApiFactory**(configuration?: *[Configuration](classes/configuration.md)*, fetch?: *[FetchAPI](interfaces/fetchapi.md)*, basePath?: *`string`*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:2681](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2681)*

GridApi - factory interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |
| `Optional` fetch | [FetchAPI](interfaces/fetchapi.md) |
| `Optional` basePath | `string` |

**Returns:** `object`

___
<a id="gridapifetchparamcreator"></a>

### `<Const>` GridApiFetchParamCreator

▸ **GridApiFetchParamCreator**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:2337](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2337)*

GridApi - fetch parameter creator

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="gridapifp"></a>

### `<Const>` GridApiFp

▸ **GridApiFp**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:2572](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2572)*

GridApi - functional programming interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="gridchainapifactory"></a>

### `<Const>` GridchainApiFactory

▸ **GridchainApiFactory**(configuration?: *[Configuration](classes/configuration.md)*, fetch?: *[FetchAPI](interfaces/fetchapi.md)*, basePath?: *`string`*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:3133](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3133)*

GridchainApi - factory interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |
| `Optional` fetch | [FetchAPI](interfaces/fetchapi.md) |
| `Optional` basePath | `string` |

**Returns:** `object`

___
<a id="gridchainapifetchparamcreator"></a>

### `<Const>` GridchainApiFetchParamCreator

▸ **GridchainApiFetchParamCreator**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:2819](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L2819)*

GridchainApi - fetch parameter creator

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="gridchainapifp"></a>

### `<Const>` GridchainApiFp

▸ **GridchainApiFp**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:3048](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3048)*

GridchainApi - functional programming interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="neighborhoodapifactory"></a>

### `<Const>` NeighborhoodApiFactory

▸ **NeighborhoodApiFactory**(configuration?: *[Configuration](classes/configuration.md)*, fetch?: *[FetchAPI](interfaces/fetchapi.md)*, basePath?: *`string`*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:3913](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3913)*

NeighborhoodApi - factory interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |
| `Optional` fetch | [FetchAPI](interfaces/fetchapi.md) |
| `Optional` basePath | `string` |

**Returns:** `object`

___
<a id="neighborhoodapifetchparamcreator"></a>

### `<Const>` NeighborhoodApiFetchParamCreator

▸ **NeighborhoodApiFetchParamCreator**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:3255](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3255)*

NeighborhoodApi - fetch parameter creator

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="neighborhoodapifp"></a>

### `<Const>` NeighborhoodApiFp

▸ **NeighborhoodApiFp**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:3690](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L3690)*

NeighborhoodApi - functional programming interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="nhpathapifactory"></a>

### `<Const>` NhPathApiFactory

▸ **NhPathApiFactory**(configuration?: *[Configuration](classes/configuration.md)*, fetch?: *[FetchAPI](interfaces/fetchapi.md)*, basePath?: *`string`*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:4255](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4255)*

NhPathApi - factory interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |
| `Optional` fetch | [FetchAPI](interfaces/fetchapi.md) |
| `Optional` basePath | `string` |

**Returns:** `object`

___
<a id="nhpathapifetchparamcreator"></a>

### `<Const>` NhPathApiFetchParamCreator

▸ **NhPathApiFetchParamCreator**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:4183](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4183)*

NhPathApi - fetch parameter creator

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="nhpathapifp"></a>

### `<Const>` NhPathApiFp

▸ **NhPathApiFp**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:4227](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4227)*

NhPathApi - functional programming interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="setdefaultheaders"></a>

###  SetDefaultHeaders

▸ **SetDefaultHeaders**(obj: *`any`*): `void`

*Defined in [restApi.ts:20](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L20)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| obj | `any` |

**Returns:** `void`

___
<a id="setdefaultoptions"></a>

###  SetDefaultOptions

▸ **SetDefaultOptions**(obj: *`any`*): `void`

*Defined in [restApi.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/restApi.ts#L15)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| obj | `any` |

**Returns:** `void`

___
<a id="setupprodfactories"></a>

###  SetupProdFactories

▸ **SetupProdFactories**(force?: *`boolean`*): `void`

*Defined in [index.ts:22](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/index.ts#L22)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` force | `boolean` |

**Returns:** `void`

___
<a id="userapifactory"></a>

### `<Const>` UserApiFactory

▸ **UserApiFactory**(configuration?: *[Configuration](classes/configuration.md)*, fetch?: *[FetchAPI](interfaces/fetchapi.md)*, basePath?: *`string`*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:4642](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4642)*

UserApi - factory interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |
| `Optional` fetch | [FetchAPI](interfaces/fetchapi.md) |
| `Optional` basePath | `string` |

**Returns:** `object`

___
<a id="userapifetchparamcreator"></a>

### `<Const>` UserApiFetchParamCreator

▸ **UserApiFetchParamCreator**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:4295](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4295)*

UserApi - fetch parameter creator

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="userapifp"></a>

### `<Const>` UserApiFp

▸ **UserApiFp**(configuration?: *[Configuration](classes/configuration.md)*): `object`

*Defined in [typescript-fetch-client-generated/api.ts:4519](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L4519)*

UserApi - functional programming interface

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` configuration | [Configuration](classes/configuration.md) |

**Returns:** `object`

___
<a id="setfactories"></a>

###  setFactories

▸ **setFactories**(f: *[IFactories](interfaces/ifactories.md)*): `void`

*Defined in [model.ts:50](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L50)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| f | [IFactories](interfaces/ifactories.md) |

**Returns:** `void`

___

## Object literals

<a id="collection_formats"></a>

### `<Const>` COLLECTION_FORMATS

**COLLECTION_FORMATS**: *`object`*

*Defined in [typescript-fetch-client-generated/api.ts:26](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L26)*

*__export__*: 

<a id="collection_formats.csv"></a>

####  csv

**● csv**: *`string`* = ","

*Defined in [typescript-fetch-client-generated/api.ts:27](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L27)*

___
<a id="collection_formats.pipes"></a>

####  pipes

**● pipes**: *`string`* = "|"

*Defined in [typescript-fetch-client-generated/api.ts:30](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L30)*

___
<a id="collection_formats.ssv"></a>

####  ssv

**● ssv**: *`string`* = " "

*Defined in [typescript-fetch-client-generated/api.ts:28](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L28)*

___
<a id="collection_formats.tsv"></a>

####  tsv

**● tsv**: *`string`* = "	"

*Defined in [typescript-fetch-client-generated/api.ts:29](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/typescript-fetch-client-generated/api.ts#L29)*

___

___

