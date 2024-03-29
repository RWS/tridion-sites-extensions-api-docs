<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ListsService](./open-api-client.listsservice.md) &gt; [getCategories](./open-api-client.listsservice.getcategories.md)

## ListsService.getCategories() method

Gets a list of Categories related to the specified Publication. This operation returns an instance of 'Category' type or one of the following inherited types:<ul class="model-list"><li><span>ExternalCategory</span></li></ul>

**Signature:**

```typescript
static getCategories({ escapedPublicationId, }: {
        escapedPublicationId: string;
    }): CancelablePromise<Array<Category>>;
```

## Parameters

| Parameter                 | Type                              | Description |
| ------------------------- | --------------------------------- | ----------- |
| { escapedPublicationId, } | { escapedPublicationId: string; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Array&lt;[Category](./open-api-client.category.md)<!-- -->&gt;&gt;

Category The request was successful.

## Exceptions

ApiError
