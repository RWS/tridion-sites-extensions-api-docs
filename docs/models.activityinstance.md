<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [ActivityInstance](./models.activityinstance.md)

## ActivityInstance class

Represents an Activity Instance: a current Activity which is part of a Process Instance.

**Signature:**

```typescript
export declare class ActivityInstance extends Activity
```

**Extends:** [Activity](./models.activity.md)

## Constructors

| Constructor                                                                                                                                                                                             | Modifiers | Description                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------- |
| [(constructor)({ backendModel, activityConstraints, activityDefinition, activityState, approvalStatus, processDefinition, workflowType, ...acticityArgs })](./models.activityinstance._constructor_.md) |           | Constructs a new instance of the <code>ActivityInstance</code> class |

## Properties

| Property                                                                    | Modifiers | Type                                                                                             | Description                                                                                                                                                                                                                               |
| --------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.activityinstance._backendmodel.md)                |           | [BackendActivityInstance](./open-api-client.activityinstance.md)                                 |                                                                                                                                                                                                                                           |
| [activityConstraints](./models.activityinstance.activityconstraints.md)     |           | ReadonlyArray&lt;[ActivityConstraints](./models.activityconstraints.md)<!-- -->&gt; \| undefined | Constraints of this activity.                                                                                                                                                                                                             |
| [activityDefinition](./models.activityinstance.activitydefinition.md)       |           | [Link](./models.link.md) \| undefined                                                            | Activity Definition on which the Activity Instance is based.                                                                                                                                                                              |
| [activityState](./models.activityinstance.activitystate.md)                 |           | [ActivityState](./models.activitystate.md) \| undefined                                          | State of the Activity Instance.                                                                                                                                                                                                           |
| [approvalStatus](./models.activityinstance.approvalstatus.md)               |           | [Link](./models.link.md) \| undefined                                                            | Approval Status for this Activity Instance.                                                                                                                                                                                               |
| [getInternalModel](./models.activityinstance.getinternalmodel.md)           |           | () =&gt; [BackendActivityInstance](./open-api-client.activityinstance.md)                        |                                                                                                                                                                                                                                           |
| [isExpirationExecution](./models.activityinstance.isexpirationexecution.md) |           | boolean \| undefined                                                                             | Value, indicated whether this activity expired or not. This property is used by Workflow Agent while expiring the activity.                                                                                                               |
| [processDefinition](./models.activityinstance.processdefinition.md)         |           | [Link](./models.link.md) \| undefined                                                            | Process Definition on which the Activity Instance is based.                                                                                                                                                                               |
| [resumeBookmark](./models.activityinstance.resumebookmark.md)               |           | string \| undefined                                                                              | Resume bookmark for suspended automated activities. During suspending of activity user can specify "ResumeBookmark" object. With its help script execution can be started in future from specific place, but not from the very beginning. |
| [suspendOrFailReason](./models.activityinstance.suspendorfailreason.md)     |           | string \| undefined                                                                              | Reason why this Activity was suspended or failed.                                                                                                                                                                                         |
| [workflowType](./models.activityinstance.workflowtype.md)                   |           | [Link](./models.link.md) \| undefined                                                            | Workflow type of the Process which contains this Activity.                                                                                                                                                                                |
