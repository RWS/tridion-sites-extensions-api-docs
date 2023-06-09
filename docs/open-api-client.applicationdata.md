<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ApplicationData](./open-api-client.applicationdata.md)

## ApplicationData type

Represents application-specific data which can be stored system-wide (global) or associated with any identifiable object.

**Signature:**

```typescript
export type ApplicationData = {
    $type?: string;
    ApplicationId?: string;
    Data?: string;
    IsInherited?: boolean;
    ManagedLinks?: Link;
    OwningRepositoryId?: string;
    TypeId?: string;
};
```

**References:** [Link](./open-api-client.link.md)
