<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ItemsService](./open-api-client.itemsservice.md) &gt; [itemExists](./open-api-client.itemsservice.itemexists.md)

## ItemsService.itemExists() method

Checks whether an item exists in the system based on its URI.

**Signature:**

```typescript
static itemExists({ escapedItemId, }: {
        escapedItemId: string;
    }): CancelablePromise<void>;
```

## Parameters

| Parameter          | Type                       | Description |
| ------------------ | -------------------------- | ----------- |
| { escapedItemId, } | { escapedItemId: string; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;void&gt;

void

## Exceptions

ApiError
