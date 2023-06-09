<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [TranslationStatus](./models.translationstatus.md)

## TranslationStatus type

Represents translation status of an Item.

\* `notTranslated` - Item is not translated. \* `inProgress` - Translation in progress. \* `upToDate` - Items contains latest translation of source. \* `newSourceVersionExists` - New version of source available. \* `newTargetVersionExists` - Previous version of target item contains translation but target item was changed after. \* `unknownByClient` - Special reserved value used to notify an older API version client about the presence of an enumeration member added in a later API version. Explicitly setting this value by a client is not allowed, but client code should check it and be able to handle such cases.

**Signature:**

```typescript
export type TranslationStatus =
    | 'notTranslated'
    | 'inProgress'
    | 'upToDate'
    | 'newSourceVersionExists'
    | 'newTargetVersionExists'
    | 'unknownByClient';
```
