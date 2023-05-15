<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [Batch](./open-api-client.batch.md)

## Batch type

Represents the data of a Batch. Defines batch operations and additional info related to batch invocation.

**Signature:**

```typescript
export type Batch = SystemWideObject & {
    NumberOfDoneOperations?: number;
    Operations?: Array<BatchOperation>;
    Performer?: Link;
    StartAt?: string;
    TotalNumberOfOperations?: number;
};
```

**References:** [SystemWideObject](./open-api-client.systemwideobject.md)<!-- -->, [BatchOperation](./open-api-client.batchoperation.md)<!-- -->, [Link](./open-api-client.link.md)