<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ActivityInstanceBase](./open-api-client.activityinstancebase.md)

## ActivityInstanceBase type

Represents the data of an Activity Instance: a current Activity which is part of a Process Instance.

**Signature:**

```typescript
export type ActivityInstanceBase = Activity & {
    ActivityDefinition?: Link;
    ApprovalStatus?: Link;
    IsExpirationExecution?: boolean;
    ProcessDefinition?: Link;
    ResumeBookmark?: string;
    SuspendOrFailReason?: string;
    WorkflowType?: Link;
};
```

**References:** [Activity](./open-api-client.activity.md)<!-- -->, [Link](./open-api-client.link.md)