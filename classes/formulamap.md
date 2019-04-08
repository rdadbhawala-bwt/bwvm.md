[bcvm](../README.md) > [FormulaMap](../classes/formulamap.md)

# Class: FormulaMap

## Hierarchy

 `Map`<`number`, [IFormula](../interfaces/iformula.md)>

**↳ FormulaMap**

## Index

### Properties

* [__@toStringTag](formulamap.md#___tostringtag)
* [size](formulamap.md#size)
* [Map](formulamap.md#map)

### Methods

* [__@iterator](formulamap.md#___iterator)
* [clear](formulamap.md#clear)
* [delete](formulamap.md#delete)
* [entries](formulamap.md#entries)
* [forEach](formulamap.md#foreach)
* [get](formulamap.md#get)
* [has](formulamap.md#has)
* [keys](formulamap.md#keys)
* [merge](formulamap.md#merge)
* [set](formulamap.md#set)
* [values](formulamap.md#values)

---

## Properties

<a id="___tostringtag"></a>

###  __@toStringTag

**● __@toStringTag**: *`string`*

*Inherited from Map.[Symbol.toStringTag]*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.symbol.wellknown.d.ts:130*

___
<a id="size"></a>

###  size

**● size**: *`number`*

*Inherited from Map.size*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:28*

___
<a id="map"></a>

### `<Static>` Map

**● Map**: *`MapConstructor`*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:36*

___

## Methods

<a id="___iterator"></a>

###  __@iterator

▸ **__@iterator**(): `IterableIterator`<[`number`, [IFormula](../interfaces/iformula.md)]>

*Inherited from Map.[Symbol.iterator]*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.iterable.d.ts:113*

Returns an iterable of entries in the map.

**Returns:** `IterableIterator`<[`number`, [IFormula](../interfaces/iformula.md)]>

___
<a id="clear"></a>

###  clear

▸ **clear**(): `void`

*Inherited from Map.clear*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:22*

**Returns:** `void`

___
<a id="delete"></a>

###  delete

▸ **delete**(key: *`number`*): `boolean`

*Inherited from Map.delete*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:23*

**Parameters:**

| Name | Type |
| ------ | ------ |
| key | `number` |

**Returns:** `boolean`

___
<a id="entries"></a>

###  entries

▸ **entries**(): `IterableIterator`<[`number`, [IFormula](../interfaces/iformula.md)]>

*Inherited from Map.entries*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.iterable.d.ts:118*

Returns an iterable of key, value pairs for every entry in the map.

**Returns:** `IterableIterator`<[`number`, [IFormula](../interfaces/iformula.md)]>

___
<a id="foreach"></a>

###  forEach

▸ **forEach**(callbackfn: *`function`*, thisArg?: *`any`*): `void`

*Inherited from Map.forEach*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:24*

**Parameters:**

| Name | Type |
| ------ | ------ |
| callbackfn | `function` |
| `Optional` thisArg | `any` |

**Returns:** `void`

___
<a id="get"></a>

###  get

▸ **get**(key: *`number`*): [IFormula](../interfaces/iformula.md) \| `undefined`

*Inherited from Map.get*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:25*

**Parameters:**

| Name | Type |
| ------ | ------ |
| key | `number` |

**Returns:** [IFormula](../interfaces/iformula.md) \| `undefined`

___
<a id="has"></a>

###  has

▸ **has**(key: *`number`*): `boolean`

*Inherited from Map.has*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:26*

**Parameters:**

| Name | Type |
| ------ | ------ |
| key | `number` |

**Returns:** `boolean`

___
<a id="keys"></a>

###  keys

▸ **keys**(): `IterableIterator`<`number`>

*Inherited from Map.keys*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.iterable.d.ts:123*

Returns an iterable of keys in the map

**Returns:** `IterableIterator`<`number`>

___
<a id="merge"></a>

###  merge

▸ **merge**(pFormulas: *[IFormulaValueFields](../interfaces/iformulavaluefields.md)[]*): `void`

*Defined in [model.cell.ts:199](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.cell.ts#L199)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| pFormulas | [IFormulaValueFields](../interfaces/iformulavaluefields.md)[] |

**Returns:** `void`

___
<a id="set"></a>

###  set

▸ **set**(key: *`number`*, value: *[IFormula](../interfaces/iformula.md)*): `this`

*Inherited from Map.set*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.collection.d.ts:27*

**Parameters:**

| Name | Type |
| ------ | ------ |
| key | `number` |
| value | [IFormula](../interfaces/iformula.md) |

**Returns:** `this`

___
<a id="values"></a>

###  values

▸ **values**(): `IterableIterator`<[IFormula](../interfaces/iformula.md)>

*Inherited from Map.values*

*Defined in node_modules/typedoc/node_modules/typescript/lib/lib.es2015.iterable.d.ts:128*

Returns an iterable of values in the map

**Returns:** `IterableIterator`<[IFormula](../interfaces/iformula.md)>

___

