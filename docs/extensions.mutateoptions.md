<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [MutateOptions](./extensions.mutateoptions.md)

## MutateOptions interface

**Signature:**

```typescript
export interface MutateOptions<TData = unknown, TError = unknown, TVariables = void>
```

## Properties

| Property                                              | Modifiers | Type                                                                                | Description  |
| ----------------------------------------------------- | --------- | ----------------------------------------------------------------------------------- | ------------ |
| [onError?](./extensions.mutateoptions.onerror.md)     |           | (error: TError, variables: TVariables) =&gt; void                                   | _(Optional)_ |
| [onSettled?](./extensions.mutateoptions.onsettled.md) |           | (data: TData \| undefined, error: TError \| null, variables: TVariables) =&gt; void | _(Optional)_ |
| [onSuccess?](./extensions.mutateoptions.onsuccess.md) |           | (data: TData, variables: TVariables) =&gt; void                                     | _(Optional)_ |