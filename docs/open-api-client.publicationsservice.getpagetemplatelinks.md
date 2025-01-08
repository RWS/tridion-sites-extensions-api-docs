<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [PublicationsService](./open-api-client.publicationsservice.md) &gt; [getPageTemplateLinks](./open-api-client.publicationsservice.getpagetemplatelinks.md)

## PublicationsService.getPageTemplateLinks() method

> Warning: This API is now obsolete.
>
> Gets a list of all Page Template links contained within a specified Publication. This operation returns an instance of 'Link' type.

**Signature:**

```typescript
static getPageTemplateLinks({ escapedPublicationId, }: {
        escapedPublicationId: string;
    }): CancelablePromise<Array<Link>>;
```

## Parameters

| Parameter                 | Type                              | Description |
| ------------------------- | --------------------------------- | ----------- |
| { escapedPublicationId, } | { escapedPublicationId: string; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Array&lt;[Link](./open-api-client.link.md)<!-- -->&gt;&gt;

Link The request was successful.

## Exceptions

ApiError