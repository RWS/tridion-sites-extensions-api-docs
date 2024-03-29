<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [BatchOperationsService](./open-api-client.batchoperationsservice.md) &gt; [batchPublish](./open-api-client.batchoperationsservice.batchpublish.md)

## BatchOperationsService.batchPublish() method

Publishes a batch of items. This operation returns an instance of 'BatchOperationCreationResult' type.

**Signature:**

```typescript
static batchPublish({ requestModel, }: {
        requestModel: BatchPublishRequest;
    }): CancelablePromise<BatchOperationCreationResult>;
```

## Parameters

| Parameter         | Type                                                                                       | Description |
| ----------------- | ------------------------------------------------------------------------------------------ | ----------- |
| { requestModel, } | { requestModel: [BatchPublishRequest](./open-api-client.batchpublishrequest.md)<!-- -->; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[BatchOperationCreationResult](./open-api-client.batchoperationcreationresult.md)<!-- -->&gt;

BatchOperationCreationResult The request has been accepted for processing, but the processing has not been completed.

## Exceptions

ApiError
