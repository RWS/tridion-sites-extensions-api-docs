<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [ItemUsedByQueryHook](./extensions.itemusedbyqueryhook.md)

## ItemUsedByQueryHook type

**Signature:**

```typescript
export type ItemUsedByQueryHook = <TItem extends IdentifiableObject>(
    props: ItemUsedByQueryProps | undefined,
    options?: QueryOptions<ReadonlyArray<TItem> | undefined, ApiError>,
) => QueryResult<ReadonlyArray<TItem> | undefined, ApiError>;
```

**References:** [IdentifiableObject](./models.identifiableobject.md)<!-- -->, [ItemUsedByQueryProps](./extensions.itemusedbyqueryprops.md)<!-- -->, [QueryOptions](./extensions.queryoptions.md)<!-- -->, [ApiError](./models.apierror.md)<!-- -->, [QueryResult](./extensions.queryresult.md)
