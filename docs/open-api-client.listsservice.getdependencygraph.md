<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ListsService](./open-api-client.listsservice.md) &gt; [getDependencyGraph](./open-api-client.listsservice.getdependencygraph.md)

## ListsService.getDependencyGraph() method

Gets a dependency graph for the specified item. This operation returns an instance of 'DependencyGraphNode' type.

**Signature:**

```typescript
static getDependencyGraph({ escapedItemId, direction, contextRepositoryId, rloItemTypes, includeContainers, resultLimit, details, }: {
        escapedItemId: string;
        direction?: 'Uses' | 'UsedBy';
        contextRepositoryId?: string;
        rloItemTypes?: Array<any>;
        includeContainers?: boolean;
        resultLimit?: number;
        details?: 'IdAndTitleOnly' | 'WithApplicableActions' | 'Contentless';
    }): CancelablePromise<DependencyGraphNode>;
```

## Parameters

| Parameter                                                                                                 | Type                                                                                                                                                                                                                                                 | Description |
| --------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| { escapedItemId, direction, contextRepositoryId, rloItemTypes, includeContainers, resultLimit, details, } | { escapedItemId: string; direction?: 'Uses' \| 'UsedBy'; contextRepositoryId?: string; rloItemTypes?: Array&lt;any&gt;; includeContainers?: boolean; resultLimit?: number; details?: 'IdAndTitleOnly' \| 'WithApplicableActions' \| 'Contentless'; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[DependencyGraphNode](./open-api-client.dependencygraphnode.md)<!-- -->&gt;

DependencyGraphNode The request was successful.

## Exceptions

ApiError
