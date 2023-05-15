<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [TranslationService](./open-api-client.translationservice.md) &gt; [sendTranslationJob](./open-api-client.translationservice.sendtranslationjob.md)

## TranslationService.sendTranslationJob() method

Sends a job for translation. This operation returns an instance of 'TranslationJob' type.

**Signature:**

```typescript
static sendTranslationJob(jobId: number): CancelablePromise<TranslationJob>;
```

## Parameters

| Parameter | Type   | Description                                                                          |
| --------- | ------ | ------------------------------------------------------------------------------------ |
| jobId     | number | The ID of the translation job you want to send to the translation management system. |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[TranslationJob](./open-api-client.translationjob.md)<!-- -->&gt;

TranslationJob The request was successful.

## Exceptions

ApiError