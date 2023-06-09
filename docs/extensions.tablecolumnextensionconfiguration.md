<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [TableColumnExtensionConfiguration](./extensions.tablecolumnextensionconfiguration.md)

## TableColumnExtensionConfiguration interface

**Signature:**

```typescript
export interface TableColumnExtensionConfiguration<TItem extends IdentifiableObject>
```

## Properties

| Property                                                                 | Modifiers | Type                                                                                                                               | Description                                      |
| ------------------------------------------------------------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| [component](./extensions.tablecolumnextensionconfiguration.component.md) |           | ComponentType&lt;[TableColumnExtensionComponentProps](./extensions.tablecolumnextensioncomponentprops.md)<!-- -->&lt;TItem&gt;&gt; | Component to render on this path                 |
| [id](./extensions.tablecolumnextensionconfiguration.id.md)               |           | string                                                                                                                             | Column id (unique)                               |
| [useColumn](./extensions.tablecolumnextensionconfiguration.usecolumn.md) |           | [TableColumnHook](./extensions.tablecolumnhook.md)                                                                                 | Hook to determine if a table column is available |
