<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [OptionalPublishingQueueExplorerTableHook](./extensions.optionalpublishingqueueexplorertablehook.md)

## OptionalPublishingQueueExplorerTableHook type

Hook for accessing PublishingQueue Explorer Table data and methods when available.

**Signature:**

```typescript
export type OptionalPublishingQueueExplorerTableHook = () => PublishingQueueExplorerTableHookResult | undefined;
```

**References:** [PublishingQueueExplorerTableHookResult](./extensions.publishingqueueexplorertablehookresult.md)

## Remarks

Safe to be used within or outside of the PublishingQueue Explorer Table. `undefined` is returned when used outside of the PublishingQueue Explorer Table.