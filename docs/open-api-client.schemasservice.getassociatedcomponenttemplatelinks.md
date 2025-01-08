<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [SchemasService](./open-api-client.schemasservice.md) &gt; [getAssociatedComponentTemplateLinks](./open-api-client.schemasservice.getassociatedcomponenttemplatelinks.md)

## SchemasService.getAssociatedComponentTemplateLinks() method

Gets a list of all Component Template links that can render Components based on the specified Schema. This operation returns an instance of 'Link' type.

**Signature:**

```typescript
static getAssociatedComponentTemplateLinks({ escapedSchemaId, }: {
        escapedSchemaId: string;
    }): CancelablePromise<Array<Link>>;
```

## Parameters

| Parameter            | Type                         | Description |
| -------------------- | ---------------------------- | ----------- |
| { escapedSchemaId, } | { escapedSchemaId: string; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Array&lt;[Link](./open-api-client.link.md)<!-- -->&gt;&gt;

Link The request was successful.

## Exceptions

ApiError