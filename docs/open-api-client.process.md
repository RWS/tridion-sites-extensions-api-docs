<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [Process](./open-api-client.process.md)

## Process type

Abstract base class for the data of Processes.

**Signature:**

```typescript
export type Process = WorkflowObject & {
    Activities?: Array<Activity>;
    Creator?: Link;
    HasSnapshots?: boolean;
    Subjects?: Array<Link>;
    WorkflowType?: Link;
};
```

**References:** [WorkflowObject](./open-api-client.workflowobject.md)<!-- -->, [Activity](./open-api-client.activity.md)<!-- -->, [Link](./open-api-client.link.md)
