<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [BluePrintingService](./open-api-client.blueprintingservice.md) &gt; [getBluePrintHierarchy](./open-api-client.blueprintingservice.getblueprinthierarchy.md)

## BluePrintingService.getBluePrintHierarchy() method

Gets the context of an item in the BluePrint hierarchy. This operation returns an instance of 'BlueprintHierarchyResponse' type.

**Signature:**

```typescript
static getBluePrintHierarchy({ escapedItemId, details, }: {
        escapedItemId: string;
        details?: 'IdAndTitleOnly' | 'WithApplicableActions' | 'Contentless';
    }): CancelablePromise<BlueprintHierarchyResponse>;
```

## Parameters

| Parameter                   | Type                                                                                               | Description |
| --------------------------- | -------------------------------------------------------------------------------------------------- | ----------- |
| { escapedItemId, details, } | { escapedItemId: string; details?: 'IdAndTitleOnly' \| 'WithApplicableActions' \| 'Contentless'; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[BlueprintHierarchyResponse](./open-api-client.blueprinthierarchyresponse.md)<!-- -->&gt;

BlueprintHierarchyResponse The request was successful.

## Exceptions

ApiError