<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [PublishLocationInfo](./models.publishlocationinfo.md) &gt; [publishLocationUrl](./models.publishlocationinfo.publishlocationurl.md)

## PublishLocationInfo.publishLocationUrl property

Publish URL of the container object.

The publish URL is formed by a concatenation of the context Publication's PublicationUrl, the intermediary Structure Groups' Directory (recursively) and the object's own directory/file name and extension.

**Signature:**

```typescript
get publishLocationUrl(): string | undefined;
```