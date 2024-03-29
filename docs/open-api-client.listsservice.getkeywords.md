<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ListsService](./open-api-client.listsservice.md) &gt; [getKeywords](./open-api-client.listsservice.getkeywords.md)

## ListsService.getKeywords() method

Gets a list of Keywords contained in the specified Category or parent Keyword. This operation returns an instance of 'Keyword' type or one of the following inherited types:<ul class="model-list"><li><span>ExternalKeyword</span></li></ul>

**Signature:**

```typescript
static getKeywords({ escapedItemId, }: {
        escapedItemId: string;
    }): CancelablePromise<Array<Keyword>>;
```

## Parameters

| Parameter          | Type                       | Description |
| ------------------ | -------------------------- | ----------- |
| { escapedItemId, } | { escapedItemId: string; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Array&lt;[Keyword](./open-api-client.keyword.md)<!-- -->&gt;&gt;

Keyword The request was successful.

## Exceptions

ApiError
