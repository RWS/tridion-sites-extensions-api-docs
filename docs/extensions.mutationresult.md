<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [MutationResult](./extensions.mutationresult.md)

## MutationResult interface

**Signature:**

```typescript
export interface MutationResult<TData = unknown, TError = unknown, TVariables = unknown>
```

## Properties

| Property                                                      | Modifiers | Type                                                                                                                              | Description                                                                                                                                                                                                                                                                             |
| ------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [data](./extensions.mutationresult.data.md)                   |           | TData \| undefined                                                                                                                | The last successfully resolved data for the query.                                                                                                                                                                                                                                      |
| [error](./extensions.mutationresult.error.md)                 |           | TError \| null                                                                                                                    | The error object for the query, if an error was encountered.                                                                                                                                                                                                                            |
| [failureCount](./extensions.mutationresult.failurecount.md)   |           | number                                                                                                                            |                                                                                                                                                                                                                                                                                         |
| [failureReason](./extensions.mutationresult.failurereason.md) |           | TError \| null                                                                                                                    |                                                                                                                                                                                                                                                                                         |
| [isError](./extensions.mutationresult.iserror.md)             |           | boolean                                                                                                                           | Is <code>true</code> when status is <code>error</code>.                                                                                                                                                                                                                                 |
| [isIdle](./extensions.mutationresult.isidle.md)               |           | boolean                                                                                                                           | Is <code>true</code> when status is <code>idle</code>.                                                                                                                                                                                                                                  |
| [isPaused](./extensions.mutationresult.ispaused.md)           |           | boolean                                                                                                                           |                                                                                                                                                                                                                                                                                         |
| [isPending](./extensions.mutationresult.ispending.md)         |           | boolean                                                                                                                           | Is <code>true</code> when status is <code>loading</code>.                                                                                                                                                                                                                               |
| [isSuccess](./extensions.mutationresult.issuccess.md)         |           | boolean                                                                                                                           | Is <code>true</code> when status is <code>success</code>.                                                                                                                                                                                                                               |
| [mutate](./extensions.mutationresult.mutate.md)               |           | (...args: Parameters&lt;[MutateFunction](./extensions.mutatefunction.md)<!-- -->&lt;TData, TError, TVariables&gt;&gt;) =&gt; void | The mutation function to call with variables to trigger the mutation and optionally override options passed to useMutation.                                                                                                                                                             |
| [mutateAsync](./extensions.mutationresult.mutateasync.md)     |           | [MutateFunction](./extensions.mutatefunction.md)<!-- -->&lt;TData, TError, TVariables&gt;                                         | Similar to mutate but returns a promise which can be awaited.                                                                                                                                                                                                                           |
| [reset](./extensions.mutationresult.reset.md)                 |           | () =&gt; void                                                                                                                     | A function to clean the mutation internal state (i.e., it resets the mutation to its initial state).                                                                                                                                                                                    |
| [status](./extensions.mutationresult.status.md)               |           | [MutationStatus](./extensions.mutationstatus.md)                                                                                  | - <code>idle</code> initial status prior to the mutation function executing. - <code>loading</code> if the mutation is currently executing. - <code>error</code> if the last mutation attempt resulted in an error. - <code>success</code> if the last mutation attempt was successful. |
| [variables](./extensions.mutationresult.variables.md)         |           | TVariables \| undefined                                                                                                           |                                                                                                                                                                                                                                                                                         |