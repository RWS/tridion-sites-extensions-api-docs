<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [TranslationService](./open-api-client.translationservice.md) &gt; [fetchTranslationInfo](./open-api-client.translationservice.fetchtranslationinfo.md)

## TranslationService.fetchTranslationInfo() method

Gets the translation information for a specified item. This operation returns an instance of 'TranslationInfo' type.

This route is used as the HATEOAS URL for the tm:TranslationInfo ListLink.

**Signature:**

```typescript
static fetchTranslationInfo({ escapedItemId, }: {
        escapedItemId: string;
    }): CancelablePromise<TranslationInfo>;
```

## Parameters

| Parameter          | Type                       | Description |
| ------------------ | -------------------------- | ----------- |
| { escapedItemId, } | { escapedItemId: string; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[TranslationInfo](./open-api-client.translationinfo.md)<!-- -->&gt;

TranslationInfo The request was successful.

## Exceptions

ApiError
