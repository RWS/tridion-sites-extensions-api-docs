<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [LoadInfo](./models.loadinfo.md)

## LoadInfo class

Represents the information about the error that was thrown while loading an item.

**Signature:**

```typescript
export declare class LoadInfo
```

## Constructors

| Constructor                                                                             | Modifiers | Description                                                  |
| --------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------ |
| [(constructor)({ backendModel, errorType, state })](./models.loadinfo._constructor_.md) |           | Constructs a new instance of the <code>LoadInfo</code> class |

## Properties

| Property                                                  | Modifiers | Type                                                            | Description         |
| --------------------------------------------------------- | --------- | --------------------------------------------------------------- | ------------------- |
| [\_backendModel](./models.loadinfo._backendmodel.md)      |           | [BackendLoadInfo](./open-api-client.loadinfo.md)                |                     |
| [errorMessage](./models.loadinfo.errormessage.md)         |           | string                                                          | Error message.      |
| [errorType](./models.loadinfo.errortype.md)               |           | [LoadInfoErrorType](./models.loadinfoerrortype.md) \| undefined | Error type.         |
| [getInternalModel](./models.loadinfo.getinternalmodel.md) |           | () =&gt; [BackendLoadInfo](./open-api-client.loadinfo.md)       |                     |
| [state](./models.loadinfo.state.md)                       |           | [LoadInfoState](./models.loadinfostate.md) \| undefined         | Load state of item. |