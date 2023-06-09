<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ItemsService](./open-api-client.itemsservice.md) &gt; [getItemsExtended](./open-api-client.itemsservice.getitemsextended.md)

## ItemsService.getItemsExtended() method

Gets a large number of items by specifying a list of item URIs in the body of the request. This operation returns an instance of 'IdentifiableObjectDictionary' type.

**Signature:**

```typescript
static getItemsExtended(itemIds: Array<string>, useDynamicVersion?: boolean, loadFullItems?: boolean): CancelablePromise<Record<string, IdentifiableObject>>;
```

## Parameters

| Parameter         | Type                | Description                                                                        |
| ----------------- | ------------------- | ---------------------------------------------------------------------------------- |
| itemIds           | Array&lt;string&gt; | A list of item URIs.                                                               |
| useDynamicVersion | boolean             | _(Optional)_ Loads a dynamic version (if available for the current user)           |
| loadFullItems     | boolean             | _(Optional)_ Determines whether full items or partially loaded items are returned. |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Record&lt;string, [IdentifiableObject](./open-api-client.identifiableobject.md)<!-- -->&gt;&gt;

IdentifiableObject The request was successful.

## Exceptions

ApiError
