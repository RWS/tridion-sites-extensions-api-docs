<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [ActivitiesExplorerHookResult](./extensions.activitiesexplorerhookresult.md)

## ActivitiesExplorerHookResult interface

Data of the Activities Explorer.

**Signature:**

```typescript
export interface ActivitiesExplorerHookResult
```

## Properties

| Property                                                                            | Modifiers | Type                                                                          | Description                                       |
| ----------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------- |
| [currentItem](./extensions.activitiesexplorerhookresult.currentitem.md)             |           | [ActivityInstance](./models.activityinstance.md) \| undefined                 | Currently active ActivityInstance.                |
| [items](./extensions.activitiesexplorerhookresult.items.md)                         |           | ReadonlyArray&lt;[ActivityInstance](./models.activityinstance.md)<!-- -->&gt; | List of Activity Instances.                       |
| [itemsLoadingState](./extensions.activitiesexplorerhookresult.itemsloadingstate.md) |           | [LoadingState](./extensions.loadingstate.md)                                  | The loading state of the Activity Instances list. |