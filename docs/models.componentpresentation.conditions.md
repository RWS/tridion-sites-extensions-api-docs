<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [ComponentPresentation](./models.componentpresentation.md) &gt; [conditions](./models.componentpresentation.conditions.md)

## ComponentPresentation.conditions property

If conditions are specified for a Component Presentation, these are published as TCDL code. This TCDL code results in Content Delivery code that only renders the Component Presentation if the user falls in the given Target Groups.

**Signature:**

```typescript
get conditions(): ReadonlyArray<TargetGroupCondition> | undefined;
```
