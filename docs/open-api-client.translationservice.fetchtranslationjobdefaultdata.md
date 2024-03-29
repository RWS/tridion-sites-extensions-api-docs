<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [TranslationService](./open-api-client.translationservice.md) &gt; [fetchTranslationJobDefaultData](./open-api-client.translationservice.fetchtranslationjobdefaultdata.md)

## TranslationService.fetchTranslationJobDefaultData() method

Gets a translation job model with default data, which you can use as the basis for creating a translation job. This operation returns an instance of 'TranslationJob' type.

**Signature:**

```typescript
static fetchTranslationJobDefaultData({ itemIds, jobType, }: {
        itemIds: Array<string>;
        jobType: 'None' | 'PushJob' | 'PullJob' | 'UnknownByClient';
    }): CancelablePromise<TranslationJob>;
```

## Parameters

| Parameter             | Type                                                                                              | Description |
| --------------------- | ------------------------------------------------------------------------------------------------- | ----------- |
| { itemIds, jobType, } | { itemIds: Array&lt;string&gt;; jobType: 'None' \| 'PushJob' \| 'PullJob' \| 'UnknownByClient'; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[TranslationJob](./open-api-client.translationjob.md)<!-- -->&gt;

TranslationJob The request was successful.

## Exceptions

ApiError
