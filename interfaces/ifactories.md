[bcvm](../README.md) > [IFactories](../interfaces/ifactories.md)

# Interface: IFactories

IFactories is the Dependency Injection Wrapper to instantiate any service in the VM.

## Hierarchy

**IFactories**

## Implemented by

* [ProdFactories](../classes/prodfactories.md)

## Index

### Methods

* [CreateEnvironment](ifactories.md#createenvironment)
* [CreateModified](ifactories.md#createmodified)
* [CreateRestApi](ifactories.md#createrestapi)

---

## Methods

<a id="createenvironment"></a>

###  CreateEnvironment

▸ **CreateEnvironment**(pCred: *[Credentials](credentials.md)*): [IEnvironment](ienvironment.md)

*Defined in [model.ts:31](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L31)*

Create an Environment

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| pCred | [Credentials](credentials.md) |  is an instance of ICredentails to access the REST APIs. |

**Returns:** [IEnvironment](ienvironment.md)
an instance of IEnvironment.

___
<a id="createmodified"></a>

###  CreateModified

▸ **CreateModified**(): [IModified](imodified.md)

*Defined in [model.ts:37](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L37)*

Creates an instance of IModified service, which evalutates if an object is modified.

**Returns:** [IModified](imodified.md)
an instance of IModified.

___
<a id="createrestapi"></a>

###  CreateRestApi

▸ **CreateRestApi**(pCred: *[Credentials](credentials.md)*): [IRestApi](irestapi.md)

*Defined in [model.ts:25](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.ts#L25)*

Create the REST API Wrapper.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| pCred | [Credentials](credentials.md) |  is an instance of ICRedentails to access the REST APIs |

**Returns:** [IRestApi](irestapi.md)
an instance of IRestApi

___

