<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [VersionedItem](./models.versioneditem.md)

## VersionedItem class

Abstract base class for Versioned Items.

**Signature:**

```typescript
export declare abstract class VersionedItem extends RepositoryLocalObject
```

**Extends:** [RepositoryLocalObject](./models.repositorylocalobject.md)

## Constructors

| Constructor                                                                                                                            | Modifiers | Description                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------- |
| [(constructor)({ backendModel, dynamicVersionInfo, fullVersionInfo, isDynamic, ...rloArgs })](./models.versioneditem._constructor_.md) |           | Constructs a new instance of the <code>VersionedItem</code> class |

## Properties

| Property                                                                   | Modifiers | Type                                                                | Description |
| -------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ----------- |
| [\_backendModel](./models.versioneditem._backendmodel.md)                  |           | [BackendVersionedItem](./open-api-client.versioneditem.md)          |             |
| [dynamicVersionInfo](./models.versioneditem.dynamicversioninfo.md)         |           | [DynamicVersionInfo](./models.dynamicversioninfo.md) \| undefined   |             |
| [getInternalModel](./models.versioneditem.getinternalmodel.md)             |           | () =&gt; [BackendVersionedItem](./open-api-client.versioneditem.md) |             |
| [isAwaitingFirstCheckIn](./models.versioneditem.isawaitingfirstcheckin.md) |           | boolean                                                             |             |
| [isCurrentVersion](./models.versioneditem.iscurrentversion.md)             |           | boolean                                                             |             |
| [isDynamic](./models.versioneditem.isdynamic.md)                           |           | boolean                                                             |             |
| [versionInfo](./models.versioneditem.versioninfo.md)                       |           | [FullVersionInfo](./models.fullversioninfo.md) \| undefined         |             |
