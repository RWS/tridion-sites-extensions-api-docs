<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [LocationInfo](./models.locationinfo.md)

## LocationInfo class

Location/context info for Repository-Local Objects.

**Signature:**

```typescript
export declare class LocationInfo
```

## Constructors

| Constructor                                                                                                      | Modifiers | Description                                                      |
| ---------------------------------------------------------------------------------------------------------------- | --------- | ---------------------------------------------------------------- |
| [(constructor)({ backendModel, contextRepository, organizationalItem })](./models.locationinfo._constructor_.md) |           | Constructs a new instance of the <code>LocationInfo</code> class |

## Properties

| Property                                                          | Modifiers | Type                                                              | Description                                                  |
| ----------------------------------------------------------------- | --------- | ----------------------------------------------------------------- | ------------------------------------------------------------ |
| [\_backendModel](./models.locationinfo._backendmodel.md)          |           | [BackendLocationInfo](./open-api-client.locationinfo.md)          |                                                              |
| [contextRepository](./models.locationinfo.contextrepository.md)   |           | [Link](./models.link.md) \| undefined                             | Context Repository from which the object has been retrieved. |
| [getInternalModel](./models.locationinfo.getinternalmodel.md)     |           | () =&gt; [BackendLocationInfo](./open-api-client.locationinfo.md) |                                                              |
| [organizationalItem](./models.locationinfo.organizationalitem.md) |           | [Link](./models.link.md) \| undefined                             | Organizational Item that contains the object.                |
| [path](./models.locationinfo.path.md)                             |           | string \| undefined                                               | Path to the item (that is, excluding the item's own title).  |
| [webDavUrl](./models.locationinfo.webdavurl.md)                   |           | string \| undefined                                               | WebDAV URL of the item.                                      |
