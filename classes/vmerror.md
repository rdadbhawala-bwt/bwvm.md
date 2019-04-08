[bcvm](../README.md) > [VmError](../classes/vmerror.md)

# Class: VmError

## Hierarchy

 `Error`

**↳ VmError**

## Index

### Constructors

* [constructor](vmerror.md#constructor)

### Properties

* [errCode](vmerror.md#errcode)
* [message](vmerror.md#message)
* [name](vmerror.md#name)
* [stack](vmerror.md#stack)
* [Error](vmerror.md#error)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new VmError**(code: *[ErrorCode](../enums/errorcode.md)*): [VmError](vmerror.md)

*Defined in [model.base.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.base.ts#L52)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| code | [ErrorCode](../enums/errorcode.md) |

**Returns:** [VmError](vmerror.md)

___

## Properties

<a id="errcode"></a>

###  errCode

**● errCode**: *[ErrorCode](../enums/errorcode.md)* =  ErrorCode.Unknown

*Defined in [model.base.ts:52](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.base.ts#L52)*

___
<a id="message"></a>

###  message

**● message**: *`string`*

*Inherited from Error.message*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:964*

___
<a id="name"></a>

###  name

**● name**: *`string`*

*Inherited from Error.name*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:963*

___
<a id="stack"></a>

### `<Optional>` stack

**● stack**: *`string`*

*Inherited from Error.stack*

*Overrides Error.stack*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:965*

___
<a id="error"></a>

### `<Static>` Error

**● Error**: *`ErrorConstructor`*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:974*

___

