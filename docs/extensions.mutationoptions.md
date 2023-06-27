<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [MutationOptions](./extensions.mutationoptions.md)

## MutationOptions interface

**Signature:**

```typescript
export interface MutationOptions<TData = unknown, TError = unknown, TVariables = void>
```

## Properties

| Property                                                  | Modifiers | Type                                                                                                       | Description  |
| --------------------------------------------------------- | --------- | ---------------------------------------------------------------------------------------------------------- | ------------ |
| [cacheTime?](./extensions.mutationoptions.cachetime.md)   |           | number                                                                                                     | _(Optional)_ |
| [meta?](./extensions.mutationoptions.meta.md)             |           | Record&lt;string, unknown&gt;                                                                              | _(Optional)_ |
| [onError?](./extensions.mutationoptions.onerror.md)       |           | (error: TError, variables: TVariables) =&gt; Promise&lt;void&gt; \| void                                   | _(Optional)_ |
| [onMutate?](./extensions.mutationoptions.onmutate.md)     |           | (variables: TVariables) =&gt; Promise&lt;void&gt; \| void                                                  | _(Optional)_ |
| [onSettled?](./extensions.mutationoptions.onsettled.md)   |           | (data: TData \| undefined, error: TError \| null, variables: TVariables) =&gt; Promise&lt;void&gt; \| void | _(Optional)_ |
| [onSuccess?](./extensions.mutationoptions.onsuccess.md)   |           | (data: TData, variables: TVariables) =&gt; Promise&lt;void&gt; \| void                                     | _(Optional)_ |
| [retry?](./extensions.mutationoptions.retry.md)           |           | boolean \| number \| ((failureCount: number, error: TError) =&gt; boolean)                                 | _(Optional)_ |
| [retryDelay?](./extensions.mutationoptions.retrydelay.md) |           | number \| ((failureCount: number, error: TError) =&gt; number)                                             | _(Optional)_ |
| [variables?](./extensions.mutationoptions.variables.md)   |           | TVariables                                                                                                 | _(Optional)_ |