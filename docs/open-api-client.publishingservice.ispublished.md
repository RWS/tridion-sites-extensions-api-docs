<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [PublishingService](./open-api-client.publishingservice.md) &gt; [isPublished](./open-api-client.publishingservice.ispublished.md)

## PublishingService.isPublished() method

Indicates whether a specified item is published (true) or not (false).

**Signature:**

```typescript
static isPublished({ escapedItemId, isPublishedInContext, targetIdOrPurpose, }: {
        escapedItemId: string;
        isPublishedInContext: boolean;
        targetIdOrPurpose?: string;
    }): CancelablePromise<boolean>;
```

## Parameters

| Parameter                                                   | Type                                                                                  | Description |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------- | ----------- |
| { escapedItemId, isPublishedInContext, targetIdOrPurpose, } | { escapedItemId: string; isPublishedInContext: boolean; targetIdOrPurpose?: string; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;boolean&gt;

boolean Successfully published

## Exceptions

ApiError
