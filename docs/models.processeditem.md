<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [ProcessedItem](./models.processeditem.md)

## ProcessedItem class

**Signature:**

```typescript
export declare class ProcessedItem
```

## Constructors

| Constructor                                                                              | Modifiers | Description                                                       |
| ---------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------- |
| [(constructor)({ backendModel, resolvedItem })](./models.processeditem._constructor_.md) |           | Constructs a new instance of the <code>ProcessedItem</code> class |

## Properties

| Property                                                                 | Modifiers | Type                                                                | Description                                                                                                   |
| ------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.processeditem._backendmodel.md)                |           | [BackendProcessedItem](./open-api-client.processeditem.md)          |                                                                                                               |
| [getInternalModel](./models.processeditem.getinternalmodel.md)           |           | () =&gt; [BackendProcessedItem](./open-api-client.processeditem.md) |                                                                                                               |
| [hasRenderFailure](./models.processeditem.hasrenderfailure.md)           |           | boolean \| undefined                                                | A value indicating whether the item failed rendering.                                                         |
| [isRendered](./models.processeditem.isrendered.md)                       |           | boolean \| undefined                                                | A value indicating whether the item has been fully rendered.                                                  |
| [reasonOfRenderFailure](./models.processeditem.reasonofrenderfailure.md) |           | string \| undefined                                                 | The reason of failure of the rendering process.                                                               |
| [renderTime](./models.processeditem.rendertime.md)                       |           | string \| undefined                                                 | The duration of the rendering process for the processed item. The render time formatted as a string: HH:MM:SS |
| [resolvedItem](./models.processeditem.resolveditem.md)                   |           | [ResolvedItem](./models.resolveditem.md) \| undefined               | The "ResolvedItem" for which this instance stores additional rendering information.                           |