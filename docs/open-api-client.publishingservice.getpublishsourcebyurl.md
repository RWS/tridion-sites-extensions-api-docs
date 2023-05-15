<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [PublishingService](./open-api-client.publishingservice.md) &gt; [getPublishSourceByUrl](./open-api-client.publishingservice.getpublishsourcebyurl.md)

## PublishingService.getPublishSourceByUrl() method

Gets information about the source from which content was published using the published URL. This operation returns an instance of 'PublishSource' type.

**Signature:**

```typescript
static getPublishSourceByUrl(url: string): CancelablePromise<PublishSource>;
```

## Parameters

| Parameter | Type   | Description                             |
| --------- | ------ | --------------------------------------- |
| url       | string | The URL to which content was published. |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[PublishSource](./open-api-client.publishsource.md)<!-- -->&gt;

PublishSource The request was successful.

## Exceptions

ApiError