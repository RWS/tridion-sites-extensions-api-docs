<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [ApprovalStatus](./models.approvalstatus.md) &gt; [position](./models.approvalstatus.position.md)

## ApprovalStatus.position property

Position of this Approval Status in the list of the Approval Statuses.

The list of Approval Statuses is ordered, because Publication Targets can have a minimal Approval Status: Approval Statuses with a Position lower than this minimal approval status won't be publishable.

**Signature:**

```typescript
get position(): number | undefined;
```
