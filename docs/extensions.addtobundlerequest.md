<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [AddToBundleRequest](./extensions.addtobundlerequest.md)

## AddToBundleRequest interface

**Signature:**

```typescript
export interface AddToBundleRequest
```

## Properties

| Property                                                           | Modifiers | Type                                                                              | Description                                      |
| ------------------------------------------------------------------ | --------- | --------------------------------------------------------------------------------- | ------------------------------------------------ |
| [bundleId](./extensions.addtobundlerequest.bundleid.md)            |           | [ItemUri](./models.itemuri.md)                                                    | ID of the bundle to which items should be added. |
| [containerItem?](./extensions.addtobundlerequest.containeritem.md) |           | [IdentifiableObject](./models.identifiableobject.md)                              | _(Optional)_ Container item of the bundle.       |
| [itemsToAdd](./extensions.addtobundlerequest.itemstoadd.md)        |           | ReadonlyArray&lt;[IdentifiableObject](./models.identifiableobject.md)<!-- -->&gt; | Items to add to the bundle.                      |