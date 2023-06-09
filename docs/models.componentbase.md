<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [ComponentBase](./models.componentbase.md)

## ComponentBase class

Represents the data of a Component: a generic holder of content and metadata.

**Signature:**

```typescript
export declare abstract class ComponentBase extends VersionedItem
```

**Extends:** [VersionedItem](./models.versioneditem.md)

## Constructors

| Constructor                                                                                                                                           | Modifiers | Description                                                       |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------- |
| [(constructor)({ backendModel, approvalStatus, componentType, schema, workflowInfo, ...componentBaseArgs })](./models.componentbase._constructor_.md) |           | Constructs a new instance of the <code>ComponentBase</code> class |

## Properties

| Property                                                                         | Modifiers | Type                                                        | Description                                                                                                                        |
| -------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.componentbase._backendmodel.md)                        |           | [BackendComponent](./open-api-client.component.md)          |                                                                                                                                    |
| [approvalStatus](./models.componentbase.approvalstatus.md)                       |           | [Link](./models.link.md) \| undefined                       | Approval Status of the item.                                                                                                       |
| [componentType](./models.componentbase.componenttype.md)                         |           | [ComponentType](./models.componenttype.md) \| undefined     | <p>Type of the Component (Normal or Multimedia).</p><p>This type is derived from the "Schema" on which the Component is based.</p> |
| [getInternalModel](./models.componentbase.getinternalmodel.md)                   |           | () =&gt; [BackendComponent](./open-api-client.component.md) |                                                                                                                                    |
| [isBasedOnMandatorySchema](./models.componentbase.isbasedonmandatoryschema.md)   |           | boolean                                                     | Whether the Component is based on a Mandatory Schema                                                                               |
| [isBasedOnTridionWebSchema](./models.componentbase.isbasedontridionwebschema.md) |           | boolean                                                     | Whether the Component is based on a Tridion Web Schema                                                                             |
| [schema](./models.componentbase.schema.md)                                       |           | [Link](./models.link.md) \| undefined                       | Schema for the Component's content                                                                                                 |
| [workflowInfo](./models.componentbase.workflowinfo.md)                           |           | [WorkflowInfo](./models.workflowinfo.md) \| undefined       | Workflow-related information for the item.                                                                                         |
