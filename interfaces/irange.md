[bcvm](../README.md) > [IRange](../interfaces/irange.md)

# Interface: IRange

## Type parameters
#### R :  [IRow](irow.md)
#### C :  [IColumn](icolumn.md)
#### L :  [ICell](icell.md)
#### RC :  [IRowCollection](irowcollection.md)<`R`>
#### CC :  [IColumnCollection](icolumncollection.md)<`C`>
#### LC :  [ICellCollection](icellcollection.md)<`L`>
## Hierarchy

 [IRangeRow](irangerow.md)<`R`, `RC`>

**↳ IRange**

↳  [IRangeData](irangedata.md)

↳  [IRangeEditor](irangeeditor.md)

## Index

### Properties

* [cells](irange.md#cells)
* [columns](irange.md#columns)
* [rows](irange.md#rows)

---

## Properties

<a id="cells"></a>

###  cells

**● cells**: *`LC`*

*Defined in [model.range.ts:16](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L16)*

___
<a id="columns"></a>

###  columns

**● columns**: *`CC`*

*Defined in [model.range.ts:15](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L15)*

___
<a id="rows"></a>

###  rows

**● rows**: *`RC`*

*Inherited from [IRangeRow](irangerow.md).[rows](irangerow.md#rows)*

*Defined in [model.range.ts:7](https://github.com/boardwalktech/Boardwalk-Client-Virtual-Machine-JS/blob/bd51c2e/typescript/src/model.range.ts#L7)*

___

