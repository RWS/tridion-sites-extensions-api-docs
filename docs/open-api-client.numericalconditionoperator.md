<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [NumericalConditionOperator](./open-api-client.numericalconditionoperator.md)

## NumericalConditionOperator enum

Defines the operator used for comparison of numerical operands.

Members: \* `Equals` - Compares if a numerical operand is equal to the given condition value.

\* `GreaterThan` - Compares if a numerical operand is greater than the given condition value.

\* `LessThan` - Compares if a numerical operand is less than the given condition value.

\* `NotEqual` - Compares if a numerical operand is not equal to the given condition value.

\* `UnknownByClient` - Special reserved value used to notify an older API version client about the presence of an enumeration member added in a later API version. Explicitly setting this value by a client is not allowed, but client code should check it and be able to handle such cases.

**Signature:**

```typescript
export declare enum NumericalConditionOperator
```

## Enumeration Members

| Member            | Value                                    | Description |
| ----------------- | ---------------------------------------- | ----------- |
| EQUALS            | <code>&quot;Equals&quot;</code>          |             |
| GREATER_THAN      | <code>&quot;GreaterThan&quot;</code>     |             |
| LESS_THAN         | <code>&quot;LessThan&quot;</code>        |             |
| NOT_EQUAL         | <code>&quot;NotEqual&quot;</code>        |             |
| UNKNOWN_BY_CLIENT | <code>&quot;UnknownByClient&quot;</code> |             |
