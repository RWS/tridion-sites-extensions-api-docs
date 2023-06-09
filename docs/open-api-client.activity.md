<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [Activity](./open-api-client.activity.md)

## Activity type

Abstract base class for the data of Activities.

**Signature:**

```typescript
export type Activity = WorkflowObject & {
    Assignee?: Link;
    AssignmentDate?: string;
    DueDate?: string;
    FinishDate?: string;
    FinishMessage?: string;
    Owner?: Link;
    Performers?: Array<Link>;
    Position?: number;
    PrimarySubject?: Link;
    Process?: Link;
    StartDate?: string;
    SuspendDate?: string;
    WorkItems?: Array<WorkItem>;
};
```

**References:** [WorkflowObject](./open-api-client.workflowobject.md)<!-- -->, [Link](./open-api-client.link.md)<!-- -->, [WorkItem](./open-api-client.workitem.md)
