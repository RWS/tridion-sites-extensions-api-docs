<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [PageTemplate](./models.pagetemplate.md) &gt; [pageSchema](./models.pagetemplate.pageschema.md)

## PageTemplate.pageSchema property

Only schemas with purpose "SchemaPurpose.Region" can be set on this property. When set, component presentation(s) and region(s) of page using this page template will be validated against this schema, along with its Metadata instead of the Metadata schema of the page.

**Signature:**

```typescript
get pageSchema(): Link | undefined;
```