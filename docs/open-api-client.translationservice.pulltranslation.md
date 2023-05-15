<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [TranslationService](./open-api-client.translationservice.md) &gt; [pullTranslation](./open-api-client.translationservice.pulltranslation.md)

## TranslationService.pullTranslation() method

Pulls a translation for a specified item by creating a pull translation job containing the item and sending it to translation. This operation returns an instance of 'TranslationJob' type.

This route is used as HATEOAS URL for the tm:PullTranslation Applicable Action

**Signature:**

```typescript
static pullTranslation(escapedItemId: string): CancelablePromise<TranslationJob>;
```

## Parameters

| Parameter     | Type   | Description                                                                                     |
| ------------- | ------ | ----------------------------------------------------------------------------------------------- |
| escapedItemId | string | The URI of an item with the colon escaped by replacing it with an underscore. E.g. "tcm_0-1-1". |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[TranslationJob](./open-api-client.translationjob.md)<!-- -->&gt;

TranslationJob The request was successful.

## Exceptions

ApiError