<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/extensions](./extensions.md) &gt; [NavigationExtensionsBuilder](./extensions.navigationextensionsbuilder.md) &gt; [register](./extensions.navigationextensionsbuilder.register.md)

## NavigationExtensionsBuilder.register property

Registers a new navigation item.

**Signature:**

```typescript
register: (item: NavigationItemExtension) => this;
```

## Remarks

This method only registers the navigation item and does not automatically make it visible in the application. To add the navigation item to the application, use [NavigationExtensionsBuilder.config](./extensions.navigationextensionsbuilder.config.md)<!-- -->.