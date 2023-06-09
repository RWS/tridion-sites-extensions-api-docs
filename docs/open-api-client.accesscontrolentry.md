<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [AccessControlEntry](./open-api-client.accesscontrolentry.md)

## AccessControlEntry type

Represents an entry in an Access Control List, which is used to restrict access to containers. An Access Control Entry specifies which Permissions and/or Rights a given "Trustee" has. Permissions and Rights can either be Allowed, Denied or Implicit Denied.

**Signature:**

```typescript
export type AccessControlEntry = {
    $type?: string;
    AllowedPermissions?: Array<Permissions>;
    AllowedRights?: Array<Rights>;
    DeniedPermissions?: Array<Permissions>;
    DeniedRights?: Array<Rights>;
    Trustee?: Link;
};
```

**References:** [Rights](./open-api-client.rights.md)<!-- -->, [Link](./open-api-client.link.md)
