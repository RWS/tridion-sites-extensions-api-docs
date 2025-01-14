<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [ContentEditorViewExtensionConfiguration](./extensions.contenteditorviewextensionconfiguration.md)

## ContentEditorViewExtensionConfiguration interface

**Signature:**

```typescript
export interface ContentEditorViewExtensionConfiguration
```

## Properties

| Property                                                                                             | Modifiers | Type                                                                                                                                                                       | Description                                                                |
| ---------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [component](./extensions.contenteditorviewextensionconfiguration.component.md)                       |           | ComponentType&lt;[ContentEditorViewExtensionComponentProps](./extensions.contenteditorviewextensioncomponentprops.md)<!-- -->&gt;                                          | Component to render on this path                                           |
| [id](./extensions.contenteditorviewextensionconfiguration.id.md)                                     |           | string                                                                                                                                                                     | Extension id                                                               |
| [useContentEditorView](./extensions.contenteditorviewextensionconfiguration.usecontenteditorview.md) |           | (props: [ContentEditorViewHookProps](./extensions.contenteditorviewhookprops.md)<!-- -->) =&gt; [ContentEditorViewHookResult](./extensions.contenteditorviewhookresult.md) | Hook which returns information about the current content for the extension |
