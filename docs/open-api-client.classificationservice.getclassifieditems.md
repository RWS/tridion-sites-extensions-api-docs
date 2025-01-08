<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ClassificationService](./open-api-client.classificationservice.md) &gt; [getClassifiedItems](./open-api-client.classificationservice.getclassifieditems.md)

## ClassificationService.getClassifiedItems() method

Gets a list of all items that are classified with a specified Keyword (internal) or Concept (external). This operation returns an instance of 'RepositoryLocalObject' type, as implemented by one of the following:<ul class="model-list"><li><span>Bundle</span></li><li><span>BusinessProcessType</span></li><li><span>Category</span></li><li><span>Component</span></li><li><span>ComponentTemplate</span></li><li><span>ExternalCategory</span></li><li><span>ExternalComponent</span></li><li><span>ExternalContainer</span></li><li><span>ExternalKeyword</span></li><li><span>Folder</span></li><li><span>Keyword</span></li><li><span>Page</span></li><li><span>PageTemplate</span></li><li><span>ResolvedBundle</span></li><li><span>Schema</span></li><li><span>SearchFolder</span></li><li><span>StructureGroup</span></li><li><span>TargetGroup</span></li><li><span>TemplateBuildingBlock</span></li></ul>

**Signature:**

```typescript
static getClassifiedItems({ escapedKeywordId, useDynamicVersion, rloItemTypes, resolveDescendantKeywords, resultLimit, }: {
        escapedKeywordId: string;
        useDynamicVersion?: boolean;
        rloItemTypes?: Array<any>;
        resolveDescendantKeywords?: boolean;
        resultLimit?: number;
    }): CancelablePromise<Array<RepositoryLocalObject>>;
```

## Parameters

| Parameter                                                                                      | Type                                                                                                                                                   | Description |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------- |
| { escapedKeywordId, useDynamicVersion, rloItemTypes, resolveDescendantKeywords, resultLimit, } | { escapedKeywordId: string; useDynamicVersion?: boolean; rloItemTypes?: Array&lt;any&gt;; resolveDescendantKeywords?: boolean; resultLimit?: number; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Array&lt;[RepositoryLocalObject](./open-api-client.repositorylocalobject.md)<!-- -->&gt;&gt;

RepositoryLocalObject The request was successful.

## Exceptions

ApiError