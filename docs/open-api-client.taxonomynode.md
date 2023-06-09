<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [TaxonomyNode](./open-api-client.taxonomynode.md)

## TaxonomyNode type

Represents a Taxonomy node, including its child nodes. The Taxonomy Root Node represents an (External) Category, child nodes represent (External) Keywords.

**Signature:**

```typescript
export type TaxonomyNode = {
    $type?: string;
    Id?: string;
    Title?: string;
    AlternativeLabels?: Array<string>;
    ChildNodes?: Array<TaxonomyNode>;
    readonly Descendants?: number;
    IsAbstract?: boolean;
};
```

**References:** [TaxonomyNode](./open-api-client.taxonomynode.md)
