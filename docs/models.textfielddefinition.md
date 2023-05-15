<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [TextFieldDefinition](./models.textfielddefinition.md)

## TextFieldDefinition class

Abstract base class for Text Field Definitions (specified in a Schema)

**Signature:**

```typescript
export declare abstract class TextFieldDefinition extends ItemPublishableFieldDefinition
```

**Extends:** [ItemPublishableFieldDefinition](./models.itempublishablefielddefinition.md)

## Constructors

| Constructor                                                                  | Modifiers | Description                                                             |
| ---------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------- |
| [(constructor)(backendModel)](./models.textfielddefinition._constructor_.md) |           | Constructs a new instance of the <code>TextFieldDefinition</code> class |

## Properties

| Property                                                                             | Modifiers | Type                                                                            | Description                                                                  |
| ------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| [\_backendModel](./models.textfielddefinition._backendmodel.md)                      |           | [BackendTextFieldDefinition](./open-api-client.textfielddefinition.md)          |                                                                              |
| [getInternalModel](./models.textfielddefinition.getinternalmodel.md)                 |           | () =&gt; [BackendTextFieldDefinition](./open-api-client.textfielddefinition.md) |                                                                              |
| [useForAutoClassification](./models.textfielddefinition.useforautoclassification.md) |           | boolean                                                                         | Whether the text field is used as input for automatic classification or not. |