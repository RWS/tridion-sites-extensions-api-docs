<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [PublishingService](./open-api-client.publishingservice.md) &gt; [getItemsToUnpublish](./open-api-client.publishingservice.getitemstounpublish.md)

## PublishingService.getItemsToUnpublish() method

Gets a list of items that will be unpublished when executing the specified instructions. This operation returns an instance of 'ResolvedItem' type.

**Signature:**

```typescript
static getItemsToUnpublish({ requestModel, }: {
        requestModel: UnPublishRequest;
    }): CancelablePromise<Array<ResolvedItem>>;
```

## Parameters

| Parameter         | Type                                                                                 | Description |
| ----------------- | ------------------------------------------------------------------------------------ | ----------- |
| { requestModel, } | { requestModel: [UnPublishRequest](./open-api-client.unpublishrequest.md)<!-- -->; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Array&lt;[ResolvedItem](./open-api-client.resolveditem.md)<!-- -->&gt;&gt;

ResolvedItem The request was successful.

## Exceptions

ApiError
