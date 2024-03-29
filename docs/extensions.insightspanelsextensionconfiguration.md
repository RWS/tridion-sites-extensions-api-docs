<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [InsightsPanelsExtensionConfiguration](./extensions.insightspanelsextensionconfiguration.md)

## InsightsPanelsExtensionConfiguration interface

**Signature:**

```typescript
export interface InsightsPanelsExtensionConfiguration<TComponentProps, THookProps>
```

## Properties

| Property                                                                    | Modifiers | Type                                                                                                             | Description                                                              |
| --------------------------------------------------------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| [component](./extensions.insightspanelsextensionconfiguration.component.md) |           | ComponentType&lt;TComponentProps&gt;                                                                             | Component to display as a panel                                          |
| [id](./extensions.insightspanelsextensionconfiguration.id.md)               |           | string                                                                                                           | Extension id                                                             |
| [usePanel](./extensions.insightspanelsextensionconfiguration.usepanel.md)   |           | (props: THookProps) =&gt; [InsightsPanelsExtensionHookResult](./extensions.insightspanelsextensionhookresult.md) | Hook which returns information about the current panel for the extension |
