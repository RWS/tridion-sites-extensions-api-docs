<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [TemplateBuildingBlock](./models.templatebuildingblock.md)

## TemplateBuildingBlock class

Represents a Template Building Block: a re-usable template module.

**Signature:**

```typescript
export declare class TemplateBuildingBlock extends Template
```

**Extends:** [Template](./models.template.md)

## Constructors

| Constructor                                                                                                                       | Modifiers | Description                                                               |
| --------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------- |
| [(constructor)({ backendModel, approvalStatus, workflowInfo, ...templateArgs })](./models.templatebuildingblock._constructor_.md) |           | Constructs a new instance of the <code>TemplateBuildingBlock</code> class |

## Properties

| Property                                                               | Modifiers | Type                                                                                | Description                                |
| ---------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------- | ------------------------------------------ |
| [\_backendModel](./models.templatebuildingblock._backendmodel.md)      |           | [BackendTemplateBuildingBlock](./open-api-client.templatebuildingblock.md)          |                                            |
| [approvalStatus](./models.templatebuildingblock.approvalstatus.md)     |           | [Link](./models.link.md) \| undefined                                               | The approval status of the item.           |
| [getInternalModel](./models.templatebuildingblock.getinternalmodel.md) |           | () =&gt; [BackendTemplateBuildingBlock](./open-api-client.templatebuildingblock.md) |                                            |
| [workflowInfo](./models.templatebuildingblock.workflowinfo.md)         |           | [WorkflowInfo](./models.workflowinfo.md) \| undefined                               | Workflow-related information for the item. |