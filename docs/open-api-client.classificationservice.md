<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ClassificationService](./open-api-client.classificationservice.md)

## ClassificationService class

**Signature:**

```typescript
export declare class ClassificationService
```

## Methods

| Method                                                                                                                                                                              | Modifiers           | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [autoClassify({ escapedItemId, })](./open-api-client.classificationservice.autoclassify.md)                                                                                         | <code>static</code> | Automatically classifies the specified item with Concepts from external taxonomy based on the current content and metadata of the item. This operation returns an instance of 'ClassificationInfo' type.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [getClassifiedItems({ escapedKeywordId, useDynamicVersion, rloItemTypes, resolveDescendantKeywords, resultLimit, })](./open-api-client.classificationservice.getclassifieditems.md) | <code>static</code> | Gets a list of all items that are classified with a specified Keyword (internal) or Concept (external). This operation returns an instance of 'RepositoryLocalObject' type, as implemented by one of the following:<ul class="model-list"><li><span>Bundle</span></li><li><span>BusinessProcessType</span></li><li><span>Category</span></li><li><span>Component</span></li><li><span>ComponentTemplate</span></li><li><span>ExternalCategory</span></li><li><span>ExternalComponent</span></li><li><span>ExternalContainer</span></li><li><span>ExternalKeyword</span></li><li><span>Folder</span></li><li><span>Keyword</span></li><li><span>Page</span></li><li><span>PageTemplate</span></li><li><span>ResolvedBundle</span></li><li><span>Schema</span></li><li><span>SearchFolder</span></li><li><span>StructureGroup</span></li><li><span>TargetGroup</span></li><li><span>TemplateBuildingBlock</span></li></ul> |
| [getKeywordSuggestions({ sourceObject, categoryId, })](./open-api-client.classificationservice.getkeywordsuggestions.md)                                                            | <code>static</code> | Get suggestions for classifying an item with concepts from an external taxonomy. Suggestions are based on the content and metadata of the source item. This operation returns an instance of 'KeywordSuggestions' type.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |