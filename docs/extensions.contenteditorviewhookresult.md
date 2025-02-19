<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [ContentEditorViewHookResult](./extensions.contenteditorviewhookresult.md)

## ContentEditorViewHookResult interface

**Signature:**

```typescript
export interface ContentEditorViewHookResult
```

## Properties

| Property                                                               | Modifiers | Type    | Description                                                                                                                                                                                                                                                                                                                   |
| ---------------------------------------------------------------------- | --------- | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [isAvailable](./extensions.contenteditorviewhookresult.isavailable.md) |           | boolean | Defines whether the content extension is available to be displayed or not                                                                                                                                                                                                                                                     |
| [priority?](./extensions.contenteditorviewhookresult.priority.md)      |           | number  | _(Optional)_ Priority value of the custom editor in the list of candidates for rendering. Extension with a higher priority will be displayed instead of an extension with lower priority. Helps to resolve collapsing cases when useIsAvailable returns true for two or more extensions for a single editor at the same time. |
