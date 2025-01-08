<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [isItemNodeOfType](./extensions.isitemnodeoftype.md)

## isItemNodeOfType variable

Checks if an item in a node, given as the first parameter, is an instance of a constructor, provided as the second parameter.

**Signature:**

```typescript
isItemNodeOfType: <TItem extends IdentifiableObject>(node: ContentExplorerNode | undefined, ctor: Constructor<TItem>) => node is ContentExplorerItemNode<TItem>
```