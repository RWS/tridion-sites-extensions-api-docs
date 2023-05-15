<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [PublishTransaction](./open-api-client.publishtransaction.md)

## PublishTransaction type

Represents the data object of a PublishTransaction.

**Signature:**

```typescript
export type PublishTransaction = SystemWideObject & {
    Creator?: Link;
    DeployerAction?: DeployerAction;
    HasRenderFailures?: boolean;
    Information?: string;
    Instruction?: PublishInstructionBase;
    IsCompleted?: boolean;
    Items?: Array<Link>;
    Priority?: PublishPriority;
    PublishContexts?: Array<PublishContext>;
    PublisherHost?: string;
    RenderingTime?: string;
    ResolvingTime?: string;
    State?: PublishTransactionState;
    StateChangeDateTime?: string;
    TargetType?: Link;
    TotalExecutionTime?: string;
};
```

**References:** [SystemWideObject](./open-api-client.systemwideobject.md)<!-- -->, [Link](./open-api-client.link.md)<!-- -->, [DeployerAction](./open-api-client.deployeraction.md)<!-- -->, [PublishInstructionBase](./open-api-client.publishinstructionbase.md)<!-- -->, [PublishPriority](./open-api-client.publishpriority.md)<!-- -->, [PublishContext](./open-api-client.publishcontext.md)<!-- -->, [PublishTransactionState](./open-api-client.publishtransactionstate.md)