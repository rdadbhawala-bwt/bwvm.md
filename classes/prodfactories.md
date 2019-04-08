[bcvm](../README.md) > [ProdFactories](../classes/prodfactories.md)

# Class: ProdFactories

## Hierarchy

**ProdFactories**

## Implements

* [IFactories](../interfaces/ifactories.md)

## Index

### Properties

* [mod](prodfactories.md#mod)

### Methods

* [CreateEnvironment](prodfactories.md#createenvironment)
* [CreateModified](prodfactories.md#createmodified)
* [CreateRestApi](prodfactories.md#createrestapi)

---

## Properties

<a id="mod"></a>

###  mod

**● mod**: *[IModified](../interfaces/imodified.md)* =  new i.Modified()

*Defined in [index.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/index.ts#L15)*

___

## Methods

<a id="createenvironment"></a>

###  CreateEnvironment

▸ **CreateEnvironment**(pCred: *`m.Credentials`*): [IEnvironment](../interfaces/ienvironment.md)

*Defined in [index.ts:11](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/index.ts#L11)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCred | `m.Credentials` |

**Returns:** [IEnvironment](../interfaces/ienvironment.md)

___
<a id="createmodified"></a>

###  CreateModified

▸ **CreateModified**(): [IModified](../interfaces/imodified.md)

*Implementation of [IFactories](../interfaces/ifactories.md).[CreateModified](../interfaces/ifactories.md#createmodified)*

*Defined in [index.ts:17](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/index.ts#L17)*

**Returns:** [IModified](../interfaces/imodified.md)

___
<a id="createrestapi"></a>

###  CreateRestApi

▸ **CreateRestApi**(pCred: *`m.Credentials`*): [IRestApi](../interfaces/irestapi.md)

*Defined in [index.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/index.ts#L7)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pCred | `m.Credentials` |

**Returns:** [IRestApi](../interfaces/irestapi.md)

___

