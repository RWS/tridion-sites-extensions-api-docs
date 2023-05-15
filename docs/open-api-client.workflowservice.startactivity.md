<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [WorkflowService](./open-api-client.workflowservice.md) &gt; [startActivity](./open-api-client.workflowservice.startactivity.md)

## WorkflowService.startActivity() method

Starts a Workflow activity. This operation returns an instance of 'ActivityInstance' type.

**Signature:**

```typescript
static startActivity(escapedActivityInstanceId: string): CancelablePromise<ActivityInstance>;
```

## Parameters

| Parameter                 | Type   | Description                                                                                                              |
| ------------------------- | ------ | ------------------------------------------------------------------------------------------------------------------------ |
| escapedActivityInstanceId | string | The URI of a Workflow activity instance with the colon escaped by replacing it with an underscore. E.g. "tcm_1-1-131104" |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[ActivityInstance](./open-api-client.activityinstance.md)<!-- -->&gt;

ActivityInstance The request was successful.

## Exceptions

ApiError