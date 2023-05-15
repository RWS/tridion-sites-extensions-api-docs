<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [BluePrintingService](./open-api-client.blueprintingservice.md) &gt; [promote](./open-api-client.blueprintingservice.promote.md)

## BluePrintingService.promote() method

Promotes an item in the BluePrint hierarchy. This operation returns an instance of 'OperationResult' type.

**Signature:**

```typescript
static promote(escapedItemId: string, requestModel: PromoteDemoteRequest): CancelablePromise<OperationResult>;
```

## Parameters

| Parameter     | Type                                                              | Description                                                                                     |
| ------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| escapedItemId | string                                                            | The URI of an item with the colon escaped by replacing it with an underscore. E.g. "tcm_0-1-1". |
| requestModel  | [PromoteDemoteRequest](./open-api-client.promotedemoterequest.md) | The model to use for the request.                                                               |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[OperationResult](./open-api-client.operationresult.md)<!-- -->&gt;

OperationResult The request has completed and has resulted in one or more new resources being created.

## Exceptions

ApiError