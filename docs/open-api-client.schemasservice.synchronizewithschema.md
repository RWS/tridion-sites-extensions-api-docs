<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [SchemasService](./open-api-client.schemasservice.md) &gt; [synchronizeWithSchema](./open-api-client.schemasservice.synchronizewithschema.md)

## SchemasService.synchronizeWithSchema() method

Synchronizes the content and metadata of a given model with its Schema. The operation returns the synchronized model and the synchronization actions that were applied. This operation returns an instance of 'SynchronizationResult' type.

Using this operation will not persist the changes made through synchronization.

**Signature:**

```typescript
static synchronizeWithSchema({ requestModel, flags, }: {
        requestModel: IdentifiableObject;
        flags?: Array<any>;
    }): CancelablePromise<SynchronizationResult>;
```

## Parameters

| Parameter                | Type                                                                                                               | Description |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------ | ----------- |
| { requestModel, flags, } | { requestModel: [IdentifiableObject](./open-api-client.identifiableobject.md)<!-- -->; flags?: Array&lt;any&gt;; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[SynchronizationResult](./open-api-client.synchronizationresult.md)<!-- -->&gt;

SynchronizationResult The request was successful.

## Exceptions

ApiError