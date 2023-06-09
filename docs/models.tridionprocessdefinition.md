<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [TridionProcessDefinition](./models.tridionprocessdefinition.md)

## TridionProcessDefinition class

Represents the data of a Tridion proprietary Process Definition.

**Signature:**

```typescript
export declare class TridionProcessDefinition extends ProcessDefinition
```

**Extends:** [ProcessDefinition](./models.processdefinition.md)

## Constructors

| Constructor                                                                                       | Modifiers | Description                                                                  |
| ------------------------------------------------------------------------------------------------- | --------- | ---------------------------------------------------------------------------- |
| [(constructor)(tridionProcessDefinitionArgs)](./models.tridionprocessdefinition._constructor_.md) |           | Constructs a new instance of the <code>TridionProcessDefinition</code> class |

## Properties

| Property                                                                  | Modifiers | Type                                                                                      | Description                                                                                                         |
| ------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.tridionprocessdefinition._backendmodel.md)      |           | [BackendTridionProcessDefinition](./open-api-client.tridionprocessdefinition.md)          |                                                                                                                     |
| [diagram](./models.tridionprocessdefinition.diagram.md)                   |           | string \| undefined                                                                       | Binary representation of the Diagram of the Activity Definition. A Microsoft Visio diagram, or an empty byte array. |
| [getInternalModel](./models.tridionprocessdefinition.getinternalmodel.md) |           | () =&gt; [BackendTridionProcessDefinition](./open-api-client.tridionprocessdefinition.md) |                                                                                                                     |
