<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [NumberFieldDefinition](./models.numberfielddefinition.md)

## NumberFieldDefinition class

Represents a number field definition (in a Schema).

**Signature:**

```typescript
export declare class NumberFieldDefinition extends ItemPublishableFieldDefinition
```

**Extends:** [ItemPublishableFieldDefinition](./models.itempublishablefielddefinition.md)

## Constructors

| Constructor                                                                              | Modifiers | Description                                                               |
| ---------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------- |
| [(constructor)({ backendModel, list })](./models.numberfielddefinition._constructor_.md) |           | Constructs a new instance of the <code>NumberFieldDefinition</code> class |

## Properties

| Property                                                                     | Modifiers | Type                                                                                | Description                                                    |
| ---------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| [\_backendModel](./models.numberfielddefinition._backendmodel.md)            |           | [BackendNumberFieldDefinition](./open-api-client.numberfielddefinition.md)          |                                                                |
| [defaultValue](./models.numberfielddefinition.defaultvalue.md)               |           | number \| undefined                                                                 |                                                                |
| [fractionDigits](./models.numberfielddefinition.fractiondigits.md)           |           | number \| undefined                                                                 | Constraints on the number of fraction digits.                  |
| [getInternalModel](./models.numberfielddefinition.getinternalmodel.md)       |           | () =&gt; [BackendNumberFieldDefinition](./open-api-client.numberfielddefinition.md) |                                                                |
| [isMaxValueExclusive](./models.numberfielddefinition.ismaxvalueexclusive.md) |           | boolean                                                                             | Whether the specified maximum value is exclusive or inclusive. |
| [isMinValueExclusive](./models.numberfielddefinition.isminvalueexclusive.md) |           | boolean                                                                             | Whether the specified minimum value is exclusive or inclusive. |
| [list](./models.numberfielddefinition.list.md)                               |           | [NumberListDefinition](./models.numberlistdefinition.md) \| undefined               | List of allowed values                                         |
| [maxValue](./models.numberfielddefinition.maxvalue.md)                       |           | number \| undefined                                                                 | Maximum value constraint.                                      |
| [minValue](./models.numberfielddefinition.minvalue.md)                       |           | number \| undefined                                                                 | Minimum value constraint.                                      |
| [pattern](./models.numberfielddefinition.pattern.md)                         |           | string \| undefined                                                                 | Regular expression pattern to constrain the value.             |
| [totalDigits](./models.numberfielddefinition.totaldigits.md)                 |           | number \| undefined                                                                 | Constraint on the total number of digits.                      |
