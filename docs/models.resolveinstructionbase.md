<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [ResolveInstructionBase](./models.resolveinstructionbase.md)

## ResolveInstructionBase class

**Signature:**

```typescript
export declare abstract class ResolveInstructionBase
```

## Constructors

| Constructor                                                                                                                              | Modifiers | Description                                                                |
| ---------------------------------------------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------- |
| [(constructor)({ backendModel, structureResolveOption, publishInChildPublications, })](./models.resolveinstructionbase._constructor_.md) |           | Constructs a new instance of the <code>ResolveInstructionBase</code> class |

## Properties

| Property                                                                                    | Modifiers | Type                                                                                  | Description                                                                                                         |
| ------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.resolveinstructionbase._backendmodel.md)                          |           | [BackendResolveInstructionBase](./open-api-client.resolveinstructionbase.md)          |                                                                                                                     |
| [getInternalModel](./models.resolveinstructionbase.getinternalmodel.md)                     |           | () =&gt; [BackendResolveInstructionBase](./open-api-client.resolveinstructionbase.md) |                                                                                                                     |
| [includeChildPublications](./models.resolveinstructionbase.includechildpublications.md)     |           | boolean \| undefined                                                                  | Value indicating whether to resolve items also from all child Publications where user has PublishManagement rights. |
| [includeCurrentPublication](./models.resolveinstructionbase.includecurrentpublication.md)   |           | boolean \| undefined                                                                  | Value indicating whether items will be (un)published inside the current Publication.                                |
| [publishInChildPublications](./models.resolveinstructionbase.publishinchildpublications.md) |           | ReadonlyArray&lt;[ItemUri](./models.itemuri.md)<!-- -->&gt; \| undefined              | Collection of TCM URIs of child Publications where items will be (un)published.                                     |
| [structureResolveOption](./models.resolveinstructionbase.structureresolveoption.md)         |           | [StructureResolveOption](./models.structureresolveoption.md) \| undefined             | Value indicating the option to include the resolved items and/or structure.                                         |