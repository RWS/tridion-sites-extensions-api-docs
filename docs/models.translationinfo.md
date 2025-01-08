<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [TranslationInfo](./models.translationinfo.md)

## TranslationInfo class

Contains information about the translation state of the Item.

**Signature:**

```typescript
export declare class TranslationInfo
```

## Constructors

| Constructor                                                                                                                   | Modifiers | Description                                                         |
| ----------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- |
| [(constructor)({ backendModel, contextLanguage, translationFrom, translationTo })](./models.translationinfo._constructor_.md) |           | Constructs a new instance of the <code>TranslationInfo</code> class |

## Properties

| Property                                                         | Modifiers | Type                                                                                           | Description                                                                                                                   |
| ---------------------------------------------------------------- | --------- | ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.translationinfo._backendmodel.md)      |           | [BackendTranslationInfo](./open-api-client.translationinfo.md)                                 |                                                                                                                               |
| [contextLanguage](./models.translationinfo.contextlanguage.md)   |           | [TmsLanguage](./models.tmslanguage.md) \| undefined                                            | The <code>TmsLanguage</code> of the context Publication (containing the current item).                                        |
| [getInternalModel](./models.translationinfo.getinternalmodel.md) |           | () =&gt; [BackendTranslationInfo](./open-api-client.translationinfo.md)                        |                                                                                                                               |
| [translationFrom](./models.translationinfo.translationfrom.md)   |           | [TranslationDetails](./models.translationdetails.md) \| undefined                              | The <code>TranslationDetails</code> for this Item as the target Item.                                                         |
| [translationTo](./models.translationinfo.translationto.md)       |           | ReadonlyArray&lt;[TranslationDetails](./models.translationdetails.md)<!-- -->&gt; \| undefined | The <code>TranslationDetails</code> for all Items that can be the target for a translation with this Item as the source Item. |