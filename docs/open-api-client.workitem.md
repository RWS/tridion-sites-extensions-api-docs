<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [WorkItem](./open-api-client.workitem.md)

## WorkItem type

Represents the data of a Work Item: the association between an item participating in workflow and an Activity.

**Signature:**

```typescript
export type WorkItem = WorkflowObject & {
    Activity?: Link;
    Comment?: string;
    Owner?: Link;
    Process?: Link;
    Subject?: Link;
    SubjectOwningRepository?: Link;
};
```

**References:** [WorkflowObject](./open-api-client.workflowobject.md)<!-- -->, [Link](./open-api-client.link.md)