<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [TextProps](./extensions.textprops.md)

## TextProps interface

**Signature:**

```typescript
export interface TextProps extends ColorProps, TooltipProps
```

**Extends:** [ColorProps](./extensions.colorprops.md)<!-- -->, [TooltipProps](./extensions.tooltipprops.md)

## Properties

| Property                                                  | Modifiers | Type                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------------------------------------------------------- | --------- | ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [alignment?](./extensions.textprops.alignment.md)         |           | [TextAlignment](./extensions.textalignment.md) | _(Optional)_ The alignment of the text in the container.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [breakWord?](./extensions.textprops.breakword.md)         |           | boolean                                        | _(Optional)_ Determines whether the text should break words if they exceed the container width. Note that it can be used in combination with <code>multiLine: true</code> only, since single line text is truncated by default.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [children?](./extensions.textprops.children.md)           |           | ReactNode                                      | _(Optional)_ The content to be rendered inside the Text component.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [compact?](./extensions.textprops.compact.md)             |           | boolean                                        | _(Optional)_ Determines whether the Text component should have compact spacing. If set to <code>true</code>, the line height of the text will be reduced.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [direction?](./extensions.textprops.direction.md)         |           | [TextDirection](./extensions.textdirection.md) | _(Optional)_ The direction of the text.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [multiLine?](./extensions.textprops.multiline.md)         |           | boolean                                        | _(Optional)_ Allow text to flow over multiple lines. By default it's a single line text with truncation enabled.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [notSelectable?](./extensions.textprops.notselectable.md) |           | boolean                                        | _(Optional)_ Option to make text non-selectable by the user.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| [tag?](./extensions.textprops.tag.md)                     |           | [TextTag](./extensions.texttag.md)             | _(Optional)_ The HTML tag to be used for rendering the Text component. Overrides default tag defined by <code>type</code>.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [type?](./extensions.textprops.type.md)                   |           | [TextType](./extensions.texttype.md)           | <p>_(Optional)_ Preset that consist of specific styling (size, weight, etc) and HTML tag.</p><p>- <code>heading1</code> - usually represents a top-level heading or title. It is styled as a large and prominent text. By default <code>&lt;h1&gt;</code> HTML tag is used. - <code>heading2</code> - a secondary-level heading. It is styled as a slightly smaller text compared to <code>heading1</code>. By default <code>&lt;h2&gt;</code> HTML tag is used. - <code>heading3</code> - a tertiary-level heading. It is styled as a smaller text compared to <code>heading2</code>. By default <code>&lt;h3&gt;</code> HTML tag is used. - <code>default</code> - default style for regular text. It is styled as a standard paragraph text. By default <code>&lt;div&gt;</code> HTML tag used. - <code>defaultBold</code> - the default style for bold text. It is styled similarly to <code>default</code> but with added font-weight. By default <code>&lt;div&gt;</code> HTML tag is used. - <code>small</code> - a smaller size for text. It is typically used for captions, footnotes, or other smaller pieces of text. By default <code>&lt;div&gt;</code> HTML tag is used. - <code>smallBold</code> - a smaller size for bold text. It combines the smaller size of 'small' with the added font-weight. By default <code>&lt;div&gt;</code> HTML tag is used.</p> |
| [underline?](./extensions.textprops.underline.md)         |           | boolean                                        | _(Optional)_ Determines whether the text should have an underline.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [uppercase?](./extensions.textprops.uppercase.md)         |           | boolean                                        | _(Optional)_ Determines whether the text should be displayed in uppercase.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |