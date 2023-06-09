<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ActivityState](./open-api-client.activitystate.md)

## ActivityState enum

Defines a state of an Activity.

Members: \* `Assigned` - The Activity is assigned to the User or Group.

\* `Started` - The Activity is started by a User.

\* `Failed` - The Activity is failed.

\* `Finished` - The Activity is finished.

\* `Suspended` - The Activity is suspended.

\* `WaitingForWorkflowAgent` - The Activity is waiting for execution by Workflow Agent.

\* `UnknownByClient` - Special reserved value used to notify an older API version client about the presence of an enumeration member added in a later API version. Explicitly setting this value by a client is not allowed, but client code should check it and be able to handle such cases.

**Signature:**

```typescript
export declare enum ActivityState
```

## Enumeration Members

| Member                     | Value                                            | Description |
| -------------------------- | ------------------------------------------------ | ----------- |
| ASSIGNED                   | <code>&quot;Assigned&quot;</code>                |             |
| FAILED                     | <code>&quot;Failed&quot;</code>                  |             |
| FINISHED                   | <code>&quot;Finished&quot;</code>                |             |
| STARTED                    | <code>&quot;Started&quot;</code>                 |             |
| SUSPENDED                  | <code>&quot;Suspended&quot;</code>               |             |
| UNKNOWN_BY_CLIENT          | <code>&quot;UnknownByClient&quot;</code>         |             |
| WAITING_FOR_WORKFLOW_AGENT | <code>&quot;WaitingForWorkflowAgent&quot;</code> |             |
