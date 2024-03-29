<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ListsService](./open-api-client.listsservice.md) &gt; [getOrganizationalStructureTree](./open-api-client.listsservice.getorganizationalstructuretree.md)

## ListsService.getOrganizationalStructureTree() method

> Warning: This API is now obsolete.
>
> Gets an (expanded) tree representation of all the items in the path of a RepositoryLocalObject. This operation returns an instance of 'TreeNode' type.

**Signature:**

```typescript
static getOrganizationalStructureTree({ escapedItemId, includeAllPublications, includeChildrenOnEveryLevel, groupCategoriesAndKeywords, groupBusinessProcessTypes, useDynamicVersion, }: {
        escapedItemId: string;
        includeAllPublications?: boolean;
        includeChildrenOnEveryLevel?: boolean;
        groupCategoriesAndKeywords?: boolean;
        groupBusinessProcessTypes?: boolean;
        useDynamicVersion?: boolean;
    }): CancelablePromise<TreeNode>;
```

## Parameters

| Parameter                                                                                                                                         | Type                                                                                                                                                                                                        | Description |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| { escapedItemId, includeAllPublications, includeChildrenOnEveryLevel, groupCategoriesAndKeywords, groupBusinessProcessTypes, useDynamicVersion, } | { escapedItemId: string; includeAllPublications?: boolean; includeChildrenOnEveryLevel?: boolean; groupCategoriesAndKeywords?: boolean; groupBusinessProcessTypes?: boolean; useDynamicVersion?: boolean; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[TreeNode](./open-api-client.treenode.md)<!-- -->&gt;

TreeNode The request was successful.

## Exceptions

ApiError
