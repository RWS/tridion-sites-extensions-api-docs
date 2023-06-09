<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ApplicationDataService](./open-api-client.applicationdataservice.md) &gt; [getApplicationData](./open-api-client.applicationdataservice.getapplicationdata.md)

## ApplicationDataService.getApplicationData() method

> Warning: This API is now obsolete.
>
> Gets application data for all applications related to a specified item. This operation returns an instance of 'ApplicationData' type.

**Signature:**

```typescript
static getApplicationData(escapedItemId: string): CancelablePromise<Array<ApplicationData>>;
```

## Parameters

| Parameter     | Type   | Description                                                                                     |
| ------------- | ------ | ----------------------------------------------------------------------------------------------- |
| escapedItemId | string | The URI of an item with the colon escaped by replacing it with an underscore. E.g. "tcm_0-1-1". |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;Array&lt;[ApplicationData](./open-api-client.applicationdata.md)<!-- -->&gt;&gt;

ApplicationData The request was successful.

## Exceptions

ApiError
