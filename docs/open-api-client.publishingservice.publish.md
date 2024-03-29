<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [PublishingService](./open-api-client.publishingservice.md) &gt; [publish](./open-api-client.publishingservice.publish.md)

## PublishingService.publish() method

Publishes items according to the specified instructions. This operation returns an instance of 'PublishTransactionsCreationResult' type.

**Signature:**

```typescript
static publish({ requestModel, }: {
        requestModel: PublishRequest;
    }): CancelablePromise<PublishTransactionsCreationResult>;
```

## Parameters

| Parameter         | Type                                                                             | Description |
| ----------------- | -------------------------------------------------------------------------------- | ----------- |
| { requestModel, } | { requestModel: [PublishRequest](./open-api-client.publishrequest.md)<!-- -->; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[PublishTransactionsCreationResult](./open-api-client.publishtransactionscreationresult.md)<!-- -->&gt;

PublishTransactionsCreationResult The request has been accepted for processing, but the processing has not been completed.

## Exceptions

ApiError
