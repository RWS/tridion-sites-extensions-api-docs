<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [BlueprintReadonlyGraph](./models.blueprintreadonlygraph.md) &gt; [ancestorsByPriority](./models.blueprintreadonlygraph.ancestorsbypriority.md)

## BlueprintReadonlyGraph.ancestorsByPriority() method

Get node ancestors by priority We are going bottom-to-top and by parent priority. Node grandparents are processed in order of priority of node's parents. This allows to handle complex use-cases with multiple parents on the same distance in different blueprint branches

**Signature:**

```typescript
ancestorsByPriority(nodeId: string): Iterable<BlueprintReadonlyParentLink<TData>>;
```

## Parameters

| Parameter | Type   | Description |
| --------- | ------ | ----------- |
| nodeId    | string |             |

**Returns:**

Iterable&lt;[BlueprintReadonlyParentLink](./models.blueprintreadonlyparentlink.md)<!-- -->&lt;TData&gt;&gt;
