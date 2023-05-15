<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ClassificationService](./open-api-client.classificationservice.md) &gt; [getKeywordSuggestions](./open-api-client.classificationservice.getkeywordsuggestions.md)

## ClassificationService.getKeywordSuggestions() method

Get suggestions for classifying an item with concepts from an external taxonomy. Suggestions are based on the content and metadata of the source item. This operation returns an instance of 'KeywordSuggestions' type.

**Signature:**

```typescript
static getKeywordSuggestions(sourceObject: IdentifiableObject, categoryId?: string): CancelablePromise<Record<string, Array<KeywordSuggestion>>>;
```

## Parameters

| Parameter    | Type                                                          | Description                                                                                                                                                                                        |
| ------------ | ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| sourceObject | [IdentifiableObject](./open-api-client.identifiableobject.md) | The source item to request the keywords for.                                                                                                                                                       |
| categoryId   | string                                                        | _(Optional)_ The Category identifier (ECL URI), if provided, the suggestions are given based on this category only, and rest of the specified categories (if any) in the sourceObject are ignored. |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Record&lt;string, Array&lt;[KeywordSuggestion](./open-api-client.keywordsuggestion.md)<!-- -->&gt;&gt;&gt;

KeywordSuggestion The request was successful.

## Exceptions

ApiError