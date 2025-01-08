<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ItemsService](./open-api-client.itemsservice.md) &gt; [delete](./open-api-client.itemsservice.delete.md)

## ItemsService.delete() method

Permanently deletes an item from the system. You can delete all versions of the item or only a specified version of the item.

**Signature:**

```typescript
static delete({ escapedItemId, }: {
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