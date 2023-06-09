<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [ValidationResult](./models.validationresult.md)

## ValidationResult class

Represents the data of a validation result which is returned when validating an item.

**Signature:**

```typescript
export declare abstract class ValidationResult
```

## Constructors

| Constructor                                                               | Modifiers | Description                                                          |
| ------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------- |
| [(constructor)(backendModel)](./models.validationresult._constructor_.md) |           | Constructs a new instance of the <code>ValidationResult</code> class |

## Properties

| Property                                                          | Modifiers | Type                                                                      | Description                                                                                                                                                            |
| ----------------------------------------------------------------- | --------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.validationresult._backendmodel.md)      |           | [BackendValidationResult](./open-api-client.validationresult.md)          |                                                                                                                                                                        |
| [getInternalModel](./models.validationresult.getinternalmodel.md) |           | () =&gt; [BackendValidationResult](./open-api-client.validationresult.md) |                                                                                                                                                                        |
| [location](./models.validationresult.location.md)                 |           | string \| undefined                                                       | Location where the validation error occurred.                                                                                                                          |
| [message](./models.validationresult.message.md)                   |           | string \| undefined                                                       | Detailed message about the validation result.                                                                                                                          |
| [source](./models.validationresult.source.md)                     |           | string \| undefined                                                       | Name of the component/subsystem that generated the message. This property is set to "Content Manager" for all errors and warnings generated by Content Manager kernel. |
