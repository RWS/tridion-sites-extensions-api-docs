<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [BatchOperationsService](./open-api-client.batchoperationsservice.md) &gt; [batchRestartActivity](./open-api-client.batchoperationsservice.batchrestartactivity.md)

## BatchOperationsService.batchRestartActivity() method

Restarts a batch of activities. This operation returns an instance of 'BatchOperationCreationResult' type.

**Signature:**

```typescript
static batchRestartActivity(requestModel: BatchOperationRequest): CancelablePromise<BatchOperationCreationResult>;
```

## Parameters

| Parameter    | Type                                                                | Description                       |
| ------------ | ------------------------------------------------------------------- | --------------------------------- |
| requestModel | [BatchOperationRequest](./open-api-client.batchoperationrequest.md) | The model to use for the request. |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[BatchOperationCreationResult](./open-api-client.batchoperationcreationresult.md)<!-- -->&gt;

BatchOperationCreationResult The request has been accepted for processing, but the processing has not been completed.

## Exceptions

ApiError