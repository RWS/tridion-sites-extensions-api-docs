<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [NumberFieldDefinition](./open-api-client.numberfielddefinition.md)

## NumberFieldDefinition type

Represents a number field definition (in a Schema).

**Signature:**

```typescript
export type NumberFieldDefinition = ItemPublishableFieldDefinition & {
    DefaultValue?: number;
    FractionDigits?: number;
    IsMaxValueExclusive?: boolean;
    IsMinValueExclusive?: boolean;
    List?: NumberListDefinition;
    MaxValue?: number;
    MinValue?: number;
    Pattern?: string;
    TotalDigits?: number;
};
```

**References:** [ItemPublishableFieldDefinition](./open-api-client.itempublishablefielddefinition.md)<!-- -->, [NumberListDefinition](./open-api-client.numberlistdefinition.md)